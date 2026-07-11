# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-11 13:12:22 |
| 运行耗时 | 245.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 76309 |
| 去重后节点 | 24020 |
| TCP 可达 | 3000 |
| 真实可用 | 293 |
| Verified 输出 | 293 |
| Global 输出 | 300 |
| All 输出 | 24020 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.6 |
| tcp | 31.9 |
| probe | 45.4 |
| real_test | 118.2 |
| generate | 43.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43572 |
| trojan | 12030 |
| vmess | 10561 |
| shadowsocks | 9493 |
| hysteria2 | 281 |
| shadowsocksr | 137 |
| http | 135 |
| socks | 90 |
| hysteria | 8 |
| tuic | 1 |
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
| 75.27 | shadowsocks | 251.8 | 613.7 | 21.95 | 0.0 | 10.0 | 12.8 | 14.52 | Au1rxx-base64 | 156.146.38.170 |
| 74.86 | shadowsocks | 269.3 | 672.9 | 21.54 | 0.0 | 10.0 | 12.8 | 14.52 | Au1rxx-base64 | 37.19.198.160 |
| 74.54 | shadowsocks | 283.5 | 708.5 | 21.22 | 0.0 | 10.0 | 12.8 | 14.52 | Au1rxx-base64 | 156.146.38.168 |
| 74.29 | shadowsocks | 284.5 | 712.9 | 21.19 | 0.0 | 10.0 | 12.8 | 14.52 | Au1rxx-base64 | 156.146.38.169 |
| 73.97 | trojan | 262.0 | 612.3 | 21.71 | 0.0 | 10.0 | 11.2 | 14.06 | DeltaKronecker-all | 64.94.95.114 |
| 73.94 | shadowsocks | 309.3 | 773.2 | 20.62 | 0.0 | 10.0 | 12.8 | 14.52 | Au1rxx-base64 | 37.19.198.243 |
| 73.85 | shadowsocks | 283.9 | 682.9 | 21.21 | 0.0 | 10.0 | 12.8 | 14.6 | mheidari-all | 108.181.57.93 |
| 73.53 | vmess | 476.0 | 1270.2 | 16.76 | 0.0 | 10.0 | 13.33 | 17.94 | Surfboard-tg-mixed | 67.220.95.3 |
| 73.16 | trojan | 313.1 | 775.1 | 20.53 | 0.0 | 10.0 | 11.2 | 14.52 | Au1rxx-base64 | 149.28.241.235 |
| 72.96 | trojan | 266.8 | 629.4 | 21.6 | 0.0 | 10.0 | 11.2 | 14.06 | DeltaKronecker-all | 64.94.95.117 |
| 72.91 | shadowsocks | 335.4 | 882.5 | 20.01 | 0.0 | 10.0 | 12.8 | 14.6 | mheidari-all | 185.196.61.82 |
| 71.97 | trojan | 390.2 | 988.5 | 18.75 | 0.0 | 10.0 | 11.2 | 14.6 | mheidari-all | 45.32.195.168 |
| 71.25 | trojan | 324.0 | 556.0 | 20.28 | 0.0 | 10.0 | 11.2 | 14.06 | DeltaKronecker-all | 104.16.101.215 |
| 70.87 | trojan | 349.3 | 880.6 | 19.69 | 0.0 | 10.0 | 11.2 | 14.06 | DeltaKronecker-all | 64.94.95.115 |
| 70.81 | trojan | 366.6 | 923.2 | 19.29 | 0.0 | 10.0 | 11.2 | 14.6 | mheidari-all | 64.94.95.118 |
| 70.32 | vmess | 434.8 | 1075.9 | 17.71 | 0.0 | 10.0 | 13.33 | 14.06 | DeltaKronecker-all | 67.220.85.46 |
| 70.25 | trojan | 272.1 | 577.7 | 21.48 | 0.0 | 10.0 | 11.2 | 14.06 | DeltaKronecker-all | 104.16.98.215 |
| 70.06 | shadowsocks | 251.8 | 616.1 | 21.95 | 0.0 | 10.0 | 12.8 | 14.52 | Au1rxx-base64 | 156.146.38.167 |
| 69.94 | trojan | 397.3 | 1027.3 | 18.58 | 0.0 | 10.0 | 11.2 | 14.06 | DeltaKronecker-all | 45.32.198.247 |
| 69.71 | shadowsocks | 324.2 | 640.1 | 20.27 | 0.0 | 10.0 | 12.8 | 14.52 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.929 | 0.947 | 38 | 106 | prefer |
| Surfboard-tg-mixed | 0.823 | 0.747 | 99 | 5543 | prefer |
| mheidari-all | 0.682 | 0.605 | 81 | 16307 | observe |
| DeltaKronecker-all | 0.636 | 0.556 | 169 | 7969 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| nscl5-all | 0.303 | 1.0 | 1 | 1207 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 3953 | observe |
| Epodonios-all | 0.255 | None | 0 | 6467 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6512 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4147 | observe |
| barry-far-vless | 0.255 | None | 0 | 4696 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5423 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 26 |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyError | - | 16 |
| speed | ClientOSError | - | 15 |
| geo | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 13 |
| geo | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 7 |
| 204 | ClientOSError | - | 6 |
| geo | ProxyError | - | 6 |
| speed | ProxyError | - | 5 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 293 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
