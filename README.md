# 软考中项（系统集成项目管理工程师）第 3 版 · 备考 Skill Pack

> 把中项两科的**训练与诊断**做成可调用的 Agent Skills。
> 不是教材索引，是备考教练：知识库告诉你"应该知道什么"，教练训练你"在考场上怎么用出来"。

## 30 秒看懂

- **是什么**：18 章知识框架 + 11 个教练（过程组、ITTO、挣值、关键路径、案例找错、等保、监理、路线、每日训练、归因）。
- **适合谁**：备考中项（第 3 版）的考生；在职、时间碎、需要"有人追问"的人。
- **不适合谁**：想找押题、想背题库原题的人。
- **注意**：中项**无论文**；论文需求请用高项/系规 skill。

## 安装

### WorkBuddy
```
C:\Users\<你的用户名>\.workbuddy\skills\zhongxiang-di3ban-jiaocai\
```

### Claude Code
```bash
git clone https://github.com/chianyuluo/zhongxiang-di3ban-jiaocai.git \
  ~/.claude/skills/zhongxiang-di3ban-jiaocai
```

### 一条命令
```bash
npx skills add chianyuluo/zhongxiang-di3ban-jiaocai
```

## 11 个教练

| # | 教练 | 什么时候用 |
|---|---|---|
| 01 | 选择题诊断器 | 贴错题、"选了 A 答案是 C" |
| 02 | 五大过程组教练 | 48 过程计数、过程归属 |
| 03 | ITTO 框架教练 | "输入输出是什么" |
| 04 | 挣值纠错器 | CV/CPI/EAC 算不对 |
| 05 | 关键路径检查器 | 关键路径、浮动算不对 |
| 06 | 案例找错教练 | 案例不知道从哪找问题 |
| 07 | 等保 2.0 教练 | 级别、三重防护、测评 |
| 08 | 监理教练 | 四控三管一协调 |
| 09 | 备考路线规划器 | "每天 1 小时""还有 3 个月" |
| 10 | 每日微训练调度 | "今天练什么" |
| 11 | 错题归因日志 | 总是同类错 |

完整依赖与触发速查见 [INDEX.md](INDEX.md)。

## 目录结构

```
SKILL.md                  主入口（框架 + 路由 + 常见坑）
INDEX.md                  技能地图与触发速查
coaches/                  11 个教练（六段式 R/I/A1/A2/E/B）
chapters/ch01~ch18.md     18 章知识框架
cheatsheet.md / glossary.md / patterns.md / calculation.md
kaogan_map.md / kaopin_frequency.md / must_know.md / zhenti_traps.md / prep_strategy.md / exam_format.md
examples/                 3 个"输入→输出"示例
```

## 使用示例

**例 1：过程组**
> 你：监控过程组有几个？
> 教练：总数 48，启动 2、收尾 1、执行 10、规划 24，剩下是几个？

**例 2：案例**
> 你：我只看出变更没走流程。
> 教练：质量维度有没有"未测试"？风险维度有没有"登记册不更新"？

**例 3：计算**
> 你：CPI=1.5，成本节约。
> 教练：CPI 是 EV/AC 还是 AC/EV？你先说 EV 和 AC 各是多少？

更多见 [examples/](examples/)。

## 常见坑（Gotchas）

- **48 过程**：启动 2 / 规划 24 / 执行 10 / 监控 11 / 收尾 1。
- **管理质量执行组，控制质量监控组**；前者管过程，后者管结果。
- **三类绩效**：数据→信息→报告。
- **典型/非典型**：没说"剩余按原计划"就是典型（EAC=BAC/CPI）。
- **中项无论文**，别按高级论文准备。
- **2026 年恢复一年两考（5 月、10 月）**，沿用第 3 版/2024 大纲。

## 适用考试

系统集成项目管理工程师（中项）：中级；基础知识 75 题 + 应用技术 4 题（3 分析 + 1 计算）；两科连考 240 分钟，同次均 ≥45，单科不保留；2026 年一年两考。

## 版权声明

本仓库为**个人备考学习整理，非官方资料**，仅供学习交流，**请勿商业转售**。
知识点提炼自《系统集成项目管理工程师教程（第 3 版）》，版权归原出版社及作者所有，请支持正版教材。

**License：CC BY-NC-SA 4.0**（署名—非商业性使用—相同方式共享）。内容型资料，不用 MIT。

## 相关仓库

- 高项（第 4 版）：https://github.com/chianyuluo/gaoxiang-di4ban-jiaocai
- 系规（第 2 版）：https://github.com/chianyuluo/xitongguihua-di2ban-jiaocai

## 更新日志

见 [CHANGELOG.md](CHANGELOG.md)。当前版本 **v0.2.1**（2026-10-17）：修正教练命名一致性、License 识别。
