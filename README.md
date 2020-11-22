# 改造frp

参考了uknowsec的frp改造计划，链接在这：https://uknowsec.cn/posts/notes/FRP%E6%94%B9%E9%80%A0%E8%AE%A1%E5%88%92.html

改动：

- 加入了sock5代理
- 添加连接客户端认证 用户密码：pentest/luckyeast
- 增加指定sock5端口参数
- t参数指定远程服务器IP， p参数指定frps监听端口，r参数指定sock5端口

usage： 客户端： frpc.exe -t 1.1.1.1 -p 7777 -r 2333

