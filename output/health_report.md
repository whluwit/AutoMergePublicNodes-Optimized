# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-07 19:51:38 |
| 运行耗时 | 176.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 84837 |
| 去重后节点 | 24901 |
| TCP 可达 | 3000 |
| 真实可用 | 216 |
| Verified 输出 | 216 |
| Global 输出 | 227 |
| All 输出 | 24901 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.5 |
| tcp | 32.4 |
| probe | 42.8 |
| real_test | 57.5 |
| generate | 36.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50521 |
| trojan | 13191 |
| vmess | 10624 |
| shadowsocks | 9441 |
| hysteria2 | 715 |
| http | 140 |
| shadowsocksr | 138 |
| socks | 54 |
| hysteria | 8 |
| anytls | 3 |
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
| 79.63 | shadowsocks | 218.5 | 502.7 | 22.72 | 0.0 | 10.0 | 13.27 | 17.64 | Au1rxx-base64 | 173.244.56.6 |
| 79.03 | shadowsocks | 222.8 | 542.7 | 22.62 | 0.0 | 10.0 | 13.27 | 17.64 | Au1rxx-base64 | 108.181.118.10 |
| 78.94 | shadowsocks | 226.6 | 571.0 | 22.53 | 0.0 | 10.0 | 13.27 | 17.64 | Au1rxx-base64 | 108.181.0.177 |
| 78.03 | shadowsocks | 257.2 | 630.3 | 21.82 | 0.0 | 10.0 | 13.27 | 17.64 | Au1rxx-base64 | 156.146.38.169 |
| 77.43 | shadowsocks | 227.2 | 477.5 | 22.52 | 0.0 | 10.0 | 13.27 | 17.64 | Au1rxx-base64 | 173.244.56.9 |
| 77.06 | shadowsocks | 256.6 | 626.5 | 21.84 | 0.0 | 10.0 | 13.27 | 17.64 | Au1rxx-base64 | 156.146.38.170 |
| 75.71 | shadowsocks | 270.8 | 622.1 | 21.51 | 0.0 | 10.0 | 13.27 | 17.64 | Au1rxx-base64 | 156.146.38.168 |
| 74.63 | shadowsocks | 306.5 | 766.3 | 20.68 | 0.0 | 10.0 | 13.27 | 17.78 | mheidari-all | 107.172.219.230 |
| 74.48 | trojan | 315.5 | 747.5 | 20.47 | 0.0 | 10.0 | 12.53 | 16.46 | Surfboard-tg-mixed | 149.28.241.235 |
| 73.74 | shadowsocks | 279.1 | 590.6 | 21.32 | 0.0 | 10.0 | 13.27 | 17.64 | Au1rxx-base64 | 149.22.95.183 |
| 73.58 | trojan | 305.5 | 735.8 | 20.71 | 0.0 | 10.0 | 12.53 | 13.9 | DeltaKronecker-all | 45.32.198.247 |
| 73.28 | shadowsocks | 282.8 | 291.3 | 21.23 | 4.07 | 8.41 | 13.27 | 17.64 | Au1rxx-base64 | 149.22.87.204 |
| 72.12 | trojan | 309.0 | 740.5 | 20.63 | 0.0 | 10.0 | 12.53 | 13.9 | DeltaKronecker-all | 45.32.195.168 |
| 71.55 | shadowsocks | 280.5 | 689.5 | 21.28 | 0.0 | 10.0 | 13.27 | 17.64 | Au1rxx-base64 | 156.146.38.167 |
| 71.26 | shadowsocks | 365.9 | 735.0 | 19.31 | 0.0 | 10.0 | 13.27 | 17.78 | mheidari-all | 147.90.234.133 |
| 71.1 | shadowsocks | 298.8 | 341.9 | 20.86 | 2.18 | 8.41 | 13.27 | 17.64 | Au1rxx-base64 | 149.22.87.240 |
| 70.67 | trojan | 393.5 | 905.5 | 18.67 | 0.0 | 10.0 | 12.53 | 16.46 | Surfboard-tg-mixed | 64.94.95.118 |
| 70.5 | shadowsocks | 303.8 | 354.3 | 20.75 | 1.71 | 8.41 | 13.27 | 17.64 | Au1rxx-base64 | 149.22.87.241 |
| 69.56 | trojan | 398.0 | 963.1 | 18.57 | 0.0 | 10.0 | 12.53 | 13.9 | DeltaKronecker-all | 64.94.95.115 |
| 69.53 | shadowsocks | 349.8 | 714.7 | 19.68 | 0.0 | 8.6 | 13.27 | 17.64 | Au1rxx-base64 | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.9 | 0.913 | 46 | 104 | prefer |
| mheidari-all | 0.784 | 0.71 | 69 | 18207 | prefer |
| Surfboard-tg-mixed | 0.655 | 0.576 | 85 | 6066 | observe |
| DeltaKronecker-all | 0.476 | 0.394 | 94 | 8472 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3626 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 170 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4700 | observe |
| Epodonios-all | 0.255 | None | 0 | 7120 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3980 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7035 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4596 | observe |
| barry-far-vless | 0.255 | None | 0 | 5281 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5339 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 43 |
| 204 | TimeoutError | - | 17 |
| speed | ClientOSError | - | 13 |
| 204 | ClientOSError | - | 11 |
| geo | TimeoutError | - | 11 |
| cn-block | ProxyError | - | 8 |
| cn-block | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| geo | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 216 | - |
| global | False | 300 | 227 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
