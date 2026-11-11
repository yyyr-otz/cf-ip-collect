# CF 优选 IP 筛选报告

- 时间: 2026-11-11 00:37:38
- 候选池: 139 个 (成功 131 / 失败 8 / 跳过 0)
- 解析候选: 15288 → 保留(去重后) 15288 → 已测 11864 → 测速 300 → 收满剔除 1 → 纯净 50（含 5 条域名可达但无速度数据）
> **探针盲区候选**：测速端点对它 403（不服务该 Host），但普通 CF 域名可达 → **对订阅者可用**，只是**没有速度数据**。它们的 score **不含速度项**（速度未知 ≠ 速度慢），与有速度数据的候选**不可直接比较**。

- 耗时: 210.4s

## 池命中率

| 池 | 运营商 | 段 | 解析 | 保留 | 命中纯净 | 状态 |
| --- | --- | --- | --- | --- | --- | --- |
| https://ip.ehb.cc.cd/ | - | - | 20 | 20 | 0 | OK |
| https://bestcf.pages.dev/wetest/ipv4.txt | - | - | 14 | 14 | 0 | OK |
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
| https://raw.githubusercontent.com/joname1/BestCFip/main/ipv4.txt | - | - | 92 | 92 | 0 | OK |
| https://raw.githubusercontent.com/hubbylei/bestcf/main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/gshtwy/CF-DNS-Clone/main/wetest-cloudflare-v4.txt | - | - | 70 | 70 | 0 | OK |
| https://raw.githubusercontent.com/svip-s/cloudflare_ip/main/best_ips.txt | - | - | 34 | 34 | 0 | OK |
| https://raw.githubusercontent.com/svip-s/cloudflare_ip/main/full_ips.txt | - | 外延1 | 413 | 413 | 1 | OK |
| https://raw.githubusercontent.com/XIU2/CloudflareSpeedTest/master/ip.txt | - | - | 1600 | 1600 | 19 | OK |
| https://raw.githubusercontent.com/LancelotRar/best-cf-ips/main/best-cf-ip-scanned-top400.txt | - | - | 400 | 400 | 0 | OK |
| https://raw.githubusercontent.com/sanzang-tango/best-cf-ip/main/best-cf-ipv4.txt | - | - | 303 | 303 | 1 | OK |
| https://raw.githubusercontent.com/mall994/cloudflare-best-ip/main/best-ips.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://raw.githubusercontent.com/vipmc838/cf_best_ip/main/cloudflare_bestip.txt | - | - | 70 | 70 | 0 | OK |
| https://raw.githubusercontent.com/suancaicc/cf-ip/main/ip.txt | - | - | 27 | 27 | 0 | OK |
| https://raw.githubusercontent.com/KafeMars/best-ips-domains/main/cf-bestips.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/aihddelyy/Cloudflare_ips/main/CFST.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/yuanxiawan/cfipv4db/main/high_score_ips.txt | - | - | 15 | 15 | 0 | OK |
| https://raw.githubusercontent.com/zy1078/cf-IP/master/ip.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://raw.githubusercontent.com/ymyuuu/IPDB/main/bestcf.txt | - | - | 15 | 15 | 0 | OK |
| https://raw.githubusercontent.com/demon-hugo/CF-iP/main/cloudflare_ips-us.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/demon-hugo/CF-iP/main/cloudflare_ips.txt | - | - | 10 | 10 | 0 | OK |
| https://raw.githubusercontent.com/a2622113/cloudflare_IPv4/main/ip.txt | - | - | 125 | 125 | 0 | OK |
| https://bestcf.pages.dev/s5gy/all.txt | - | - | 52 | 52 | 0 | OK |
| https://raw.githubusercontent.com/Coolapk-Code9527/Cloudflare-IP/main/ip.txt | - | - | 24 | 24 | 0 | OK |
| https://raw.githubusercontent.com/einsitang/my-fast-cf-ip/master/fastips.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/uezer/cf-prefer-ips/main/best.txt | - | - | 20 | 20 | 0 | OK |
| https://raw.githubusercontent.com/aihddelyy/Cloudflare_ips/main/CF.txt | - | - | 6 | 6 | 0 | OK |
| https://cdn.jsdelivr.net/gh/joname1/BestCFip@main/ipv4.txt | - | - | 103 | 103 | 0 | OK |
| https://cdn.jsdelivr.net/gh/joname1/BestCFip@main/ipv6.txt | - | - | 41 | 41 | 0 | OK |
| https://cdn.jsdelivr.net/gh/hubbylei/bestcf@main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/gshtwy/CF-DNS-Clone@main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/best_ips.txt | - | - | 37 | 37 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/full_ips.txt | - | - | 408 | 408 | 0 | OK |
| https://cdn.jsdelivr.net/gh/XIU2/CloudflareSpeedTest@master/ip.txt | - | - | 1600 | 1600 | 8 | OK |
| https://cdn.jsdelivr.net/gh/LancelotRar/best-cf-ips@main/best-cf-ip-scanned-top400.txt | - | - | 400 | 400 | 0 | OK |
| https://cdn.jsdelivr.net/gh/sanzang-tango/best-cf-ip@main/best-cf-ipv4.txt | - | 外延3 | 338 | 338 | 3 | OK |
| https://cdn.jsdelivr.net/gh/mall994/cloudflare-best-ip@main/best-ips.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/suancaicc/cf-ip@main/ip.txt | - | - | 30 | 30 | 0 | OK |
| https://cdn.jsdelivr.net/gh/KafeMars/best-ips-domains@main/cf-bestips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/aihddelyy/Cloudflare_ips@main/CFST.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/cfipv4db@main/high_score_ips.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/zy1078/cf-IP@master/ip.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/bestcf.txt | - | - | 15 | 15 | 0 | OK |
| https://ipdb.api.030101.xyz/?type=cfv4%3Bproxy | - | 外延1 | 1683 | 1683 | 4 | OK |
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
| https://bestcf.tools12345.com/cmliu/all.txt | - | 外延1 | 32 | 32 | 1 | OK |
| https://bestcf.tools12345.com/cmliu2/all.txt | - | - | 15 | 15 | 0 | OK |
| https://bestcf.tools12345.com/gslege/Cfxyz.txt | - | - | 3 | 3 | 0 | OK |
| https://bestcf.tools12345.com/gslege/DE.txt | - | - | 22 | 22 | 1 | OK |
| https://bestcf.tools12345.com/gslege/SG.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/gslege/US.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/ircf/ipv4.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/lajiao/all.txt | - | - | 129 | 129 | 0 | OK |
| https://bestcf.tools12345.com/luoli/all.txt | - | - | 31 | 31 | 0 | OK |
| https://bestcf.tools12345.com/lzj/all.txt | - | - | 10 | 10 | 2 | OK |
| https://bestcf.tools12345.com/moistr/all.txt | - | - | 33 | 33 | 0 | OK |
| https://bestcf.tools12345.com/nirevil/ipv4.txt | - | - | 37 | 37 | 0 | OK |
| https://bestcf.tools12345.com/nirevil/ipv6.txt | - | - | 7 | 7 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/all.txt | - | - | 52 | 52 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/hk.txt | - | - | 4 | 4 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/jp.txt | - | - | 27 | 27 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/mini.txt | - | - | 20 | 20 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/sg.txt | - | - | 10 | 10 | 0 | OK |
| https://bestcf.tools12345.com/s5gy/us.txt | - | - | 16 | 16 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/all.txt | - | - | 68 | 68 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/hk.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/jp.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/kr.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/mini.txt | - | - | 23 | 23 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/sg.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/tiancheng/us.txt | - | - | 12 | 12 | 0 | OK |
| https://bestcf.tools12345.com/uouin/all.txt | - | - | 42 | 42 | 0 | OK |
| https://bestcf.tools12345.com/vvhan/ipv4.txt | - | - | 27 | 27 | 0 | OK |
| https://bestcf.tools12345.com/vvhan/ipv6.txt | - | - | 22 | 22 | 0 | OK |
| https://bestcf.tools12345.com/wetest/ipv4.txt | - | - | 15 | 15 | 0 | OK |
| https://bestcf.tools12345.com/xinyitang3/ipv4.txt | - | - | 20 | 20 | 0 | OK |
| https://bestcf.tools12345.com/zhixuanwang/ipv4-onlyip.txt | - | - | 4 | 4 | 0 | OK |
| https://cf.junzhen.qzz.io/best_ips.txt | - | - | 12 | 12 | 0 | OK |
| https://cf.junzhen.qzz.io/best_ips_bj.txt | - | - | 27 | 27 | 0 | OK |
| https://cdn.jsdelivr.net/gh/JieChaoCC/cf-ip-auto@main/data/ipapi.txt | - | - | 9 | 9 | 0 | OK |
| https://cdn.jsdelivr.net/gh/LancelotRar/best-cf-ips@main/best-cf-ipv4.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/Senflare/Senflare-IP@main/IPlist-Pro.txt | - | - | 29 | 29 | 0 | OK |
| https://cdn.jsdelivr.net/gh/Senflare/Senflare-IP@main/Senflare-Pro.txt | - | - | 29 | 29 | 0 | OK |
| https://cdn.jsdelivr.net/gh/ahang39/router@main/all.txt | - | - | 5 | 5 | 0 | OK |
| https://cdn.jsdelivr.net/gh/cmliu/WorkerVless2sub@main/addressesapi.txt | - | - | 4 | 4 | 0 | OK |
| https://cdn.jsdelivr.net/gh/einsitang/my-fast-cf-ip@master/fastips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/gshtwy/CF-DNS-Clone@main/wetest-cloudflare-v4.txt | - | - | 75 | 75 | 0 | OK |
| https://cdn.jsdelivr.net/gh/hubbylei/bestcf@main/bestcf.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/love-ztm/cfip@main/best_ips.txt | - | - | 3 | 3 | 0 | OK |
| https://cdn.jsdelivr.net/gh/love-ztm/cfip@main/ubest_ips.txt | - | - | 12 | 12 | 0 | OK |
| https://cdn.jsdelivr.net/gh/svip-s/cloudflare_ip@main/best_ips.txt | - | - | 37 | 37 | 0 | OK |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/BestCF/bestcfv4.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/ymyuuu/IPDB@main/BestCF/bestcfv6.txt | - | - | 10 | 10 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/cfipv4db@main/cfip.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yuanxiawan/ipscan-pages@main/output/ips.txt | - | - | 20 | 20 | 0 | OK |
| https://cdn.jsdelivr.net/gh/spew1165/cf-yx@main/ip/cf-speed-dns-top10.txt | - | - | 4 | 4 | 0 | OK |
| https://cdn.jsdelivr.net/gh/xxzh72/yxym@main/ip.txt | - | - | 80 | 80 | 0 | OK |
| https://cdn.jsdelivr.net/gh/meishero/cf-bestip@main/best_ip_dianxin.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/meishero/cf-bestip@main/best_ip_yidong.txt | - | - | 15 | 15 | 0 | OK |
| https://cdn.jsdelivr.net/gh/YiMing918/ym-cfip@main/data/full.txt | - | - | 403 | 403 | 0 | OK |
| https://cdn.jsdelivr.net/gh/YiMing918/ym-cfip@main/data/all6.tx | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/jifengwind/HHP-cf-ips@main/ips.txt | - | - | 29 | 29 | 0 | OK |
| https://cdn.jsdelivr.net/gh/luckyops/cf-pool@main/add.txt | - | - | 50 | 50 | 0 | OK |
| https://cdn.jsdelivr.net/gh/minghe168/cfip-auto@main/best_ips.txt | - | - | 0 | 0 | 0 | OK |
| https://cdn.jsdelivr.net/gh/burylove-baby/cf-ips@main/ai.txt | - | - | 8 | 8 | 0 | OK |
| https://cdn.jsdelivr.net/gh/yydfys/cm@main/1-px.txt | - | - | 0 | 0 | 0 | FAIL HTTP Error 404: Not Found |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/best.txt | - | - | 11 | 11 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/day1.txt | - | - | 559 | 559 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/day2.txt | - | - | 93 | 93 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time0.txt | - | - | 126 | 126 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time12.txt | - | - | 161 | 161 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time16.txt | - | - | 156 | 156 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time2.txt | - | - | 154 | 154 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time20.txt | - | - | 194 | 194 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time4.txt | - | - | 172 | 172 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/time8.txt | - | - | 158 | 158 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/topbest.txt | - | - | 8 | 8 | 0 | OK |
| https://cdn.jsdelivr.net/gh/kele9988/cf-best-ip@main/web.txt | - | - | 1874 | 1874 | 3 | OK |

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
| <10 | 6 |
| >=10 | 39 |

## 机房地区分布 (Top)
| 机房 | 数量 |
| --- | --- |
| LAX | 50 |

## 纯净 IP 明细

| IP:端口 | 延迟(ms) | 丢包 | TLS | 速度(MB/s) | 机房 | 原生 | 段 | 分数 | 分数构成 | 达标轮次 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 141.148.187.195:443 | 2.8 | 0% | OK | 7.98 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 129.153.127.204:20756 | 4.6 | 0% | OK | 7.80 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 179.255.111.123:443 | 8.4 | 0% | OK | 7.60 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 179.255.133.246:80 | 8.4 | 0% | OK | 7.60 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 179.255.103.81:443 | 8.6 | 0% | OK | 7.77 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 179.255.141.129:443 | 8.6 | 0% | OK | 7.57 | LAX | - | 外延段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.69.75:443 | 8.7 | 0% | OK | 13.46 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.108.58:443 | 8.7 | 0% | OK | 13.85 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.149.96:443 | 8.7 | 0% | OK | 13.51 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.18.58.34:443 | 8.7 | 0% | OK | 13.00 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.17.214.161:2053 | 8.7 | 0% | OK | 12.92 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.65.60.221:443 | 8.8 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.45.166:443 | 8.8 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 190.93.244.136:443 | 8.8 | 0% | OK | 12.91 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.203.244:443 | 8.8 | 0% | OK | 13.30 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.24.210.148:443 | 8.8 | 0% | OK | 13.22 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.168.171:443 | 8.8 | 0% | OK | 12.10 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.16.0.7:443 | 8.8 | 0% | OK | 13.02 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.245.117:443 | 8.8 | 0% | OK | 13.28 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 162.159.156.14:443 | 8.8 | 0% | OK | 13.95 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.66.162.205:443 | 8.8 | 0% | OK | 13.60 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.66.41.147:443 | 8.8 | 0% | OK | 12.95 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.66.0.59:443 | 8.8 | 0% | OK | 12.81 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 173.245.59.208:443 | 8.8 | 0% | OK | 13.28 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.132.181:443 | 8.8 | 0% | OK | 14.01 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.200.72:443 | 8.8 | 0% | OK | 12.94 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 162.159.82.37:443 | 8.8 | 0% | OK | 13.39 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.17.24.183:443 | 8.8 | 0% | OK | 11.49 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.16.235.118:443 | 8.8 | 0% | OK | 13.28 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.27.118.9:443 | 8.8 | 0% | OK | 13.45 | LAX | 是 | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 原生段+10 反标记-20 (合计120→封顶100) | 3/3 |
| 104.19.84.42:443 | 8.8 | 0% | OK | 13.44 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.25.0.1:443 | 8.8 | 0% | OK | 13.25 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.69.44:443 | 8.8 | 0% | OK | 13.10 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.26.4.7:443 | 8.8 | 0% | OK | 11.40 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 104.19.133.113:443 | 8.8 | 0% | OK | 13.23 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.244.249:443 | 8.9 | 0% | OK | 12.60 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 190.93.246.212:443 | 8.9 | 0% | OK | 13.72 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.99.34:443 | 8.9 | 0% | OK | 12.68 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.96.77:443 | 8.9 | 0% | OK | 13.32 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 188.114.96.57:443 | 8.9 | 0% | OK | 13.10 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.215.47:443 | 8.9 | 0% | OK | 13.00 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.217.125:443 | 8.9 | 0% | OK | 13.09 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 198.41.207.169:443 | 8.9 | 0% | OK | 13.02 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 162.159.145.180:443 | 8.9 | 0% | OK | 13.07 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.64.145.133:443 | 8.9 | 0% | OK | 12.96 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.66.3.217:443 | 8.9 | 0% | OK | 13.46 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.67.103.163:443 | 8.9 | 0% | OK | 13.16 | LAX | - | 公告段 | 100 good | 延迟+20 丢包+15 速度+15 TLS+10 colo+10 反标记-20 (合计110→封顶100) | 3/3 |
| 172.65.35.154:443 | 9.0 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.51.235:443 | 9.0 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |
| 172.65.42.121:443 | 9.0 | 0% | OK | - | LAX | - | 公告段 | 95 good | 延迟+20 丢包+15 速度 未测(0) TLS+10 colo+10 反标记-20 | - |