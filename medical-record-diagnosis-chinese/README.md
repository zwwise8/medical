---
license: Apache License 2.0
---

## 数据说明

| 字段 | 类型 | 描述      |
| --- | --- |---------|
| condition | Object | 患者的基本情况和检查结果 |
| condition.gender | String | 性别      |
| condition.age | Number | 年龄      |
| condition.chiefComplaint | String | 主诉      |
| condition.historyOfPresentIllness | String | 现病史     |
| condition.pastHistory | String | 既往史     |
| condition.personalHistory | String | 个人史     |
| condition.allergicHistory | String | 过敏史     |
| condition.reproductiveHistory | String | 生育史（ TPAL 数据 ） |
| condition.pregnancyAndDelivery | String | 婚育史     |
| condition.epidemicHistory | String | 流行病史    |
| condition.physicalExamination | String | 体格检查结果  |
| condition.auxiliaryExamination | String | 辅助检查结果  |
| diseases | Array | 诊断的疾病列表 |
| analyses | Array | 病例分析列表  |
| analyses.description | String | 分析描述    |
| analyses.score | Number | 分析评分（ 1 - 3 分 ） |
| diagnoses | Array | 最终诊断结果  |
| diagnoses.reason | String | 诊断依据    |
| diagnoses.conclusion | String | 诊断结论    |
