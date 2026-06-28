# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-28 19:16:32 |
| 运行耗时 | 263.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 76407 |
| 去重后节点 | 22880 |
| TCP 可达 | 3000 |
| 真实可用 | 470 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22880 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.4 |
| tcp | 30.9 |
| probe | 58.3 |
| real_test | 137.5 |
| generate | 30.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42925 |
| trojan | 12580 |
| vmess | 11088 |
| shadowsocks | 9238 |
| hysteria2 | 235 |
| shadowsocksr | 157 |
| http | 136 |
| socks | 40 |
| hysteria | 6 |
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
| 79.15 | vless | 304.4 | 770.4 | 20.73 | 0.0 | 10.0 | 11.2 | 17.22 | mheidari-all | 47.253.226.114 |
| 77.7 | shadowsocks | 246.1 | 607.0 | 22.08 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 156.146.38.168 |
| 77.44 | shadowsocks | 257.3 | 633.3 | 21.82 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 156.146.38.167 |
| 77.19 | shadowsocks | 268.4 | 669.6 | 21.57 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 37.19.198.244 |
| 77.13 | shadowsocks | 270.9 | 671.9 | 21.51 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 37.19.198.243 |
| 76.68 | shadowsocks | 281.1 | 680.0 | 21.27 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 76.04 | shadowsocks | 274.9 | 669.5 | 21.41 | 0.0 | 10.0 | 12.44 | 17.22 | mheidari-all | 108.181.57.93 |
| 75.63 | shadowsocks | 249.0 | 619.4 | 22.01 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 156.146.38.169 |
| 75.48 | shadowsocks | 245.6 | 602.3 | 22.09 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 156.146.38.170 |
| 74.71 | vless | 371.5 | 908.0 | 19.18 | 0.0 | 10.0 | 11.2 | 15.84 | Surfboard-tg-mixed | 15.223.121.250 |
| 74.13 | shadowsocks | 270.8 | 676.7 | 21.51 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 37.19.198.236 |
| 74.07 | shadowsocks | 381.3 | 980.9 | 18.95 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 172.234.202.34 |
| 73.5 | vless | 421.6 | 833.9 | 18.02 | 0.0 | 10.0 | 11.2 | 15.84 | Surfboard-tg-mixed | 137.184.218.169 |
| 72.22 | shadowsocks | 281.7 | 566.4 | 21.26 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 173.244.56.9 |
| 72.09 | shadowsocks | 299.8 | 618.7 | 20.84 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 149.22.95.183 |
| 72.0 | vless | 290.8 | 684.8 | 21.05 | 0.0 | 10.0 | 11.2 | 13.0 | DeltaKronecker-all | 198.41.209.87 |
| 71.96 | vless | 279.5 | 658.0 | 21.31 | 0.0 | 10.0 | 11.2 | 13.0 | DeltaKronecker-all | 162.159.252.15 |
| 71.82 | vless | 283.8 | 668.5 | 21.21 | 0.0 | 10.0 | 11.2 | 13.0 | DeltaKronecker-all | 104.19.142.226 |
| 71.59 | shadowsocks | 289.2 | 616.6 | 21.08 | 0.0 | 10.0 | 12.44 | 17.18 | Au1rxx-base64 | 108.181.0.177 |
| 71.41 | vless | 369.5 | 661.2 | 19.22 | 0.0 | 10.0 | 11.2 | 17.22 | mheidari-all | 34.213.172.16 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.828 | 0.749 | 299 | 16170 | prefer |
| Au1rxx-base64 | 0.778 | 0.789 | 38 | 78 | prefer |
| Surfboard-tg-mixed | 0.671 | 0.592 | 228 | 5075 | observe |
| DeltaKronecker-all | 0.553 | 0.473 | 91 | 6788 | observe |
| nscl5-all | 0.302 | 1.0 | 1 | 1174 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7720 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3982 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7087 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3780 | observe |
| barry-far-vless | 0.255 | None | 0 | 4558 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5325 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 75 |
| 204 | ProxyError | - | 31 |
| 204 | TimeoutError | - | 29 |
| 204 | ClientOSError | - | 23 |
| speed | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 11 |
| geo | ClientOSError | - | 9 |
| geo | TimeoutError | - | 9 |
| cn-block | TimeoutError | - | 8 |
| cn-block | ProxyError | - | 5 |
| geo | ProxyError | - | 5 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
