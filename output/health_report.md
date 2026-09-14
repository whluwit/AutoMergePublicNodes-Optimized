# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 21:31:11 |
| 运行耗时 | 620.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 89797 |
| 去重后节点 | 25632 |
| TCP 可达 | 3000 |
| 真实可用 | 486 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25632 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.4 |
| tcp | 41.8 |
| probe | 232.1 |
| real_test | 263.8 |
| generate | 77.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55573 |
| vmess | 12999 |
| shadowsocks | 10132 |
| trojan | 8367 |
| hysteria2 | 1892 |
| http | 603 |
| shadowsocksr | 128 |
| socks | 57 |
| anytls | 22 |
| hysteria | 14 |
| tuic | 10 |

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
| 81.31 | shadowsocks | 249.5 | 611.2 | 22.0 | 0.0 | 10.0 | 13.85 | 19.46 | Au1rxx-base64 | 156.146.38.167 |
| 80.65 | shadowsocks | 243.6 | 592.2 | 22.14 | 0.0 | 10.0 | 13.85 | 19.46 | Au1rxx-base64 | 156.146.38.169 |
| 80.51 | shadowsocks | 250.9 | 616.2 | 21.97 | 0.0 | 10.0 | 13.85 | 19.46 | Au1rxx-base64 | 156.146.38.168 |
| 80.1 | hysteria2 | 252.6 | 543.9 | 21.93 | 0.0 | 9.87 | 12.75 | 19.46 | Au1rxx-base64 | 66.94.121.46 |
| 79.53 | vless | 316.2 | 756.2 | 20.46 | 0.0 | 10.0 | 12.24 | 19.46 | Au1rxx-base64 | 47.253.226.114 |
| 79.32 | vless | 323.7 | 759.2 | 20.29 | 0.0 | 10.0 | 12.24 | 19.46 | Au1rxx-base64 | 216.152.147.28 |
| 79.27 | shadowsocks | 316.0 | 572.8 | 20.46 | 0.0 | 10.0 | 13.85 | 19.46 | Au1rxx-base64 | 23.150.248.20 |
| 79.02 | shadowsocks | 295.1 | 697.9 | 20.95 | 0.0 | 10.0 | 13.85 | 19.46 | Au1rxx-base64 | 37.19.198.243 |
| 78.5 | vless | 312.3 | 676.3 | 20.55 | 0.0 | 10.0 | 12.24 | 19.46 | Au1rxx-base64 | 195.123.235.177 |
| 78.19 | vless | 416.0 | 942.9 | 18.15 | 0.0 | 10.0 | 12.24 | 19.46 | Au1rxx-base64 | 169.40.42.89 |
| 77.72 | shadowsocks | 293.6 | 683.5 | 20.98 | 0.0 | 10.0 | 13.85 | 19.46 | Au1rxx-base64 | 37.19.198.236 |
| 77.45 | vless | 304.0 | 610.4 | 20.74 | 0.0 | 10.0 | 12.24 | 19.46 | Au1rxx-base64 | 172.233.139.46 |
| 77.19 | shadowsocks | 287.9 | 672.2 | 21.11 | 0.0 | 9.83 | 13.85 | 19.46 | Au1rxx-base64 | 37.19.198.244 |
| 77.11 | vless | 332.6 | 748.2 | 20.08 | 0.0 | 9.82 | 12.24 | 19.46 | Au1rxx-base64 | 169.40.42.35 |
| 76.96 | shadowsocks | 260.3 | 639.5 | 21.75 | 0.0 | 10.0 | 13.85 | 19.46 | Au1rxx-base64 | 156.146.38.170 |
| 76.95 | vless | 342.1 | 733.3 | 19.86 | 0.0 | 9.87 | 12.24 | 19.46 | Au1rxx-base64 | 169.40.42.173 |
| 76.9 | vless | 315.8 | 593.4 | 20.47 | 0.0 | 10.0 | 12.24 | 19.46 | Au1rxx-base64 | 172.235.43.210 |
| 76.86 | vless | 312.2 | 695.2 | 20.55 | 0.0 | 10.0 | 12.24 | 19.46 | Au1rxx-base64 | 169.40.42.184 |
| 76.7 | vless | 337.3 | 586.7 | 19.97 | 0.0 | 10.0 | 12.24 | 19.46 | Au1rxx-base64 | 150.241.102.181 |
| 76.61 | vless | 374.5 | 785.4 | 19.11 | 0.0 | 9.86 | 12.24 | 19.46 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | 0.906 | 309 | 1752 | prefer |
| mheidari-all | 0.875 | 0.803 | 71 | 21195 | prefer |
| DeltaKronecker-all | 0.818 | 0.746 | 63 | 5972 | prefer |
| Surfboard-tg-mixed | 0.77 | 0.693 | 114 | 7482 | prefer |
| ermaozi | 0.644 | 0.636 | 33 | 393 | observe |
| ermaozi-get_subscribe | 0.272 | 1.0 | 1 | 427 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 135 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4914 | observe |
| Epodonios-all | 0.255 | None | 0 | 7941 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8691 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6061 | observe |
| barry-far-vless | 0.255 | None | 0 | 6284 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4099 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 15 |
| 204 | ProxyError | - | 12 |
| geo | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| speed | TimeoutError | - | 7 |
| speed | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
