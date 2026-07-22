# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-22 13:45:18 |
| 运行耗时 | 292.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 82331 |
| 去重后节点 | 22710 |
| TCP 可达 | 3000 |
| 真实可用 | 533 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22710 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.3 |
| tcp | 31.7 |
| probe | 60.1 |
| real_test | 150.7 |
| generate | 42.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48230 |
| trojan | 12678 |
| vmess | 10767 |
| shadowsocks | 10068 |
| hysteria2 | 398 |
| shadowsocksr | 71 |
| http | 50 |
| socks | 46 |
| hysteria | 16 |
| tuic | 5 |
| anytls | 2 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 75.27 | vless | 175.1 | 474.3 | 23.72 | 0.0 | 10.0 | 4.17 | 17.38 | mheidari-all | 86.109.75.147 |
| 73.22 | vless | 220.8 | 596.4 | 22.67 | 0.0 | 10.0 | 4.17 | 17.38 | mheidari-all | 104.16.9.20 |
| 72.41 | trojan | 299.7 | 726.8 | 20.84 | 0.0 | 10.0 | 11.71 | 17.38 | mheidari-all | 34.222.117.208 |
| 71.66 | trojan | 284.7 | 669.9 | 21.19 | 0.0 | 10.0 | 11.71 | 17.38 | mheidari-all | 35.163.152.150 |
| 71.42 | trojan | 329.5 | 672.1 | 20.15 | 0.0 | 10.0 | 11.71 | 17.38 | mheidari-all | 163.245.196.68 |
| 70.43 | trojan | 295.9 | 688.9 | 20.93 | 0.0 | 10.0 | 11.71 | 17.38 | mheidari-all | 44.255.92.71 |
| 69.65 | vless | 202.3 | 521.8 | 23.1 | 0.0 | 10.0 | 4.17 | 17.38 | mheidari-all | 167.17.68.205 |
| 68.86 | vless | 257.7 | 700.0 | 21.81 | 0.0 | 10.0 | 4.17 | 17.38 | mheidari-all | 104.18.42.163 |
| 66.86 | trojan | 593.9 | 1579.1 | 14.03 | 0.0 | 10.0 | 11.71 | 17.38 | mheidari-all | 35.89.240.174 |
| 65.58 | trojan | 328.6 | 795.9 | 20.17 | 0.0 | 10.0 | 11.71 | 12.9 | DeltaKronecker-all | 16.147.206.1 |
| 65.35 | vless | 283.7 | 628.4 | 21.21 | 0.0 | 10.0 | 4.17 | 17.38 | mheidari-all | 216.227.161.95 |
| 65.22 | trojan | 563.9 | 1512.4 | 14.72 | 0.0 | 10.0 | 11.71 | 17.38 | mheidari-all | 184.33.27.255 |
| 64.93 | hysteria2 | 276.1 | 373.2 | 21.39 | 1.0 | 9.93 | 12.0 | 8.76 | xiaoji235-airport-v2ray-all | 45.76.202.45 |
| 64.12 | trojan | 510.0 | 691.2 | 15.97 | 0.0 | 9.58 | 11.71 | 17.38 | mheidari-all | 82.117.225.20 |
| 64.09 | vless | 353.4 | 703.8 | 19.6 | 0.0 | 10.0 | 4.17 | 17.38 | mheidari-all | 154.193.55.183 |
| 64.07 | trojan | 509.7 | 689.9 | 15.98 | 0.0 | 9.58 | 11.71 | 17.38 | mheidari-all | 82.117.225.216 |
| 64.05 | trojan | 513.3 | 696.5 | 15.9 | 0.0 | 9.58 | 11.71 | 17.38 | mheidari-all | 87.121.33.68 |
| 63.9 | trojan | 518.4 | 710.5 | 15.78 | 0.0 | 9.58 | 11.71 | 17.38 | mheidari-all | 82.117.225.249 |
| 63.86 | trojan | 520.9 | 716.3 | 15.72 | 0.0 | 9.58 | 11.71 | 17.38 | mheidari-all | 87.121.33.171 |
| 63.63 | trojan | 529.0 | 731.2 | 15.53 | 0.0 | 9.58 | 11.71 | 17.38 | mheidari-all | 82.117.225.56 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.883 | 0.814 | 59 | 5401 | prefer |
| mheidari-all | 0.699 | 0.619 | 588 | 19287 | observe |
| DeltaKronecker-all | 0.647 | 0.568 | 139 | 5212 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 4246 | observe |
| Au1rxx-base64 | 0.329 | 1.0 | 2 | 432 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4613 | observe |
| Epodonios-all | 0.255 | None | 0 | 6476 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6830 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4210 | observe |
| barry-far-vless | 0.255 | None | 0 | 4805 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5204 | observe |
| nscl5-all | 0.255 | None | 0 | 2197 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 99 |
| speed | ClientOSError | - | 92 |
| cn-block | TimeoutError | - | 26 |
| 204 | TimeoutError | - | 23 |
| geo | ClientOSError | - | 20 |
| speed | TimeoutError | - | 16 |
| cn-block | ProxyError | - | 6 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
