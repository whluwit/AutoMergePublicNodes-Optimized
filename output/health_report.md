# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-08 13:55:10 |
| 运行耗时 | 187.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83182 |
| 去重后节点 | 24779 |
| TCP 可达 | 3000 |
| 真实可用 | 229 |
| Verified 输出 | 229 |
| Global 输出 | 242 |
| All 输出 | 24779 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.3 |
| tcp | 31.6 |
| probe | 42.6 |
| real_test | 77.8 |
| generate | 29.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48482 |
| trojan | 13471 |
| vmess | 10529 |
| shadowsocks | 9533 |
| hysteria2 | 827 |
| shadowsocksr | 147 |
| http | 140 |
| socks | 39 |
| hysteria | 8 |
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
| 76.7 | shadowsocks | 253.2 | 691.7 | 21.92 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 37.19.198.244 |
| 76.69 | shadowsocks | 253.3 | 690.6 | 21.91 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 37.19.198.160 |
| 76.68 | shadowsocks | 254.0 | 693.9 | 21.9 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 37.19.198.236 |
| 76.59 | shadowsocks | 257.6 | 702.9 | 21.81 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 37.19.198.243 |
| 76.02 | shadowsocks | 260.9 | 689.0 | 21.74 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 108.181.57.93 |
| 73.95 | shadowsocks | 248.6 | 664.7 | 22.02 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 198.98.53.130 |
| 73.74 | shadowsocks | 285.6 | 648.1 | 21.17 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 156.146.38.168 |
| 73.62 | trojan | 334.8 | 776.3 | 20.03 | 0.0 | 10.0 | 12.31 | 16.52 | DeltaKronecker-all | 45.32.198.247 |
| 73.56 | shadowsocks | 282.4 | 653.9 | 21.24 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 156.146.38.169 |
| 73.4 | shadowsocks | 278.4 | 643.0 | 21.33 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 156.146.38.170 |
| 72.87 | shadowsocks | 339.0 | 834.9 | 19.93 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 185.196.61.82 |
| 71.93 | shadowsocks | 278.9 | 637.1 | 21.32 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 156.146.38.167 |
| 69.07 | trojan | 315.8 | 707.1 | 20.47 | 0.0 | 10.0 | 12.31 | 16.52 | DeltaKronecker-all | 64.94.95.115 |
| 68.28 | shadowsocks | 321.2 | 586.3 | 20.34 | 0.0 | 8.61 | 12.26 | 16.52 | Au1rxx-base64 | 173.244.56.6 |
| 67.76 | vless | 335.2 | 713.0 | 20.02 | 0.0 | 10.0 | 6.14 | 16.52 | DeltaKronecker-all | 20.84.155.134 |
| 67.57 | shadowsocks | 316.8 | 880.3 | 20.44 | 0.0 | 10.0 | 12.26 | 16.52 | Au1rxx-base64 | 147.90.234.133 |
| 67.43 | shadowsocks | 328.3 | 599.0 | 20.18 | 0.0 | 8.77 | 12.26 | 16.52 | Au1rxx-base64 | 108.181.0.177 |
| 67.37 | trojan | 378.5 | 873.9 | 19.02 | 0.0 | 10.0 | 12.31 | 16.52 | DeltaKronecker-all | 64.94.95.117 |
| 67.23 | trojan | 380.7 | 860.5 | 18.97 | 0.0 | 10.0 | 12.31 | 16.52 | DeltaKronecker-all | 64.94.95.114 |
| 67.04 | shadowsocks | 364.6 | 725.9 | 19.34 | 0.0 | 8.58 | 12.26 | 16.52 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.827 | 0.833 | 60 | 116 | prefer |
| DeltaKronecker-all | 0.582 | 0.502 | 257 | 8321 | observe |
| Surfboard-tg-mixed | 0.482 | 0.5 | 14 | 5948 | observe |
| xiaoji235-airport-v2ray-all | 0.4 | 0.75 | 4 | 3640 | observe |
| mheidari-all | 0.337 | 0.308 | 13 | 17790 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4408 | observe |
| Epodonios-all | 0.255 | None | 0 | 6852 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6934 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4400 | observe |
| barry-far-vless | 0.255 | None | 0 | 4939 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5352 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.237 | None | 0 | 1561 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 65 |
| geo | TimeoutError | - | 26 |
| 204 | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| geo | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 229 | - |
| global | False | 300 | 242 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
