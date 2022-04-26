## SCM_RIGHTS

使用sendmsg + SCM_RIGHTS实现跨进程 dup(fd)

https://blog.cloudflare.com/know-your-scm_rights 


### This is a sample code for my Cloudflare blogpost about SCM_RIGHTS

Instructions:

Run `make`
Then launch `c_serv` and one of `rust_serv` or `go_serv`
Test using `echo passwhatever | nc localhost 8001` to get response from the secondary server or `echo anythingelse | nc localhost 8001` to get response from the C server


## Nginx Envoy MOSN热升级对比
https://ms2008.github.io/2019/12/28/hot-upgrade/

## TCP连接迁移示例
https://zhuanlan.zhihu.com/p/97340154
