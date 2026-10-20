# 项目模板

按需使用并保存用户项目，复用已有等价记录。以下全部为空模板，不代表任何项目已经通过；不得自动填入作者身份或虚构确认。

## 1. 关卡状态

```yaml
current_gate: G0
status: not_started
artifact_version: null
author_approval: pending
approved_artifacts: []
logic_and_expression: pending
facts_and_evidence: pending
verification_scope: []
open_issues: []
invalidated_artifacts: []
next_action: 启动问答
agreement_carrier: pending
file_save_status: not_saved
approved_snapshot: null
```

status使用not_started、in_progress、awaiting_review、needs_revision、approved、waived。事实核实另记verified、pending、deferred、not_applicable，并附范围。批准须关联产物版本及实际决定依据。

agreement_carrier按实际记录为项目文件/已有版本系统/作者明确指定的对话确认文本，并记录定位；不预填同意。approved_snapshot指可恢复的确认内容，不必是哈希。对话载体不等于文件已保存，跨会话需提供文本。

## 2. 材料与来源

|材料ID|名称/位置|版本|收到|读取|核实范围|冲突/缺口|
|---|---|---|---|---|---|---|

## 3. 事实与数值

|结果ID|问题/主次身份|数据库及分析域|N/暴露/事件|定义/模型/参照|时间点|原值及CI/P/q|展示单位/方向|来源|图表位置|状态|
|---|---|---|---|---|---|---|---|---|---|---|

## 4. 框架与契约

|段落|功能/主题判断|证据锚点|必须报告|上一段关系|下一段桥接|解释范围|版本/作者状态|
|---|---|---|---|---|---|---|---|

契约字段：中心问题、读者和期刊、语言篇幅、授权范围、确认框架、数字图号约定、证据边界、批次粒度、审核规则、待补、保存位置及版本。

## 5. 修改对照与影响

|原段版本|作者改段|改变的功能/顺序/表达|拟提炼规则|适用范围/例外|作者状态|
|---|---|---|---|---|---|

|改动|受影响产物|需重核内容|已更新/待处理/不适用|失效确认|新的确认依据|
|---|---|---|---|---|---|

## 6. 审核与handoff

```text
当前关卡及产物版本：
逻辑与表达：
事实与证据及核查范围：
必须修：
建议修：
待作者确认：
通过后的下一关：
```

交接字段：本次用途、问题与数据库角色、材料版本、图表面板目录、各分析域与核心数字、单位换算、结果段落顺序、解释边界、未决项、已完成检查、下一步及当前关卡。
