# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 03:18:14 |
| 运行耗时 | 846.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89232 |
| 去重后节点 | 24474 |
| TCP 可达 | 3000 |
| 真实可用 | 520 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24474 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.4 |
| tcp | 41.5 |
| probe | 271.8 |
| real_test | 374.2 |
| generate | 150.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52789 |
| vmess | 14172 |
| shadowsocks | 10916 |
| trojan | 9030 |
| hysteria2 | 1434 |
| http | 678 |
| shadowsocksr | 127 |
| socks | 74 |
| hysteria | 8 |
| tuic | 2 |
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
| 81.28 | hysteria2 | 258.3 | 563.3 | 21.8 | 0.0 | 10.0 | 14.32 | 18.2 | Au1rxx-base64 | 66.94.121.46 |
| 81.08 | hysteria2 | 334.4 | 842.6 | 20.04 | 0.0 | 10.0 | 14.32 | 17.82 | mheidari-all | 159.223.157.129 |
| 80.08 | shadowsocks | 241.9 | 587.0 | 22.18 | 0.0 | 10.0 | 13.85 | 18.2 | Au1rxx-base64 | 156.146.38.170 |
| 80.02 | shadowsocks | 250.4 | 631.5 | 21.98 | 0.0 | 10.0 | 13.85 | 18.2 | Au1rxx-base64 | 156.146.38.168 |
| 79.13 | shadowsocks | 289.1 | 680.8 | 21.08 | 0.0 | 10.0 | 13.85 | 18.2 | Au1rxx-base64 | 37.19.198.236 |
| 78.79 | shadowsocks | 282.2 | 592.8 | 21.24 | 0.0 | 10.0 | 13.85 | 18.2 | Au1rxx-base64 | 23.150.248.20 |
| 78.72 | vless | 279.7 | 651.7 | 21.3 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 198.251.78.29 |
| 77.69 | vless | 307.3 | 735.8 | 20.66 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 47.253.226.114 |
| 77.09 | hysteria2 | 281.3 | 673.8 | 21.27 | 0.0 | 10.0 | 14.32 | 18.2 | Au1rxx-base64 | 108.59.244.158 |
| 75.85 | shadowsocks | 286.0 | 673.2 | 21.16 | 0.0 | 10.0 | 13.85 | 18.2 | Au1rxx-base64 | 37.19.198.243 |
| 75.62 | vless | 355.4 | 783.9 | 19.55 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 169.40.42.225 |
| 75.59 | shadowsocks | 295.8 | 700.3 | 20.93 | 0.0 | 10.0 | 13.85 | 18.2 | Au1rxx-base64 | 37.19.198.160 |
| 75.52 | vless | 288.4 | 565.4 | 21.1 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 172.235.43.210 |
| 75.22 | vless | 322.2 | 744.2 | 20.32 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 195.123.235.177 |
| 75.05 | vless | 343.5 | 690.0 | 19.83 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 169.40.42.104 |
| 74.77 | shadowsocks | 418.1 | 1059.8 | 18.1 | 0.0 | 10.0 | 13.85 | 18.2 | Au1rxx-base64 | 37.19.198.244 |
| 74.68 | vless | 391.5 | 876.0 | 18.72 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 169.40.42.232 |
| 74.6 | vless | 388.9 | 929.2 | 18.77 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 216.152.147.28 |
| 74.19 | vless | 400.2 | 957.3 | 18.51 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 169.40.42.163 |
| 74.18 | vless | 352.9 | 677.7 | 19.61 | 0.0 | 10.0 | 10.62 | 18.2 | Au1rxx-base64 | 169.40.42.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | 0.888 | 295 | 1703 | prefer |
| ermaozi | 0.809 | 0.815 | 27 | 396 | prefer |
| Surfboard-tg-mixed | 0.762 | 0.684 | 209 | 7464 | prefer |
| mheidari-all | 0.496 | 0.414 | 152 | 17792 | observe |
| DeltaKronecker-all | 0.366 | 0.28 | 82 | 6081 | observe |
| ermaozi-get_subscribe | 0.344 | 0.455 | 11 | 431 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 140 | observe |
| Epodonios-all | 0.255 | None | 0 | 7930 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8850 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5964 | observe |
| barry-far-vless | 0.255 | None | 0 | 6194 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4234 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1703 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 64 |
| speed | TimeoutError | - | 55 |
| geo | ClientOSError | - | 47 |
| speed | ClientOSError | - | 22 |
| 204 | ProxyError | - | 21 |
| cn-block | TimeoutError | - | 21 |
| cn-block | ClientOSError | - | 12 |
| 204 | ProxyConnectionError | - | 10 |
| 204 | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
