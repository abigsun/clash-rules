# clash-rules
rules for clash


Windows版  Clash Verge
方法1.直接修改订阅文件，适用于订阅文件不需要更新的
  <img width="1884" height="1014" alt="image" src="https://github.com/user-attachments/assets/6d1c60c1-a8e1-4f93-bbe1-6a26113120ba" />
修改 clash-verge
在Prepend-rules：
下面添加
方法2，增量合并，订阅更新不会丢失
在订阅栏，全局扩展覆写配置，双击
删除所有
添加
prepend-rules:
  - DOMAIN-KEYWORD,wechat,DIRECT
