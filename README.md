# A-share-quant-strategies
# A股量化策略仓库

这是一个专门存放A股量化交易策略的GitHub仓库，用于管理、版本控制和分享我的Python量化策略代码。

---

## 仓库简介
- 主要语言：Python
- 策略框架：基于QMT量化交易平台API开发
- 适用市场：A股（沪深主板、创业板）
- 数据来源：本地行情数据 + 第三方财经API

---

## 仓库结构
A-share-quant-strategies/
├── strategies/ # 核心策略代码目录
│ ├── double_sma.py # 双均线策略示例
│ ├── breakout.py # 突破交易策略
│ └── grid_trade.py # 网格交易策略
├── utils/ # 工具函数库
│ ├── data_fetch.py # 数据获取工具
│ └── risk_control.py # 风险控制模块
├── .gitignore # 忽略文件配置
└── README.md # 仓库说明文档

---

## 策略使用方法

### 1. 本地环境准备
- 安装Python 3.8+
- 安装依赖库：
  ```bash
  pip install pandas numpy tushare
  git clone https://github.com/lianhou8988-quant/A-share-quant-strategies.git
cd A-share-quant-strategies
python strategies/double_sma.py

粘贴完成后，拉到页面底部，点「Commit changes」就保存成功了。

---
仓库配置到这里就基本完成啦！接下来你就可以把本地的策略代码推上来了，需要我给你一份完整的 Git 命令清单吗？
