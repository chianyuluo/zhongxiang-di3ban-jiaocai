---
name: zhongxiang-di3ban-jiaocai
description: "中项（系统集成项目管理工程师）第3版备考 Skill Pack：18章框架 + 11个教练。覆盖五大过程组48过程、十大领域ITTO、挣值/关键路径计算、案例找错、等保2.0、监理四控三管一协调、备考路线。当考生问'过程组几个/ITTO/挣值算不对/关键路径不一致/案例不知道找什么/监理怎么记'时使用；用于备考答疑、框架梳理、出题与第3版术语核对。"
---

<!-- argument-hint: 五大过程组 / 变更流程 / WBS / 等保2.0 / ITSS / 生命周期模型 / 监理 / 招标 / 法律法规 / 案例找错 -->

# 系统集成项目管理工程师教程（第3版）· 备考框架库
**Author**: 软考办指定教程（中项第3版） | **Pages**: ~700 | **Chapters**: 18 | **Generated**: 2026-10-17

## How to Use This Skill

- **不带参数** — 加载下方核心框架做总体参考
- **带主题** — 说「变更流程」「规划过程组」「等保2.0」「WBS」等，我定位并读取对应章节
- **带章号** — 说「ch11」，我加载该章文件
- **浏览** — 问「有哪些章节」，看完整索引
- **问考情/考纲/怎么复习** — 说「这章考什么」「怎么备考」，我读取 `kaogan_map.md` / `kaopin_frequency.md` / `exam_format.md` / `prep_strategy.md`
- **找教练** — 说「过程组几个」「挣值算不对」「案例不知道找什么」「监理怎么记」「今天练什么」，我加载 `coaches/` 对应模块（不直接给答案，先追问）
- **看技能地图** — 问「怎么用这套 skill」，我读取 `INDEX.md`

> **考试导向提示**：中项**无论文**，成败在"综合 75 选择 + 案例 4 题（含 1 道 18–22 分计算）"。复习优先 🔴掌握章——**项目管理板块（第 9–16 章，过程组为核心）** + **IT 板块（第 4–8 章）**。各章末尾已附 📌考情/⚠️陷阱/🔢必背 三栏；计算题务必练熟 `calculation.md`。

> 注意：本 skill 是**框架/原则/技法/反模式层**，不是教材全文。需要逐句原文时，底层 clean 正文在 `D:\WorkBuddy\Claw\05_临时文件\教材skill_source\中项\`（18 章 markdown），本 skill 每条都标注了对应章号，可直接回查。

---

## Core Frameworks & Mental Models

**1. 全书的两条主线**
- 主线一：**技术与工程基础**（第1–8章）——信息化战略、技术底座、IT服务、架构、软件工程、数据工程、系统集成、信息安全。
- 主线二：**项目管理 + 保障**（第9–18章）——五大过程组为核心，外加上组织保障、监理、法规、职业道德。

**2. 五大过程组（第3版骨架，过程总数 48）**
- 启动 2 / 规划 24 / 执行 10 / 监控 11 / 收尾 1。规划组最大（WBS、进度、成本、风险×5 等）。

**3. 变更控制铁律**
- 任何范围/进度/成本变更 → 书面变更请求 → 评估影响 → **CCB 审批** → 更新基准 → 执行。**CCB 不直接改基准**。实施整体变更控制贯穿全程。

**4. 绩效三层递进**
- 工作绩效**数据**（原始）→ **信息**（分析后）→ **报告**（汇编传达）；监控据此与基准比对。

**5. ITSS（第3版信息技术服务标准）**
- IT 服务生命周期 5 阶段：规划设计→部署实施→服务运营→持续改进→监督管理。
- 四要素 **PPTR**（人员/过程/技术/资源）——注意与系规第2版"人员/资源/技术/过程"口径不同。

**6. 等保 2.0（第3版安全主线）**
- 1–5 级；"一个中心、三重防护"（安全管理中心 + 通信/边界/计算环境）；三级以上每年测评。

**7. 新一代信息技术（中项口径 6 大）**
- 物联网、云计算、大数据、区块链、人工智能、虚拟现实（注意：中项第3版不含边缘计算/数字孪生单列，与系规第2版"7 大"区分）。

**8. 监理"四控三管一协调"**
- 四控：投资/质量/进度/变更；三管：合同/信息/安全；一协调：组织。

**9. 生命周期模型选型**
- 稳→瀑布/V；模糊→原型；高风险→螺旋；快交付→敏捷/DevOps。

---

## 教练系统（Coaches · 六段式 R/I/A1/A2/E/B）

> 知识库回答"是什么"，教练回答"你卡在哪、怎么练"。默认**不直接给答案**，先用分层追问暴露空缺。

| 触发 | 教练模块 |
|---|---|
| 错题 / 选了A答案是C | [01-mcq-diagnoser](coaches/01-mcq-diagnoser.md) |
| 五大过程组各几个/过程归属 | [02-process-group-coach](coaches/02-process-group-coach.md) |
| ITTO / 输入输出 | [03-itto-coach](coaches/03-itto-coach.md) |
| CV/CPI/EAC 算不对 | [04-evm-step-debugger](coaches/04-evm-step-debugger.md) |
| 关键路径/浮动算不对 | [05-cpm-reverse-checker](coaches/05-cpm-reverse-checker.md) |
| 案例不知道从哪找问题 | [06-case-finding-coach](coaches/06-case-finding-coach.md) |
| 等保几级/三重防护 | [07-security-coach](coaches/07-security-coach.md) |
| 监理四控三管一协调 | [08-supervision-coach](coaches/08-supervision-coach.md) |
| 每天1小时/还有X个月 | [09-study-route-planner](coaches/09-study-route-planner.md) |
| 今天练什么 | [10-daily-drill-scheduler](coaches/10-daily-drill-scheduler.md) |
| 总是同类错/错题怎么总结 | [11-mistake-attribution-log](coaches/11-mistake-attribution-log.md) |

**编排原则**：问定义/框架 → 查 `chapters/`；问"我为什么错/怎么练" → 进教练。教练只做追问与纠错，不代写、不代算、不押题。

## Chapter Index

| # | Title | Key Frameworks |
|---|-------|----------------|
| [ch01](chapters/ch01-xinxihua-fazhan.md) | 信息化发展 | 国家信息化6要素、两化融合、数字中国、新基建 |
| [ch02](chapters/ch02-xinxijishu-fazhan.md) | 信息技术发展 | 6大新技术、云IaaS/PaaS/SaaS、大数据5V、区块链 |
| [ch03](chapters/ch03-xinxijishu-fuwu.md) | 信息技术服务 | ITSS、生命周期5阶段、四要素PPTR、服务质量5特性 |
| [ch04](chapters/ch04-xinxixitong-jiagou.md) | 信息系统架构 | 总体架构4视图、TOGAF/Zachman、ATAM |
| [ch05](chapters/ch05-ruanjian-gongcheng.md) | 软件工程 | 生命周期模型、需求工程、测试4级、CMMI5级 |
| [ch06](chapters/ch06-shuju-gongcheng.md) | 数据工程 | 采集→治理→集成、DCMM、主数据 |
| [ch07](chapters/ch07-xuruanjia-jiicheng.md) | 软硬件系统集成 | 4集成模式、ESB、验收流程 |
| [ch08](chapters/ch08-xinxianquan-gongcheng.md) | 信息安全工程 | 等保2.0、风险评估、CIA、关基 |
| [ch09](chapters/ch09-xiangmu-guanli-gailun.md) | 项目管理概论 | 项目定义、立项三步、生命周期类型、过程组总览 |
| [ch10](chapters/ch10-qidong-guochengzu.md) | 启动过程组 | 2过程：制定章程、识别干系人 |
| [ch11](chapters/ch11-guihua-guochengzu.md) | 规划过程组 | **24 过程**：WBS、进度、成本、风险×5 等 |
| [ch12](chapters/ch12-zhixing-guochengzu.md) | 执行过程组 | 10过程：指导工作、质量、团队、沟通、采购 |
| [ch13](chapters/ch13-jiankong-guochengzu.md) | 监控过程组 | 11过程：控制X、整体变更控制、EVM |
| [ch14](chapters/ch14-shouwei-guochengzu.md) | 收尾过程组 | 1过程：结束项目或阶段；验收/移交/总结 |
| [ch15](chapters/ch15-zuzhi-baozhang.md) | 组织保障 | 组织3型、经理能力三角、RACI、塔克曼 |
| [ch16](chapters/ch16-jianli-jichu.md) | 监理基础知识 | 四控三管一协调、监理规划/细则 |
| [ch17](chapters/ch17-falv-biaozhun.md) | 法律法规和标准规范 | 招投标、合同法、著作权、网安/数安/个保法 |
| [ch18](chapters/ch18-zhiye-daode.md) | 职业道德规范 | 四底线：守法/诚信/敬业/保密 |

## Topic Index

- **五大过程组 / 过程数** → ch09–ch14（启动2/规划24/执行10/监控11/收尾1=48）
- **变更控制 / CCB** → ch13, ch09
- **WBS / 基准 / 渐进明细** → ch11
- **EVM / 挣值** → ch13
- **ITSS / 服务质量** → ch03
- **等保2.0 / 风险评估** → ch08
- **信息系统架构 4 视图** → ch04
- **软件生命周期模型 / CMMI** → ch05
- **数据治理 / DCMM** → ch06
- **系统集成 4 模式** → ch07
- **监理 四控三管一协调** → ch16
- **招投标 / 合同法 / 著作权** → ch17
- **职业道德** → ch18
- **案例找错** → patterns
- **规划方法/模型选型** → cheatsheet, patterns

## Supporting Files

**考试导向（考纲/考频/备考）**
- [exam_format.md](exam_format.md) — 考试科目、时长、范围、合格线、第3版变化、案例考法
- [kaogan_map.md](kaogan_map.md) — 考纲考试目标/要求(8条) + 18 章逐章掌握度与考法映射
- [kaopin_frequency.md](kaopin_frequency.md) — 板块权重、高频章 Top、案例/计算范围、过程组计数
- [prep_strategy.md](prep_strategy.md) — 三阶段备考路线图与权重分配

**硬货（数字/陷阱/计算/速记）**
- [must_know.md](must_know.md) — 必背过程计数、公式、级别、组织矩阵、监理、单位进制
- [zhenti_traps.md](zhenti_traps.md) — 高频易混对与案例命题陷阱
- [calculation.md](calculation.md) — **计算专题**：关键路径/挣值/三点估算/进度压缩（案例必拿分）
- [cheatsheet.md](cheatsheet.md) — 过程数、口诀、决策规则速查（含数字速记板块）

**框架/术语**
- [glossary.md](glossary.md) — 核心术语与定义（标注章号）
- [patterns.md](patterns.md) — 案例找错反模式、过程组匹配、变更/选型套路

**教练与成品**
- [INDEX.md](INDEX.md) — 技能地图与触发速查
- [coaches/](coaches/) — 11 个教练模块（六段式）
- [examples/](examples/) — 3 个"输入→输出"示例
- [CHANGELOG.md](CHANGELOG.md) — 版本更新记录
- [LICENSE](LICENSE) — CC BY-NC-SA 4.0

---

## 常见坑（Gotchas）

1. **48 过程**：启动 2 / 规划 24 / 执行 10 / 监控 11 / 收尾 1。
2. **管理质量在执行组，控制质量在监控组**；前者管过程，后者管结果。
3. **三类绩效**：数据（原始）→ 信息（对比基准）→ 报告（汇总）。
4. **典型/非典型**：没说"剩余按原计划"就是典型（EAC=BAC/CPI）。
5. **中项无论文**，别按高级论文准备。
6. **2026 年恢复一年两考（5 月、10 月）**，沿用第 3 版/2024 大纲。
7. **监理**：四控（质量/进度/投资/变更）、三管（合同/信息/安全）、一协调。
8. **等保 2.0**：5 级，一个中心+三重防护，三级以上每年测评。

## Scope & Limits

覆盖中项第3版教程 18 章框架 + 11 个教练，面向 2026 年两考备考（5 月、10 月）。不含高项/系规内容，不含实时考情公告（以软考办官方为准）。不代算整题、不押题。底层逐句原文见 `D:\WorkBuddy\Claw\05_临时文件\教材skill_source\中项\`。
