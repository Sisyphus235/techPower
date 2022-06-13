# techPower

a repo accelerating routines by tech

## 20220612

initiation  

确定方向：兴趣方向 + 技术磨练 + 用户价值 3 块的交集做点事情。   

潜在内容：
  
1. 年化收益率 XIRR 在线工具（参考[阿布量化](https://www.abuquant.com/index))；

2. git 的封装工具，实现简历/文档的版本控制；
    
    问题：简历数据存储？安装内部的gitlab仓库？个人数据大小限制？
    
    考虑：git命令封装常用的commit，push，diff接口。自动化处理临时版本管理、版本回退恢复，以及冲突问题。
    
    代办：
    
    1. 确认文本转PDF库（很多App支持转HTML、DOC、PDF，考虑是否需要支持）。
    2. 确认git形式，开源Gitlab/GitHub openapi ? 本地git存储+自定义api。
    3. 确认默认的文本形式，需考虑用户输入形式，用户文本自动识别？给定形式输入生成？
    4. 确认是否支持生成多种样式（简历的不同样子）。

3. 日后工作流（朋友生日->祝福发送）；

> TODO: XIRR 工具产品设计 + git repo 建立同步
