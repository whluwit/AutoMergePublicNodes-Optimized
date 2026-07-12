# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-12 13:12:17 |
| 运行耗时 | 183.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 77487 |
| 去重后节点 | 24240 |
| TCP 可达 | 3000 |
| 真实可用 | 268 |
| Verified 输出 | 268 |
| Global 输出 | 285 |
| All 输出 | 24240 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.3 |
| tcp | 32.7 |
| probe | 42.2 |
| real_test | 68.1 |
| generate | 32.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45097 |
| trojan | 11785 |
| vmess | 10571 |
| shadowsocks | 9405 |
| hysteria2 | 301 |
| shadowsocksr | 149 |
| http | 137 |
| socks | 30 |
| hysteria | 8 |
| tuic | 4 |

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
| 75.22 | trojan | 321.8 | 757.4 | 20.33 | 0.0 | 10.0 | 12.38 | 15.56 | DeltaKronecker-all | 45.32.195.168 |
| 72.76 | trojan | 340.4 | 762.8 | 19.9 | 0.0 | 10.0 | 12.38 | 15.56 | DeltaKronecker-all | 45.32.198.247 |
| 71.95 | trojan | 351.3 | 842.3 | 19.65 | 0.0 | 10.0 | 12.38 | 15.56 | DeltaKronecker-all | 64.94.95.117 |
| 71.73 | trojan | 250.4 | 496.7 | 21.98 | 0.0 | 10.0 | 12.38 | 16.74 | Surfboard-tg-mixed | 162.159.38.62 |
| 71.52 | trojan | 402.2 | 934.4 | 18.47 | 0.0 | 10.0 | 12.38 | 15.56 | DeltaKronecker-all | 64.94.95.114 |
| 71.0 | shadowsocks | 260.7 | 639.4 | 21.74 | 0.0 | 10.0 | 12.8 | 15.56 | DeltaKronecker-all | 107.172.219.230 |
| 70.99 | trojan | 375.1 | 911.4 | 19.1 | 0.0 | 10.0 | 12.38 | 15.56 | DeltaKronecker-all | 64.94.95.115 |
| 70.81 | trojan | 263.3 | 450.7 | 21.68 | 0.0 | 10.0 | 12.38 | 19.16 | mheidari-all | 5.10.215.9 |
| 70.34 | trojan | 366.5 | 879.3 | 19.29 | 0.0 | 10.0 | 12.38 | 19.16 | mheidari-all | 64.94.95.118 |
| 70.11 | trojan | 289.3 | 443.3 | 21.08 | 0.0 | 10.0 | 12.38 | 16.74 | Surfboard-tg-mixed | 104.21.52.100 |
| 68.92 | trojan | 261.2 | 465.0 | 21.73 | 0.0 | 10.0 | 12.38 | 16.74 | Surfboard-tg-mixed | 162.159.252.15 |
| 68.38 | trojan | 257.0 | 531.8 | 21.83 | 0.0 | 10.0 | 12.38 | 16.74 | Surfboard-tg-mixed | 45.131.5.9 |
| 66.73 | shadowsocks | 459.6 | 1015.6 | 17.14 | 0.0 | 10.0 | 12.8 | 16.74 | Surfboard-tg-mixed | 185.196.61.82 |
| 66.14 | shadowsocks | 469.5 | 1043.9 | 16.91 | 0.0 | 10.0 | 12.8 | 16.74 | Surfboard-tg-mixed | 108.181.57.93 |
| 65.33 | trojan | 467.6 | 641.1 | 16.95 | 0.0 | 10.0 | 12.38 | 16.74 | Surfboard-tg-mixed | 108.162.194.119 |
| 65.0 | trojan | 436.2 | 532.8 | 17.68 | 0.0 | 10.0 | 12.38 | 16.74 | Surfboard-tg-mixed | 45.8.211.217 |
| 64.79 | trojan | 459.5 | 373.5 | 17.14 | 0.99 | 9.9 | 12.38 | 15.56 | DeltaKronecker-all | 138.3.212.160 |
| 64.77 | trojan | 391.8 | 418.1 | 18.71 | 0.0 | 10.0 | 12.38 | 16.74 | Surfboard-tg-mixed | 104.24.212.83 |
| 64.68 | trojan | 659.2 | 953.3 | 12.52 | 0.0 | 10.0 | 12.38 | 19.16 | mheidari-all | 104.17.121.9 |
| 63.49 | hysteria2 | 444.2 | 759.4 | 17.49 | 0.0 | 9.64 | 10.0 | 14.62 | Au1rxx-base64 | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.81 | 0.734 | 109 | 5473 | prefer |
| DeltaKronecker-all | 0.68 | 0.601 | 173 | 8141 | observe |
| mheidari-all | 0.641 | 0.562 | 80 | 16365 | observe |
| xiaoji235-airport-v2ray-all | 0.315 | 1.0 | 1 | 1508 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Au1rxx-base64 | 0.259 | 1.0 | 1 | 99 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4003 | observe |
| Epodonios-all | 0.255 | None | 0 | 6473 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6883 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4231 | observe |
| barry-far-vless | 0.255 | None | 0 | 4831 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5416 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 30 |
| 204 | ProxyError | - | 23 |
| cn-block | ProxyError | - | 15 |
| cn-block | ClientOSError | - | 13 |
| geo | ClientOSError | - | 10 |
| speed | ProxyError | - | 10 |
| geo | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 8 |
| cn-block | TimeoutError | - | 3 |
| geo | ProxyError | - | 3 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 268 | - |
| global | False | 300 | 285 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
