# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-31 19:21:15 |
| 运行耗时 | 233.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78880 |
| 去重后节点 | 22839 |
| TCP 可达 | 3000 |
| 真实可用 | 421 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22839 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.3 |
| tcp | 33.9 |
| probe | 56.0 |
| real_test | 106.7 |
| generate | 29.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47353 |
| vmess | 11919 |
| shadowsocks | 10178 |
| trojan | 8582 |
| hysteria2 | 576 |
| http | 87 |
| shadowsocksr | 74 |
| socks | 57 |
| anytls | 26 |
| hysteria | 14 |
| tuic | 14 |

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
| 81.36 | hysteria2 | 265.7 | 668.0 | 21.63 | 0.0 | 9.41 | 14.12 | 17.3 | Au1rxx-base64 | 159.223.157.129 |
| 77.81 | hysteria2 | 306.6 | 725.7 | 20.68 | 0.0 | 8.87 | 14.12 | 17.3 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 77.71 | shadowsocks | 248.7 | 610.9 | 22.02 | 0.0 | 9.47 | 12.92 | 17.3 | Au1rxx-base64 | 156.146.38.169 |
| 77.58 | shadowsocks | 254.2 | 624.1 | 21.89 | 0.0 | 9.47 | 12.92 | 17.3 | Au1rxx-base64 | 156.146.38.170 |
| 77.52 | hysteria2 | 296.4 | 712.2 | 20.92 | 0.0 | 9.42 | 14.12 | 17.3 | Au1rxx-base64 | 138.124.68.188 |
| 77.51 | shadowsocks | 257.6 | 650.3 | 21.81 | 0.0 | 9.48 | 12.92 | 17.3 | Au1rxx-base64 | 37.19.198.160 |
| 77.01 | shadowsocks | 279.5 | 710.3 | 21.31 | 0.0 | 9.48 | 12.92 | 17.3 | Au1rxx-base64 | 37.19.198.244 |
| 76.84 | shadowsocks | 254.7 | 629.8 | 21.88 | 0.0 | 9.47 | 12.92 | 17.3 | Au1rxx-base64 | 156.146.38.168 |
| 76.8 | shadowsocks | 288.4 | 745.2 | 21.1 | 0.0 | 9.48 | 12.92 | 17.3 | Au1rxx-base64 | 37.19.198.243 |
| 76.77 | http | 522.3 | 1398.2 | 15.69 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.5 |
| 76.71 | trojan | 347.6 | 859.5 | 19.73 | 0.0 | 9.67 | 13.64 | 17.3 | Au1rxx-base64 | 64.94.95.117 |
| 76.5 | vless | 326.7 | 879.6 | 20.21 | 0.0 | 10.0 | 8.99 | 17.3 | Au1rxx-base64 | 216.152.147.28 |
| 76.41 | shadowsocks | 305.3 | 792.9 | 20.71 | 0.0 | 9.48 | 12.92 | 17.3 | Au1rxx-base64 | 37.19.198.236 |
| 76.23 | http | 517.3 | 1396.1 | 15.8 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.8 |
| 75.92 | trojan | 340.9 | 837.8 | 19.89 | 0.0 | 9.67 | 13.64 | 17.3 | Au1rxx-base64 | 64.94.95.114 |
| 75.5 | trojan | 344.7 | 846.9 | 19.8 | 0.0 | 9.67 | 13.64 | 17.3 | Au1rxx-base64 | 64.94.95.115 |
| 75.49 | http | 524.4 | 1400.3 | 15.64 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.7 |
| 75.28 | trojan | 332.5 | 788.1 | 20.08 | 0.0 | 9.68 | 13.64 | 17.3 | Au1rxx-base64 | 163.245.196.68 |
| 75.19 | trojan | 376.1 | 942.8 | 19.07 | 0.0 | 9.67 | 13.64 | 17.3 | Au1rxx-base64 | 64.94.95.118 |
| 74.93 | vless | 347.1 | 943.9 | 19.74 | 0.0 | 10.0 | 8.99 | 17.3 | Au1rxx-base64 | 45.138.100.226 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 80 | 110 | prefer |
| Au1rxx-base64 | 0.83 | 0.765 | 396 | 1655 | prefer |
| DeltaKronecker-all | 0.622 | 0.667 | 15 | 5144 | observe |
| Surfboard-tg-mixed | 0.542 | 0.458 | 24 | 5433 | observe |
| mheidari-all | 0.537 | 0.455 | 33 | 16449 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 51 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5507 | observe |
| Epodonios-all | 0.255 | None | 0 | 6115 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6602 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4317 | observe |
| barry-far-vless | 0.255 | None | 0 | 4677 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5081 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 42 |
| 204 | TimeoutError | - | 17 |
| speed | TimeoutError | - | 15 |
| 204 | ProxyError | - | 14 |
| speed | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 8 |
| geo | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| speed | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
