<p align="center">
  <samp>hover / zushover</samp><br>
  <sub>ML Research · Efficient AI · Personal Automation</sub>
</p>

---

I work on making large models smaller, faster, and cheaper to run — not as an academic exercise, but as an engineering constraint you can feel in your GPU memory and your wallet.

### What I care about

**Efficient AI.** Quantization, pruning, KV cache optimization, speculative decoding. The whole pipeline from weight compression to inference-time acceleration. If it makes a model run on less hardware without breaking, I want to understand it.

**The memory problem.** LLMs need to remember — across turns, across sessions, across tasks. Context windows don't solve this. I'm tracking every serious attempt at memory mechanisms (KV cache eviction strategies, online state models, external memory banks) to find the one primitive that actually works.

**AI as infrastructure.** I build systems where AI agents don't just answer prompts — they run your workstation while you're away. Telegram → Claude Code → Obsidian, fully automated. The agent isn't the product; the pipeline is.

### How I work

- **First-principles first.** Start from the constraint, not the solution. Why is quantization error structured the way it is? What does the KV cache actually need to store?
- **Build to understand.** Reading papers isn't enough. Run the code, hit the OOM, profile the bottleneck — then read the paper again.
- **Compression reveals structure.** The bits you can throw away tell you what matters. SQP, delta-rule memory, per-channel quantization — different surfaces, same underlying principle.

### What I'm building

| | |
|---|---|
| **[efficient-ai-learning-roadmap](https://github.com/zushover/efficient-ai-learning-roadmap)** | 5-phase progressive path through Efficient AI. 50+ curated papers with links. Quantization → pruning → KV cache → speculative decoding → industrial practice. |
| **[cc-automation-workstation](https://github.com/zushover/cc-automation-workstation)** | Telegram-controlled Claude Code + Obsidian workstation. Full deployment guide — phone in your pocket, agent on your desktop. |
| **[cc-autodl](https://github.com/zushover/cc-autodl)** | AutoDL GPU manager. CLI + system tray + web dashboard. Manage cloud GPU instances without touching the console. |

### Current compass

```
Quantization:  GPTQ → AWQ → BitNet → OSAQ
Pruning:       SparseGPT → Wanda → UniComp
KV Cache:      StreamingLLM → DuoAttention → KVzip → TurboQuant → CompilerKV
Deploy:        DeepSeek V3 · Kimi · ByteDance
```

Open questions I'm tracking: Can 1-bit LLMs scale to 100B+? What exactly does compression break in reasoning? Is there a unified memory primitive that replaces both KV cache and external retrieval?

---

<p align="center">
  <sub>Shanghai · <a href="https://github.com/zushover">github.com/zushover</a></sub>
</p>
