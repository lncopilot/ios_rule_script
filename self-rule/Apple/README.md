# 🧸 Self-Rule

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-DOMAIN--SUFFIX间合并-critical) ![](https://shields.io/badge/-DOMAIN与DOMAIN--KEYWORD合并-9cf) ![](https://shields.io/badge/-DOMAIN--SUFFIX与DOMAIN--KEYWORD合并-blue) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) 

自定义规则由《RULE GENERATOR 规则生成器》自动生成。

目前有以下规则类型：

    - AppleUpdateRules 是与本地化息息相关的规则，比如地图、天气、查找、Facetime、Apple Pay ( iCloud 上传与下载也归于此规则集

    - AppleCDNRules 是苹果的全球 CDN

    - AppleNoChinaCDNRules 是大陆没有的 CDN 节点

    - AppleAPIRules 是苹果的 API 域名

分流规则是互联网公共服务的域名和IP地址汇总，所有数据均收集自互联网公开信息，不代表我们支持或使用这些服务。

请通过【中华人民共和国 People's Republic of China】合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。

## 规则统计

最后更新时间：2024-01-08 16:02:56

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| DOMAIN-SUFFIX | 3  | 
| DOMAIN-KEYWORD | 1 |
| TOTAL | 4  | 


## Clash 

#### 使用说明

##### 使用中国区账号（App Store + iCloud）
AppleUpdateRules 直连

AppleCDNRules 直连

AppleNoChinaCDNRules 代理

AppleAPIRules 直连

##### 使用美国区账号（App Store + iCloud）
AppleUpdateRules 直连

AppleCDNRules 直连

AppleNoChinaCDNRules 代理

AppleAPIRules 代理

建议 AppleAPIRules 依然直连，上文是根据上述文章给出的建议，请结合自身情况使用

#### 规则链接
**MASTER分支 (每日更新)**

https://raw.githubusercontent.com/OxygenLost/ios_rule_script/master/self-rule/Apple/AppleUpdateRules.yaml

https://raw.githubusercontent.com/OxygenLost/ios_rule_script/master/self-rule/Apple/AppleCDNRules.yaml

https://raw.githubusercontent.com/OxygenLost/ios_rule_script/master/self-rule/Apple/AppleNoChinaCDNRules.yaml

https://raw.githubusercontent.com/OxygenLost/ios_rule_script/master/self-rule/Apple/AppleAPIRules.yaml

**MASTER分支 CDN (每日更新)**

https://cdn.jsdelivr.net/gh/OxygenLost/ios_rule_script@master/self-rule/Apple/AppleUpdateRules.yaml

https://cdn.jsdelivr.net/gh/OxygenLost/ios_rule_script@master/self-rule/Apple/AppleCDNRules.yaml

https://cdn.jsdelivr.net/gh/OxygenLost/ios_rule_script@master/self-rule/Apple/AppleNoChinaCDNRules.yaml

https://cdn.jsdelivr.net/gh/OxygenLost/ios_rule_script@master/self-rule/Apple/AppleAPIRules.yaml

**MASTER分支 GHProxy (每日更新)**

https://ghproxy.com/https://raw.githubusercontent.com/OxygenLost/ios_rule_script/master/self-rule/Apple/AppleUpdateRules.yaml

https://ghproxy.com/https://raw.githubusercontent.com/OxygenLost/ios_rule_script/master/self-rule/Apple/AppleCDNRules.yaml

https://ghproxy.com/https://raw.githubusercontent.com/OxygenLost/ios_rule_script/master/self-rule/Apple/AppleNoChinaCDNRules.yaml

https://ghproxy.com/https://raw.githubusercontent.com/OxygenLost/ios_rule_script/master/self-rule/Apple/AppleAPIRules.yaml


## 子规则/排除规则


当前分流规则，未包含其他子规则。

