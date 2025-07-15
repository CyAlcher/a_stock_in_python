# chapter1：A股市场与金融数据基础

本章节代码用于分析大陆A股市场的行业分布，并介绍各类金融数据类型。  
主要内容包括：  

## 1.1 A股市场结构与主要指数
- 使用pandas、matplotlib等库对A股上市公司行业分布进行统计
- 绘制行业分布条形图，图表保存在`./images/industry_distribution.png`
- 运行环境与依赖说明

## 1.2 常见金融数据类型（K线、分笔、财报、公告等）
- K线数据的获取与分析：股票历史行情数据，包含开盘价、收盘价、最高价、最低价、成交量等
- 分笔数据的获取与分析：实时交易数据，记录每笔交易的价格、数量、时间等详细信息
- 财报数据的获取与分析：上市公司财务报表数据，包括资产负债表、利润表、现金流量表
- 公告数据的获取与分析：企业公告信息，包括定期报告、重大事项公告、监管公告等
- 各类数据的可视化展示与对比分析

## 运行环境
- Python 环境: fin_ai_39
- 依赖库: pandas, numpy, matplotlib, akshare, seaborn, datetime
- 字体文件: /Users/max/Downloads/simkai.ttf

## 生成结果

### 1.1 A股市场结构与主要指数
- 行业分布图表保存在：`./images/industry_distribution.png`

### 1.2 常见金融数据类型  
- K线数据：`./outputs/kline_data_000001.csv`
- 分笔数据：`./outputs/tick_data_000001.csv`
- 财报数据：`./outputs/financial_data_600519.csv`
- 公告数据：`./outputs/announcement_data_002594.csv`
- 相关图表：`./outputs/` 目录下的 `*_visualization_*.png` 文件

## 联系方式

如需交流或获取更多信息，欢迎关注我的公众号，添加微信进群交流量化技术：

| 公众号 | 微信 |
| :----: | :--: |
| ![](png/gzh.png) | ![](png/wchat.png) |
