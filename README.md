# MFE5210 量化投资策略
本项目实现了多个量化投资策略，包括动量因子、RSI 因子等多因子策略的实现与回测。  
数据说明   
• 使用 Tushare Pro 接口获取股票数据   
• 策略测试期：2015-01-01 至 2023-12-31   
• 策略验证期：2024-01-01 至 2025-0514   
• 股票池：沪深300成分股    

## 项目结构
策略说明 
1. 动量因子策略 
• 使用历史价格数据计算动量因子 
• 通过低通滤波处理去除市场噪声 
• 结合波动率进行风险调整  
2. mv市值因子策略 
• 获取市值数据
• 通过波动率因子进行优化 
• 实现动态调仓机制
3. RSI 因子策略 
• 计算相对强弱指数(RSI) 
• 通过波动率因子进行优化 
• 实现动态调仓机制

## 最终结果
sharp ratio
动量因子策略：-0.63
mv市值因子策略： -0.03
RSI 因子策略： 0.23
动量因子策略：![image](https://github.com/user-attachments/assets/d3a18187-a977-4ed1-aa1e-544a84e03a6c)
mv市值因子策略：![image](https://github.com/user-attachments/assets/ad8836ff-5cb0-4231-a8d1-b241ae1db80b)
RSI 因子策略：![image](https://github.com/user-attachments/assets/adf8ee2a-d9b9-4556-a834-55c76ed62d3d)


