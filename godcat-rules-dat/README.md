本插件为香港本地定位节点插件（插件名称为： HK-ALL）

本插件集合香港银行 # —— 传统商业银行 —— # —— 数字/虚拟银行 —— # —— 香港本土生活与电信 ——

套用代码： 

rule-providers:
HK-ALL:    { type: http, behavior: domain, interval: 86400, url: "https://raw.githubusercontent.com/yaorongle/zashboard/refs/heads/main/godcat-rules-dat/hk_all.yaml", path: ./rules/hk_all.yaml }

rules:
  - RULE-SET,HK-ALL,香港



这份列表包含了香港地区的主要金融机构（传统银行与虚拟银行）、本地生活服务、电讯、电子支付以及政府官方网站。它们通常出现在网络代理（如 Clash、Shadowrocket 等）的规则分流（Routing Rules）配置中，用于将这些香港本土网站的流量划分为“直连”或“走香港节点”。

以下是这些域名的具体分类和对应网站介绍：

一、 传统商业银行
这些是香港传统的大型实体商业银行或其在香港的分支机构：

+.hsbc.com.hk：香港上海汇丰银行（HSBC）—— 香港最大的注册银行。

+.hangseng.com：恒生银行（Hang Seng Bank）—— 汇丰集团成员，香港主要本土银行之一。

+.icbcasia.com：工银亚洲（ICBC Asia）—— 中国工商银行在香港的业务分支。

+.sc.com：渣打银行（Standard Chartered）—— 香港三家发钞银行之一。

+.cncbinternational.com：信银国际（信中信银行国际，CNCBI）。

+.ccb.com：中国建设银行（CCB，包含建行亚洲的业务）。

+.bochk.com：中国银行（香港）（BOCHK）—— 香港三家发钞银行之一。

+.cmbwinglungbank.com：招商永隆银行（CMB Wing Lung Bank）—— 招商银行全资附属银行。

+.hkbea.com：东亚银行（BEA）—— 香港最大的本地华资银行之一。

+.dahsing.com：大新银行（Dah Sing Bank）。

二、 数字/虚拟银行
这些是近年来由香港金融管理局（金管局）颁发牌照、没有实体分行、完全通过手机 App 提供服务的全数字虚拟银行：

+.pingandb.com：平安壹账通银行（PAOB）—— 平安集团旗下虚拟银行。

+.elebank.com：理慧银行（Livi Bank）—— 由中银香港、京东科技及怡和集团合资成立。

+.za.group：众安银行（ZA Bank）—— 香港第一家也是目前规模较大的虚拟银行。

+.welab.bank：汇立银行（WeLab Bank）—— 香港本土金融科技集团 WeLab 旗下的虚拟银行。

+.antbank.hk：蚂蚁银行（Ant Bank）—— 蚂蚁集团旗下虚拟银行（支付宝母公司）。

+.livibank.com：理慧银行（Livi Bank）的另一个常用域名（同 elebank.com 关联）。

+.fusionbank.com：富融银行（Fusion Bank）—— 腾讯集团、港交所等合资成立。

+.airstarbank.com：天星银行（Airstar Bank）—— 小米集团与尚乘集团合资成立。

三、 香港本土生活与电信
这些是香港居民日常生活中最常用的民生、消费、娱乐、电讯及政府服务网站：

+.hkjc.com：香港赛马会（HKJC）—— 负责香港赛马、六合彩及体育博彩的机构，也是香港最大的慈善公益资助机构。

+.hkcsl.com：CSL Mobile —— 香港主要移动电讯运营商之一（现属于电讯盈科 HKT）。

+.octopus.com.hk / +.octopuscards.com：八达通（Octopus）—— 香港最普及的电子收费系统（交通、零售必备）。

+.price.com.hk：香港格价网（Price.com.hk）—— 香港本地最著名的电子产品及生活百货比价购物平台。

+.tvb.com：无线电视（TVB）—— 香港主要的免费电视台官方网站。

+.mytvsuper.com：myTV SUPER —— TVB 旗下的网络流媒体视频平台（相当于香港的爱奇艺/腾讯视频）。

+.gov.hk：香港特别行政区政府一站通（GovHK）—— 香港政府各部门的官方门户网站，用于办理各种政府公共服务（如报税、预约换证等）。
