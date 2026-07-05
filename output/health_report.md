# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-05 19:13:00 |
| 运行耗时 | 166.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78312 |
| 去重后节点 | 24052 |
| TCP 可达 | 3000 |
| 真实可用 | 241 |
| Verified 输出 | 241 |
| Global 输出 | 254 |
| All 输出 | 24052 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.3 |
| tcp | 31.0 |
| probe | 48.8 |
| real_test | 56.5 |
| generate | 23.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45070 |
| trojan | 12671 |
| vmess | 10384 |
| shadowsocks | 9378 |
| hysteria2 | 477 |
| shadowsocksr | 141 |
| http | 135 |
| socks | 43 |
| tuic | 7 |
| hysteria | 6 |

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
| 77.38 | shadowsocks | 245.6 | 644.8 | 22.09 | 0.0 | 10.0 | 12.63 | 17.16 | mheidari-all | 108.181.57.93 |
| 75.65 | shadowsocks | 229.7 | 626.3 | 22.46 | 0.0 | 10.0 | 12.63 | 14.56 | Au1rxx-base64 | 37.19.198.160 |
| 75.52 | trojan | 328.7 | 758.0 | 20.17 | 0.0 | 10.0 | 13.16 | 17.5 | DeltaKronecker-all | 45.32.198.247 |
| 75.49 | shadowsocks | 236.7 | 653.6 | 22.3 | 0.0 | 10.0 | 12.63 | 14.56 | Au1rxx-base64 | 37.19.198.244 |
| 75.33 | vmess | 397.0 | 1131.8 | 18.59 | 0.0 | 10.0 | 12.5 | 18.74 | Surfboard-tg-mixed | 67.220.95.3 |
| 75.16 | trojan | 332.8 | 770.6 | 20.07 | 0.0 | 10.0 | 13.16 | 17.5 | DeltaKronecker-all | 149.28.241.235 |
| 75.13 | trojan | 296.9 | 639.4 | 20.9 | 0.0 | 10.0 | 13.16 | 17.16 | mheidari-all | 64.94.95.118 |
| 74.36 | trojan | 321.0 | 717.2 | 20.35 | 0.0 | 10.0 | 13.16 | 17.5 | DeltaKronecker-all | 64.94.95.117 |
| 74.25 | shadowsocks | 290.0 | 816.2 | 21.06 | 0.0 | 10.0 | 12.63 | 14.56 | Au1rxx-base64 | 37.19.198.243 |
| 74.16 | trojan | 365.6 | 864.7 | 19.31 | 0.0 | 10.0 | 13.16 | 17.5 | DeltaKronecker-all | 45.32.195.168 |
| 74.1 | shadowsocks | 296.7 | 817.9 | 20.91 | 0.0 | 10.0 | 12.63 | 14.56 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 73.53 | shadowsocks | 345.7 | 852.1 | 19.78 | 0.0 | 10.0 | 12.63 | 17.16 | mheidari-all | 185.196.61.82 |
| 72.76 | trojan | 382.2 | 900.8 | 18.93 | 0.0 | 10.0 | 13.16 | 17.5 | DeltaKronecker-all | 64.94.95.115 |
| 72.68 | trojan | 378.7 | 907.3 | 19.01 | 0.0 | 10.0 | 13.16 | 17.5 | DeltaKronecker-all | 64.94.95.114 |
| 72.18 | shadowsocks | 283.9 | 657.6 | 21.21 | 0.0 | 10.0 | 12.63 | 14.56 | Au1rxx-base64 | 156.146.38.168 |
| 71.54 | shadowsocks | 287.1 | 664.4 | 21.13 | 0.0 | 10.0 | 12.63 | 14.56 | Au1rxx-base64 | 156.146.38.167 |
| 71.37 | shadowsocks | 280.0 | 644.3 | 21.3 | 0.0 | 10.0 | 12.63 | 14.56 | Au1rxx-base64 | 156.146.38.169 |
| 71.33 | trojan | 442.3 | 784.5 | 17.54 | 0.0 | 10.0 | 13.16 | 18.74 | Surfboard-tg-mixed | 165.215.250.14 |
| 70.39 | trojan | 436.7 | 767.8 | 17.67 | 0.0 | 10.0 | 13.16 | 17.5 | DeltaKronecker-all | 104.19.64.105 |
| 70.25 | trojan | 441.9 | 759.8 | 17.55 | 0.0 | 10.0 | 13.16 | 17.5 | DeltaKronecker-all | 162.159.253.41 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.842 | 0.769 | 78 | 16094 | prefer |
| Surfboard-tg-mixed | 0.816 | 0.742 | 89 | 5733 | prefer |
| Au1rxx-base64 | 0.778 | 0.793 | 29 | 102 | prefer |
| DeltaKronecker-all | 0.705 | 0.628 | 86 | 7739 | prefer |
| nscl5-all | 0.364 | 1.0 | 2 | 1323 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4662 | observe |
| Epodonios-all | 0.255 | None | 0 | 7047 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6940 | observe |
| barry-far-vless | 0.255 | None | 0 | 4982 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5372 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.227 | None | 0 | 1288 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 19 |
| 204 | TimeoutError | - | 16 |
| 204 | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| geo | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 241 | - |
| global | False | 300 | 254 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
