# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 20:13:32 |
| 运行耗时 | 507.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83807 |
| 去重后节点 | 23040 |
| TCP 可达 | 3000 |
| 真实可用 | 398 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23040 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 39.5 |
| probe | 195.1 |
| real_test | 177.8 |
| generate | 86.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50950 |
| vmess | 12607 |
| shadowsocks | 9733 |
| trojan | 8031 |
| hysteria2 | 1673 |
| http | 614 |
| shadowsocksr | 128 |
| socks | 53 |
| hysteria | 8 |
| tuic | 8 |
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
| 77.03 | trojan | 247.8 | 601.2 | 22.04 | 0.0 | 10.0 | 11.02 | 17.18 | Au1rxx-base64 | 64.94.95.118 |
| 76.54 | shadowsocks | 229.1 | 582.5 | 22.48 | 0.0 | 10.0 | 13.48 | 14.58 | mheidari-all | 156.146.38.168 |
| 76.43 | shadowsocks | 233.8 | 595.2 | 22.37 | 0.0 | 10.0 | 13.48 | 14.58 | mheidari-all | 156.146.38.170 |
| 76.26 | hysteria2 | 311.5 | 700.9 | 20.57 | 0.0 | 10.0 | 12.5 | 17.18 | Au1rxx-base64 | 159.223.157.129 |
| 76.14 | trojan | 295.5 | 531.1 | 20.94 | 0.0 | 10.0 | 11.02 | 17.18 | Au1rxx-base64 | 64.94.95.114 |
| 75.33 | shadowsocks | 281.0 | 739.5 | 21.27 | 0.0 | 10.0 | 13.48 | 14.58 | mheidari-all | 156.146.38.169 |
| 74.57 | vless | 286.3 | 552.8 | 21.15 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 172.235.43.210 |
| 74.47 | shadowsocks | 249.4 | 505.9 | 22.0 | 0.0 | 10.0 | 13.48 | 17.18 | Au1rxx-base64 | 108.181.0.177 |
| 74.38 | vless | 300.6 | 570.2 | 20.82 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 144.172.104.26 |
| 73.77 | vless | 290.8 | 590.3 | 21.05 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 172.233.139.46 |
| 72.63 | vless | 266.2 | 546.1 | 21.62 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 150.241.102.181 |
| 72.53 | vless | 348.1 | 753.6 | 19.72 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 216.152.147.28 |
| 72.51 | vless | 345.5 | 758.8 | 19.78 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 47.253.226.114 |
| 72.22 | shadowsocks | 239.4 | 608.4 | 22.24 | 0.0 | 10.0 | 13.48 | 15.5 | Surfboard-tg-mixed | 156.146.38.167 |
| 71.84 | shadowsocks | 301.8 | 659.8 | 20.79 | 0.0 | 10.0 | 13.48 | 15.5 | Surfboard-tg-mixed | 198.98.53.130 |
| 71.82 | vless | 341.6 | 680.6 | 19.87 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 195.123.235.177 |
| 71.58 | shadowsocks | 287.2 | 557.8 | 21.13 | 0.0 | 10.0 | 13.48 | 14.58 | mheidari-all | 173.244.56.6 |
| 71.29 | vless | 316.7 | 579.2 | 20.45 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 38.180.242.205 |
| 71.2 | vless | 381.1 | 788.8 | 18.96 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 2.24.124.64 |
| 70.76 | vless | 330.7 | 685.6 | 20.12 | 0.0 | 10.0 | 9.89 | 17.18 | Au1rxx-base64 | 198.251.78.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.919 | 0.852 | 54 | 15722 | prefer |
| Au1rxx-base64 | 0.909 | 0.845 | 317 | 1650 | prefer |
| DeltaKronecker-all | 0.822 | 0.759 | 29 | 5970 | prefer |
| Surfboard-tg-mixed | 0.82 | 0.746 | 71 | 7382 | prefer |
| ermaozi | 0.436 | 0.444 | 18 | 393 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 161 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4793 | observe |
| Epodonios-all | 0.255 | None | 0 | 7802 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8913 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5991 | observe |
| barry-far-vless | 0.255 | None | 0 | 6127 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1650 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 19 |
| geo | ClientOSError | - | 19 |
| speed | ClientOSError | - | 15 |
| cn-block | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 6 |
| speed | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 2 |
| geo | TimeoutError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
