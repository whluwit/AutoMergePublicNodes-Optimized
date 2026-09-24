# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 03:09:12 |
| 运行耗时 | 1119.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 96863 |
| 去重后节点 | 26603 |
| TCP 可达 | 3000 |
| 真实可用 | 575 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26603 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.5 |
| tcp | 43.4 |
| probe | 343.8 |
| real_test | 634.9 |
| generate | 90.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59126 |
| vmess | 14777 |
| shadowsocks | 11172 |
| trojan | 9248 |
| hysteria2 | 1561 |
| http | 669 |
| shadowsocksr | 170 |
| socks | 89 |
| anytls | 24 |
| hysteria | 19 |
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
| 83.66 | vless | 212.2 | 557.0 | 22.87 | 0.0 | 10.0 | 12.05 | 18.74 | mheidari-all | 172.233.139.46 |
| 81.4 | vless | 292.3 | 725.6 | 21.01 | 0.0 | 10.0 | 12.05 | 18.74 | mheidari-all | 47.251.108.158 |
| 81.24 | shadowsocks | 193.4 | 503.0 | 23.3 | 0.0 | 10.0 | 13.7 | 18.74 | mheidari-all | 192.3.247.109 |
| 80.76 | shadowsocks | 214.2 | 559.8 | 22.82 | 0.0 | 10.0 | 13.7 | 18.74 | mheidari-all | 108.181.118.10 |
| 79.53 | vless | 352.3 | 849.0 | 19.62 | 0.0 | 10.0 | 12.05 | 19.54 | Au1rxx-base64 | 5.78.159.214 |
| 79.19 | vless | 229.6 | 543.6 | 22.46 | 0.0 | 9.7 | 12.05 | 19.54 | Au1rxx-base64 | 172.235.43.210 |
| 79.07 | shadowsocks | 261.8 | 626.5 | 21.72 | 0.0 | 10.0 | 13.7 | 18.74 | mheidari-all | 156.146.38.168 |
| 77.32 | hysteria2 | 321.3 | 735.0 | 20.34 | 0.0 | 10.0 | 11.0 | 19.54 | Au1rxx-base64 | 66.94.121.46 |
| 77.19 | shadowsocks | 281.5 | 622.3 | 21.26 | 0.0 | 10.0 | 13.7 | 18.74 | mheidari-all | 23.150.248.20 |
| 76.84 | shadowsocks | 228.2 | 525.6 | 22.5 | 0.0 | 10.0 | 13.7 | 14.64 | Surfboard-tg-mixed | 173.244.56.6 |
| 76.68 | shadowsocks | 213.2 | 533.0 | 22.84 | 0.0 | 10.0 | 13.7 | 14.64 | Surfboard-tg-mixed | 108.181.0.177 |
| 76.51 | http | 201.7 | 526.9 | 23.11 | 0.0 | 10.0 | 10.54 | 15.86 | ermaozi | 138.199.35.210 |
| 76.44 | http | 204.6 | 529.9 | 23.04 | 0.0 | 10.0 | 10.54 | 15.86 | ermaozi | 138.199.35.198 |
| 76.38 | http | 207.2 | 524.7 | 22.98 | 0.0 | 10.0 | 10.54 | 15.86 | ermaozi | 138.199.35.216 |
| 75.99 | http | 202.8 | 518.8 | 23.08 | 0.0 | 10.0 | 10.54 | 15.86 | ermaozi | 138.199.35.207 |
| 75.98 | vless | 414.0 | 670.6 | 18.19 | 0.0 | 10.0 | 12.05 | 18.74 | mheidari-all | 104.16.174.164 |
| 75.64 | shadowsocks | 262.2 | 634.8 | 21.71 | 0.0 | 10.0 | 13.7 | 14.64 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.54 | shadowsocks | 263.8 | 642.7 | 21.67 | 0.0 | 10.0 | 13.7 | 14.64 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.78 | shadowsocks | 330.3 | 850.1 | 20.13 | 0.0 | 10.0 | 13.7 | 18.74 | mheidari-all | 156.146.38.170 |
| 74.67 | vless | 347.3 | 839.5 | 19.74 | 0.0 | 9.66 | 12.05 | 19.54 | Au1rxx-base64 | 31.58.50.200 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.951 | 0.888 | 258 | 1648 | prefer |
| Surfboard-tg-mixed | 0.864 | 0.789 | 95 | 7099 | prefer |
| ermaozi | 0.643 | 0.635 | 52 | 339 | observe |
| mheidari-all | 0.385 | 0.305 | 761 | 22298 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4332 | observe |
| DeltaKronecker-all | 0.3 | 0.4 | 5 | 6471 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5131 | observe |
| Epodonios-all | 0.255 | None | 0 | 7563 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8875 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5729 | observe |
| barry-far-vless | 0.255 | None | 0 | 5948 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.251 | 0.333 | 3 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1648 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 231 |
| speed | TimeoutError | - | 113 |
| geo | ClientOSError | - | 59 |
| cn-block | ClientOSError | - | 58 |
| speed | ClientOSError | - | 54 |
| 204 | ProxyError | - | 32 |
| 204 | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 21 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
