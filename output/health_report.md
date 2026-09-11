# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 20:30:11 |
| 运行耗时 | 523.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83905 |
| 去重后节点 | 23383 |
| TCP 可达 | 3000 |
| 真实可用 | 391 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23383 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 40.2 |
| probe | 191.7 |
| real_test | 210.8 |
| generate | 72.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51134 |
| vmess | 12557 |
| shadowsocks | 9803 |
| trojan | 8009 |
| hysteria2 | 1602 |
| http | 599 |
| shadowsocksr | 125 |
| socks | 53 |
| tuic | 12 |
| hysteria | 9 |
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
| 83.7 | hysteria2 | 235.0 | 642.3 | 22.34 | 0.0 | 10.0 | 14.4 | 18.06 | Au1rxx-base64 | 159.223.157.129 |
| 79.68 | vless | 235.2 | 616.2 | 22.33 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 195.123.235.177 |
| 79.48 | vless | 243.8 | 685.8 | 22.13 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 47.253.226.114 |
| 79.44 | vless | 245.7 | 693.0 | 22.09 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 79.141.172.154 |
| 79.43 | vless | 245.9 | 646.9 | 22.08 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.231 |
| 79.22 | vless | 255.4 | 656.8 | 21.87 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.35 |
| 78.91 | vless | 268.8 | 708.6 | 21.56 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.235 |
| 78.63 | vless | 280.6 | 698.2 | 21.28 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.225 |
| 78.31 | vless | 261.5 | 687.6 | 21.72 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 167.17.69.171 |
| 78.16 | vless | 300.9 | 757.7 | 20.81 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.224 |
| 77.86 | vless | 314.1 | 725.2 | 20.51 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.90 |
| 77.69 | vless | 321.5 | 858.0 | 20.34 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.212 |
| 77.67 | vless | 322.1 | 749.1 | 20.32 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.104 |
| 77.43 | shadowsocks | 250.1 | 680.2 | 21.99 | 0.0 | 10.0 | 13.7 | 15.74 | mheidari-all | 37.19.198.236 |
| 77.39 | vless | 334.4 | 819.4 | 20.04 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.52 |
| 77.31 | vless | 337.6 | 911.3 | 19.96 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.173 |
| 77.16 | hysteria2 | 328.5 | 610.3 | 20.17 | 0.0 | 10.0 | 14.4 | 18.06 | Au1rxx-base64 | 66.94.121.46 |
| 77.1 | vless | 346.9 | 893.5 | 19.75 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.184 |
| 77.04 | vless | 293.2 | 719.2 | 20.99 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 216.152.147.28 |
| 76.83 | vless | 358.3 | 926.1 | 19.48 | 0.0 | 10.0 | 9.29 | 18.06 | Au1rxx-base64 | 169.40.42.182 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.902 | 0.839 | 267 | 1630 | prefer |
| DeltaKronecker-all | 0.811 | 0.75 | 24 | 6070 | prefer |
| mheidari-all | 0.798 | 0.724 | 76 | 15494 | prefer |
| Surfboard-tg-mixed | 0.73 | 0.653 | 121 | 7355 | prefer |
| ermaozi | 0.58 | 0.571 | 21 | 377 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 194 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7830 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9022 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5993 | observe |
| barry-far-vless | 0.255 | None | 0 | 6209 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1630 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 35 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 13 |
| cn-block | ClientOSError | - | 13 |
| speed | ClientOSError | - | 10 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
