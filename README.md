<div align="center">
  <h1>🛠️ AlphaGBM Skills: AI 量化投研与期权分析框架</h1>
  
  <p>专业的金融量化 Agent 技能库 (Skills) 与本地命令行 (CLI) 终端工具</p>

  <!-- 核心引流按钮：极客风格徽章，高点击率 -->
  <a href="https://www.alphagbm.com/" target="_blank">
    <img src="https://img.shields.io/badge/🚀_免本地部署_开箱即用-访问_AlphaGBM_全功能网页工作台-0052FF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="AlphaGBM Web Workspace">
  </a>
  <a href="https://t.zsxq.com/38xGE" target="_blank">
    <img src="https://img.shields.io/badge/🌍_每日实盘与AI复盘-加入_AlphaGBM_投研圈-07C160?style=for-the-badge&logo=wechat&logoColor=white" alt="Knowledge Planet">
  </a>
</div>

<br>

> ### 🛑 给投资者的温馨提示
> 本开源仓库主要为您提供底层的 **AI 投研提示词（Skills）** 与 **本地 CLI 开发环境**，适合有 Python 基础的量化极客（Quants）和开发者。
> 
> **如果您不想折腾环境配置、API 密钥，希望能把精力 100% 专注在交易本身上：**
> 
> **强烈建议您直接使用我们的 👉 [AlphaGBM 网页端云工作台](https://www.alphagbm.com/)**！网页端不仅完美内置了本仓库所有的分析模块，还独家集成了：
> * 🌐 **四大市场实时数据统一分析**（美股·港股·A股·商品期货）
> * 🧠 **前沿大模型智能路由**（聚合 Gemini / Claude / GPT 等最强算力）
> * 📖 **AI 自动归档知识库**（按股票 Ticker 自动整理您的复盘笔记与资讯）

---

## 🧰 核心 AI 投研 Skills 模块目录

我们已将资深交易员的分析逻辑封装为高度模块化的 Skills。所有文件均位于 [`skills/`](./skills) 目录下：

### 📈 期权与波动率分析 (Options & Volatility)
* `alphagbm-greeks`: 期权希腊字母深度诊断与风险暴露拆解
* `alphagbm-vol-smile`: 波动率微笑曲线异常检测与套利机会识别
* `alphagbm-vol-surface`: 波动率曲面立体变动分析
* `alphagbm-iv-rank`: 隐含波动率百分位 (IVR/IVP) 评估
* `alphagbm-options-strategy`: 多腿期权策略智能生成与评估
* `alphagbm-options-score`: 期权多维度综合打分
* `alphagbm-unusual-activity`: 期权异动大单（Unusual Options Activity）追踪
* `alphagbm-pnl-simulator`: 期权策略到期盈亏 (PnL) 情景模拟推演

### 👑 大师投资框架 (Investment Masters)
* `alphagbm-buffett-analysis`: 巴菲特视角（自由现金流、ROE、宽广护城河体检）
* `alphagbm-duan-analysis`: 段永平视角（商业模式理解与绝对估值）
* `alphagbm-marks-cycle`: 霍华德·马克斯（宏观市场周期与钟摆位置定位）

### 🛡️ 风控与市场情绪信号 (Risk & Sentiment)
* `alphagbm-hedge-advisor`: 针对当前持仓组合的智能对冲保护建议
* `alphagbm-take-profit`: 动态止盈与仓位退出策略评估
* `alphagbm-fear-score` / `vix-status`: 结合 VIX 指数的恐慌/贪婪水位预警
* `alphagbm-tepper-signal`: 大卫·泰珀（David Tepper）宏观流动性信号
* `alphagbm-earnings-crush`: 财报季 IV Crush（波动率回归）风险评估
* `alphagbm-chokepoint` / `alert`: 关键支撑阻力位识别与交易信号警报

### 📊 股票基本面与宏观研究 (Equities & Macro)
* `alphagbm-stock-analysis` / `company-profile`: 股票全方位体检与商业模式画像
* `alphagbm-macro-view`: 宏观经济数据解读与大类资产配置视图
* `alphagbm-theme-research` / `compare`: 主题赛道研究与多标的横向对比
* `alphagbm-bps-backtest`: BPS 策略回测逻辑支持

---

## 💻 本地 CLI 部署与使用指南 (Local Deployment)

本仓库提供了一个纯本地运行的终端分析工具：`alphagbm_cli`。

### 1. 环境准备
确保您的本地环境已安装 **Python 3.8+**。建议使用虚拟环境（venv 或 conda）。

### 2. 克隆仓库
```bash
git clone [https://github.com/AlphaGBM/skills.git](https://github.com/AlphaGBM/skills.git)
cd skills
