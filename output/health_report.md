# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-04 08:33:49 |
| 运行耗时 | 258.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85537 |
| 去重后节点 | 24236 |
| TCP 可达 | 3000 |
| 真实可用 | 574 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24236 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.3 |
| tcp | 36.5 |
| probe | 59.8 |
| real_test | 131.9 |
| generate | 24.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52333 |
| vmess | 12996 |
| shadowsocks | 10030 |
| trojan | 8919 |
| hysteria2 | 998 |
| http | 76 |
| shadowsocksr | 74 |
| socks | 72 |
| hysteria | 19 |
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
| 84.95 | http | 189.4 | 491.9 | 23.39 | 0.0 | 10.0 | 14.78 | 19.78 | zhangkai | 138.199.35.216 |
| 84.87 | http | 192.8 | 504.8 | 23.31 | 0.0 | 10.0 | 14.78 | 19.78 | zhangkai | 138.199.35.218 |
| 83.47 | http | 253.7 | 683.4 | 21.91 | 0.0 | 10.0 | 14.78 | 19.78 | zhangkai | 138.199.35.211 |
| 81.11 | shadowsocks | 215.5 | 522.5 | 22.79 | 0.0 | 10.0 | 14.26 | 18.06 | Au1rxx-base64 | 173.244.56.6 |
| 78.77 | shadowsocks | 294.9 | 622.8 | 20.95 | 0.0 | 10.0 | 14.26 | 18.06 | Au1rxx-base64 | 108.181.118.10 |
| 78.63 | shadowsocks | 301.2 | 638.2 | 20.81 | 0.0 | 10.0 | 14.26 | 18.06 | Au1rxx-base64 | 108.181.0.177 |
| 78.6 | vless | 177.4 | 455.0 | 23.67 | 0.0 | 10.0 | 6.87 | 18.06 | Au1rxx-base64 | 70.39.198.93 |
| 78.5 | vless | 181.6 | 496.9 | 23.57 | 0.0 | 10.0 | 6.87 | 18.06 | Au1rxx-base64 | 66.175.217.170 |
| 78.28 | vless | 191.4 | 480.6 | 23.35 | 0.0 | 10.0 | 6.87 | 18.06 | Au1rxx-base64 | 70.39.198.183 |
| 78.24 | vless | 192.8 | 495.9 | 23.31 | 0.0 | 10.0 | 6.87 | 18.06 | Au1rxx-base64 | 192.204.50.220 |
| 77.53 | shadowsocks | 228.3 | 521.1 | 22.49 | 0.0 | 10.0 | 14.26 | 18.06 | Au1rxx-base64 | 173.244.56.9 |
| 76.85 | vless | 180.5 | 467.6 | 23.6 | 0.0 | 10.0 | 6.87 | 18.06 | Au1rxx-base64 | 70.39.197.13 |
| 76.85 | vless | 253.2 | 685.9 | 21.92 | 0.0 | 10.0 | 6.87 | 18.06 | Au1rxx-base64 | 70.39.178.231 |
| 76.4 | shadowsocks | 287.9 | 649.7 | 21.11 | 0.0 | 10.0 | 14.26 | 18.06 | Au1rxx-base64 | 156.146.38.168 |
| 76.33 | shadowsocks | 290.4 | 657.8 | 21.06 | 0.0 | 10.0 | 14.26 | 18.06 | Au1rxx-base64 | 156.146.38.170 |
| 76.29 | shadowsocks | 321.0 | 754.5 | 20.35 | 0.0 | 10.0 | 14.26 | 18.06 | Au1rxx-base64 | 156.146.38.169 |
| 76.2 | hysteria2 | 341.1 | 713.4 | 19.88 | 0.0 | 10.0 | 13.5 | 18.06 | Au1rxx-base64 | 159.223.157.129 |
| 75.8 | shadowsocks | 316.4 | 732.7 | 20.45 | 0.0 | 10.0 | 14.26 | 18.06 | Au1rxx-base64 | 156.146.38.167 |
| 75.67 | vless | 246.6 | 525.6 | 22.07 | 0.0 | 10.0 | 6.87 | 18.06 | Au1rxx-base64 | 69.46.46.13 |
| 75.36 | vless | 317.6 | 758.4 | 20.43 | 0.0 | 10.0 | 6.87 | 18.06 | Au1rxx-base64 | 64.49.38.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 67 | 92 | prefer |
| Au1rxx-base64 | 0.836 | 0.77 | 600 | 1672 | prefer |
| mheidari-all | 0.465 | 0.375 | 24 | 20242 | observe |
| DeltaKronecker-all | 0.436 | 0.349 | 43 | 5788 | observe |
| Surfboard-tg-mixed | 0.336 | 0.25 | 76 | 5211 | observe |
| SoliSpirit-all | 0.335 | 1.0 | 1 | 6811 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5251 | observe |
| Epodonios-all | 0.255 | None | 0 | 5819 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4191 | observe |
| barry-far-vless | 0.255 | None | 0 | 4536 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5110 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5127 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1657 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 105 |
| speed | TimeoutError | - | 38 |
| 204 | TimeoutError | - | 22 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 12 |
| 204 | ProxyError | - | 11 |
| speed | ClientOSError | - | 11 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
