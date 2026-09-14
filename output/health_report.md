# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 17:39:47 |
| 运行耗时 | 559.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84471 |
| 去重后节点 | 22923 |
| TCP 可达 | 3000 |
| 真实可用 | 404 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22923 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.5 |
| tcp | 37.1 |
| probe | 239.6 |
| real_test | 196.8 |
| generate | 77.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51467 |
| vmess | 12995 |
| shadowsocks | 9692 |
| trojan | 7973 |
| hysteria2 | 1530 |
| http | 593 |
| shadowsocksr | 127 |
| socks | 55 |
| anytls | 16 |
| tuic | 12 |
| hysteria | 11 |

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
| 83.05 | hysteria2 | 264.4 | 745.8 | 21.66 | 0.0 | 10.0 | 13.75 | 18.64 | Au1rxx-base64 | 107.175.219.48 |
| 82.12 | vless | 200.7 | 515.9 | 23.13 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 172.235.43.210 |
| 81.85 | vless | 212.6 | 526.3 | 22.86 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 45.149.172.80 |
| 81.42 | shadowsocks | 228.1 | 532.5 | 22.5 | 0.0 | 10.0 | 14.28 | 18.64 | Au1rxx-base64 | 173.244.56.9 |
| 81.03 | shadowsocks | 244.7 | 574.9 | 22.11 | 0.0 | 10.0 | 14.28 | 18.64 | Au1rxx-base64 | 149.22.95.183 |
| 81.01 | shadowsocks | 245.9 | 547.7 | 22.09 | 0.0 | 10.0 | 14.28 | 18.64 | Au1rxx-base64 | 173.244.56.6 |
| 80.36 | shadowsocks | 252.4 | 695.6 | 21.94 | 0.0 | 10.0 | 14.28 | 18.64 | Au1rxx-base64 | 192.3.247.109 |
| 79.25 | shadowsocks | 213.9 | 533.6 | 22.83 | 0.0 | 10.0 | 14.28 | 16.64 | Surfboard-tg-mixed | 5.78.51.123 |
| 79.23 | shadowsocks | 205.2 | 463.0 | 23.03 | 0.0 | 10.0 | 14.28 | 16.42 | mheidari-all | 108.181.0.177 |
| 77.85 | vless | 255.4 | 649.1 | 21.86 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 45.149.172.74 |
| 77.7 | shadowsocks | 199.7 | 476.7 | 23.15 | 0.0 | 10.0 | 14.28 | 18.64 | Au1rxx-base64 | 108.181.118.10 |
| 77.68 | vless | 176.4 | 479.6 | 23.69 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 198.200.42.129 |
| 77.65 | vless | 321.3 | 844.6 | 20.34 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 15.204.97.216 |
| 77.15 | vless | 199.7 | 518.3 | 23.16 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 192.3.247.109 |
| 76.8 | vless | 236.4 | 496.8 | 22.31 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 162.159.45.19 |
| 76.77 | shadowsocks | 295.0 | 661.7 | 20.95 | 0.0 | 10.0 | 14.28 | 18.64 | Au1rxx-base64 | 156.146.38.167 |
| 76.74 | vless | 217.2 | 522.7 | 22.75 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 38.244.20.41 |
| 76.69 | hysteria2 | 356.9 | 735.2 | 19.52 | 0.0 | 10.0 | 13.75 | 18.64 | Au1rxx-base64 | 159.223.157.129 |
| 76.6 | vless | 274.9 | 537.8 | 21.41 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 144.172.104.26 |
| 76.44 | vless | 213.7 | 518.9 | 22.83 | 0.0 | 10.0 | 10.35 | 18.64 | Au1rxx-base64 | 38.244.20.149 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.973 | 0.911 | 282 | 1619 | prefer |
| DeltaKronecker-all | 0.913 | 0.864 | 22 | 5972 | prefer |
| Surfboard-tg-mixed | 0.811 | 0.736 | 91 | 7478 | prefer |
| mheidari-all | 0.807 | 0.738 | 42 | 15899 | prefer |
| ermaozi | 0.69 | 0.683 | 41 | 393 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 145 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4914 | observe |
| Epodonios-all | 0.255 | None | 0 | 7933 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8881 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6074 | observe |
| barry-far-vless | 0.255 | None | 0 | 6293 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4176 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1619 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 21 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 13 |
| geo | ClientOSError | - | 12 |
| speed | ClientOSError | - | 7 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 4 |
| geo | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
