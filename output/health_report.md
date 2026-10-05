# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-05 23:45:56 |
| 运行耗时 | 466.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98528 |
| 去重后节点 | 27348 |
| TCP 可达 | 3000 |
| 真实可用 | 480 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27348 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.5 |
| tcp | 47.1 |
| probe | 201.3 |
| real_test | 179.4 |
| generate | 31.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58673 |
| vmess | 15719 |
| shadowsocks | 11616 |
| trojan | 10165 |
| hysteria2 | 1396 |
| http | 635 |
| shadowsocksr | 169 |
| socks | 92 |
| anytls | 27 |
| tuic | 19 |
| hysteria | 17 |

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
| 80.77 | shadowsocks | 253.5 | 615.4 | 21.91 | 0.0 | 10.0 | 13.48 | 19.38 | Au1rxx-base64 | 156.146.38.170 |
| 80.55 | shadowsocks | 262.9 | 639.8 | 21.69 | 0.0 | 10.0 | 13.48 | 19.38 | Au1rxx-base64 | 156.146.38.167 |
| 80.34 | shadowsocks | 257.5 | 623.2 | 21.82 | 0.0 | 10.0 | 13.48 | 19.38 | Au1rxx-base64 | 156.146.38.168 |
| 79.78 | hysteria2 | 323.4 | 751.9 | 20.29 | 0.0 | 10.0 | 14.21 | 19.38 | Au1rxx-base64 | 129.213.91.185 |
| 79.04 | hysteria2 | 312.3 | 625.2 | 20.55 | 0.0 | 10.0 | 14.21 | 19.38 | Au1rxx-base64 | 66.94.121.46 |
| 78.52 | vless | 288.3 | 647.7 | 21.1 | 0.0 | 10.0 | 12.3 | 18.84 | mheidari-all | 216.227.161.95 |
| 78.0 | hysteria2 | 305.8 | 277.7 | 20.7 | 4.59 | 6.95 | 14.21 | 19.38 | Au1rxx-base64 | open.2ml.bid |
| 76.35 | vless | 314.4 | 606.2 | 20.5 | 0.0 | 10.0 | 12.3 | 19.38 | Au1rxx-base64 | 107.173.237.146 |
| 76.35 | hysteria2 | 406.9 | 909.6 | 18.36 | 0.0 | 10.0 | 14.21 | 18.84 | mheidari-all | 159.223.157.129 |
| 75.28 | vless | 364.1 | 592.7 | 19.35 | 0.0 | 10.0 | 12.3 | 19.38 | Au1rxx-base64 | 137.175.82.40 |
| 75.13 | hysteria2 | 289.5 | 281.8 | 21.08 | 4.43 | 8.83 | 14.21 | 19.38 | Au1rxx-base64 | open.w2m.ink |
| 74.29 | shadowsocks | 281.9 | 571.4 | 21.25 | 0.0 | 10.0 | 13.48 | 18.84 | mheidari-all | 216.105.168.18 |
| 74.28 | vless | 402.6 | 784.3 | 18.46 | 0.0 | 10.0 | 12.3 | 19.38 | Au1rxx-base64 | 137.184.218.169 |
| 74.16 | hysteria2 | 301.5 | 319.4 | 20.8 | 3.02 | 9.52 | 14.21 | 19.38 | Au1rxx-base64 | 132.226.14.77 |
| 74.15 | shadowsocks | 289.9 | 587.5 | 21.07 | 0.0 | 10.0 | 13.48 | 18.84 | mheidari-all | 173.244.56.9 |
| 73.91 | vless | 392.9 | 701.0 | 18.68 | 0.0 | 10.0 | 12.3 | 19.38 | Au1rxx-base64 | 15.204.97.216 |
| 73.8 | vless | 415.0 | 814.0 | 18.17 | 0.0 | 10.0 | 12.3 | 19.38 | Au1rxx-base64 | 169.40.42.90 |
| 73.52 | vless | 417.6 | 774.6 | 18.11 | 0.0 | 10.0 | 12.3 | 19.38 | Au1rxx-base64 | 169.40.42.184 |
| 73.24 | shadowsocks | 345.6 | 686.9 | 19.78 | 0.0 | 10.0 | 13.48 | 19.38 | Au1rxx-base64 | 108.181.0.177 |
| 73.21 | shadowsocks | 333.2 | 708.9 | 20.07 | 0.0 | 10.0 | 13.48 | 19.38 | Au1rxx-base64 | 66.23.204.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | 0.942 | 69 | 7145 | prefer |
| Au1rxx-base64 | 0.965 | 0.893 | 318 | 1862 | prefer |
| mheidari-all | 0.891 | 0.817 | 109 | 23213 | prefer |
| ermaozi | 0.609 | 0.583 | 60 | 701 | observe |
| DeltaKronecker-all | 0.446 | 0.8 | 5 | 5300 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 176 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5111 | observe |
| Epodonios-all | 0.255 | None | 0 | 7624 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9352 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5642 | observe |
| barry-far-vless | 0.255 | None | 0 | 5871 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4375 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 28 |
| cn-block | TimeoutError | - | 21 |
| geo | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 8 |
| speed | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
