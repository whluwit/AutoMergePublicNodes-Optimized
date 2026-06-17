# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-17 17:33:50 |
| 运行耗时 | 124.2s |
| 订阅源总数 | 44 |
| 健康订阅源 | 44 |
| 原始节点 | 43725 |
| 去重后节点 | 18176 |
| TCP 可达 | 1500 |
| 真实可用 | 110 |
| Verified 输出 | 110 |
| Global 输出 | 111 |
| All 输出 | 18176 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.7 |
| geo | 1.2 |
| tcp | 19.7 |
| probe | 27.1 |
| real_test | 51.7 |
| generate | 20.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 22388 |
| shadowsocks | 8311 |
| trojan | 7058 |
| vmess | 5556 |
| hysteria2 | 185 |
| http | 95 |
| shadowsocksr | 87 |
| socks | 38 |
| hysteria | 6 |
| tuic | 1 |

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
| 67.27 | trojan | 329.3 | 663.3 | 20.16 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 207.126.167.150 |
| 65.32 | trojan | 409.6 | 962.5 | 18.3 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 45.61.52.243 |
| 62.41 | trojan | 419.3 | 968.1 | 18.07 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 45.61.58.89 |
| 59.51 | vmess | 255.2 | 647.9 | 21.87 | 0.0 | 10.0 | 12.86 | 4.28 | Barabama-yudou | 82.198.246.233 |
| 54.28 | trojan | 656.2 | 925.1 | 12.59 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 104.16.122.175 |
| 53.96 | trojan | 669.0 | 917.4 | 12.29 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 104.25.109.237 |
| 53.92 | trojan | 667.1 | 925.6 | 12.34 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 104.17.121.43 |
| 53.86 | trojan | 668.9 | 898.6 | 12.29 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 162.159.253.41 |
| 53.71 | trojan | 676.9 | 980.1 | 12.11 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 104.18.8.83 |
| 53.45 | trojan | 678.4 | 945.8 | 12.07 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 45.130.125.76 |
| 53.24 | trojan | 696.4 | 916.6 | 11.66 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 45.130.125.75 |
| 53.21 | trojan | 696.8 | 1004.1 | 11.65 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 185.18.250.245 |
| 53.16 | trojan | 701.9 | 934.4 | 11.53 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 104.17.121.9 |
| 51.49 | vmess | 730.4 | 1122.6 | 10.87 | 0.0 | 9.43 | 12.86 | 14.64 | DeltaKronecker-all | 141.95.65.9 |
| 50.63 | vmess | 766.0 | 1181.8 | 10.05 | 0.0 | 9.44 | 12.86 | 14.64 | DeltaKronecker-all | 159.223.13.109 |
| 49.99 | trojan | 829.3 | 982.2 | 8.58 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 104.19.208.184 |
| 49.84 | vmess | 794.7 | 1286.8 | 9.38 | 0.0 | 9.37 | 12.86 | 14.64 | DeltaKronecker-all | 51.89.41.22 |
| 49.82 | trojan | 824.7 | 1102.1 | 8.69 | 0.0 | 10.0 | 11.79 | 14.64 | DeltaKronecker-all | 202.37.33.80 |
| 49.47 | vmess | 747.4 | 1165.6 | 10.48 | 0.0 | 9.36 | 12.86 | 14.64 | DeltaKronecker-all | 45.90.106.24 |
| 49.12 | http | 890.7 | 1091.5 | 7.16 | 0.0 | 8.99 | 14.06 | 15.82 | snakem982 | 84.239.49.173 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.87 | 0.893 | 28 | 73 | prefer |
| DeltaKronecker-all | 0.624 | 0.544 | 147 | 7763 | observe |
| Surfboard-tg-mixed | 0.4 | 0.75 | 4 | 4729 | observe |
| nscl5-all | 0.294 | 1.0 | 1 | 967 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 2000 | observe |
| Epodonios-all | 0.255 | None | 0 | 3000 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3000 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 3000 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3741 | observe |
| barry-far-vless | 0.255 | None | 0 | 2000 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4541 | observe |
| mheidari-all | 0.255 | None | 0 | 2000 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| Barabama-yudou | 0.214 | 0.5 | 2 | 166 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 25 |
| 204 | ProxyError | - | 17 |
| 204 | TimeoutError | - | 8 |
| cn-block | ProxyError | - | 6 |
| speed | ProxyError | - | 5 |
| geo | status | 429 | 4 |
| cn-block | TimeoutError | - | 2 |
| geo | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | status | 403 | 1 |
| speed | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 78 | 110 | - |
| global | False | 81 | 111 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
