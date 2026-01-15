# AI-Assisted Urban Drainage Load Prediction

## 项目概述

本项目旨在通过 AI 辅助预测城市排水系统未来 24–72 小时内的运行负荷，并为水务运维和城市管理部门提供**量化风险预警**，实现从**事后响应**到**前瞻预判**的转变。

## 功能描述
- **排水负荷预测**：使用多因素（降雨、人口、用水假设）预测未来排水负荷。
- **风险评估**：对预测结果进行风险等级评估（低/中/高）。

## 技术栈
- **Python**（线性回归模型）
- **Pandas, NumPy**（数据处理）
- **Matplotlib**（可视化）

## 项目文件
- **PRD.pdf**：产品需求文档。
- **原型图**：产品界面设计原型。
- **model.py**：AI 模型代码。
- **requirements.txt**：项目所需 Python 库。

## 使用说明
1. 克隆此仓库：`git clone https://github.com/yourusername/urban-drainage-load-prediction`
2. 安装依赖：`pip install -r requirements.txt`
3. 运行模型：`python model.py`
4. 运行 Jupyter Notebook 示例：`jupyter notebook notebooks/example_notebook.ipynb`

## 许可证
MIT License
