# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 15:46:12 |
| 运行耗时 | 571.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99539 |
| 去重后节点 | 27327 |
| TCP 可达 | 3000 |
| 真实可用 | 354 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27327 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.0 |
| tcp | 47.4 |
| probe | 274.6 |
| real_test | 166.0 |
| generate | 75.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60960 |
| vmess | 15424 |
| shadowsocks | 11445 |
| trojan | 9362 |
| hysteria2 | 1541 |
| http | 522 |
| shadowsocksr | 170 |
| socks | 66 |
| anytls | 24 |
| hysteria | 17 |
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
| 86.07 | hysteria2 | 208.7 | 512.4 | 22.95 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 192.255.128.123 |
| 85.66 | vless | 196.1 | 515.8 | 23.24 | 0.0 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 85.64 | vless | 196.8 | 511.7 | 23.22 | 0.0 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 85.6 | vless | 198.5 | 510.3 | 23.18 | 0.0 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 172.235.43.210 |
| 84.88 | vless | 229.6 | 571.0 | 22.46 | 0.0 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 38.246.229.58 |
| 84.8 | vless | 233.1 | 534.1 | 22.38 | 0.0 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 195.123.240.65 |
| 84.65 | vless | 239.7 | 579.8 | 22.23 | 0.0 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 15.204.97.216 |
| 84.44 | hysteria2 | 263.4 | 629.9 | 21.68 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 82.85 | http | 205.4 | 506.6 | 23.02 | 0.0 | 10.0 | 13.85 | 18.98 | ermaozi | 138.199.35.198 |
| 82.8 | http | 207.6 | 523.9 | 22.97 | 0.0 | 10.0 | 13.85 | 18.98 | ermaozi | 138.199.35.216 |
| 82.33 | vless | 173.0 | 463.1 | 23.77 | 0.0 | 10.0 | 12.42 | 16.14 | mheidari-all | 47.251.108.158 |
| 81.77 | shadowsocks | 234.6 | 535.2 | 22.35 | 0.0 | 10.0 | 13.42 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 80.72 | vless | 193.4 | 506.4 | 23.3 | 0.0 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 23.106.157.238 |
| 80.04 | vless | 240.8 | 450.9 | 22.2 | 0.0 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 172.64.42.85 |
| 79.72 | vless | 258.0 | 412.2 | 21.8 | 0.0 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 172.64.32.103 |
| 78.1 | hysteria2 | 298.7 | 359.8 | 20.86 | 1.51 | 9.38 | 14.12 | 20.0 | Au1rxx-base64 | open.2ml.bid |
| 77.97 | shadowsocks | 232.0 | 549.9 | 22.41 | 0.0 | 10.0 | 13.42 | 16.14 | mheidari-all | 173.244.56.9 |
| 77.95 | shadowsocks | 274.4 | 285.0 | 21.43 | 4.31 | 9.94 | 13.42 | 20.0 | Au1rxx-base64 | 149.22.87.240 |
| 77.85 | vless | 294.3 | 375.8 | 20.96 | 0.91 | 10.0 | 12.42 | 20.0 | Au1rxx-base64 | 104.21.70.21 |
| 77.75 | shadowsocks | 202.4 | 494.9 | 23.09 | 0.0 | 10.0 | 13.42 | 15.74 | Surfboard-tg-mixed | 108.181.118.10 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.934 | 0.872 | 39 | 7404 | prefer |
| Au1rxx-base64 | 0.906 | 0.837 | 288 | 1778 | prefer |
| mheidari-all | 0.839 | 0.765 | 81 | 23342 | prefer |
| ermaozi | 0.619 | 0.6 | 25 | 656 | observe |
| ermaozi-get_subscribe | 0.274 | 1.0 | 1 | 478 | observe |
| DeltaKronecker-all | 0.259 | 0.333 | 3 | 5207 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5192 | observe |
| Epodonios-all | 0.255 | None | 0 | 7883 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9374 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6035 | observe |
| barry-far-vless | 0.255 | None | 0 | 6273 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4335 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyConnectionError | - | 16 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 8 |
| speed | TimeoutError | - | 6 |
| geo | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
