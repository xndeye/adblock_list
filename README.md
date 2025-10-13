# AbBlock List

![Last Update](https://img.shields.io/github/last-commit/xndeye/adblock_list?style=flat-square&branch=release)
![Build Status](https://img.shields.io/github/actions/workflow/status/xndeye/adblock_list/auto-update.yml?branch=main&style=flat-square)
![Stars](https://img.shields.io/github/stars/xndeye/adblock_list?style=flat-square)
![Forks](https://img.shields.io/github/forks/xndeye/adblock_list?style=flat-square)


💪 强大而克制的广告过滤规则，可拦截 99%[^1] 的 Web 广告！

> [!TIP]
> 本仓库通过 [ad-filters-subscriber](https://github.com/fordes123/ad-filters-subscriber/) 构建，定时合并多个优质上游规则，并去除重复和失效项。  
> 构建和转换错误请反馈至 [此处](https://github.com/fordes123/ad-filters-subscriber/issues)，误杀和规则推荐请提交至本仓库 [issues](https://github.com/xndeye/adblock_list/issues)

| 文件              | 说明                          |        github        |         ghproxy          |         jsdelivr          |
|-----------------|:----------------------------|:--------------------:|:------------------------:|:-------------------------:|
| `easylist.txt`  | 完整主规则                       | [link][easylist-raw] | [link][easylist-ghproxy] | [link][easylist-jsdelivr] |
| `modify.txt`    | 不含 DNS 过滤规则的 `easylist.txt` |  [link][modify-raw]  |  [link][modify-ghproxy]  |  [link][modify-jsdelivr]  |
| `dns.txt`       | 仅含 DNS 过滤规则的 `easylist.txt` |   [link][dns-raw]    |   [link][dns-ghproxy]    |   [link][dns-jsdelivr]    |
| `dnsmasq.conf`  | dnsmasq 及其衍生版本              | [link][dnsmasq-raw]  | [link][dnsmasq-ghproxy]  | [link][dnsmasq-jsdelivr]  |
| `clash.yaml`    | clash 及其衍生版本                |  [link][clash-raw]   |  [link][clash-ghproxy]   |  [link][clash-jsdelivr]   |
| `smartdns.conf` | smartdns                    | [link][smartdns-raw] | [link][smartdns-ghproxy] | [link][smartdns-jsdelivr] |
| `hosts`         | 几乎所有操作系统原生支持                |  [link][hosts-raw]   |  [link][hosts-ghproxy]   |  [link][hosts-jsdelivr]   |
| `private.txt`   | 本仓库维护的私有规则，以 easylist 形式提供  | [link][private-raw]  | [link][private-ghproxy]  | [link][private-jsdelivr]  |

[easylist-raw]: https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/easylist.txt

[easylist-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/easylist.txt

[easylist-jsdelivr]: https://gcore.jsdelivr.net/gh/ALLOVERleng/ad-filters-subscriber@refs/heads/release/easylist.txt

[modify-raw]: https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/modify.txt

[modify-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/modify.txt

[modify-jsdelivr]: https://gcore.jsdelivr.net/gh/ALLOVERleng/ad-filters-subscriber@refs/heads/release/modify.txt

[dns-raw]: https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/dns.txt

[dns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/dns.txt

[dns-jsdelivr]: https://gcore.jsdelivr.net/gh/ALLOVERleng/ad-filters-subscriber@refs/heads/release/dns.txt

[dnsmasq-raw]: https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/dnsmasq.conf

[dnsmasq-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/dnsmasq.conf

[dnsmasq-jsdelivr]: https://gcore.jsdelivr.net/gh/ALLOVERleng/ad-filters-subscriber@refs/heads/release/dnsmasq.conf

[clash-raw]: https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/clash.yaml

[clash-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/clash.yaml

[clash-jsdelivr]: https://gcore.jsdelivr.net/gh/ALLOVERleng/ad-filters-subscriber@refs/heads/release/clash.yaml

[smartdns-raw]: https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/smartdns.conf

[smartdns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/smartdns.conf

[smartdns-jsdelivr]: https://gcore.jsdelivr.net/gh/ALLOVERleng/ad-filters-subscriber@refs/heads/release/smartdns.conf

[hosts-raw]: https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/hosts

[hosts-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/hosts

[hosts-jsdelivr]: https://gcore.jsdelivr.net/gh/ALLOVERleng/ad-filters-subscriber@refs/heads/release/hosts

[private-raw]: https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/private.txt

[private-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/ALLOVERleng/ad-filters-subscriber/refs/heads/release/private.txt

[private-jsdelivr]: https://gcore.jsdelivr.net/gh/ALLOVERleng/ad-filters-subscriber@refs/heads/release/private.txt

<details>
<summary>点击查看上游规则</summary>
<ul>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt">AdGuard 基础过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt">AdGuard 移动广告过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt">AdGuard 防跟踪保护过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_17_TrackParam/filter.txt">AdGuard URL跟踪过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt">AdGuard 恼人广告过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt">AdGuard 解除搜索广告和自我推销过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt">AdGuard 中文过滤器</a></li>
    <li><a href="https://github.com/TG-Twilight/AWAvenue-Adblock-Rule">AWAvenue-Adblock-Rule</a></li>
    <li><a href="https://raw.githubusercontent.com/Noyllopa/NoAppDownload/master/NoAppDownload.txt">NoAppDownload</a></li>
    <li><a href="https://github.com/xndeye/web-ad-rule">xndeye/web-ad-rule</a></li>
    <li><a href="https://github.com/xinggsf/Adblock-Plus-Rule">xinggsf/Adblock-Plus-Rule</a></li>
    <li><a href="https://github.com/damengzhu/banad">damengzhu/banad</a></li>
    <li><a href="https://github.com/cjx82630/cjxlist">cjx82630/cjxlist</a></li>
    <li><a href="https://easylist-downloads.adblockplus.org/antiadblockfilters.txt">ABP EasyList</a></li>
    <li><a href="https://easylist-downloads.adblockplus.org/abp-filters-anti-cv.txt">ABP anti-circumvention filter list</a></li>
    <li><a href="https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/privacy.txt">uBlockOrigin privacy</a></li>
    <li><a href="https://raw.githubusercontent.com/SystemJargon/filters/refs/heads/main/telemetry.txt">Telemetry Lists - Aggregated</a></li>
</ul>
</details>

[^1]: 数据在 `Chrome 130.0` 上使用 `AdGuard 浏览器扩展` 订阅本仓库 `easylist.txt` 规则，
通过 [d3ward/toolz](https://d3ward.github.io/toolz/adblock.html) 测得，[结果](https://github.com/user-attachments/assets/76ccfcac-9ffd-4bed-89d7-08cdfe6cc33d)仅供参考
