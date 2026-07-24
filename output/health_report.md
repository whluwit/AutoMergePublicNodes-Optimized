# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-24 02:17:34 |
| 运行耗时 | 331.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83447 |
| 去重后节点 | 23086 |
| TCP 可达 | 3000 |
| 真实可用 | 822 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23086 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.3 |
| tcp | 32.8 |
| probe | 68.1 |
| real_test | 191.9 |
| generate | 32.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47039 |
| trojan | 15498 |
| shadowsocks | 10163 |
| vmess | 10139 |
| hysteria2 | 402 |
| shadowsocksr | 75 |
| socks | 60 |
| http | 50 |
| hysteria | 15 |
| tuic | 4 |
| anytls | 2 |

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
| 75.48 | trojan | 370.5 | 698.2 | 19.2 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 91.107.145.13 |
| 74.96 | vless | 262.7 | 615.4 | 21.7 | 0.0 | 10.0 | 4.4 | 19.38 | mheidari-all | 154.193.55.183 |
| 74.19 | vmess | 365.7 | 1033.1 | 19.31 | 0.0 | 10.0 | 10.0 | 19.38 | mheidari-all | 67.220.95.3 |
| 73.15 | trojan | 301.9 | 650.1 | 20.79 | 0.0 | 10.0 | 13.75 | 15.6 | Surfboard-tg-mixed | 163.245.196.68 |
| 72.66 | trojan | 444.4 | 781.2 | 17.49 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 104.16.174.6 |
| 72.61 | trojan | 447.0 | 786.8 | 17.43 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 104.18.152.219 |
| 72.59 | trojan | 449.8 | 794.6 | 17.37 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 104.26.14.137 |
| 72.56 | trojan | 445.2 | 784.9 | 17.47 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 104.18.152.208 |
| 72.48 | trojan | 448.7 | 800.0 | 17.39 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 104.16.174.22 |
| 72.46 | trojan | 448.9 | 797.1 | 17.39 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 104.18.152.210 |
| 72.39 | trojan | 457.0 | 805.4 | 17.2 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 212.183.88.136 |
| 72.2 | trojan | 459.1 | 789.8 | 17.15 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 185.18.250.245 |
| 72.13 | trojan | 462.6 | 789.8 | 17.07 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 45.130.125.160 |
| 72.1 | vless | 295.7 | 682.5 | 20.93 | 0.0 | 10.0 | 4.4 | 19.38 | mheidari-all | 45.206.5.122 |
| 71.96 | trojan | 448.8 | 791.9 | 17.39 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 104.18.152.97 |
| 71.92 | trojan | 472.4 | 811.8 | 16.84 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 45.130.125.76 |
| 71.71 | trojan | 453.3 | 775.1 | 17.28 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 104.16.174.121 |
| 71.57 | trojan | 476.4 | 837.9 | 16.75 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 172.64.147.166 |
| 71.56 | trojan | 411.3 | 777.4 | 18.26 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 108.130.91.15 |
| 71.48 | trojan | 435.0 | 754.6 | 17.71 | 0.0 | 10.0 | 13.75 | 19.38 | mheidari-all | 3.78.254.140 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.97 | 0.897 | 107 | 5362 | prefer |
| DeltaKronecker-all | 0.773 | 0.695 | 174 | 5572 | prefer |
| mheidari-all | 0.663 | 0.584 | 958 | 20024 | observe |
| Au1rxx-base64 | 0.531 | 1.0 | 7 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3843 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4757 | observe |
| Epodonios-all | 0.255 | None | 0 | 6509 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6779 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4119 | observe |
| barry-far-vless | 0.255 | None | 0 | 4750 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4971 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 198 |
| speed | ClientOSError | - | 96 |
| speed | TimeoutError | - | 52 |
| geo | ClientOSError | - | 46 |
| cn-block | TimeoutError | - | 43 |
| 204 | ProxyError | - | 12 |
| geo | ProxyError | - | 5 |
| 204 | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
