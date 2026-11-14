# CF 优选 IP 筛选报告

- 时间: 2026-11-14 06:08:55
- 候选池: 139 个 (成功 129 / 失败 10 / 跳过 0)
- 解析候选: 15053 → 保留(去重后) 15053 → 已测 11602 → 测速 300 → 纯净 50（含 5 条域名可达但无速度数据）
> **探针盲区候选**：测速端点对它 403（不服务该 Host），但普通 CF 域名可达 → **对订阅者可用**，只是**没有速度数据**。它们的 score **不含速度项**（速度未知 ≠ 速度慢），与有速度数据的候选**不可直接比较**。

- 耗时: 214.5s

## 池命中率

| 池 | 运营商 | 段 | 解析 | 保留 | 命中纯净 | 状态 |
| --- | --- | --- | --- | --- | --- | --- |
| https://ip.ehb.cc.cd/ | - | - | 20 | 20 | 0 | OK |
| https://bestcf.pages.dev/wetest/ipv4.txt | - | - | 17 | 17 | 0 | OK |
| https://bestcf.pages.dev/cfyes/ipv4.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.pages.dev/domain/all.txt | - | - | 6 | 6 | 0 | OK |
| https://bestcf.pages.dev/cmliu/all.txt | - | - | 32 | 32 | 0 | OK |
| https://bestcf.pages.dev/tiancheng/all.txt | - | - | 72 | 72 | 0 | OK |
| https://bestcf.pages.dev/s5gy/mini.txt | - | - | 32 | 32 | 0 | OK |
| https://cf.090227.xyz/ct?ips=200 | 电信 | - | 6 | 6 | 0 | OK |
| https://cf.090227.xyz/cmcc?ips=200 | 移动 | - | 8 | 8 | 0 | OK |
| https://090227.pages.dev/bestcf?isp=all&ips=200 | - | - | 18 | 18 | 0 | OK |
| https://090227.pages.dev/bestcf?isp=ct&ips=50 | 电信 | - | 6 | 6 | 0 | OK |
| https://090227.pages.dev/bestcf?isp=cmcc&ips=50 | 移动 | - | 8 | 8 | 0 | OK |
| https://raw.githubusercontent.com/joname1/BestCFip/main/ipv4.txt | - | - | 109 | 109 | 0 | OK |
| https://raw.githubusercontent.com/hubbylei/bestcf/main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/gshtwy/CF-DNS-Clone/main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://raw.githubusercontent.com/svip-s/cloudflare_ip/main/best_ips.txt | - | - | 37 | 37 | 0 | OK |
| https://raw.githubusercontent.com/svip-s/cloudflare_ip/main/full_ips.txt | - | - | 410 | 410 | 0 | OK |
| https://raw.githubusercontent.com/XIU2/CloudflareSpeedTest/master/ip.txt | - | - | 1600 | 1600 | 21 | OK |
| https://raw.githubusercontent.com/LancelotRar/best-cf-ips/main/best-cf-ip-scanned-top400.txt | - | - | 400 | 400 | 1 | OK |
| https://raw.githubusercontent.com/sanzang-tango/best-cf-ip/main/best-cf-ipv4.txt | - | - | 333 | 333 | 0 | OK |
| https://raw.githubusercontent.com/mall994/cloudflare-best-ip/main/best-ips.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://raw.githubusercontent.com/vipmc838/cf_best_ip/main/cloudflare_bestip.txt | - | - | 70 | 70 | 0 | OK |
| https://raw.githubusercontent.com/suancaicc/cf-ip/main/ip.txt | - | - | 30 | 30 | 0 | OK |
| https://raw.githubusercontent.com/KafeMars/best-ips-domains/main/cf-bestips.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/aihddelyy/Cloudflare_ips/main/CFST.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/yuanxiawan/cfipv4db/main/high_score_ips.txt | - | - | 15 | 15 | 0 | OK |
| https://raw.githubusercontent.com/zy1078/cf-IP/master/ip.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://raw.githubusercontent.com/ymyuuu/IPDB/main/bestcf.txt | - | - | 15 | 15 | 0 | OK |
| https://raw.githubusercontent.com/demon-hugo/CF-iP/main/cloudflare_ips-us.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/demon-hugo/CF-iP/main/cloudflare_ips.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/a2622113/cloudflare_IPv4/main/ip.txt | - | - | 111 | 111 | 0 | OK |
| https://bestcf.pages.dev/s5gy/all.txt | - | - | 107 | 107 | 0 | OK |
| https://raw.githubusercontent.com/Coolapk-Code9527/Cloudflare-IP/main/ip.txt | - | - | 32 | 32 | 0 | OK |
| https://raw.githubusercontent.com/einsitang/my-fast-cf-ip/master/fastips.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/uezer/cf-prefer-ips/main/best.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/aihddelyy/Cloudflare_ips/main/CF.txt | - | - | 6 | 6 | 0 | OK |
| https://cdn.jsdelivr.net/gh/joname1/BestCFip@main/ipv4.txt | - | - | 95 | 95 | 0 | OK |
| https://cdn.jsdelivr.net/gh/joname1/BestCFip@main/ipv6.txt | - | - | 41 | 41 | 0 | OK |
| https://cdn.jsdelivr.net/gh/hubbylei/bestcf@main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/gshtwy/CF-DNS-Clone@main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/best_ips.txt | - | - | 46 | 46 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/full_ips.txt | - | - | 412 | 412 | 0 | OK |
| https://cdn.jsdelivr.net/gh/XIU2/CloudflareSpeedTest@master/ip.txt | - | - | 1600 | 1600 | 11 | OK |
| https://cdn.jsdelivr.net/gh/LancelotRar/best-cf-ips@main/best-cf-ip-scanned-top400.txt | - | - | 400 | 400 | 1 | OK |
| https://cdn.jsdelivr.net/gh/sanzang-tango/best-cf-ip@main/best-cf-ipv4.txt | - | - | 321 | 321 | 0 | OK |
| https://cdn.jsdelivr.net/gh/mall994/cloudflare-best-ip@main/best-ips.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/suancaicc/cf-ip@main/ip.txt | - | - | 30 | 30 | 0 | OK |
| https://cdn.jsdelivr.net/gh/KafeMars/best-ips-domains@main/cf-bestips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/aihddelyy/Cloudflare_ips@main/CFST.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/cfipv4db@main/high_score_ips.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/zy1078/cf-IP@master/ip.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/bestcf.txt | - | - | 15 | 15 | 0 | OK |
| https://ipdb.api.030101.xyz/?type=cfv4%3Bproxy | - | - | 1683 | 1683 | 5 | OK |
| https://ipdb.api.030101.xyz/?type=bestcf&country=true | - | - | 10 | 10 | 0 | OK |
| https://www.cloudflare.com/ips-v4 | - | 原生 | 960 | 960 | 8 | OK |
| https://www.cloudflare.com/ips-v6 | - | 原生 | 448 | 448 | 0 | OK |
| https://raw.githubusercontent.com/LancelotRar/best-cf-ips/main/best-cf-ip-collected.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://raw.githubusercontent.com/kinghui-001/cfip/main/best_ips.txt | - | - | 23 | 23 | 0 | OK |
| https://raw.githubusercontent.com/HandsomeMJZ/cfip/main/best_ips.txt | - | - | 7 | 7 | 0 | OK |
| https://raw.githubusercontent.com/cmliu/WorkerVless2sub/main/addressesipv6api.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/200111226011qw-debug/cf-ip-screener@main/result/clean-ips.txt | - | - | 50 | 50 | 0 | OK |
| https://bestcf.tools12345.com/WARP/WARP-MINI-443.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/WARP/WARP-MINI-8443.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/WARP/WARP-MINI.txt | - | - | 8 | 8 | 0 | OK |
| https://bestcf.tools12345.com/cfyes/ipv4.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/cfyes/ipv6.txt | - | - | 7 | 7 | 0 | OK |
| https://bestcf.tools12345.com/cmliu/all.txt | - | - | 32 | 32 | 0 | OK |
| https://bestcf.tools12345.com/cmliu2/all.txt | - | - | 15 | 15 | 0 | OK |
| https://bestcf.tools12345.com/gslege/Cfxyz.txt | - | - | 12 | 12 | 1 | OK |
| https://bestcf.tools12345.com/gslege/DE.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/gslege/SG.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/gslege/US.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/ircf/ipv4.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/lajiao/all.txt | - | - | 129 | 129 | 0 | OK |
| https://bestcf.tools12345.com/luoli/all.txt | - | - | 31 | 31 | 0 | OK |
| https://bestcf.tools12345.com/lzj/all.txt | - | - | 50 | 50 | 0 | OK |
| https://bestcf.tools12345.com/moistr/all.txt | - | - | 33 | 33 | 0 | OK |
| https://bestcf.tools12345.com/nirevil/ipv4.txt | - | - | 37 | 37 | 0 | OK |
| https://bestcf.tools12345.com/nirevil/ipv6.txt | - | - | 7 | 7 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/all.txt | - | - | 103 | 103 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/hk.txt | - | - | 24 | 24 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/jp.txt | - | - | 19 | 19 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/mini.txt | - | - | 29 | 29 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/sg.txt | - | - | 19 | 19 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/us.txt | - | - | 25 | 25 | 0 | OK |
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
| https://bestcf.tools12345.com/wetest/ipv4.txt | - | - | 16 | 16 | 0 | OK |
| https://bestcf.tools12345.com/xinyitang3/ipv4.txt | - | - | 13 | 13 | 0 | OK |
| https://bestcf.tools12345.com/zhixuanwang/ipv4-onlyip.txt | - | - | 6 | 6 | 0 | OK |
| https://cf.junzhen.qzz.io/best_ips.txt | - | - | 12 | 12 | 0 | OK |
| https://cf.junzhen.qzz.io/best_ips_bj.txt | - | - | 27 | 27 | 0 | OK |
| https://cdn.jsdelivr.net/gh/JieChaoCC/cf-ip-auto@main/data/ipapi.txt | - | - | 5 | 5 | 0 | OK |
| https://cdn.jsdelivr.net/gh/LancelotRar/best-cf-ips@main/best-cf-ipv4.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/Senflare/Senflare-IP@main/IPlist-Pro.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/Senflare/Senflare-IP@main/Senflare-Pro.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/ahang39/router@main/all.txt | - | - | 6 | 6 | 0 | OK |
| https://cdn.jsdelivr.net/gh/cmliu/WorkerVless2sub@main/addressesapi.txt | - | - | 4 | 4 | 0 | OK |
| https://cdn.jsdelivr.net/gh/einsitang/my-fast-cf-ip@master/fastips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/gshtwy/CF-DNS-Clone@main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://cdn.jsdelivr.net/gh/hubbylei/bestcf@main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/love-ztm/cfip@main/best_ips.txt | - | - | 3 | 3 | 0 | OK |
| https://cdn.jsdelivr.net/gh/love-ztm/cfip@main/ubest_ips.txt | - | - | 4 | 4 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/best_ips.txt | - | - | 46 | 46 | 0 | OK |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/BestCF/bestcfv4.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/BestCF/bestcfv6.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/cfipv4db@main/cfip.txt | - | - | 14 | 14 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/ipscan-pages@main/output/ips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/spew1165/cf-yx@main/ip/cf-speed-dns-top10.txt | - | - | 4 | 4 | 0 | OK |
| https://cdn.jsdelivr.net/gh/xxzh72/yxym@main/ip.txt | - | - | 71 | 71 | 0 | OK |
| https://cdn.jsdelivr.net/gh/meishero/cf-bestip@main/best_ip_dianxin.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/meishero/cf-bestip@main/best_ip_yidong.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/YiMing918/ym-cfip@main/data/full.txt | - | - | 400 | 400 | 0 | OK |
| https://cdn.jsdelivr.net/gh/YiMing918/ym-cfip@main/data/all6.tx | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/jifengwind/HHP-cf-ips@main/ips.txt | - | - | 29 | 29 | 0 | OK |
| https://cdn.jsdelivr.net/gh/luckyops/cf-pool@main/add.txt | - | - | 50 | 50 | 0 | OK |
| https://cdn.jsdelivr.net/gh/minghe168/cfip-auto@main/best_ips.txt | - | - | 2 | 2 | 0 | OK |
| https://cdn.jsdelivr.net/gh/burylove-baby/cf-ips@main/ai.txt | - | - | 8 | 8 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yydfys/cm@main/1-px.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/best.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/day1.txt | - | - | 173 | 173 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/day2.txt | - | - | 56 | 56 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time0.txt | - | - | 152 | 152 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time12.txt | - | - | 152 | 152 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time16.txt | - | - | 167 | 167 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time2.txt | - | - | 154 | 154 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time20.txt | - | - | 178 | 178 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time4.txt | - | - | 173 | 173 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time8.txt | - | - | 159 | 159 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/topbest.txt | - | - | 8 | 8 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/web.txt | - | - | 1874 | 1874 | 2 | OK |

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
| <10 | 0 |
| >=10 | 45 |

## 机房地区分布 (Top)
| 机房 | 数量 |
| --- | --- |
| ORD | 50 |

## 纯净 IP 明细

| IP:端口 | 延迟(ms) | 丢包 | TLS | 速度(MB/s) | 机房 | 原生 | 段 | 分数 | 分数构成 | 达标轮次 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 198.41.205.138:443 | 1.8 | 0% | OK | 67.11 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.205.206:443 | 2.0 | 0% | OK | 51.05 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.200.223:443 | 2.0 | 0% | OK | 55.71 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.187.6:443 | 2.0 | 0% | OK | 49.34 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.65.42.147:443 | 2.1 | 0% | OK | - | ORD | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 190.93.244.201:443 | 2.1 | 0% | OK | 54.10 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.97.234:443 | 2.1 | 0% | OK | 54.91 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.203.157:443 | 2.1 | 0% | OK | 69.35 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.18.32.215:443 | 2.1 | 0% | OK | 52.23 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 108.162.196.117:443 | 2.1 | 0% | OK | 56.68 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 108.162.193.106:443 | 2.1 | 0% | OK | 57.80 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.247.193:443 | 2.1 | 0% | OK | 59.37 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.185.191:443 | 2.1 | 0% | OK | 52.26 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 162.159.150.56:443 | 2.1 | 0% | OK | 72.03 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.244.235:443 | 2.1 | 0% | OK | 47.08 | ORD | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 198.41.205.101:443 | 2.1 | 0% | OK | 53.76 | ORD | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 162.159.11.246:443 | 2.1 | 0% | OK | 53.20 | ORD | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.18.40.179:443 | 2.1 | 0% | OK | 59.72 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.121.38:443 | 2.1 | 0% | OK | 50.78 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 108.162.194.70:443 | 2.2 | 0% | OK | 47.29 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.246.70:443 | 2.2 | 0% | OK | 44.81 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.211.46:443 | 2.2 | 0% | OK | 67.99 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 162.159.194.58:443 | 2.2 | 0% | OK | 58.18 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.19.21.115:443 | 2.2 | 0% | OK | 49.83 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.229.120:443 | 2.2 | 0% | OK | 48.85 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.203.126:443 | 2.2 | 0% | OK | 62.31 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.24.54.216:443 | 2.2 | 0% | OK | 53.49 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.145.118:443 | 2.2 | 0% | OK | 50.49 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 141.101.120.163:443 | 2.2 | 0% | OK | 70.92 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 141.101.120.162:443 | 2.2 | 0% | OK | 31.49 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.244.158:443 | 2.2 | 0% | OK | 49.48 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 173.245.58.61:443 | 2.2 | 0% | OK | 64.59 | ORD | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 198.41.202.48:443 | 2.2 | 0% | OK | 61.31 | ORD | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 162.159.49.16:443 | 2.2 | 0% | OK | 45.21 | ORD | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.24.155.16:443 | 2.2 | 0% | OK | 59.93 | ORD | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.27.77.216:443 | 2.2 | 0% | OK | 38.18 | ORD | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 172.65.227.223:443 | 2.3 | 0% | OK | - | ORD | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 190.93.246.47:443 | 2.3 | 0% | OK | 44.72 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.97.108:443 | 2.3 | 0% | OK | 55.59 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.206.2:443 | 2.3 | 0% | OK | 40.64 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 162.159.207.67:443 | 2.3 | 0% | OK | 61.94 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.147.63:443 | 2.3 | 0% | OK | 46.41 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.229.8:443 | 2.3 | 0% | OK | 67.51 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.96.205:443 | 2.3 | 0% | OK | 53.53 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.97.197:443 | 2.3 | 0% | OK | 44.48 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.207.109:443 | 2.3 | 0% | OK | 58.53 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.217.81:443 | 2.3 | 0% | OK | 47.57 | ORD | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.65.40.206:443 | 2.4 | 0% | OK | - | ORD | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.222.124:443 | 2.5 | 0% | OK | - | ORD | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.59.96:443 | 2.6 | 0% | OK | - | ORD | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |