# Axios试用
试用Axios发请求以及拦截器功能。

axios 在本地 http-server 发GET以外的请求会触发CORS预检，错误405。

暂时没找到解决办法，先用server.js做个服务器接收这些请求，再axios拦截吧。

server.js启用

```bash
node server.js 6000
```

