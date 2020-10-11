# MyBlog
一个简单的黑与白主题的个人博客，基于Django。

博客地址:black-white.me（域名已过期）

博客服务器基于Ubuntu使用Ngnix作为HTTP代理用于接收WEB的所有请求并统一请求管理，将所有的静态文件交给Ngnix管理、
Ngnix将所有非静态请求通过uWSGI传递给Django，由Django进行处理并返回，从而完成一次WEB请求。
