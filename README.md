# 港股多因子回测系统

## 🌐 在线访问
访问: https://stevenwangj-shanghai.github.io/hk-stock-backtest/index.html

## 📦 后端下载运行

### 方法1: 直接下载
点击右侧 Releases 查看源代码下载

### 方法2: 命令行
```bash
# 下载后端代码
wget https://github.com/stevenwangj-shanghai/hk-stock-backtest/raw/main/hk_backtest.zip
unzip hk_backtest.zip
cd hk_backtest

# 安装依赖
pip install flask pandas numpy

# 运行
python app.py
```

### 前端修改API地址
如果后端不在 47.253.131.29:5000，需修改 index.html 中的：
```javascript
const API_BASE = 'http://你的服务器IP:5000';
```

## 📋 功能
- 获取港股列表
- 运行多因子回测
- 查看收益曲线、持仓、交易记录
