# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-08 18:33:36 |
| 运行耗时 | 228.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83395 |
| 去重后节点 | 23589 |
| TCP 可达 | 3000 |
| 真实可用 | 426 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23589 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.3 |
| tcp | 35.3 |
| probe | 49.4 |
| real_test | 98.9 |
| generate | 39.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48932 |
| vmess | 13063 |
| trojan | 10089 |
| shadowsocks | 9789 |
| hysteria2 | 1333 |
| shadowsocksr | 68 |
| socks | 63 |
| http | 36 |
| hysteria | 13 |
| tuic | 8 |
| anytls | 1 |

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
| 84.13 | hysteria2 | 263.5 | 663.0 | 21.68 | 0.0 | 10.0 | 13.75 | 19.8 | Au1rxx-base64 | 159.223.157.129 |
| 84.06 | hysteria2 | 270.6 | 709.6 | 21.51 | 0.0 | 10.0 | 13.75 | 19.8 | Au1rxx-base64 | 138.124.68.188 |
| 83.07 | hysteria2 | 271.2 | 710.3 | 21.5 | 0.0 | 9.02 | 13.75 | 19.8 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.26 | trojan | 285.3 | 678.4 | 21.17 | 0.0 | 10.0 | 14.15 | 19.8 | Au1rxx-base64 | 64.94.95.115 |
| 80.98 | shadowsocks | 251.0 | 615.5 | 21.97 | 0.0 | 10.0 | 13.21 | 19.8 | Au1rxx-base64 | 156.146.38.170 |
| 80.9 | trojan | 285.2 | 680.8 | 21.18 | 0.0 | 10.0 | 14.15 | 19.8 | Au1rxx-base64 | 64.94.95.114 |
| 80.88 | shadowsocks | 255.3 | 633.4 | 21.87 | 0.0 | 10.0 | 13.21 | 19.8 | Au1rxx-base64 | 156.146.38.167 |
| 80.72 | shadowsocks | 262.2 | 661.4 | 21.71 | 0.0 | 10.0 | 13.21 | 19.8 | Au1rxx-base64 | 37.19.198.236 |
| 80.62 | trojan | 287.5 | 684.7 | 21.12 | 0.0 | 10.0 | 14.15 | 19.8 | Au1rxx-base64 | 64.94.95.118 |
| 80.48 | shadowsocks | 272.7 | 704.8 | 21.47 | 0.0 | 10.0 | 13.21 | 19.8 | Au1rxx-base64 | 37.19.198.244 |
| 80.45 | shadowsocks | 273.7 | 706.3 | 21.44 | 0.0 | 10.0 | 13.21 | 19.8 | Au1rxx-base64 | 37.19.198.160 |
| 79.2 | shadowsocks | 327.8 | 867.6 | 20.19 | 0.0 | 10.0 | 13.21 | 19.8 | Au1rxx-base64 | 37.19.198.243 |
| 77.11 | trojan | 284.6 | 678.2 | 21.19 | 0.0 | 10.0 | 14.15 | 19.8 | Au1rxx-base64 | 64.94.95.117 |
| 75.58 | vless | 372.4 | 1002.0 | 19.16 | 0.0 | 10.0 | 7.72 | 19.8 | Au1rxx-base64 | 45.138.100.226 |
| 75.52 | shadowsocks | 285.3 | 534.1 | 21.17 | 0.0 | 10.0 | 13.21 | 19.8 | Au1rxx-base64 | 108.181.0.177 |
| 75.5 | shadowsocks | 252.7 | 623.9 | 21.93 | 0.0 | 10.0 | 13.21 | 19.8 | Au1rxx-base64 | 156.146.38.169 |
| 75.37 | trojan | 338.6 | 597.5 | 19.94 | 0.0 | 10.0 | 14.15 | 19.8 | Au1rxx-base64 | 44.244.3.114 |
| 75.26 | trojan | 336.5 | 579.1 | 19.99 | 0.0 | 10.0 | 14.15 | 19.8 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 75.21 | trojan | 336.7 | 588.7 | 19.98 | 0.0 | 10.0 | 14.15 | 19.8 | Au1rxx-base64 | 44.246.163.102 |
| 75.14 | shadowsocks | 255.1 | 619.7 | 21.87 | 0.0 | 10.0 | 13.21 | 19.8 | Au1rxx-base64 | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.948 | 345 | 1540 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.489 | 0.667 | 9 | 6588 | observe |
| mheidari-all | 0.48 | 1.0 | 4 | 17642 | observe |
| DeltaKronecker-all | 0.463 | 0.381 | 181 | 5347 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5450 | observe |
| Epodonios-all | 0.255 | None | 0 | 7201 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7604 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5351 | observe |
| barry-far-vless | 0.255 | None | 0 | 5666 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5127 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1540 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 37 |
| 204 | TimeoutError | - | 23 |
| geo | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 14 |
| speed | TimeoutError | - | 13 |
| geo | TimeoutError | - | 7 |
| speed | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
