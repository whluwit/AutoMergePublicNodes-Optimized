# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-30 17:38:28 |
| 运行耗时 | 547.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96189 |
| 去重后节点 | 27002 |
| TCP 可达 | 3000 |
| 真实可用 | 354 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27002 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 46.0 |
| probe | 240.2 |
| real_test | 161.2 |
| generate | 91.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58690 |
| vmess | 15045 |
| shadowsocks | 11295 |
| trojan | 9029 |
| hysteria2 | 1399 |
| http | 440 |
| shadowsocksr | 166 |
| socks | 70 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 8 |

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
| 79.56 | hysteria2 | 349.3 | 854.0 | 19.69 | 0.0 | 10.0 | 13.64 | 18.74 | mheidari-all | 159.223.157.129 |
| 79.33 | vless | 261.1 | 632.9 | 21.73 | 0.0 | 10.0 | 9.65 | 18.74 | mheidari-all | 216.227.161.95 |
| 78.05 | shadowsocks | 256.8 | 627.1 | 21.83 | 0.0 | 10.0 | 13.4 | 17.04 | Au1rxx-base64 | 156.146.38.168 |
| 77.95 | hysteria2 | 270.6 | 593.4 | 21.51 | 0.0 | 8.54 | 13.64 | 17.04 | Au1rxx-base64 | 192.255.128.123 |
| 77.35 | shadowsocks | 235.9 | 601.8 | 22.32 | 0.0 | 8.59 | 13.4 | 17.04 | Au1rxx-base64 | 156.146.38.169 |
| 77.25 | vless | 285.6 | 678.6 | 21.17 | 0.0 | 10.0 | 9.65 | 17.04 | Au1rxx-base64 | 198.251.78.29 |
| 76.89 | shadowsocks | 268.0 | 635.3 | 21.58 | 0.0 | 10.0 | 13.4 | 17.04 | Au1rxx-base64 | 198.98.53.130 |
| 76.71 | shadowsocks | 252.2 | 615.0 | 21.94 | 0.0 | 8.63 | 13.4 | 17.04 | Au1rxx-base64 | 156.146.38.170 |
| 74.62 | shadowsocks | 364.3 | 844.4 | 19.34 | 0.0 | 10.0 | 13.4 | 18.74 | mheidari-all | 140.82.63.79 |
| 74.27 | shadowsocks | 310.3 | 754.8 | 20.59 | 0.0 | 10.0 | 13.4 | 14.28 | Surfboard-tg-mixed | 156.146.38.167 |
| 73.37 | shadowsocks | 298.4 | 790.4 | 20.87 | 0.0 | 8.56 | 13.4 | 17.04 | Au1rxx-base64 | 66.23.204.219 |
| 73.35 | vless | 324.5 | 730.7 | 20.27 | 0.0 | 10.0 | 9.65 | 17.04 | Au1rxx-base64 | 66.70.179.198 |
| 73.02 | shadowsocks | 306.1 | 750.8 | 20.69 | 0.0 | 8.66 | 13.4 | 17.04 | Au1rxx-base64 | 37.19.198.236 |
| 72.68 | vless | 310.9 | 676.8 | 20.58 | 0.0 | 10.0 | 9.65 | 17.04 | Au1rxx-base64 | 195.123.235.177 |
| 72.41 | shadowsocks | 305.5 | 748.2 | 20.71 | 0.0 | 8.56 | 13.4 | 17.04 | Au1rxx-base64 | 37.19.198.244 |
| 72.41 | shadowsocks | 318.1 | 787.2 | 20.41 | 0.0 | 8.66 | 13.4 | 17.04 | Au1rxx-base64 | 37.19.198.243 |
| 72.29 | vless | 325.2 | 621.1 | 20.25 | 0.0 | 10.0 | 9.65 | 17.04 | Au1rxx-base64 | 15.204.97.216 |
| 72.24 | vless | 314.0 | 623.2 | 20.51 | 0.0 | 10.0 | 9.65 | 17.04 | Au1rxx-base64 | 172.233.139.46 |
| 72.11 | hysteria2 | 424.2 | 743.7 | 17.96 | 0.0 | 9.8 | 13.64 | 18.74 | mheidari-all | 62.210.124.146 |
| 71.56 | shadowsocks | 326.4 | 711.0 | 20.22 | 0.0 | 10.0 | 13.4 | 17.04 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.889 | 0.821 | 279 | 1754 | prefer |
| mheidari-all | 0.869 | 0.796 | 93 | 22479 | prefer |
| Surfboard-tg-mixed | 0.813 | 0.744 | 43 | 6952 | prefer |
| zhangkai | 0.567 | 0.611 | 18 | 144 | observe |
| DeltaKronecker-all | 0.418 | 0.5 | 10 | 5434 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4183 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7462 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9367 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5632 | observe |
| barry-far-vless | 0.255 | None | 0 | 5879 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1754 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 29 |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 12 |
| 204 | ProxyConnectionError | - | 11 |
| 204 | ProxyError | - | 11 |
| geo | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| speed | TimeoutError | - | 2 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
