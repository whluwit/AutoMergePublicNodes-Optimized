# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-09 14:51:24 |
| 运行耗时 | 218.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79768 |
| 去重后节点 | 23975 |
| TCP 可达 | 3000 |
| 真实可用 | 345 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23975 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.3 |
| tcp | 32.1 |
| probe | 51.7 |
| real_test | 96.6 |
| generate | 32.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45627 |
| trojan | 12865 |
| vmess | 10551 |
| shadowsocks | 9462 |
| hysteria2 | 900 |
| http | 136 |
| shadowsocksr | 133 |
| socks | 77 |
| hysteria | 10 |
| anytls | 5 |
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
| 76.23 | shadowsocks | 228.7 | 629.3 | 22.48 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 37.19.198.236 |
| 76.0 | shadowsocks | 238.9 | 661.1 | 22.25 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 37.19.198.244 |
| 75.94 | shadowsocks | 241.5 | 662.9 | 22.19 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 37.19.198.160 |
| 75.32 | shadowsocks | 246.6 | 644.5 | 22.07 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 108.181.57.93 |
| 74.77 | shadowsocks | 291.8 | 819.4 | 21.02 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 37.19.198.243 |
| 74.37 | socks | 258.0 | 673.7 | 21.8 | 0.0 | 10.0 | 12.27 | 14.8 | Surfboard-tg-mixed | 134.122.1.61 |
| 73.7 | shadowsocks | 219.4 | 589.6 | 22.7 | 0.0 | 10.0 | 13.29 | 16.18 | mheidari-all | 198.98.53.130 |
| 72.5 | shadowsocks | 352.0 | 862.1 | 19.63 | 0.0 | 10.0 | 13.29 | 16.18 | mheidari-all | 185.196.61.82 |
| 72.48 | shadowsocks | 290.4 | 669.6 | 21.05 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 156.146.38.167 |
| 71.6 | shadowsocks | 334.1 | 802.7 | 20.04 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 156.146.38.168 |
| 70.77 | shadowsocks | 323.3 | 624.6 | 20.29 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 156.146.38.169 |
| 70.61 | shadowsocks | 239.5 | 641.0 | 22.23 | 0.0 | 10.0 | 13.29 | 16.18 | mheidari-all | 147.90.234.133 |
| 70.2 | vmess | 341.2 | 934.4 | 19.88 | 0.0 | 10.0 | 12.86 | 11.96 | DeltaKronecker-all | 67.220.85.46 |
| 69.97 | trojan | 328.1 | 755.2 | 20.18 | 0.0 | 10.0 | 9.18 | 16.18 | mheidari-all | 45.32.195.168 |
| 69.3 | hysteria2 | 372.0 | 709.7 | 19.17 | 0.0 | 10.0 | 12.5 | 14.46 | Au1rxx-base64 | 62.210.124.146 |
| 69.11 | shadowsocks | 233.4 | 628.6 | 22.38 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 68.62 | hysteria2 | 434.5 | 894.7 | 17.72 | 0.0 | 10.0 | 12.5 | 14.8 | Surfboard-tg-mixed | 5.255.102.165 |
| 68.54 | shadowsocks | 328.8 | 555.3 | 20.17 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 173.244.56.6 |
| 68.5 | trojan | 330.4 | 765.1 | 20.13 | 0.0 | 10.0 | 9.18 | 14.46 | Au1rxx-base64 | 149.28.241.235 |
| 67.97 | shadowsocks | 346.5 | 652.5 | 19.76 | 0.0 | 10.0 | 13.29 | 14.46 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.935 | 0.945 | 55 | 120 | prefer |
| Surfboard-tg-mixed | 0.837 | 0.761 | 109 | 5805 | prefer |
| DeltaKronecker-all | 0.781 | 0.705 | 105 | 7533 | prefer |
| mheidari-all | 0.512 | 0.431 | 225 | 16991 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 2703 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4306 | observe |
| Epodonios-all | 0.255 | None | 0 | 6648 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7014 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4318 | observe |
| barry-far-vless | 0.255 | None | 0 | 4797 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5440 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.228 | None | 0 | 1319 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 42 |
| geo | TimeoutError | - | 41 |
| speed | ClientOSError | - | 33 |
| 204 | TimeoutError | - | 17 |
| 204 | ClientOSError | - | 15 |
| cn-block | ProxyError | - | 12 |
| geo | ClientOSError | - | 10 |
| geo | ProxyError | - | 8 |
| speed | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | TimeoutError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
