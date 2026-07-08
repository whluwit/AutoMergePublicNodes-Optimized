# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-08 02:17:54 |
| 运行耗时 | 276.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 84060 |
| 去重后节点 | 24941 |
| TCP 可达 | 3000 |
| 真实可用 | 525 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24941 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.3 |
| tcp | 32.3 |
| probe | 53.9 |
| real_test | 138.6 |
| generate | 45.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49786 |
| trojan | 13135 |
| vmess | 10519 |
| shadowsocks | 9441 |
| hysteria2 | 832 |
| shadowsocksr | 151 |
| http | 140 |
| socks | 42 |
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
| 77.63 | shadowsocks | 197.9 | 471.0 | 23.2 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 108.181.118.10 |
| 77.35 | shadowsocks | 209.7 | 486.3 | 22.92 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 108.181.0.177 |
| 77.22 | shadowsocks | 237.2 | 569.6 | 22.29 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 149.22.95.183 |
| 76.3 | shadowsocks | 227.7 | 493.3 | 22.51 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 173.244.56.9 |
| 75.54 | shadowsocks | 228.6 | 501.4 | 22.48 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 173.244.56.6 |
| 75.46 | shadowsocks | 183.3 | 487.4 | 23.53 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 216.105.168.18 |
| 73.11 | shadowsocks | 286.8 | 642.9 | 21.14 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 156.146.38.168 |
| 72.58 | shadowsocks | 288.5 | 651.8 | 21.1 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 156.146.38.170 |
| 72.15 | shadowsocks | 291.7 | 654.4 | 21.03 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 156.146.38.169 |
| 71.55 | vless | 230.6 | 573.3 | 22.44 | 0.0 | 10.0 | 1.11 | 18.0 | Au1rxx-base64 | 15.204.97.214 |
| 70.86 | shadowsocks | 295.1 | 340.6 | 20.95 | 2.23 | 9.93 | 10.93 | 18.0 | Au1rxx-base64 | 149.22.87.240 |
| 70.59 | shadowsocks | 297.7 | 346.0 | 20.89 | 2.02 | 9.94 | 10.93 | 18.0 | Au1rxx-base64 | 149.22.87.204 |
| 70.24 | shadowsocks | 301.3 | 354.3 | 20.8 | 1.71 | 9.94 | 10.93 | 18.0 | Au1rxx-base64 | 149.22.87.241 |
| 68.89 | trojan | 291.2 | 740.8 | 21.04 | 0.0 | 10.0 | 10.09 | 13.1 | Surfboard-tg-mixed | 140.248.185.252 |
| 68.79 | shadowsocks | 331.2 | 769.0 | 20.11 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 156.146.38.167 |
| 68.76 | trojan | 353.2 | 788.8 | 19.6 | 0.0 | 10.0 | 10.09 | 15.68 | mheidari-all | 149.28.241.235 |
| 68.36 | shadowsocks | 370.1 | 742.4 | 19.21 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 37.19.198.243 |
| 68.22 | shadowsocks | 370.3 | 744.8 | 19.21 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 37.19.198.236 |
| 68.07 | shadowsocks | 378.5 | 771.5 | 19.02 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 37.19.198.244 |
| 67.9 | shadowsocks | 386.8 | 788.5 | 18.82 | 0.0 | 10.0 | 10.93 | 18.0 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.961 | 0.888 | 107 | 5874 | prefer |
| Au1rxx-base64 | 0.719 | 0.72 | 75 | 125 | prefer |
| DeltaKronecker-all | 0.644 | 0.565 | 147 | 8472 | observe |
| mheidari-all | 0.553 | 0.473 | 533 | 18232 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3640 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 170 | observe |
| nscl5-all | 0.317 | 1.0 | 1 | 1561 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4700 | observe |
| Epodonios-all | 0.255 | None | 0 | 6908 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3969 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6912 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4417 | observe |
| barry-far-vless | 0.255 | None | 0 | 5099 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5339 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 174 |
| speed | ClientOSError | - | 99 |
| geo | ClientOSError | - | 37 |
| speed | TimeoutError | - | 30 |
| 204 | TimeoutError | - | 11 |
| cn-block | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 8 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 216 | 300 | - |
| global | False | 227 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
