# Zashboard 面板 (Mihomo内核)

本文件是基于Magic Catling2制作
专用于添加订阅网络节点使用。

增加：香港银行规则锁定香港节点

增加: 香港证券域名规则锁定香港节点

移除：ChatGPT, TikTok移除香港节点


请按照标准格式提问！！！
【不按此格式提问一律不回答】
-----------------------
路由型号:
固件版本:
MC插件版本:
-----------------------
是否开启路由IPv6支持：
(是 / 否)
-----------------------
DNS模式: Fake-ip

#Fake IP
dns:
  enable: true
  ipv6: true
  enhanced-mode: fake-ip
  listen: :23453
  fake-ip-range: 198.18.0.1/16
  fake-ip-range6: fdfe:dcba:9876::1/64
  fake-ip-filter-mode: rule
  respect-rules: false
  prefer-h3: false
  fake-ip-filter:
    - RULE-SET,cn,real-ip
    - RULE-SET,private,real-ip
    - RULE-SET,geolocation-!cn,fake-ip
    - MATCH,fake-ip
  default-nameserver:
    - 223.5.5.5
    - 182.254.116.116
    - 202.96.128.86    
  nameserver:
    - tls://dns.alidns.com:853
    - tls://dot.pub:853
  proxy-nameserver:
    - tls://one.one.one.one:853
    - tls://dns.google:853
-----------------------
高级设置 > 代理设置 > 代理模式: 
Redir TCP & Tproxt UDP
-----------------------
IPv6转发:
(关闭 / 开启)
-----------------------
订阅规则:
(MC系列规则 / 订阅原始规则 /  YAML上传)
-----------------------
是否开启其他功能:
( 访问控制 / 大陆IP绕行 / 代理路由自身流量 / 自定义IPtables分流规则)
-----------------------

C.PC的 本地连接 状态 详细信息 
