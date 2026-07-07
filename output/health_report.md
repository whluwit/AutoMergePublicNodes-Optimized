# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-07 09:36:44 |
| 运行耗时 | 175.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 84946 |
| 去重后节点 | 24814 |
| TCP 可达 | 3000 |
| 真实可用 | 344 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24814 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.3 |
| tcp | 31.8 |
| probe | 46.9 |
| real_test | 72.8 |
| generate | 18.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50778 |
| trojan | 13033 |
| vmess | 10576 |
| shadowsocks | 9508 |
| hysteria2 | 701 |
| shadowsocksr | 140 |
| http | 140 |
| socks | 54 |
| hysteria | 8 |
| tuic | 4 |
| anytls | 4 |

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
| 79.55 | shadowsocks | 198.1 | 476.8 | 23.19 | 0.0 | 10.0 | 14.06 | 16.8 | Au1rxx-base64 | 108.181.0.177 |
| 79.54 | shadowsocks | 198.7 | 483.5 | 23.18 | 0.0 | 10.0 | 14.06 | 16.8 | Au1rxx-base64 | 108.181.118.10 |
| 79.47 | shadowsocks | 223.3 | 524.3 | 22.61 | 0.0 | 10.0 | 14.06 | 16.8 | Au1rxx-base64 | 149.22.95.183 |
| 79.44 | shadowsocks | 224.4 | 504.2 | 22.58 | 0.0 | 10.0 | 14.06 | 16.8 | Au1rxx-base64 | 173.244.56.6 |
| 77.16 | trojan | 268.5 | 425.9 | 21.56 | 0.0 | 10.0 | 14.14 | 14.46 | Surfboard-tg-mixed | 89.116.250.135 |
| 76.66 | shadowsocks | 308.0 | 759.4 | 20.65 | 0.0 | 10.0 | 14.06 | 16.8 | Au1rxx-base64 | 172.245.235.84 |
| 75.99 | vless | 229.9 | 572.1 | 22.46 | 0.0 | 10.0 | 6.73 | 16.8 | Au1rxx-base64 | 15.204.97.214 |
| 75.03 | shadowsocks | 271.4 | 273.3 | 21.49 | 4.75 | 9.1 | 14.06 | 16.8 | Au1rxx-base64 | 149.22.87.241 |
| 74.23 | shadowsocks | 233.7 | 489.7 | 22.37 | 0.0 | 10.0 | 14.06 | 16.8 | Au1rxx-base64 | 173.244.56.9 |
| 74.05 | shadowsocks | 292.4 | 657.9 | 21.01 | 0.0 | 9.17 | 14.06 | 16.8 | Au1rxx-base64 | 156.146.38.168 |
| 73.24 | shadowsocks | 284.8 | 639.5 | 21.18 | 0.0 | 9.16 | 14.06 | 16.8 | Au1rxx-base64 | 156.146.38.169 |
| 72.49 | trojan | 305.9 | 633.7 | 20.7 | 0.0 | 10.0 | 14.14 | 14.46 | Surfboard-tg-mixed | 64.94.95.118 |
| 72.3 | shadowsocks | 363.8 | 872.5 | 19.36 | 0.0 | 9.18 | 14.06 | 16.8 | Au1rxx-base64 | 156.146.38.170 |
| 71.97 | shadowsocks | 293.7 | 341.4 | 20.98 | 2.2 | 9.1 | 14.06 | 16.8 | Au1rxx-base64 | 149.22.87.204 |
| 71.73 | shadowsocks | 295.7 | 346.1 | 20.93 | 2.02 | 9.1 | 14.06 | 16.8 | Au1rxx-base64 | 149.22.87.240 |
| 70.67 | trojan | 343.3 | 767.5 | 19.83 | 0.0 | 10.0 | 14.14 | 12.62 | mheidari-all | 149.28.241.235 |
| 70.62 | trojan | 346.8 | 782.2 | 19.75 | 0.0 | 10.0 | 14.14 | 12.92 | DeltaKronecker-all | 45.32.195.168 |
| 70.61 | trojan | 360.4 | 824.6 | 19.43 | 0.0 | 10.0 | 14.14 | 12.92 | DeltaKronecker-all | 45.32.198.247 |
| 69.26 | shadowsocks | 376.7 | 756.7 | 19.06 | 0.0 | 9.09 | 14.06 | 16.8 | Au1rxx-base64 | 37.19.198.236 |
| 68.91 | shadowsocks | 384.7 | 785.7 | 18.87 | 0.0 | 9.09 | 14.06 | 16.8 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.904 | 0.83 | 106 | 6102 | prefer |
| DeltaKronecker-all | 0.867 | 0.792 | 125 | 8472 | prefer |
| mheidari-all | 0.822 | 0.747 | 95 | 18158 | prefer |
| Au1rxx-base64 | 0.751 | 0.754 | 61 | 118 | prefer |
| xiaoji235-airport-v2ray-all | 0.4 | 0.75 | 4 | 3626 | observe |
| nscl5-all | 0.314 | 1.0 | 1 | 1478 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4700 | observe |
| Epodonios-all | 0.255 | None | 0 | 7013 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7353 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4575 | observe |
| barry-far-vless | 0.255 | None | 0 | 5256 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5338 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 26 |
| speed | ClientOSError | - | 23 |
| 204 | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 6 |
| geo | ClientOSError | - | 5 |
| 204 | ProxyError | - | 5 |
| speed | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
