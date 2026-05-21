<div align="center">
  <h1>hover</h1>
  <p>
    <img src="https://img.shields.io/badge/Efficient_AI-Quant_|_Prune_|_KV_Cache-1c1c1e?style=flat-square" />
    <img src="https://img.shields.io/badge/Focus-Model_Compression_&_Deployment-c44a2a?style=flat-square" />
    <img src="https://img.shields.io/badge/Stack-Python_|_TypeScript_|_Next.js-8c8880?style=flat-square" />
  </p>
  <p>Shanghai · ML Research & Systems</p>
</div>

---

## Projects

### [cc-automation-workstation](https://github.com/zushover/cc-automation-workstation) — 手机遥控电脑的全自动工作地基

一套完整部署手册：Telegram Bot → cc-connect 桥接 → Claude Code Agent → Obsidian 第二大脑。你在外面用手机发消息，家里电脑执行任务——写代码、做调研、查资料、跑测试——结果自动归档 Obsidian，手机 App 随时翻阅。覆盖 Telegram Bot 创建、DeepSeek API 配置、代理注入、cc-switch 多档案管理、开机自启、故障排查全流程。

`cc-connect` `cc-switch` `Claude Code` `DeepSeek v4` `Obsidian` `Telegram Bot`

<br>

### [cc-autodl](https://github.com/zushover/cc-autodl) — AutoDL GPU 云实例管理器

CLI + 系统托盘 + Web 面板（localhost:8899），一站式管理 AutoDL GPU 实例。15 个 CLI 子命令覆盖开机/关机/释放/余额/费用/训练脚本上传/远程命令执行，系统托盘 4 色状态图标 + 右键快捷操作，Web 面板提供 HTML 仪表盘。打包为单文件 exe (~28MB)，无需安装 Python。

`Python` `FastAPI` `pystray` `paramiko` `PyInstaller`

<br>

### [efficient-ai-learning-roadmap](https://github.com/zushover/efficient-ai-learning-roadmap) — Efficient AI 渐进学习路线

5 阶段、50+ 篇精选论文、带链接和阅读优先级——从量化/剪枝/蒸馏的原理性论文，到投机解码/KV Cache 优化/Token 压缩的推理加速链，再到 DeepSeek/Kimi/ByteDance 的工业实践。每篇标注了星级和阅读顺序，附带一键复制给 AI 助手的引导 Prompt。

量化 GPTQ → AWQ → QLoRA → BitNet → OSAQ，剪枝 SparseGPT → Wanda → UniComp，KV Cache StreamingLLM → H2O → DuoAttention → KVzip → TurboQuant → CompilerKV。

<br>

## Skills

| Skill | 做什么 |
|---|---|
| [**seestarai-xiaohongshu**](https://github.com/zushover/seestarai-xiaohongshu) | Claude Code Skill：全自动 AI 日报 → 小红书。5 阶段流水线（新闻发现→数据审查→叙事设计→HTML 生成→文案），并行抓取 TechCrunch/FT/Bloomberg 信源，3 级数据交叉验证，10 页 540×720px SeestarAI 品牌卡片 |

---

## Compass

```
Quantization:    GPTQ → AWQ → QLoRA → BitNet → OSAQ
Pruning:         SparseGPT → Wanda → UniComp
KV Cache:        StreamingLLM → H2O → DuoAttention → KVzip → TurboQuant → CompilerKV
Spec. Decoding:  EAGLE-3 → DFlash → RACER
Inference:       vLLM · SGLang · llama.cpp · DeepSpeed
Industry:        DeepSeek V3 · Kimi · ByteDance · Baidu Kunlun
```

---

<div align="center">
  <sub><a href="https://github.com/zushover">github.com/zushover</a></sub>
</div>
