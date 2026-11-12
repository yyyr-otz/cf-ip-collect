# CF 优选 IP 筛选报告

- 时间: 2026-11-12 18:11:55
- 候选池: 139 个 (成功 129 / 失败 10 / 跳过 0)
- 解析候选: 14732 → 保留(去重后) 14732 → 已测 11200 → 测速 300 → 纯净 50（含 5 条域名可达但无速度数据）
> **探针盲区候选**：测速端点对它 403（不服务该 Host），但普通 CF 域名可达 → **对订阅者可用**，只是**没有速度数据**。它们的 score **不含速度项**（速度未知 ≠ 速度慢），与有速度数据的候选**不可直接比较**。

- 耗时: 197.2s

## 池命中率

| 池 | 运营商 | 段 | 解析 | 保留 | 命中纯净 | 状态 |
| --- | --- | --- | --- | --- | --- | --- |
| https://ip.ehb.cc.cd/ | - | - | 20 | 20 | 0 | OK |
| https://bestcf.pages.dev/wetest/ipv4.txt | - | - | 17 | 17 | 0 | OK |
| https://bestcf.pages.dev/cfyes/ipv4.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.pages.dev/domain/all.txt | - | - | 6 | 6 | 0 | OK |
| https://bestcf.pages.dev/cmliu/all.txt | - | - | 32 | 32 | 0 | OK |
| https://bestcf.pages.dev/tiancheng/all.txt | - | - | 72 | 72 | 0 | OK |
| https://bestcf.pages.dev/s5gy/mini.txt | - | - | 20 | 20 | 0 | OK |
| https://cf.090227.xyz/ct?ips=200 | 电信 | - | 6 | 6 | 0 | OK |
| https://cf.090227.xyz/cmcc?ips=200 | 移动 | - | 8 | 8 | 0 | OK |
| https://090227.pages.dev/bestcf?isp=all&ips=200 | - | - | 18 | 18 | 0 | OK |
| https://090227.pages.dev/bestcf?isp=ct&ips=50 | 电信 | - | 6 | 6 | 0 | OK |
| https://090227.pages.dev/bestcf?isp=cmcc&ips=50 | 移动 | - | 8 | 8 | 0 | OK |
| https://raw.githubusercontent.com/joname1/BestCFip/main/ipv4.txt | - | - | 96 | 96 | 0 | OK |
| https://raw.githubusercontent.com/hubbylei/bestcf/main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/gshtwy/CF-DNS-Clone/main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://raw.githubusercontent.com/svip-s/cloudflare_ip/main/best_ips.txt | - | - | 36 | 36 | 0 | OK |
| https://raw.githubusercontent.com/svip-s/cloudflare_ip/main/full_ips.txt | - | - | 412 | 412 | 0 | OK |
| https://raw.githubusercontent.com/XIU2/CloudflareSpeedTest/master/ip.txt | - | - | 1600 | 1600 | 9 | OK |
| https://raw.githubusercontent.com/LancelotRar/best-cf-ips/main/best-cf-ip-scanned-top400.txt | - | - | 400 | 400 | 0 | OK |
| https://raw.githubusercontent.com/sanzang-tango/best-cf-ip/main/best-cf-ipv4.txt | - | - | 297 | 297 | 1 | OK |
| https://raw.githubusercontent.com/mall994/cloudflare-best-ip/main/best-ips.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://raw.githubusercontent.com/vipmc838/cf_best_ip/main/cloudflare_bestip.txt | - | - | 70 | 70 | 6 | OK |
| https://raw.githubusercontent.com/suancaicc/cf-ip/main/ip.txt | - | - | 30 | 30 | 0 | OK |
| https://raw.githubusercontent.com/KafeMars/best-ips-domains/main/cf-bestips.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/aihddelyy/Cloudflare_ips/main/CFST.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/yuanxiawan/cfipv4db/main/high_score_ips.txt | - | - | 15 | 15 | 0 | OK |
| https://raw.githubusercontent.com/zy1078/cf-IP/master/ip.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://raw.githubusercontent.com/ymyuuu/IPDB/main/bestcf.txt | - | - | 15 | 15 | 0 | OK |
| https://raw.githubusercontent.com/demon-hugo/CF-iP/main/cloudflare_ips-us.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/demon-hugo/CF-iP/main/cloudflare_ips.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/a2622113/cloudflare_IPv4/main/ip.txt | - | - | 121 | 121 | 0 | OK |
| https://bestcf.pages.dev/s5gy/all.txt | - | - | 52 | 52 | 0 | OK |
| https://raw.githubusercontent.com/Coolapk-Code9527/Cloudflare-IP/main/ip.txt | - | - | 26 | 26 | 0 | OK |
| https://raw.githubusercontent.com/einsitang/my-fast-cf-ip/master/fastips.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/uezer/cf-prefer-ips/main/best.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/aihddelyy/Cloudflare_ips/main/CF.txt | - | - | 6 | 6 | 0 | OK |
| https://cdn.jsdelivr.net/gh/joname1/BestCFip@main/ipv4.txt | - | - | 96 | 96 | 0 | OK |
| https://cdn.jsdelivr.net/gh/joname1/BestCFip@main/ipv6.txt | - | - | 41 | 41 | 0 | OK |
| https://cdn.jsdelivr.net/gh/hubbylei/bestcf@main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/gshtwy/CF-DNS-Clone@main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/best_ips.txt | - | - | 36 | 36 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/full_ips.txt | - | - | 412 | 412 | 0 | OK |
| https://cdn.jsdelivr.net/gh/XIU2/CloudflareSpeedTest@master/ip.txt | - | - | 1600 | 1600 | 5 | OK |
| https://cdn.jsdelivr.net/gh/LancelotRar/best-cf-ips@main/best-cf-ip-scanned-top400.txt | - | - | 400 | 400 | 0 | OK |
| https://cdn.jsdelivr.net/gh/sanzang-tango/best-cf-ip@main/best-cf-ipv4.txt | - | - | 296 | 296 | 0 | OK |
| https://cdn.jsdelivr.net/gh/mall994/cloudflare-best-ip@main/best-ips.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/suancaicc/cf-ip@main/ip.txt | - | - | 30 | 30 | 0 | OK |
| https://cdn.jsdelivr.net/gh/KafeMars/best-ips-domains@main/cf-bestips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/aihddelyy/Cloudflare_ips@main/CFST.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/cfipv4db@main/high_score_ips.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/zy1078/cf-IP@master/ip.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/bestcf.txt | - | - | 15 | 15 | 0 | OK |
| https://ipdb.api.030101.xyz/?type=cfv4%3Bproxy | - | - | 1683 | 1683 | 8 | OK |
| https://ipdb.api.030101.xyz/?type=bestcf&country=true | - | - | 10 | 10 | 0 | OK |
| https://www.cloudflare.com/ips-v4 | - | 原生 | 960 | 960 | 6 | OK |
| https://www.cloudflare.com/ips-v6 | - | 原生 | 448 | 448 | 0 | OK |
| https://raw.githubusercontent.com/LancelotRar/best-cf-ips/main/best-cf-ip-collected.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://raw.githubusercontent.com/kinghui-001/cfip/main/best_ips.txt | - | - | 23 | 23 | 0 | OK |
| https://raw.githubusercontent.com/HandsomeMJZ/cfip/main/best_ips.txt | - | - | 7 | 7 | 0 | OK |
| https://raw.githubusercontent.com/cmliu/WorkerVless2sub/main/addressesipv6api.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/200111226011qw-debug/cf-ip-screener@main/result/clean-ips.txt | - | - | 50 | 50 | 1 | OK |
| https://bestcf.tools12345.com/WARP/WARP-MINI-443.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/WARP/WARP-MINI-8443.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/WARP/WARP-MINI.txt | - | - | 8 | 8 | 0 | OK |
| https://bestcf.tools12345.com/cfyes/ipv4.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/cfyes/ipv6.txt | - | - | 7 | 7 | 0 | OK |
| https://bestcf.tools12345.com/cmliu/all.txt | - | - | 32 | 32 | 0 | OK |
| https://bestcf.tools12345.com/cmliu2/all.txt | - | - | 15 | 15 | 0 | OK |
| https://bestcf.tools12345.com/gslege/Cfxyz.txt | - | - | 3 | 3 | 0 | OK |
| https://bestcf.tools12345.com/gslege/DE.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/gslege/SG.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/gslege/US.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/ircf/ipv4.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/lajiao/all.txt | - | - | 129 | 129 | 0 | OK |
| https://bestcf.tools12345.com/luoli/all.txt | - | - | 31 | 31 | 0 | OK |
| https://bestcf.tools12345.com/lzj/all.txt | - | 外延1 | 50 | 50 | 1 | OK |
| https://bestcf.tools12345.com/moistr/all.txt | - | - | 33 | 33 | 0 | OK |
| https://bestcf.tools12345.com/nirevil/ipv4.txt | - | - | 37 | 37 | 3 | OK |
| https://bestcf.tools12345.com/nirevil/ipv6.txt | - | - | 7 | 7 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/all.txt | - | - | 52 | 52 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/hk.txt | - | - | 4 | 4 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/jp.txt | - | - | 27 | 27 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/mini.txt | - | - | 20 | 20 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/sg.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/us.txt | - | - | 16 | 16 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/all.txt | - | - | 72 | 72 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/hk.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/jp.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/kr.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/mini.txt | - | - | 23 | 23 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/sg.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/us.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/uouin/all.txt | - | - | 42 | 42 | 0 | OK |
| https://bestcf.tools12345.com/vvhan/ipv4.txt | - | - | 27 | 27 | 0 | OK |
| https://bestcf.tools12345.com/vvhan/ipv6.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/wetest/ipv4.txt | - | - | 17 | 17 | 0 | OK |
| https://bestcf.tools12345.com/xinyitang3/ipv4.txt | - | - | 7 | 7 | 0 | OK |
| https://bestcf.tools12345.com/zhixuanwang/ipv4-onlyip.txt | - | - | 4 | 4 | 0 | OK |
| https://cf.junzhen.qzz.io/best_ips.txt | - | - | 12 | 12 | 0 | OK |
| https://cf.junzhen.qzz.io/best_ips_bj.txt | - | - | 27 | 27 | 0 | OK |
| https://cdn.jsdelivr.net/gh/JieChaoCC/cf-ip-auto@main/data/ipapi.txt | - | - | 6 | 6 | 0 | OK |
| https://cdn.jsdelivr.net/gh/LancelotRar/best-cf-ips@main/best-cf-ipv4.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/Senflare/Senflare-IP@main/IPlist-Pro.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/Senflare/Senflare-IP@main/Senflare-Pro.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/ahang39/router@main/all.txt | - | - | 6 | 6 | 1 | OK |
| https://cdn.jsdelivr.net/gh/cmliu/WorkerVless2sub@main/addressesapi.txt | - | - | 4 | 4 | 0 | OK |
| https://cdn.jsdelivr.net/gh/einsitang/my-fast-cf-ip@master/fastips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/gshtwy/CF-DNS-Clone@main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://cdn.jsdelivr.net/gh/hubbylei/bestcf@main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/love-ztm/cfip@main/best_ips.txt | - | - | 3 | 3 | 0 | OK |
| https://cdn.jsdelivr.net/gh/love-ztm/cfip@main/ubest_ips.txt | - | - | 5 | 5 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/best_ips.txt | - | - | 36 | 36 | 0 | OK |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/BestCF/bestcfv4.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/BestCF/bestcfv6.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/cfipv4db@main/cfip.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/ipscan-pages@main/output/ips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/spew1165/cf-yx@main/ip/cf-speed-dns-top10.txt | - | - | 2 | 2 | 0 | OK |
| https://cdn.jsdelivr.net/gh/xxzh72/yxym@main/ip.txt | - | - | 77 | 77 | 0 | OK |
| https://cdn.jsdelivr.net/gh/meishero/cf-bestip@main/best_ip_dianxin.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/meishero/cf-bestip@main/best_ip_yidong.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/YiMing918/ym-cfip@main/data/full.txt | - | - | 402 | 402 | 0 | OK |
| https://cdn.jsdelivr.net/gh/YiMing918/ym-cfip@main/data/all6.tx | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/jifengwind/HHP-cf-ips@main/ips.txt | - | - | 26 | 26 | 0 | OK |
| https://cdn.jsdelivr.net/gh/luckyops/cf-pool@main/add.txt | - | - | 50 | 50 | 0 | OK |
| https://cdn.jsdelivr.net/gh/minghe168/cfip-auto@main/best_ips.txt | - | - | 4 | 4 | 0 | OK |
| https://cdn.jsdelivr.net/gh/burylove-baby/cf-ips@main/ai.txt | - | - | 8 | 8 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yydfys/cm@main/1-px.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/best.txt | - | - | 11 | 11 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/day1.txt | - | - | 78 | 78 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/day2.txt | - | - | 93 | 93 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time0.txt | - | 外延1 | 119 | 119 | 1 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time12.txt | - | - | 153 | 153 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time16.txt | - | - | 162 | 162 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time2.txt | - | - | 154 | 154 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time20.txt | - | - | 183 | 183 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time4.txt | - | - | 181 | 181 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time8.txt | - | - | 172 | 172 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/topbest.txt | - | - | 8 | 8 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/web.txt | - | 外延3 | 1874 | 1874 | 8 | OK |

## 延迟分布 (ms)
| 区间 | 数量 |
| --- | --- |
| <50 | 50 |
| <100 | 0 |
| <200 | 0 |
| <300 | 0 |

## 速度分布 (MB/s)

| 区间 | 数量 |
| --- | --- |
| <1 | 0 |
| <3 | 0 |
| <5 | 0 |
| <10 | 2 |
| >=10 | 43 |

## 机房地区分布 (Top)
| 机房 | 数量 |
| --- | --- |
| LAX | 48 |
| SJC | 1 |
| HAM | 1 |

## 纯净 IP 明细

| IP:端口 | 延迟(ms) | 丢包 | TLS | 速度(MB/s) | 机房 | 原生 | 段 | 分数 | 分数构成 | 达标轮次 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 141.148.186.22:443 | 8.2 | 0% | OK | 5.33 | SJC | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.65.48.35:443 | 9.0 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.33.202:443 | 9.0 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.64.154.13:443 | 9.0 | 0% | OK | 13.31 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.25.223.176:443 | 9.0 | 0% | OK | 13.52 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.18.32.242:443 | 9.1 | 0% | OK | 13.53 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.149.185:443 | 9.1 | 0% | OK | 13.30 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.146.243:443 | 9.1 | 0% | OK | 12.90 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.247.56:443 | 9.1 | 0% | OK | 13.49 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 27.50.48.28:443 | 9.1 | 0% | OK | 13.75 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 (合计130→封顶100) | 3/3 |
| 172.65.243.41:443 | 9.2 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 190.93.245.203:443 | 9.2 | 0% | OK | 13.87 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.16.233.17:443 | 9.2 | 0% | OK | 12.82 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.87.45:443 | 9.2 | 0% | OK | 13.04 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 37.153.171.117:2087 | 9.2 | 0% | OK | 13.13 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.98.247:8443 | 9.2 | 0% | OK | 14.21 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.61.158:2053 | 9.2 | 0% | OK | 12.09 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.159.111:443 | 9.3 | 0% | OK | 13.05 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.18.35.208:443 | 9.3 | 0% | OK | 13.31 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.202.242:443 | 9.3 | 0% | OK | 13.11 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.19.153.241:443 | 9.3 | 0% | OK | 13.23 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.24.245.162:443 | 9.3 | 0% | OK | 12.50 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 108.162.192.30:443 | 9.3 | 0% | OK | 13.61 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 162.159.60.5:443 | 9.3 | 0% | OK | 13.58 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 141.101.115.61:443 | 9.3 | 0% | OK | 13.64 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.19.198.189:443 | 9.3 | 0% | OK | 13.29 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 89.116.161.122:443 | 9.3 | 0% | OK | 13.87 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 (合计130→封顶100) | 3/3 |
| 172.65.249.187:443 | 9.4 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.246.86:443 | 9.4 | 0% | OK | - | HAM | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 190.93.245.107:443 | 9.4 | 0% | OK | 13.70 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.16.225.200:443 | 9.4 | 0% | OK | 13.50 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.32.1:443 | 9.4 | 0% | OK | 13.89 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.155.22:443 | 9.4 | 0% | OK | 13.31 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 162.159.49.118:443 | 9.4 | 0% | OK | 13.04 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.16.92.190:443 | 9.4 | 0% | OK | 12.17 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.69.224:443 | 9.5 | 0% | OK | 13.58 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.119.119:443 | 9.5 | 0% | OK | 13.02 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.84.159:443 | 9.5 | 0% | OK | 13.92 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.154.239:2083 | 9.5 | 0% | OK | 13.22 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.17.202:443 | 9.5 | 0% | OK | 14.20 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.229.20:443 | 9.6 | 0% | OK | 12.46 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.233.159:443 | 9.6 | 0% | OK | 13.51 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.245.174:443 | 9.6 | 0% | OK | 13.00 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.244.8:443 | 9.6 | 0% | OK | 13.36 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.247.164:443 | 9.6 | 0% | OK | 13.59 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 198.41.218.167:443 | 9.6 | 0% | OK | 13.33 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 172.64.229.224:443 | 9.6 | 0% | OK | 13.22 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.16.140.252:443 | 9.6 | 0% | OK | 13.36 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 179.255.133.82:443 | 9.6 | 0% | OK | 7.95 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.23.131:443 | 9.6 | 0% | OK | 12.96 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |