# adguard-home-rules

| 规则名称                   | 订阅地址                                                     | 说明                                                         |
| -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| anti-AD                    | https://anti-ad.net/easylist.txt                             | 命中率最高列表，每天更新维护                                 |
| Halflife规则               | https://gitee.com/halflife/list/raw/master/ad.txt            | 涵盖了 EasyList China、EasyList Lite、CJX ’s Annoyance、乘风视频过滤规则，以及补充的其它规则 |
| EasyPrivacy                | https://easylist.to/easylist/easyprivacy.txt                 | 去除隐私、跟踪定位相关代码                                   |
| I don't care about cookies | https://www.i-dont-care-about-cookies.eu/abp                | 去除隐私、跟踪定位相关代码                                   |
| 百万ADH广告拦截过滤规则    | https://raw.githubusercontent.com/BlueSkyXN/AdGuardHomeRules/master/all.txt | 国内通用型，去广告能力较强                                   |
| 1024_hosts                 | https://cdn.jsdelivr.net/gh/Goooler/1024_hosts@master/hosts  | host去除法                                                   |
| adgk手机去广告规则         | https://cdn.jsdelivr.net/gh/banbendalao/ADgk@master/ADgk.txt | 手机代码去广告，手机版本推荐订阅                             |
| 大圣净化                   | https://cdn.jsdelivr.net/gh/jdlingyu/ad-wars@master/hosts    | host去除法                                                   |
| CJX's Annoyance List       | https://cdn.jsdelivr.net/gh/cjx82630/cjxlist@master/cjx-annoyance.txt | 去自我推广列表                                               |
|                            |                                                              |                                                              |

## 上游 DNS 服务器

```yaml
114.114.114.114
https://dns.alidns.com/dns-query
https://doh.pub/dns-query
https://doh.360.cn/dns-query
https://dns.cloudflare.com/dns-query
https://dns.google/dns-query
https://dns.adguard.com/dns-query
https://dns.quad9.net/dns-query
https://dns.nextdns.io # /id/你的设备名称
```



## Bootstrap DNS 服务器

```yaml
223.5.5.5
114.114.114.114
119.29.29.29
101.226.4.6
180.76.76.76
117.50.10.10
1.1.1.1
8.8.8.8
9.9.9.10
149.112.112.10
2620:fe::10
2620:fe::fe:10
```

