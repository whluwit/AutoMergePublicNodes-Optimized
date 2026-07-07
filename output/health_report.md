# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-07 14:25:15 |
| 运行耗时 | 208.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 85084 |
| 去重后节点 | 24830 |
| TCP 可达 | 3000 |
| 真实可用 | 328 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24830 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 32.1 |
| probe | 43.5 |
| real_test | 87.7 |
| generate | 39.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50826 |
| trojan | 13037 |
| vmess | 10644 |
| shadowsocks | 9516 |
| hysteria2 | 707 |
| shadowsocksr | 144 |
| http | 140 |
| socks | 55 |
| hysteria | 8 |
| tuic | 4 |
| anytls | 3 |

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
| 78.29 | trojan | 306.3 | 746.8 | 20.69 | 0.0 | 10.0 | 13.47 | 17.34 | DeltaKronecker-all | 45.32.195.168 |
| 77.81 | trojan | 314.4 | 767.8 | 20.5 | 0.0 | 10.0 | 13.47 | 17.34 | DeltaKronecker-all | 45.32.198.247 |
| 77.13 | trojan | 308.3 | 742.2 | 20.64 | 0.0 | 10.0 | 13.47 | 16.44 | mheidari-all | 149.28.241.235 |
| 76.67 | trojan | 280.0 | 616.8 | 21.3 | 0.0 | 10.0 | 13.47 | 17.34 | DeltaKronecker-all | 64.94.95.114 |
| 76.43 | shadowsocks | 220.2 | 472.5 | 22.68 | 0.0 | 10.0 | 12.73 | 15.02 | Au1rxx-base64 | 173.244.56.6 |
| 76.33 | trojan | 284.0 | 631.5 | 21.2 | 0.0 | 10.0 | 13.47 | 17.34 | DeltaKronecker-all | 64.94.95.115 |
| 75.81 | shadowsocks | 225.6 | 562.1 | 22.56 | 0.0 | 10.0 | 12.73 | 15.02 | Au1rxx-base64 | 108.181.0.177 |
| 75.45 | shadowsocks | 258.9 | 632.4 | 21.78 | 0.0 | 10.0 | 12.73 | 15.02 | Au1rxx-base64 | 156.146.38.168 |
| 74.83 | shadowsocks | 267.9 | 687.9 | 21.58 | 0.0 | 10.0 | 12.73 | 15.02 | Au1rxx-base64 | 108.181.118.10 |
| 74.62 | shadowsocks | 264.1 | 644.9 | 21.66 | 0.0 | 10.0 | 12.73 | 15.02 | Au1rxx-base64 | 156.146.38.169 |
| 74.19 | trojan | 281.8 | 621.3 | 21.25 | 0.0 | 10.0 | 13.47 | 17.34 | DeltaKronecker-all | 64.94.95.117 |
| 73.7 | trojan | 394.5 | 933.7 | 18.65 | 0.0 | 10.0 | 13.47 | 18.08 | Surfboard-tg-mixed | 64.94.95.118 |
| 73.49 | shadowsocks | 304.0 | 758.9 | 20.74 | 0.0 | 10.0 | 12.73 | 15.02 | Au1rxx-base64 | 156.146.38.170 |
| 72.99 | shadowsocks | 239.3 | 568.0 | 22.24 | 0.0 | 10.0 | 12.73 | 15.02 | Au1rxx-base64 | 173.244.56.9 |
| 71.6 | trojan | 384.5 | 382.7 | 18.88 | 0.65 | 10.0 | 13.47 | 18.08 | Surfboard-tg-mixed | 199.232.237.250 |
| 71.46 | shadowsocks | 279.6 | 281.0 | 21.3 | 4.46 | 9.26 | 12.73 | 15.02 | Au1rxx-base64 | 149.22.87.241 |
| 71.21 | shadowsocks | 285.1 | 286.8 | 21.18 | 4.25 | 9.26 | 12.73 | 15.02 | Au1rxx-base64 | 149.22.87.240 |
| 71.13 | shadowsocks | 288.7 | 597.6 | 21.09 | 0.0 | 9.26 | 12.73 | 15.02 | Au1rxx-base64 | 149.22.95.183 |
| 70.33 | trojan | 394.5 | 441.7 | 18.65 | 0.0 | 10.0 | 13.47 | 18.08 | Surfboard-tg-mixed | 162.159.38.119 |
| 69.48 | shadowsocks | 261.0 | 636.8 | 21.74 | 0.0 | 10.0 | 12.73 | 15.02 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.889 | 0.815 | 92 | 18192 | prefer |
| Au1rxx-base64 | 0.882 | 0.891 | 55 | 115 | prefer |
| Surfboard-tg-mixed | 0.823 | 0.747 | 99 | 6102 | prefer |
| DeltaKronecker-all | 0.695 | 0.616 | 146 | 8472 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3626 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 176 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4700 | observe |
| Epodonios-all | 0.255 | None | 0 | 7142 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3977 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7271 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4575 | observe |
| barry-far-vless | 0.255 | None | 0 | 5254 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5338 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 44 |
| 204 | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 10 |
| geo | TimeoutError | - | 9 |
| geo | ClientOSError | - | 7 |
| cn-block | TimeoutError | - | 6 |
| geo | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
