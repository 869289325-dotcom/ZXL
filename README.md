# A股财务风险预警系统

基于XGBoost机器学习的A股上市公司财务风险预警工具。

## 项目链接
部署后访问：https://你的用户名-streamlit-app-name.streamlit.app

## 模型性能
- AUC-ROC: 0.9961
- 准确率: 99%
- 训练数据: 600家公司
- 特征维度: 17维

## 文件说明
| 文件 | 说明 |
|------|------|
| app.py | 主程序（包含完整功能） |
| risk_model_v2.pkl | 训练好的XGBoost模型（188KB） |
| requirements.txt | Python依赖 |

## 部署步骤
1. 上传所有文件到GitHub仓库
2. 在Streamlit Cloud部署
3. Main file path填: app.py
4. 等待2-3分钟即可访问

## 核心功能
- 单股票风险查询
- 批量风险扫描
- 模型性能分析
- 特征重要性可视化

## 免责声明
本系统仅供学习研究使用，不构成投资建议。
