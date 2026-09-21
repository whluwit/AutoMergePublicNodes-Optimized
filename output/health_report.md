# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 03:13:11 |
| 运行耗时 | 814.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83863 |
| 去重后节点 | 23662 |
| TCP 可达 | 3000 |
| 真实可用 | 695 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23662 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.3 |
| tcp | 39.9 |
| probe | 272.5 |
| real_test | 417.4 |
| generate | 79.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50224 |
| vmess | 13530 |
| shadowsocks | 9787 |
| trojan | 8349 |
| hysteria2 | 1112 |
| http | 646 |
| shadowsocksr | 130 |
| socks | 67 |
| hysteria | 9 |
| anytls | 5 |
| tuic | 4 |

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
| 81.3 | vless | 281.4 | 704.3 | 21.26 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 79.141.172.154 |
| 81.17 | hysteria2 | 294.4 | 693.2 | 20.96 | 0.0 | 10.0 | 14.0 | 17.6 | mheidari-all | 159.223.157.129 |
| 80.69 | hysteria2 | 335.0 | 799.5 | 20.02 | 0.0 | 10.0 | 14.0 | 19.46 | Au1rxx-base64 | 66.94.121.46 |
| 80.14 | vless | 331.6 | 776.1 | 20.1 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 216.152.147.28 |
| 79.69 | shadowsocks | 309.9 | 789.9 | 20.61 | 0.0 | 10.0 | 13.62 | 19.46 | Au1rxx-base64 | 156.146.38.168 |
| 79.29 | shadowsocks | 305.4 | 729.3 | 20.71 | 0.0 | 10.0 | 13.62 | 19.46 | Au1rxx-base64 | 23.150.248.20 |
| 79.2 | shadowsocks | 250.4 | 635.7 | 21.98 | 0.0 | 10.0 | 13.62 | 17.6 | mheidari-all | 156.146.38.170 |
| 79.14 | vless | 317.7 | 772.8 | 20.42 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 47.253.226.114 |
| 77.75 | vless | 317.6 | 733.8 | 20.43 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 169.40.42.225 |
| 76.16 | vless | 374.0 | 760.8 | 19.12 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 169.40.42.163 |
| 76.09 | vless | 377.1 | 903.6 | 19.05 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 137.184.218.169 |
| 75.95 | vless | 258.6 | 664.7 | 21.79 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 195.211.98.43 |
| 75.88 | shadowsocks | 347.6 | 880.7 | 19.73 | 0.0 | 10.0 | 13.62 | 17.6 | mheidari-all | 37.19.198.244 |
| 75.86 | vless | 297.1 | 598.6 | 20.9 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 172.235.43.210 |
| 75.55 | vless | 335.8 | 682.8 | 20.0 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 169.40.42.35 |
| 75.5 | shadowsocks | 246.9 | 647.9 | 22.06 | 0.0 | 10.0 | 13.62 | 13.82 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.46 | vless | 325.5 | 682.9 | 20.24 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 169.40.42.232 |
| 75.17 | vless | 341.5 | 766.9 | 19.87 | 0.0 | 10.0 | 10.58 | 19.46 | Au1rxx-base64 | 169.40.42.16 |
| 75.16 | shadowsocks | 300.7 | 725.2 | 20.82 | 0.0 | 10.0 | 13.62 | 17.6 | mheidari-all | 37.19.198.236 |
| 75.02 | shadowsocks | 350.9 | 866.2 | 19.65 | 0.0 | 10.0 | 13.62 | 19.46 | Au1rxx-base64 | 142.4.216.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | 0.918 | 353 | 1668 | prefer |
| Surfboard-tg-mixed | 0.773 | 0.697 | 99 | 7202 | prefer |
| ermaozi | 0.688 | 0.682 | 44 | 355 | observe |
| DeltaKronecker-all | 0.558 | 0.478 | 452 | 6092 | observe |
| mheidari-all | 0.555 | 0.475 | 99 | 15960 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4315 | observe |
| tg-oneclickvpnkeys | 0.314 | 1.0 | 2 | 74 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| Epodonios-all | 0.255 | None | 0 | 7661 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8824 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5800 | observe |
| barry-far-vless | 0.255 | None | 0 | 6015 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1668 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 158 |
| geo | ClientOSError | - | 64 |
| speed | ClientOSError | - | 47 |
| speed | TimeoutError | - | 47 |
| 204 | ProxyError | - | 22 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
