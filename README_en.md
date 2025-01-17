# AdBlock List

![Last Update](https://img.shields.io/github/last-commit/xndeye/adblock_list?style=flat-square&branch=release)
![Build Status](https://img.shields.io/github/actions/workflow/status/xndeye/adblock_list/auto-update.yml?branch=main&style=flat-square)
![Stars](https://img.shields.io/github/stars/xndeye/adblock_list?style=flat-square)
![Forks](https://img.shields.io/github/forks/xndeye/adblock_list?style=flat-square)

💪 Powerful yet restrained ad filtering rules that can block 99%[^1] of Web ads!

> [!TIP]
> This repository is built using [ad-filters-subscriber](https://github.com/fordes123/ad-filters-subscriber/), which regularly merges multiple high-quality upstream rules and removes duplicates and invalid items.  
> Please report build and conversion errors [here](https://github.com/fordes123/ad-filters-subscriber/issues), and submit false positives and rule recommendations to this repository's [issues](https://github.com/xndeye/adblock_list/issues)

| File | Description | github | ghproxy | jsdelivr |
|------|:------------|:------:|:-------:|:--------:|
| `easylist.txt` | Complete main rules | [link][easylist-raw] | [link][easylist-ghproxy] | [link][easylist-jsdelivr] |
| `modify.txt` | `easylist.txt` without DNS filtering rules | [link][modify-raw] | [link][modify-ghproxy] | [link][modify-jsdelivr] |
| `dns.txt` | DNS filtering rules only from `easylist.txt` | [link][dns-raw] | [link][dns-ghproxy] | [link][dns-jsdelivr] |
| `dnsmasq.conf` | For dnsmasq and its derivatives | [link][dnsmasq-raw] | [link][dnsmasq-ghproxy] | [link][dnsmasq-jsdelivr] |
| `clash.yaml` | For clash and its derivatives | [link][clash-raw] | [link][clash-ghproxy] | [link][clash-jsdelivr] |
| `smartdns.conf` | For smartdns | [link][smartdns-raw] | [link][smartdns-ghproxy] | [link][smartdns-jsdelivr] |
| `hosts` | Natively supported by almost all operating systems | [link][hosts-raw] | [link][hosts-ghproxy] | [link][hosts-jsdelivr] |
| `private.txt` | Private rules maintained by this repository, provided in easylist format | [link][private-raw] | [link][private-ghproxy] | [link][private-jsdelivr] |

[easylist-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/easylist.txt

[easylist-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/easylist.txt

[easylist-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@refs/heads/release/easylist.txt

[modify-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/modify.txt

[modify-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/modify.txt

[modify-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@refs/heads/release/modify.txt

[dns-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/dns.txt

[dns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/dns.txt

[dns-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@refs/heads/release/dns.txt

[dnsmasq-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/dnsmasq.conf

[dnsmasq-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/dnsmasq.conf

[dnsmasq-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@refs/heads/release/dnsmasq.conf

[clash-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/clash.yaml

[clash-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/clash.yaml

[clash-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@refs/heads/release/clash.yaml

[smartdns-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/smartdns.conf

[smartdns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/smartdns.conf

[smartdns-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@refs/heads/release/smartdns.conf

[hosts-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/hosts

[hosts-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/hosts

[hosts-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@refs/heads/release/hosts

[private-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/private.txt

[private-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/refs/heads/release/private.txt

[private-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@refs/heads/release/private.txt

<details>
<summary>Click to view upstream rules</summary>
<ul>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt">AdGuard Base Filter</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt">AdGuard Mobile Ads Filter</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt">AdGuard Tracking Protection Filter</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_17_TrackParam/filter.txt">AdGuard URL Tracking Filter</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt">AdGuard Annoyances Filter</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt">AdGuard Search Ads and Self-Promotion Filter</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt">AdGuard Chinese Filter</a></li>
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

[^1]: Data measured using [d3ward/toolz](https://d3ward.github.io/toolz/adblock.html) with `AdGuard Browser Extension` subscribing to this repository's `easylist.txt` rules on `Chrome 130.0`. [Results](https://github.com/user-attachments/assets/76ccfcac-9ffd-4bed-89d7-08cdfe6cc33d) are for reference only.
