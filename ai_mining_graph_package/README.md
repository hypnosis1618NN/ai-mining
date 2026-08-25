# AI+探矿知识图谱交付包

这次重做的目标是让图谱从“数据文件”变成“可阅读、可演示、可继续扩展”的行业地图。

## 怎么看

1. 先打开 `ai_mining_knowledge_graph.html`，用搜索框找技术、任务或公司。
2. 点击节点看位置、解释、关系和来源。
3. 需要工程导入时，用 JSON、GraphML 或 Neo4j Cypher。

## 图谱层级

- 数据层: data
- 特征/工程层: feature
- AI 模型层: model
- 任务层: task
- 决策层: decision
- 公司/竞争层: company
- 论文证据层: paper
- 论文分类层: category

## 关键判断

- 行业中心任务是 MPM（矿产远景区预测），但商业竞争会从“概率图”转向“可钻靶区 + 证据链 + ROI”。
- 传统 ML 仍是主力，因为地学样本少、客户需要解释；深度学习在遥感、高光谱、岩心和地球物理中更有优势。
- GNN、知识图谱、基础模型、LLM/RAG 的价值不在替代地质专家，而在把空间关系、历史报告和跨区域知识变成可复用证据。
- 未来差异化最可能来自失败样本库、空间外推验证、低扰动快速验证、预测-钻探闭环和人机协同证据链。

## 高频技术 Top 20

- Machine learning: 341
- Deep learning: 147
- Random Forest: 124
- Support Vector Machine: 91
- Convolutional Neural Network: 74
- Exploration target ranking: 63
- Supervised learning: 48
- Attention mechanism: 48
- Ensemble learning: 45
- Multilayer Perceptron / ANN: 45
- ROC-AUC / PR-AUC: 43
- Gradient Boosting: 41
- Multi-source data fusion: 38
- XGBoost: 36
- Drilling recommendation: 28
- Logistic Regression: 27
- Principal Component Analysis: 26
- Transformer: 26
- GIS overlay modeling: 26
- Unsupervised learning: 26

## 高频任务

- Mineral prospectivity mapping: 174
- Remote sensing mineral/alteration mapping: 133
- Hyperspectral/lithology mapping: 120
- Geophysical inversion and interpretation: 95
- Portfolio and target ranking: 68
- Ore deposit classification: 55
- Geochemical anomaly detection: 44
- Drill core logging and assay prediction: 26
- Exploration knowledge management: 13