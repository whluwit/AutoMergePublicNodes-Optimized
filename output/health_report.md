# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 16:04:24 |
| 运行耗时 | 692.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 90275 |
| 去重后节点 | 25000 |
| TCP 可达 | 3000 |
| 真实可用 | 476 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25000 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.3 |
| tcp | 41.9 |
| probe | 278.8 |
| real_test | 269.0 |
| generate | 94.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56157 |
| vmess | 12334 |
| shadowsocks | 10221 |
| trojan | 8937 |
| hysteria2 | 1966 |
| http | 437 |
| shadowsocksr | 129 |
| socks | 55 |
| hysteria | 16 |
| tuic | 13 |
| anytls | 10 |

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
| 83.88 | hysteria2 | 213.1 | 543.0 | 22.85 | 0.0 | 10.0 | 13.33 | 18.7 | Au1rxx-base64 | 66.94.121.46 |
| 82.7 | vless | 214.4 | 488.1 | 22.82 | 0.0 | 10.0 | 11.18 | 18.7 | Au1rxx-base64 | 172.233.139.46 |
| 82.51 | vless | 222.4 | 483.5 | 22.63 | 0.0 | 10.0 | 11.18 | 18.7 | Au1rxx-base64 | 172.235.43.210 |
| 82.32 | vless | 230.6 | 588.8 | 22.44 | 0.0 | 10.0 | 11.18 | 18.7 | Au1rxx-base64 | 38.244.20.160 |
| 82.21 | vless | 235.3 | 551.7 | 22.33 | 0.0 | 10.0 | 11.18 | 18.7 | Au1rxx-base64 | 172.235.38.85 |
| 81.99 | http | 251.8 | 623.4 | 21.95 | 0.0 | 10.0 | 14.41 | 19.64 | ermaozi | 138.199.35.198 |
| 81.77 | vless | 254.4 | 591.1 | 21.89 | 0.0 | 10.0 | 11.18 | 18.7 | Au1rxx-base64 | 38.246.229.58 |
| 81.29 | http | 231.5 | 534.7 | 22.42 | 0.0 | 10.0 | 14.41 | 19.64 | ermaozi | 138.199.35.216 |
| 80.18 | vless | 193.6 | 504.5 | 23.3 | 0.0 | 10.0 | 11.18 | 18.7 | Au1rxx-base64 | 31.58.50.200 |
| 78.53 | http | 228.7 | 549.2 | 22.48 | 0.0 | 10.0 | 14.41 | 19.64 | ermaozi | 138.199.35.211 |
| 76.96 | shadowsocks | 199.5 | 484.3 | 23.16 | 0.0 | 10.0 | 13.2 | 15.1 | mheidari-all | 108.181.118.10 |
| 76.85 | vless | 181.9 | 494.2 | 23.57 | 0.0 | 10.0 | 11.18 | 15.1 | mheidari-all | 47.251.108.158 |
| 76.67 | vless | 280.3 | 405.2 | 21.29 | 0.0 | 10.0 | 11.18 | 18.7 | Au1rxx-base64 | 104.18.46.234 |
| 76.28 | shadowsocks | 244.0 | 590.4 | 22.13 | 0.0 | 10.0 | 13.2 | 17.04 | Surfboard-tg-mixed | 149.22.95.183 |
| 75.96 | vless | 267.8 | 438.1 | 21.58 | 0.0 | 10.0 | 11.18 | 18.7 | Au1rxx-base64 | 172.64.42.85 |
| 75.72 | shadowsocks | 274.5 | 597.9 | 21.42 | 0.0 | 10.0 | 13.2 | 15.1 | mheidari-all | 173.244.56.9 |
| 75.4 | http | 346.0 | 639.8 | 19.77 | 0.0 | 10.0 | 14.41 | 19.64 | ermaozi | 38.28.193.188 |
| 75.38 | vless | 257.5 | 618.9 | 21.82 | 0.0 | 10.0 | 11.18 | 18.7 | Au1rxx-base64 | 172.64.229.2 |
| 75.34 | http | 172.2 | 470.3 | 23.79 | 0.0 | 0.0 | 14.41 | 19.64 | ermaozi | purposebydesig.club |
| 75.12 | http | 181.6 | 485.5 | 23.57 | 0.0 | 0.0 | 14.41 | 19.64 | ermaozi | voteshirleysew.club |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | 0.932 | 279 | 1658 | prefer |
| Surfboard-tg-mixed | 0.779 | 0.701 | 144 | 7484 | prefer |
| ermaozi | 0.692 | 0.686 | 35 | 409 | observe |
| mheidari-all | 0.589 | 0.509 | 173 | 21582 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 212 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 6097 | observe |
| Epodonios-all | 0.255 | None | 0 | 7932 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8488 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6283 | observe |
| barry-far-vless | 0.255 | None | 0 | 6501 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4209 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1658 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 40 |
| cn-block | ClientOSError | - | 32 |
| 204 | ProxyError | - | 24 |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 15 |
| speed | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 6 |
| geo | TimeoutError | - | 6 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
