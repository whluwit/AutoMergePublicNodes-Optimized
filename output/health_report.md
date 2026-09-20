# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 03:15:12 |
| 运行耗时 | 774.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 87229 |
| 去重后节点 | 25359 |
| TCP 可达 | 3000 |
| 真实可用 | 573 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25359 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 42.8 |
| probe | 272.1 |
| real_test | 368.9 |
| generate | 83.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52108 |
| vmess | 13819 |
| shadowsocks | 10727 |
| trojan | 8607 |
| hysteria2 | 1082 |
| http | 668 |
| shadowsocksr | 126 |
| socks | 73 |
| hysteria | 12 |
| tuic | 4 |
| anytls | 3 |

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
| 82.64 | vless | 193.0 | 500.7 | 23.31 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 172.235.43.210 |
| 81.74 | vless | 231.9 | 549.0 | 22.41 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 45.149.172.74 |
| 78.93 | shadowsocks | 262.1 | 644.0 | 21.71 | 0.0 | 10.0 | 13.2 | 19.06 | Au1rxx-base64 | 156.146.38.168 |
| 77.15 | vless | 214.2 | 528.4 | 22.82 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 195.123.240.65 |
| 76.93 | vless | 330.9 | 751.0 | 20.12 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 79.141.172.154 |
| 76.48 | vless | 198.2 | 499.1 | 23.19 | 0.0 | 10.0 | 10.27 | 14.02 | Surfboard-tg-mixed | 172.235.38.85 |
| 76.25 | vless | 364.5 | 879.6 | 19.34 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 15.204.97.214 |
| 76.16 | trojan | 209.6 | 502.6 | 22.93 | 0.0 | 10.0 | 11.67 | 19.06 | Au1rxx-base64 | 43.173.90.202 |
| 75.99 | trojan | 229.8 | 529.6 | 22.46 | 0.0 | 10.0 | 11.67 | 19.06 | Au1rxx-base64 | 100.42.228.109 |
| 75.74 | vless | 365.6 | 879.0 | 19.32 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 15.204.97.216 |
| 75.03 | shadowsocks | 257.7 | 631.7 | 21.81 | 0.0 | 10.0 | 13.2 | 14.02 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.03 | hysteria2 | 372.1 | 806.2 | 19.16 | 0.0 | 10.0 | 14.12 | 19.06 | Au1rxx-base64 | 159.223.157.129 |
| 74.14 | vless | 354.3 | 791.4 | 19.58 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 34.19.91.203 |
| 73.8 | vless | 235.3 | 538.6 | 22.33 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 31.58.50.200 |
| 73.39 | shadowsocks | 261.4 | 661.0 | 21.73 | 0.0 | 10.0 | 13.2 | 12.46 | mheidari-all | 173.244.56.9 |
| 73.24 | shadowsocks | 267.9 | 675.7 | 21.58 | 0.0 | 10.0 | 13.2 | 12.46 | mheidari-all | 173.244.56.6 |
| 73.12 | shadowsocks | 273.1 | 617.1 | 21.46 | 0.0 | 10.0 | 13.2 | 12.46 | mheidari-all | 156.146.38.170 |
| 73.01 | vless | 308.4 | 434.2 | 20.64 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 172.64.32.108 |
| 72.9 | vless | 470.4 | 1150.0 | 16.89 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 51.81.203.63 |
| 72.44 | vless | 222.2 | 488.6 | 22.64 | 0.0 | 10.0 | 10.27 | 19.06 | Au1rxx-base64 | 162.159.45.19 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.938 | 0.877 | 309 | 1576 | prefer |
| ermaozi | 0.76 | 0.755 | 53 | 365 | prefer |
| Surfboard-tg-mixed | 0.697 | 0.618 | 262 | 7138 | observe |
| mheidari-all | 0.474 | 0.393 | 135 | 15978 | observe |
| DeltaKronecker-all | 0.46 | 0.377 | 106 | 6421 | observe |
| ermaozi-get_subscribe | 0.337 | 0.571 | 7 | 394 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| xiaoji235-airport-v2ray-all | 0.272 | 0.286 | 7 | 3625 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5174 | observe |
| Epodonios-all | 0.255 | None | 0 | 7601 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8846 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5693 | observe |
| barry-far-vless | 0.255 | None | 0 | 5908 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1576 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 114 |
| speed | TimeoutError | - | 55 |
| geo | ClientOSError | - | 52 |
| speed | ClientOSError | - | 24 |
| 204 | ProxyError | - | 19 |
| 204 | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 12 |
| 204 | ProxyConnectionError | - | 2 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
