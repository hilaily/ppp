# PPP
## 三种使用方式
1 启动 http 代理服务  
ppp http {ip:port}  
2 启动 socks5 代理服务  
ppp socks {ip:port}  
3 socks5 代理 转 http 代理  
ppp s2h {socks5_ip:port} {http_ip:port}   