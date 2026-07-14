# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-14 07:58:00 |
| 运行耗时 | 180.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 44 |
| 原始节点 | 78965 |
| 去重后节点 | 23661 |
| TCP 可达 | 3000 |
| 真实可用 | 250 |
| Verified 输出 | 250 |
| Global 输出 | 254 |
| All 输出 | 23661 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.4 |
| tcp | 30.8 |
| probe | 44.5 |
| real_test | 72.8 |
| generate | 23.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46712 |
| trojan | 11418 |
| vmess | 10689 |
| shadowsocks | 9376 |
| hysteria2 | 456 |
| http | 135 |
| shadowsocksr | 131 |
| socks | 30 |
| hysteria | 12 |
| anytls | 4 |
| tuic | 2 |

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
| 74.62 | shadowsocks | 344.2 | 816.4 | 19.81 | 0.0 | 10.0 | 14.3 | 16.94 | mheidari-all | 172.245.235.84 |
| 74.37 | trojan | 322.0 | 710.5 | 20.32 | 0.0 | 10.0 | 13.42 | 16.94 | mheidari-all | 64.94.95.118 |
| 71.74 | shadowsocks | 342.7 | 684.6 | 19.85 | 0.0 | 10.0 | 14.3 | 16.94 | mheidari-all | 198.98.53.130 |
| 70.71 | trojan | 248.6 | 458.6 | 22.02 | 0.0 | 10.0 | 13.42 | 16.96 | Surfboard-tg-mixed | 162.159.252.15 |
| 70.45 | trojan | 391.2 | 916.2 | 18.72 | 0.0 | 10.0 | 13.42 | 15.1 | DeltaKronecker-all | 64.94.95.117 |
| 70.34 | trojan | 237.3 | 538.5 | 22.28 | 0.0 | 10.0 | 13.42 | 16.96 | Surfboard-tg-mixed | 199.232.22.39 |
| 70.34 | trojan | 403.0 | 953.6 | 18.45 | 0.0 | 10.0 | 13.42 | 15.1 | DeltaKronecker-all | 64.94.95.114 |
| 69.81 | trojan | 438.7 | 1058.2 | 17.62 | 0.0 | 10.0 | 13.42 | 15.1 | DeltaKronecker-all | 64.94.95.115 |
| 69.73 | trojan | 337.8 | 337.5 | 19.96 | 2.34 | 9.9 | 13.42 | 15.1 | DeltaKronecker-all | 18.179.120.96 |
| 69.44 | shadowsocks | 389.4 | 775.1 | 18.76 | 0.0 | 10.0 | 14.3 | 16.94 | mheidari-all | 108.181.57.93 |
| 69.36 | trojan | 399.7 | 476.0 | 18.53 | 0.0 | 10.0 | 13.42 | 16.96 | Surfboard-tg-mixed | 199.232.78.140 |
| 69.28 | trojan | 406.0 | 401.0 | 18.38 | 0.0 | 10.0 | 13.42 | 16.96 | Surfboard-tg-mixed | 172.64.53.65 |
| 69.24 | trojan | 401.7 | 423.9 | 18.48 | 0.0 | 10.0 | 13.42 | 16.96 | Surfboard-tg-mixed | 151.101.56.7 |
| 69.02 | shadowsocks | 419.4 | 898.3 | 18.07 | 0.0 | 10.0 | 14.3 | 16.94 | mheidari-all | 185.196.61.82 |
| 68.79 | trojan | 470.8 | 327.5 | 16.88 | 2.72 | 9.47 | 13.42 | 16.96 | Surfboard-tg-mixed | 119.246.1.143 |
| 68.5 | trojan | 209.2 | 472.5 | 22.94 | 0.0 | 10.0 | 13.42 | 16.96 | Surfboard-tg-mixed | 45.131.5.9 |
| 66.96 | trojan | 493.9 | 780.1 | 16.35 | 0.0 | 10.0 | 13.42 | 16.96 | Surfboard-tg-mixed | 104.17.122.62 |
| 65.62 | trojan | 416.4 | 575.8 | 18.14 | 0.0 | 9.94 | 13.42 | 15.1 | DeltaKronecker-all | 52.68.90.114 |
| 65.32 | shadowsocks | 354.5 | 343.5 | 19.57 | 2.12 | 9.6 | 14.3 | 15.1 | DeltaKronecker-all | 36.224.158.182 |
| 65.22 | trojan | 351.2 | 352.3 | 19.65 | 1.79 | 10.0 | 13.42 | 15.1 | DeltaKronecker-all | 104.18.45.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| DeltaKronecker-all | 0.737 | 0.659 | 138 | 7942 | prefer |
| mheidari-all | 0.697 | 0.62 | 92 | 18408 | observe |
| Surfboard-tg-mixed | 0.653 | 0.574 | 108 | 5561 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 3836 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Au1rxx-base64 | 0.26 | 1.0 | 1 | 114 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4019 | observe |
| Epodonios-all | 0.255 | None | 0 | 6471 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6407 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4279 | observe |
| barry-far-vless | 0.255 | None | 0 | 4827 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5405 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 63 |
| speed | ClientOSError | - | 18 |
| 204 | TimeoutError | - | 11 |
| 204 | ClientOSError | - | 10 |
| geo | ClientOSError | - | 8 |
| speed | TimeoutError | - | 7 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| speed | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 250 | - |
| global | False | 300 | 254 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
