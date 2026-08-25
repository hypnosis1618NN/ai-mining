# AI+探矿本体设计

## 节点类型

| 类型 | 含义 | 例子 |
|---|---|---|
| data | 输入证据源 | 地球化学、地球物理、遥感、钻孔、已知矿床 |
| feature | 数据到模型之间的特征工程 | 分形、小波、PCA、数据融合、GIS overlay |
| model | AI/统计模型 | RF、SVM、XGBoost、CNN、GNN、Transformer、LLM |
| task | 研究/业务任务 | MPM、异常识别、岩性识别、反演、岩心识别 |
| decision | 面向客户的决策能力 | 靶区排序、钻探建议、可解释性、不确定性 |
| company | 竞争者或潜在伙伴 | KoBold、Earth AI、Fleet Space、GeologicAI |
| paper | 代表论文证据 | 本地 PDF 或高被引记录 |
| category | 论文主题簇 | 综述、MPM、遥感、地化、地物等 |

## 关系类型

| 关系 | 含义 |
|---|---|
| feeds / input_to | 数据进入技术或任务 |
| applied_to | 模型用于某项探矿任务 |
| supports / reduces_risk_for | 能力支撑业务或降低决策风险 |
| produces_evidence_for / prioritizes | 任务输出进入靶区排序或钻探决策 |
| classified_as / mentions_technology / studies_task / uses_data | 论文证据与分类、技术、任务、数据的连接 |
| competes_on | 公司在某项能力或任务上形成竞争定位 |