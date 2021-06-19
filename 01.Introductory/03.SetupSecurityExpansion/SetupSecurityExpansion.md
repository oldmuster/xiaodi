## 基础入门-搭建安全拓展

- **常见搭建平台脚本启用**

- **域名IP目录解析安全问题**

- **常见文件后缀解析对应安全**

- **常见安全测试中的安全防护**

- **WEB后门与用户及文件权限**

```
#ASP, PHP, ASPX, JSP, PY, JAVAWEB等环境

#WEB源码中敏感文件
后台路径，数据库配置文件，备份文件

#IP或域名解析WEB源码目录对应下的存在的安全问题
域名访问，IP访问（结合类似备份文件目录）

使用IP地址进行访问一个网站时，一般访问的是网站域名的上一级。
出现这个现象的原因：
	一般网络在搭建的过程中，既支持IP访问也支持域名访问，域名在访问时一般是指向某个目录，而IP地址在访问时一般是指向根目录

#脚本后缀对应解析（其他格式可相同-上传安全）
#存在下载或为解析问题

#常见防护中的IP验证，域名验证等

#后门是否给予执行权限
#后门是否给予操作目录或文件权限
#后门是否给予其他用户权限

#总结下关于可能会存在的安全或防护问题
```

### 演示案例

```
基于中间件的简要识别
	通过返回的数据包中server可以识别网站的中间件平台
	根据不同的搭建平台可以找到不同的漏洞
基于中间件的安全漏洞
基于中间件的靶场使用
```
