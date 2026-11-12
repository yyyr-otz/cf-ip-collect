# CF 优选 IP 筛选报告

- 时间: 2026-11-12 00:34:40
- 候选池: 139 个 (成功 129 / 失败 10 / 跳过 0)
- 解析候选: 14760 → 保留(去重后) 14760 → 已测 11414 → 测速 300 → 纯净 50（含 5 条域名可达但无速度数据）
> **探针盲区候选**：测速端点对它 403（不服务该 Host），但普通 CF 域名可达 → **对订阅者可用**，只是**没有速度数据**。它们的 score **不含速度项**（速度未知 ≠ 速度慢），与有速度数据的候选**不可直接比较**。

- 耗时: 207.0s

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
| https://raw.githubusercontent.com/joname1/BestCFip/main/ipv4.txt | - | - | 91 | 91 | 0 | OK |
| https://raw.githubusercontent.com/hubbylei/bestcf/main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/gshtwy/CF-DNS-Clone/main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://raw.githubusercontent.com/svip-s/cloudflare_ip/main/best_ips.txt | - | - | 36 | 36 | 0 | OK |
| https://raw.githubusercontent.com/svip-s/cloudflare_ip/main/full_ips.txt | - | - | 412 | 412 | 0 | OK |
| https://raw.githubusercontent.com/XIU2/CloudflareSpeedTest/master/ip.txt | - | - | 1600 | 1600 | 24 | OK |
| https://raw.githubusercontent.com/LancelotRar/best-cf-ips/main/best-cf-ip-scanned-top400.txt | - | - | 400 | 400 | 2 | OK |
| https://raw.githubusercontent.com/sanzang-tango/best-cf-ip/main/best-cf-ipv4.txt | - | - | 307 | 307 | 0 | OK |
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
| https://raw.githubusercontent.com/a2622113/cloudflare_IPv4/main/ip.txt | - | - | 121 | 121 | 0 | OK |
| https://bestcf.pages.dev/s5gy/all.txt | - | - | 52 | 52 | 0 | OK |
| https://raw.githubusercontent.com/Coolapk-Code9527/Cloudflare-IP/main/ip.txt | - | - | 24 | 24 | 0 | OK |
| https://raw.githubusercontent.com/einsitang/my-fast-cf-ip/master/fastips.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/uezer/cf-prefer-ips/main/best.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/aihddelyy/Cloudflare_ips/main/CF.txt | - | - | 7 | 7 | 0 | OK |
| https://cdn.jsdelivr.net/gh/joname1/BestCFip@main/ipv4.txt | - | - | 98 | 98 | 0 | OK |
| https://cdn.jsdelivr.net/gh/joname1/BestCFip@main/ipv6.txt | - | - | 27 | 27 | 0 | OK |
| https://cdn.jsdelivr.net/gh/hubbylei/bestcf@main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/gshtwy/CF-DNS-Clone@main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/best_ips.txt | - | - | 34 | 34 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/full_ips.txt | - | - | 413 | 413 | 0 | OK |
| https://cdn.jsdelivr.net/gh/XIU2/CloudflareSpeedTest@master/ip.txt | - | - | 1600 | 1600 | 9 | OK |
| https://cdn.jsdelivr.net/gh/LancelotRar/best-cf-ips@main/best-cf-ip-scanned-top400.txt | - | - | 400 | 400 | 0 | OK |
| https://cdn.jsdelivr.net/gh/sanzang-tango/best-cf-ip@main/best-cf-ipv4.txt | - | - | 307 | 307 | 0 | OK |
| https://cdn.jsdelivr.net/gh/mall994/cloudflare-best-ip@main/best-ips.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/suancaicc/cf-ip@main/ip.txt | - | - | 30 | 30 | 0 | OK |
| https://cdn.jsdelivr.net/gh/KafeMars/best-ips-domains@main/cf-bestips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/aihddelyy/Cloudflare_ips@main/CFST.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/cfipv4db@main/high_score_ips.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/zy1078/cf-IP@master/ip.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/bestcf.txt | - | - | 15 | 15 | 0 | OK |
| https://ipdb.api.030101.xyz/?type=cfv4%3Bproxy | - | 外延1 | 1683 | 1683 | 7 | OK |
| https://ipdb.api.030101.xyz/?type=bestcf&country=true | - | - | 10 | 10 | 0 | OK |
| https://www.cloudflare.com/ips-v4 | - | 原生 | 960 | 960 | 4 | OK |
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
| https://bestcf.tools12345.com/gslege/Cfxyz.txt | - | - | 7 | 7 | 0 | OK |
| https://bestcf.tools12345.com/gslege/DE.txt | - | - | 22 | 22 | 1 | OK |
| https://bestcf.tools12345.com/gslege/SG.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/gslege/US.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/ircf/ipv4.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/lajiao/all.txt | - | - | 129 | 129 | 0 | OK |
| https://bestcf.tools12345.com/luoli/all.txt | - | - | 31 | 31 | 0 | OK |
| https://bestcf.tools12345.com/lzj/all.txt | - | - | 50 | 50 | 0 | OK |
| https://bestcf.tools12345.com/moistr/all.txt | - | - | 33 | 33 | 0 | OK |
| https://bestcf.tools12345.com/nirevil/ipv4.txt | - | - | 37 | 37 | 0 | OK |
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
| https://bestcf.tools12345.com/xinyitang3/ipv4.txt | - | - | 14 | 14 | 0 | OK |
| https://bestcf.tools12345.com/zhixuanwang/ipv4-onlyip.txt | - | - | 2 | 2 | 0 | OK |
| https://cf.junzhen.qzz.io/best_ips.txt | - | - | 12 | 12 | 0 | OK |
| https://cf.junzhen.qzz.io/best_ips_bj.txt | - | - | 27 | 27 | 0 | OK |
| https://cdn.jsdelivr.net/gh/JieChaoCC/cf-ip-auto@main/data/ipapi.txt | - | - | 7 | 7 | 0 | OK |
| https://cdn.jsdelivr.net/gh/LancelotRar/best-cf-ips@main/best-cf-ipv4.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/Senflare/Senflare-IP@main/IPlist-Pro.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/Senflare/Senflare-IP@main/Senflare-Pro.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/ahang39/router@main/all.txt | - | - | 5 | 5 | 0 | OK |
| https://cdn.jsdelivr.net/gh/cmliu/WorkerVless2sub@main/addressesapi.txt | - | - | 4 | 4 | 0 | OK |
| https://cdn.jsdelivr.net/gh/einsitang/my-fast-cf-ip@master/fastips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/gshtwy/CF-DNS-Clone@main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://cdn.jsdelivr.net/gh/hubbylei/bestcf@main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/love-ztm/cfip@main/best_ips.txt | - | - | 3 | 3 | 0 | OK |
| https://cdn.jsdelivr.net/gh/love-ztm/cfip@main/ubest_ips.txt | - | - | 7 | 7 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/best_ips.txt | - | - | 34 | 34 | 0 | OK |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/BestCF/bestcfv4.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/BestCF/bestcfv6.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/cfipv4db@main/cfip.txt | - | - | 14 | 14 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/ipscan-pages@main/output/ips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/spew1165/cf-yx@main/ip/cf-speed-dns-top10.txt | - | - | 3 | 3 | 0 | OK |
| https://cdn.jsdelivr.net/gh/xxzh72/yxym@main/ip.txt | - | - | 67 | 67 | 0 | OK |
| https://cdn.jsdelivr.net/gh/meishero/cf-bestip@main/best_ip_dianxin.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/meishero/cf-bestip@main/best_ip_yidong.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/YiMing918/ym-cfip@main/data/full.txt | - | - | 402 | 402 | 0 | OK |
| https://cdn.jsdelivr.net/gh/YiMing918/ym-cfip@main/data/all6.tx | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/jifengwind/HHP-cf-ips@main/ips.txt | - | - | 28 | 28 | 0 | OK |
| https://cdn.jsdelivr.net/gh/luckyops/cf-pool@main/add.txt | - | - | 50 | 50 | 0 | OK |
| https://cdn.jsdelivr.net/gh/minghe168/cfip-auto@main/best_ips.txt | - | - | 4 | 4 | 0 | OK |
| https://cdn.jsdelivr.net/gh/burylove-baby/cf-ips@main/ai.txt | - | - | 8 | 8 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yydfys/cm@main/1-px.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/best.txt | - | - | 11 | 11 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/day1.txt | - | - | 78 | 78 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/day2.txt | - | - | 93 | 93 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time0.txt | - | 外延1 | 119 | 119 | 1 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time12.txt | - | - | 164 | 164 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time16.txt | - | - | 176 | 176 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time2.txt | - | - | 154 | 154 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time20.txt | - | - | 183 | 183 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time4.txt | - | - | 181 | 181 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time8.txt | - | - | 172 | 172 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/topbest.txt | - | - | 8 | 8 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/web.txt | - | - | 1874 | 1874 | 1 | OK |

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
| <10 | 1 |
| >=10 | 44 |

## 机房地区分布 (Top)
| 机房 | 数量 |
| --- | --- |
| LAX | 49 |
| CDG | 1 |

## 纯净 IP 明细

| IP:端口 | 延迟(ms) | 丢包 | TLS | 速度(MB/s) | 机房 | 原生 | 段 | 分数 | 分数构成 | 达标轮次 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 141.148.187.195:443 | 3.3 | 0% | OK | 7.75 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.65.63.126:443 | 8.6 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.202.13:443 | 8.7 | 0% | OK | - | CDG | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 141.101.123.88:443 | 8.7 | 0% | OK | 13.21 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.246.124:443 | 8.7 | 0% | OK | 13.20 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.122.220:443 | 8.7 | 0% | OK | 13.54 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 108.162.195.207:443 | 8.7 | 0% | OK | 12.79 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.218.90:443 | 8.7 | 0% | OK | 13.60 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.200.254:443 | 8.7 | 0% | OK | 13.24 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 162.159.154.212:443 | 8.7 | 0% | OK | 12.38 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.24.0.5:443 | 8.7 | 0% | OK | 13.06 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.97.196:443 | 8.8 | 0% | OK | 13.36 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.197.194:443 | 8.8 | 0% | OK | 12.96 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.250.33:443 | 8.8 | 0% | OK | 13.29 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.18.38.156:443 | 8.8 | 0% | OK | 14.20 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 141.101.120.139:443 | 8.8 | 0% | OK | 12.33 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.247.210:443 | 8.8 | 0% | OK | 13.61 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.97.199:443 | 8.8 | 0% | OK | 12.80 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.27.23.51:443 | 8.8 | 0% | OK | 12.79 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.102.217:443 | 8.8 | 0% | OK | 12.79 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.245.140:443 | 8.8 | 0% | OK | 13.67 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.96.46:443 | 8.8 | 0% | OK | 13.01 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.18.29.243:443 | 8.8 | 0% | OK | 13.36 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.18.115.152:443 | 8.8 | 0% | OK | 13.35 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.19.248.98:443 | 8.8 | 0% | OK | 12.93 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.17.119.60:443 | 8.8 | 0% | OK | 13.28 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 23.227.39.200:443 | 8.8 | 0% | OK | 13.53 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.17.71:2096 | 8.8 | 0% | OK | 13.19 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.65.247.194:443 | 8.9 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.40.118:443 | 8.9 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.62.159:443 | 8.9 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 141.101.121.118:443 | 8.9 | 0% | OK | 13.08 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 141.101.121.6:443 | 8.9 | 0% | OK | 13.42 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.246.221:443 | 8.9 | 0% | OK | 13.49 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.246.44:443 | 8.9 | 0% | OK | 12.81 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.196.7:443 | 8.9 | 0% | OK | 13.36 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.205.250:443 | 8.9 | 0% | OK | 13.59 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.16.148.8:443 | 8.9 | 0% | OK | 12.38 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.50.85:443 | 8.9 | 0% | OK | 13.02 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.79.247:443 | 8.9 | 0% | OK | 13.41 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.18.99.117:443 | 8.9 | 0% | OK | 13.44 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.16.40.84:443 | 8.9 | 0% | OK | 13.18 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.76.189:443 | 8.9 | 0% | OK | 12.14 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.229.236:443 | 8.9 | 0% | OK | 13.41 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.66.146.84:443 | 8.9 | 0% | OK | 13.65 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.145.243:443 | 8.9 | 0% | OK | 13.33 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 108.162.194.203:443 | 8.9 | 0% | OK | 13.87 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.196.13:443 | 8.9 | 0% | OK | 12.89 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.19.156.154:443 | 8.9 | 0% | OK | 13.07 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 141.101.115.43:443 | 8.9 | 0% | OK | 13.55 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |