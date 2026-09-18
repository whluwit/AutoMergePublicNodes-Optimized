# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 20:28:57 |
| 运行耗时 | 619.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 87606 |
| 去重后节点 | 25089 |
| TCP 可达 | 3000 |
| 真实可用 | 425 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25089 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.4 |
| tcp | 42.1 |
| probe | 250.8 |
| real_test | 227.5 |
| generate | 92.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52428 |
| vmess | 13860 |
| shadowsocks | 10579 |
| trojan | 8619 |
| hysteria2 | 1318 |
| http | 586 |
| shadowsocksr | 120 |
| socks | 72 |
| anytls | 11 |
| hysteria | 10 |
| tuic | 3 |

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
| 81.4 | hysteria2 | 263.9 | 590.1 | 21.67 | 0.0 | 10.0 | 14.06 | 18.52 | Au1rxx-base64 | 66.94.121.46 |
| 79.8 | hysteria2 | 300.6 | 690.2 | 20.82 | 0.0 | 10.0 | 14.06 | 18.52 | Au1rxx-base64 | 159.223.157.129 |
| 79.17 | shadowsocks | 247.9 | 607.4 | 22.04 | 0.0 | 10.0 | 12.61 | 18.52 | Au1rxx-base64 | 156.146.38.170 |
| 77.85 | vless | 207.2 | 551.9 | 22.98 | 0.0 | 10.0 | 10.21 | 14.66 | Surfboard-tg-mixed | 88.216.57.128 |
| 77.56 | vless | 292.5 | 718.0 | 21.01 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 79.141.172.154 |
| 76.78 | shadowsocks | 290.8 | 693.5 | 21.05 | 0.0 | 10.0 | 12.61 | 18.52 | Au1rxx-base64 | 37.19.198.160 |
| 75.8 | vless | 314.3 | 667.9 | 20.5 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 195.123.235.177 |
| 75.48 | vless | 333.5 | 697.2 | 20.06 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 169.40.42.75 |
| 75.35 | shadowsocks | 246.1 | 604.2 | 22.08 | 0.0 | 10.0 | 12.61 | 14.66 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.94 | shadowsocks | 261.1 | 639.6 | 21.73 | 0.0 | 10.0 | 12.61 | 14.66 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.87 | vless | 310.2 | 626.6 | 20.6 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 172.235.43.210 |
| 74.84 | shadowsocks | 262.1 | 642.3 | 21.71 | 0.0 | 10.0 | 12.61 | 14.52 | mheidari-all | 156.146.38.168 |
| 74.72 | hysteria2 | 252.7 | 591.2 | 21.93 | 0.0 | 10.0 | 14.06 | 18.52 | Au1rxx-base64 | 108.59.244.158 |
| 74.39 | vless | 354.3 | 810.2 | 19.58 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 169.40.42.212 |
| 74.38 | vless | 389.4 | 889.6 | 18.76 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 66.70.179.198 |
| 74.35 | vless | 385.8 | 777.7 | 18.85 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 169.40.42.74 |
| 74.2 | hysteria2 | 270.0 | 541.8 | 21.53 | 0.0 | 10.0 | 14.06 | 14.52 | mheidari-all | 45.149.172.80 |
| 73.98 | vless | 386.7 | 783.3 | 18.83 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 169.40.42.224 |
| 73.92 | vless | 457.3 | 923.7 | 17.19 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 169.40.42.52 |
| 73.73 | vless | 421.0 | 913.8 | 18.03 | 0.0 | 10.0 | 10.21 | 18.52 | Au1rxx-base64 | 169.40.42.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.925 | 0.863 | 277 | 1615 | prefer |
| ermaozi | 0.828 | 0.84 | 25 | 325 | prefer |
| Surfboard-tg-mixed | 0.755 | 0.677 | 158 | 7333 | prefer |
| mheidari-all | 0.613 | 0.534 | 103 | 19747 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5076 | observe |
| Epodonios-all | 0.255 | None | 0 | 7771 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8922 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5838 | observe |
| barry-far-vless | 0.255 | None | 0 | 6051 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1615 | observe |
| DeltaKronecker-all | 0.226 | 0.2 | 5 | 6040 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 39 |
| cn-block | ClientOSError | - | 26 |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 16 |
| 204 | ProxyError | - | 15 |
| geo | TimeoutError | - | 14 |
| speed | ClientOSError | - | 12 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
