本插件为香港本地定位节点插件（插件名称为： HK-ALL）

本插件集合香港银行
# —— 传统商业银行 —— # —— 数字/虚拟银行 —— # —— 香港本土生活与电信 ——

套用代码： 

rule-providers:
HK-ALL:    { type: http, behavior: domain, interval: 86400, url: "https://raw.githubusercontent.com/yaorongle/zashboard/refs/heads/main/godcat-rules-dat/hk_all.yaml", path: ./rules/hk_all.yaml }

rules:
  - RULE-SET,HK-ALL,香港
