# MoonRabbits · 五色五季文化叙事平台

> **From one object, an entire era.**
> **从一件文物，讲出一个时代。**

MoonRabbits（月兔）是一个基于多专家 AI Agent 协同的文化遗产数字叙事平台。以中华文明五色观（青·赤·黄·白·黑）为哲学框架，对应五行（木·火·土·金·水），构建「一色一季、一季一载体」的五色五季文化叙事体系。

---

## 五色五季 · 平台定位

| 季 | 色系 | 五行 | 载体 | 状态 |
|:---|:---|:---|:---|:---|
| 第一季 | 白 | 金 | 德化白瓷 | **当前季 · 已验证** |
| 第二季 | 青 | 木 | 青瓷等 | 规划中 |
| 第三季 | 赤（彩） | 火 | 彩瓷等 | 规划中 |
| 第四季 | 黄 | 土 | 黄瓷等 | 规划中 |
| 第五季 | 黑 | 水 | 黑瓷等 | 规划中 |

> 载体维度可扩展：本平台以陶瓷为基础载体，后续可扩展至服饰、丝绸、漆器、青铜器等更多文化遗产门类。知识库标签体系与 Agent 协同引擎无需改造即可复用。

---

## 核心创新

**1. 多专家 Agent 协同校验**
四位专家（考据官、格物官、灵感官、讲述者）各有所长，并行协作，通过交叉校验机制确保内容准确——本质是协同作战，而非单纯对抗。

**2. 中华五色观哲学框架**
以青赤黄白黑五色对应木火土金水五行，将零散的文化遗产知识纳入统一的哲学叙事体系，让每件文物在其所属的「色系·季节」中找到位置。

**3. 来源溯源 · 有据可依**
每段生成内容均标注知识来源与置信度。不编造、不越界、不替代——文化叙事需有坚实深厚的支撑。

**4. 全程本地运行 · 数据不出机器**
所有推理与知识检索均在本地完成，数据安全可控，适用于博物馆、文博机构等对数据隐私有严格要求的场景。

---

## 技术亮点

| 层 | 技术 |
|---|---|
| 模型层 | Step 3.7 Flash（196B MoE，原生多模态）+ Qwen 3.6 35B（本地辅助） |
| 知识层 | RAG 向量知识库（ChromaDB + bge-large-zh-v1.5）+ 10 维标签体系 |
| 编排层 | 多专家 Agent 协同（OpenClaw）+ NVIDIA NeMo Guardrails 安全护栏 |
| 硬件层 | NVIDIA DGX Spark（128GB 统一内存）· 全链路本地推理 |

---

## Demo 视频

▶️ **[观看 Demo 视频](https://github.com/jing-zephyr/moonrabbits/releases/download/v1.0-demo/MoonRabbits_Demo_v1.mp4)**

---

## 当前进度

- **第一季·白色季（德化白瓷）**：最小闭环已跑通——从拍照识别 → 色彩基因提取 → 五色定位 → 四专家协同叙事 → 安全审查，全链路验证完成。
- 后续扩展至青色季、赤色季等，以及服饰、丝绸、漆器、青铜等更多载体，引擎与知识库架构无需改造。

---

## 作者

**jing-zephyr** · 项目负责人  
Marketing 背景，15 年+海内外品牌营销经验，非物质文化遗产传播者。  
专注深度挖掘文化+科技专业领域背后的底层逻辑，向受众转译。

---

*MoonRabbits · 光而不耀，静水流深。*

---

# MoonRabbits · Five Colors, Five Seasons Cultural Narrative Platform

> **From one object, an entire era.**
> **从一件文物，讲出一个时代。**

MoonRabbits is a multi-agent AI cultural heritage narrative platform. Built on the Chinese philosophy of Five Colors (blue · red · yellow · white · black), corresponding to the Five Elements (wood · fire · earth · metal · water), it constructs a "one color, one season; one season, one carrier" narrative framework for cultural heritage.

---

## Five Colors · Five Seasons

| Season | Color | Element | Carrier | Status |
|:---|:---|:---|:---|:---|
| Season 1 | White | Metal | Dehua White Porcelain | **Current · Verified** |
| Season 2 | Blue/Green | Wood | Celadon, etc. | Planned |
| Season 3 | Red | Fire | Polychrome, etc. | Planned |
| Season 4 | Yellow | Earth | Yellow ware, etc. | Planned |
| Season 5 | Black | Water | Black ware, etc. | Planned |

> The carrier dimension is extensible: ceramics serve as the foundational carrier, with future expansion to silk, lacquerware, bronze, and more. The knowledge base tag system and agent orchestration engine require no modification to scale.

---

## Core Innovations

**1. Multi-Expert Agent Collaboration**
Four expert agents (The Historian, The Scientist, The Muse, The Narrator) work in parallel, cross-validating each other's output — collaboration, not confrontation.

**2. Five-Color Philosophical Framework**
Rooted in the Chinese Five-Color cosmology, the platform places every artifact within a unified "color · season · element" narrative, transforming scattered knowledge into a coherent cultural story.

**3. Source Attribution & Trust**
Every generated narrative includes knowledge source citations and confidence scores. No fabrication. No overreach. Cultural narratives demand solid foundations.

**4. Fully Local · Data Never Leaves Your Machine**
All inference and knowledge retrieval runs locally, ensuring data security — critical for museums and cultural institutions with strict privacy requirements.

---

## Tech Highlights

| Layer | Technology |
|---|---|
| Models | Step 3.7 Flash (196B MoE, native multimodal) + Qwen 3.6 35B (local) |
| Knowledge | RAG vector database (ChromaDB + bge-large-zh-v1.5) + 10-dimension tag system |
| Orchestration | Multi-agent collaboration (OpenClaw) + NVIDIA NeMo Guardrails |
| Hardware | NVIDIA DGX Spark (128GB unified memory) · end-to-end local inference |

---

## Demo Video

▶️ **[Watch Demo](https://github.com/jing-zephyr/moonrabbits/releases/download/v1.0-demo/MoonRabbits_Demo_v1.mp4)**

---

## Current Status

- **Season 1 · White Season (Dehua White Porcelain)** : Minimum viable loop verified — photo → color gene extraction → five-color mapping → four-agent collaborative narrative → content safety review.
- Future seasons and carrier expansion (silk, lacquerware, bronze, etc.) require no architectural changes to the engine or knowledge base.

---

## Author

**jing-zephyr** · Project Lead  
15+ years in global brand marketing. Cultural heritage communicator.  
Focused on unearthing the deep logic beneath the intersection of culture and technology.

---

*MoonRabbits · Shine without glare. Flow without noise.*
