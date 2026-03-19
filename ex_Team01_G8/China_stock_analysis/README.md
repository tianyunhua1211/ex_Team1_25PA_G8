# 中国股票市场概览数据分析
    ## 项目说明
本项目对中国A股市场的上市公司数量、板块分布及行业结构进行统计分析。

## 数据来源
- adata库（聚合自东方财富、同花顺等公开数据源）
- 中国上市公司协会月度报告
- 上海证券报专题报道

## 目录结构
China_stock_analysis/
│
├── data/ # 原始和处理后的数据
│ ├── raw/ # 下载的原始数据
│ └── processed/ # 清洗后的数据
│
├── output/ # 输出结果
│ ├── tables/ # 统计表格（CSV）
│ └── figures/ # 可视化图表（PNG）
│
├── reports/ # 完整分析报告（Excel）
│
├── requirements.txt # 依赖包列表
├── README.md # 本文档
└── China_stock_analysis.ipynb # 主分析文件

text

## 运行方法
1. 安装依赖：`pip install -r requirements.txt`
2. 启动 Jupyter Notebook 或 VSCode
3. 打开 `China_stock_analysis.ipynb` 并运行所有单元格

## 注意事项
- 行业分布数据基于抽样估算，如需精确数据请使用专业数据库
- 如遇网络问题，程序会自动使用本地缓存
