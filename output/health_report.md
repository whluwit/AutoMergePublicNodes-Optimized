# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 15:04:17 |
| 运行耗时 | 642.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 82953 |
| 去重后节点 | 22795 |
| TCP 可达 | 3000 |
| 真实可用 | 399 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22795 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 37.9 |
| probe | 270.5 |
| real_test | 245.3 |
| generate | 80.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50432 |
| vmess | 12590 |
| shadowsocks | 9740 |
| trojan | 7940 |
| hysteria2 | 1467 |
| http | 580 |
| shadowsocksr | 129 |
| socks | 57 |
| hysteria | 9 |
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
| 80.26 | vless | 249.7 | 653.6 | 22.0 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 172.233.139.46 |
| 79.65 | vless | 276.0 | 503.9 | 21.39 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 31.58.50.200 |
| 78.99 | vless | 304.4 | 793.3 | 20.73 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 15.204.97.216 |
| 76.54 | vless | 280.6 | 636.1 | 21.28 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 150.241.102.181 |
| 76.5 | vless | 289.8 | 533.2 | 21.07 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 144.172.104.26 |
| 75.21 | vless | 336.0 | 909.2 | 20.0 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 172.235.43.210 |
| 73.58 | shadowsocks | 344.4 | 795.1 | 19.81 | 0.0 | 10.0 | 13.32 | 18.4 | Au1rxx-base64 | 156.146.38.169 |
| 71.89 | vless | 416.7 | 427.7 | 18.13 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 104.21.70.21 |
| 71.73 | hysteria2 | 454.5 | 1023.0 | 17.26 | 0.0 | 10.0 | 11.4 | 18.4 | Au1rxx-base64 | 159.223.157.129 |
| 71.47 | vless | 291.0 | 310.8 | 21.04 | 3.34 | 9.77 | 9.86 | 14.68 | Surfboard-tg-mixed | 31.76.91.72 |
| 70.96 | vless | 651.4 | 1848.9 | 12.7 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 172.235.38.85 |
| 70.69 | vless | 414.4 | 837.9 | 18.18 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 47.253.226.114 |
| 70.63 | shadowsocks | 276.9 | 653.9 | 21.37 | 0.0 | 10.0 | 13.32 | 14.94 | mheidari-all | 173.244.56.9 |
| 70.4 | vless | 406.2 | 745.4 | 18.38 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 195.123.235.177 |
| 70.05 | vless | 464.7 | 306.8 | 17.02 | 3.5 | 9.49 | 9.86 | 18.4 | Au1rxx-base64 | 207.57.128.241 |
| 70.02 | trojan | 409.0 | 965.5 | 18.31 | 0.0 | 10.0 | 11.14 | 18.4 | Au1rxx-base64 | 64.94.95.114 |
| 69.93 | vless | 469.1 | 306.5 | 16.92 | 3.51 | 9.48 | 9.86 | 18.4 | Au1rxx-base64 | 38.147.172.2 |
| 69.91 | shadowsocks | 296.1 | 347.5 | 20.92 | 1.97 | 9.95 | 13.32 | 14.94 | mheidari-all | 149.22.87.240 |
| 69.8 | vless | 470.5 | 1037.3 | 16.89 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 216.152.147.28 |
| 69.7 | vless | 229.0 | 574.0 | 22.48 | 0.0 | 10.0 | 9.86 | 18.4 | Au1rxx-base64 | 104.18.46.234 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.859 | 0.803 | 264 | 1455 | prefer |
| Surfboard-tg-mixed | 0.775 | 0.698 | 126 | 7345 | prefer |
| mheidari-all | 0.729 | 0.653 | 72 | 15620 | prefer |
| DeltaKronecker-all | 0.685 | 0.61 | 41 | 5970 | observe |
| ermaozi | 0.583 | 0.571 | 35 | 393 | observe |
| ermaozi-get_subscribe | 0.465 | 0.857 | 7 | 408 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4793 | observe |
| Epodonios-all | 0.255 | None | 0 | 7743 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8825 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5912 | observe |
| barry-far-vless | 0.255 | None | 0 | 6112 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4207 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 36 |
| 204 | TimeoutError | - | 23 |
| 204 | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 13 |
| cn-block | ClientOSError | - | 11 |
| speed | TimeoutError | - | 11 |
| geo | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 5 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
