# 修改host实现访问GitHub、谷歌等网站

- 很多小伙伴很大程度上都依赖于GitHub仓库，来管理自己的代码，但是近期有GitHub频频登录不上，导致自己辛辛苦苦码的程序变成了与世无关的东西，就有点太惨了；
- 有些需要谷歌账号，同步相关的收藏还有一些插件，又或者喜欢谷歌的所有方式等等原因；但是奈何VPN太贵，代理使用太过繁琐，那么简单而又实用的方法来了；
- 所以想到通过  **C:\Windows\System32\drivers\etc\hosts** 文件来实现，对其的访问。

---
## 1.host介绍  

- host 文件主要用于存储计算机网络中节点信息等，主要是映射相应IP地址，实现DNS的功能。也就是说当打开一个网址时，计算机会现在host文件中查找对应IP地址建立关联，如果host没有找到对应的网址，则交给DNS域名解析服务器来解析。
- 也就是说，如果我们访问Google时，知道它的IP地址，就不用让DNS域名解析服务器解析了，就可以直接访问了。

---

## 2.咋个知道网址的IP地址  

可以直接登录这个进行查询对应网址的IP地址  ：

​                                              [查询对应IP地址](https://www.ipaddress.com/)  

---

## 3.如何修改host  

- 自然用自己勤劳的双手修改了，这里仅仅以Windows为例，路径存在  **C:\Windows\System32\drivers\etc\hosts**  

- 这里自然建议使用工具进行修改，  [SwitchHosts](<https://oldj.github.io/SwitchHosts/#cn>)   

- 或者也可以使用前人大佬已经总结好的host文件  

  链接: https://pan.baidu.com/s/1R1StMAoKVHRM1McPMnZLXw     提取码: f987   

  [大佬网站-老D博客](<https://laod.cn/hosts/2020-hosts.html>)    解压密码：LAOD  

---

## 4. 如何访问  

- 还需以法宝-谷歌浏览器需要金丝雀版或者最新的Dev开发板

  [WIN 32下载](<https://laod.cn/wp-content/themes/begin/go.php?url=aHR0cHM6Ly9yZWRpcmVjdG9yLmd2dDEuY29tL2VkZ2VkbC9yZWxlYXNlMi9jaHJvbWUvQU44X3B1X0J0T1dEMGZCeHFHWVp6enNfODIuMC40MDU0LjIvODIuMC40MDU0LjJfY2hyb21lX2luc3RhbGxlci5leGU=>)  

  [WIN 64下载](<https://laod.cn/wp-content/themes/begin/go.php?url=aHR0cHM6Ly9yZWRpcmVjdG9yLmd2dDEuY29tL2VkZ2VkbC9yZWxlYXNlMi9jaHJvbWUvQUtqWWIzOXdVTkljdGdMRGZlTXJkVWNfODIuMC40MDU0LjIvODIuMC40MDU0LjJfY2hyb21lX2luc3RhbGxlci5leGU=>)

---

## 结语

- 感谢各位大佬们的网络支持；充分了解了计算机DNS解析的运作，其次就是完成了实现自我手动解析DNS的小确幸！  

   感谢  [一键墙包哦](<https://github.com/bannedbook/fanqiang/wiki>)    

   感谢 [老D博客](<https://laod.cn/>) 

  == 如果遇到不能连接访问，可以使用  [SwitchHosts](<https://oldj.github.io/SwitchHosts/#cn>)  ，关闭打开即可 ==

- 网络审查在各国家都普遍存在，他并不仅仅存在于中国。在全球的局势下对中国都不利的当下，当局会过滤掉影响、危害到中国长远发展的信息，此时国家的安全的意义更加重大。
- 所以请正确使用此服务，请尊重并理解当局做法更不要盲目攻击当局做法。
- 拜谢！！