# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 21:18:48 |
| 运行耗时 | 569.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96058 |
| 去重后节点 | 26884 |
| TCP 可达 | 3000 |
| 真实可用 | 365 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26884 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 44.6 |
| probe | 235.4 |
| real_test | 197.1 |
| generate | 82.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57123 |
| vmess | 16954 |
| shadowsocks | 11916 |
| trojan | 8419 |
| hysteria2 | 1261 |
| shadowsocksr | 164 |
| http | 121 |
| socks | 56 |
| anytls | 21 |
| hysteria | 17 |
| tuic | 6 |

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
| 77.36 | shadowsocks | 263.8 | 619.1 | 21.67 | 0.0 | 10.0 | 13.03 | 16.66 | mheidari-all | 156.146.38.168 |
| 77.1 | shadowsocks | 239.2 | 593.3 | 22.24 | 0.0 | 8.77 | 13.03 | 17.06 | Au1rxx-base64 | 156.146.38.170 |
| 77.1 | shadowsocks | 243.9 | 627.3 | 22.13 | 0.0 | 8.88 | 13.03 | 17.06 | Au1rxx-base64 | 156.146.38.167 |
| 76.92 | shadowsocks | 247.7 | 613.3 | 22.04 | 0.0 | 8.79 | 13.03 | 17.06 | Au1rxx-base64 | 156.146.38.169 |
| 76.78 | hysteria2 | 300.4 | 635.9 | 20.82 | 0.0 | 8.78 | 12.0 | 17.06 | Au1rxx-base64 | 66.94.121.46 |
| 75.54 | shadowsocks | 294.3 | 712.1 | 20.97 | 0.0 | 10.0 | 13.03 | 16.66 | mheidari-all | 37.19.198.236 |
| 75.42 | hysteria2 | 322.0 | 773.7 | 20.32 | 0.0 | 8.88 | 12.0 | 17.06 | Au1rxx-base64 | 129.213.91.185 |
| 74.63 | shadowsocks | 298.7 | 731.5 | 20.86 | 0.0 | 10.0 | 13.03 | 17.16 | Surfboard-tg-mixed | 185.230.230.18 |
| 74.11 | shadowsocks | 296.7 | 718.4 | 20.91 | 0.0 | 8.77 | 13.03 | 17.06 | Au1rxx-base64 | 37.19.198.160 |
| 74.1 | vless | 338.4 | 784.6 | 19.94 | 0.0 | 10.0 | 10.56 | 17.06 | Au1rxx-base64 | 195.123.235.183 |
| 73.99 | shadowsocks | 309.0 | 765.0 | 20.62 | 0.0 | 8.88 | 13.03 | 17.06 | Au1rxx-base64 | 37.19.198.244 |
| 73.89 | vless | 363.8 | 779.0 | 19.36 | 0.0 | 10.0 | 10.56 | 17.06 | Au1rxx-base64 | 66.70.179.198 |
| 73.77 | shadowsocks | 379.8 | 931.6 | 18.99 | 0.0 | 10.0 | 13.03 | 17.06 | Au1rxx-base64 | 15.204.233.41 |
| 73.32 | vless | 395.7 | 860.9 | 18.62 | 0.0 | 10.0 | 10.56 | 17.06 | Au1rxx-base64 | 23.94.251.190 |
| 73.2 | vless | 283.2 | 645.1 | 21.22 | 0.0 | 8.86 | 10.56 | 17.06 | Au1rxx-base64 | 69.48.201.136 |
| 73.12 | trojan | 370.5 | 939.8 | 19.2 | 0.0 | 8.81 | 11.05 | 17.06 | Au1rxx-base64 | 66.23.203.21 |
| 73.12 | vless | 407.5 | 867.7 | 18.35 | 0.0 | 8.86 | 10.56 | 17.06 | Au1rxx-base64 | 169.40.42.90 |
| 72.47 | hysteria2 | 290.2 | 683.2 | 21.06 | 0.0 | 8.35 | 12.0 | 17.06 | Au1rxx-base64 | clash2.deep-links.com |
| 72.44 | vless | 408.3 | 952.1 | 18.33 | 0.0 | 10.0 | 10.56 | 17.06 | Au1rxx-base64 | 209.200.246.148 |
| 72.29 | shadowsocks | 363.5 | 876.8 | 19.36 | 0.0 | 8.75 | 13.03 | 17.06 | Au1rxx-base64 | 45.86.51.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.91 | 0.837 | 86 | 23903 | prefer |
| Au1rxx-base64 | 0.864 | 0.802 | 253 | 1598 | prefer |
| Surfboard-tg-mixed | 0.846 | 0.772 | 92 | 7007 | prefer |
| zhangkai | 0.518 | 0.519 | 27 | 31 | observe |
| DeltaKronecker-all | 0.401 | 0.571 | 7 | 4067 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| Epodonios-all | 0.255 | None | 0 | 7500 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10005 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5519 | observe |
| barry-far-vless | 0.255 | None | 0 | 5734 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1598 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 21 |
| 204 | TimeoutError | - | 14 |
| speed | ClientOSError | - | 13 |
| speed | TimeoutError | - | 11 |
| geo | ClientOSError | - | 8 |
| geo | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
