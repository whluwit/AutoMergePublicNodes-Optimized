# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-04 02:08:24 |
| 运行耗时 | 308.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85812 |
| 去重后节点 | 24670 |
| TCP 可达 | 3000 |
| 真实可用 | 692 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24670 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.5 |
| tcp | 37.2 |
| probe | 60.8 |
| real_test | 177.8 |
| generate | 26.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52308 |
| vmess | 12893 |
| shadowsocks | 10250 |
| trojan | 9100 |
| hysteria2 | 999 |
| socks | 76 |
| http | 76 |
| shadowsocksr | 72 |
| hysteria | 18 |
| tuic | 10 |
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
| 83.66 | http | 245.4 | 657.0 | 22.1 | 0.0 | 10.0 | 14.78 | 19.78 | zhangkai | 138.199.35.211 |
| 83.41 | http | 256.2 | 692.5 | 21.85 | 0.0 | 10.0 | 14.78 | 19.78 | zhangkai | 138.199.35.216 |
| 83.28 | http | 261.6 | 702.5 | 21.72 | 0.0 | 10.0 | 14.78 | 19.78 | zhangkai | 138.199.35.218 |
| 79.41 | vless | 170.3 | 468.9 | 23.84 | 0.0 | 10.0 | 9.23 | 16.34 | Au1rxx-base64 | 47.251.25.74 |
| 79.26 | trojan | 246.8 | 431.6 | 22.07 | 0.0 | 10.0 | 13.91 | 14.7 | Surfboard-tg-mixed | 172.67.149.60 |
| 79.21 | vless | 178.8 | 457.2 | 23.64 | 0.0 | 10.0 | 9.23 | 16.34 | Au1rxx-base64 | 70.39.198.93 |
| 78.97 | vless | 189.2 | 452.3 | 23.4 | 0.0 | 10.0 | 9.23 | 16.34 | Au1rxx-base64 | 70.39.198.183 |
| 78.47 | vless | 210.8 | 491.3 | 22.9 | 0.0 | 10.0 | 9.23 | 16.34 | Au1rxx-base64 | 70.39.197.13 |
| 78.27 | shadowsocks | 216.4 | 522.1 | 22.77 | 0.0 | 10.0 | 13.16 | 16.34 | Au1rxx-base64 | 173.244.56.9 |
| 78.27 | vless | 219.3 | 522.6 | 22.7 | 0.0 | 10.0 | 9.23 | 16.34 | Au1rxx-base64 | 192.204.50.220 |
| 78.25 | shadowsocks | 217.3 | 522.9 | 22.75 | 0.0 | 10.0 | 13.16 | 16.34 | Au1rxx-base64 | 173.244.56.6 |
| 78.24 | shadowsocks | 196.1 | 463.9 | 23.24 | 0.0 | 10.0 | 13.16 | 16.34 | Au1rxx-base64 | 108.181.0.177 |
| 78.23 | shadowsocks | 196.6 | 476.4 | 23.23 | 0.0 | 10.0 | 13.16 | 16.34 | Au1rxx-base64 | 108.181.118.10 |
| 77.82 | shadowsocks | 235.7 | 545.8 | 22.32 | 0.0 | 10.0 | 13.16 | 16.34 | Au1rxx-base64 | 149.22.95.183 |
| 77.61 | vless | 228.7 | 592.5 | 22.48 | 0.0 | 10.0 | 9.23 | 16.34 | Au1rxx-base64 | 70.39.178.231 |
| 77.31 | vless | 261.0 | 746.0 | 21.74 | 0.0 | 10.0 | 9.23 | 16.34 | Au1rxx-base64 | 66.175.217.170 |
| 76.23 | hysteria2 | 256.7 | 319.0 | 21.84 | 3.04 | 9.94 | 12.0 | 16.34 | Au1rxx-base64 | 45.76.202.45 |
| 75.14 | vless | 268.0 | 649.4 | 21.57 | 0.0 | 10.0 | 9.23 | 16.34 | Au1rxx-base64 | 69.46.46.13 |
| 73.93 | shadowsocks | 284.1 | 634.6 | 21.2 | 0.0 | 10.0 | 13.16 | 16.34 | Au1rxx-base64 | 156.146.38.169 |
| 73.77 | vless | 179.6 | 492.4 | 23.62 | 0.0 | 4.58 | 9.23 | 16.34 | Au1rxx-base64 | t18.qifei.app |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 67 | 92 | prefer |
| Au1rxx-base64 | 0.903 | 0.836 | 617 | 1692 | prefer |
| Surfboard-tg-mixed | 0.478 | 0.397 | 131 | 5262 | observe |
| DeltaKronecker-all | 0.269 | 0.171 | 35 | 6205 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| Epodonios-all | 0.255 | None | 0 | 5848 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6833 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4123 | observe |
| barry-far-vless | 0.255 | None | 0 | 4484 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5152 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5127 | observe |
| mheidari-all | 0.247 | 0.165 | 303 | 19963 | downweight |
| Au1rxx-clash | 0.243 | None | 0 | 1692 | observe |
| nscl5-all | 0.226 | None | 0 | 1267 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 242 |
| speed | TimeoutError | - | 82 |
| speed | ClientOSError | - | 58 |
| geo | ClientOSError | - | 50 |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyError | - | 5 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
