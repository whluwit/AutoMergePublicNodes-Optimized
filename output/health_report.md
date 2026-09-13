# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 03:08:57 |
| 运行耗时 | 1283.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 94344 |
| 去重后节点 | 25317 |
| TCP 可达 | 3000 |
| 真实可用 | 628 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25317 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 42.7 |
| probe | 473.5 |
| real_test | 678.0 |
| generate | 82.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57437 |
| vmess | 13747 |
| shadowsocks | 11033 |
| trojan | 8990 |
| hysteria2 | 2240 |
| http | 669 |
| shadowsocksr | 124 |
| socks | 63 |
| hysteria | 15 |
| anytls | 14 |
| tuic | 12 |

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
| 81.98 | vless | 201.1 | 494.9 | 23.12 | 0.0 | 9.22 | 11.46 | 18.18 | Au1rxx-base64 | 172.235.38.85 |
| 81.51 | hysteria2 | 295.4 | 725.7 | 20.94 | 0.0 | 10.0 | 13.39 | 18.18 | Au1rxx-base64 | 66.94.121.46 |
| 80.83 | shadowsocks | 222.6 | 496.4 | 22.63 | 0.0 | 10.0 | 13.82 | 18.38 | mheidari-all | 173.244.56.6 |
| 80.12 | shadowsocks | 253.0 | 610.7 | 21.92 | 0.0 | 10.0 | 13.82 | 18.38 | mheidari-all | 156.146.38.168 |
| 79.71 | shadowsocks | 251.8 | 612.6 | 21.95 | 0.0 | 10.0 | 13.82 | 18.38 | mheidari-all | 156.146.38.170 |
| 79.4 | shadowsocks | 217.1 | 541.3 | 22.75 | 0.0 | 9.15 | 13.82 | 18.18 | Au1rxx-base64 | 108.181.0.177 |
| 79.39 | shadowsocks | 240.7 | 582.5 | 22.21 | 0.0 | 9.18 | 13.82 | 18.18 | Au1rxx-base64 | 156.146.38.169 |
| 77.85 | shadowsocks | 221.6 | 532.2 | 22.65 | 0.0 | 10.0 | 13.82 | 18.38 | mheidari-all | 173.244.56.9 |
| 76.92 | vless | 241.0 | 611.1 | 22.2 | 0.0 | 10.0 | 11.46 | 18.18 | Au1rxx-base64 | 172.236.233.59 |
| 76.9 | hysteria2 | 329.3 | 731.2 | 20.16 | 0.0 | 9.22 | 13.39 | 18.18 | Au1rxx-base64 | 159.223.157.129 |
| 76.74 | vless | 219.3 | 464.6 | 22.7 | 0.0 | 10.0 | 11.46 | 18.38 | mheidari-all | 172.64.53.55 |
| 76.64 | vless | 203.0 | 508.4 | 23.08 | 0.0 | 9.18 | 11.46 | 18.18 | Au1rxx-base64 | 172.233.139.46 |
| 75.86 | shadowsocks | 288.5 | 631.5 | 21.1 | 0.0 | 10.0 | 13.82 | 18.38 | mheidari-all | 149.22.95.183 |
| 75.78 | vless | 274.2 | 463.5 | 21.43 | 0.0 | 9.21 | 11.46 | 18.18 | Au1rxx-base64 | 172.64.154.8 |
| 75.1 | vless | 265.5 | 545.2 | 21.63 | 0.0 | 10.0 | 11.46 | 18.38 | mheidari-all | 104.19.87.194 |
| 75.08 | shadowsocks | 246.5 | 602.8 | 22.07 | 0.0 | 10.0 | 13.82 | 16.4 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.06 | shadowsocks | 279.7 | 620.4 | 21.3 | 0.0 | 10.0 | 13.82 | 16.4 | Surfboard-tg-mixed | 23.150.248.20 |
| 74.56 | shadowsocks | 341.9 | 674.6 | 19.86 | 0.0 | 10.0 | 13.82 | 18.38 | mheidari-all | 108.181.118.10 |
| 74.48 | hysteria2 | 334.1 | 886.4 | 20.04 | 0.0 | 9.18 | 13.39 | 18.18 | Au1rxx-base64 | 107.175.219.48 |
| 73.87 | trojan | 282.6 | 626.6 | 21.24 | 0.0 | 10.0 | 10.0 | 18.38 | mheidari-all | 64.94.95.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.947 | 0.885 | 384 | 1598 | prefer |
| Surfboard-tg-mixed | 0.937 | 0.869 | 61 | 7440 | prefer |
| ermaozi | 0.71 | 0.708 | 24 | 436 | prefer |
| DeltaKronecker-all | 0.385 | 0.303 | 234 | 5970 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5301 | observe |
| mheidari-all | 0.333 | 0.253 | 570 | 20709 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 141 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4793 | observe |
| Epodonios-all | 0.255 | None | 0 | 7895 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8734 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6133 | observe |
| barry-far-vless | 0.255 | None | 0 | 6259 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1598 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 228 |
| geo | ClientOSError | - | 106 |
| speed | TimeoutError | - | 99 |
| speed | ClientOSError | - | 97 |
| cn-block | ClientOSError | - | 52 |
| 204 | TimeoutError | - | 34 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 18 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
