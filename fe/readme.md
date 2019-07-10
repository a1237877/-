## Cors
规定了一组http 的头部字段作用时 允许哪些网站通过浏览器有访问的权限
1. access-X
2. cookie
3. 浏览器会先 以 OPTIONS 请求方法发起一个预检(preflight)请求
获取一下允不允许当前请求
