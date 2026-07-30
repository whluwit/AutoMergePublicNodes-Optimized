# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-30 02:03:43 |
| 运行耗时 | 406.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 77741 |
| 去重后节点 | 22691 |
| TCP 可达 | 3000 |
| 真实可用 | 841 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22691 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.5 |
| tcp | 32.1 |
| probe | 79.8 |
| real_test | 256.0 |
| generate | 30.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45475 |
| vmess | 11109 |
| shadowsocks | 10457 |
| trojan | 9909 |
| hysteria2 | 529 |
| shadowsocksr | 74 |
| http | 73 |
| socks | 67 |
| anytls | 26 |
| hysteria | 14 |
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
| 77.92 | trojan | 242.8 | 584.5 | 22.16 | 0.0 | 10.0 | 12.24 | 16.52 | Au1rxx-base64 | 64.94.95.117 |
| 76.74 | trojan | 293.7 | 751.5 | 20.98 | 0.0 | 10.0 | 12.24 | 16.52 | Au1rxx-base64 | 64.94.95.118 |
| 75.47 | shadowsocks | 295.0 | 731.9 | 20.95 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 156.146.38.170 |
| 75.37 | hysteria2 | 286.2 | 680.1 | 21.15 | 0.0 | 10.0 | 10.0 | 16.52 | Au1rxx-base64 | 159.223.157.129 |
| 74.97 | trojan | 297.5 | 768.9 | 20.89 | 0.0 | 10.0 | 12.24 | 16.52 | Au1rxx-base64 | 64.94.95.115 |
| 74.63 | shadowsocks | 290.2 | 686.3 | 21.06 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 37.19.198.243 |
| 74.49 | trojan | 255.9 | 607.1 | 21.85 | 0.0 | 10.0 | 12.24 | 16.52 | Au1rxx-base64 | 163.245.196.68 |
| 74.28 | trojan | 347.9 | 889.5 | 19.72 | 0.0 | 10.0 | 12.24 | 16.52 | Au1rxx-base64 | 64.94.95.114 |
| 74.19 | shadowsocks | 288.7 | 672.6 | 21.09 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 37.19.198.236 |
| 73.84 | trojan | 318.1 | 724.1 | 20.41 | 0.0 | 10.0 | 12.24 | 16.52 | Au1rxx-base64 | 153.75.250.171 |
| 73.71 | shadowsocks | 241.6 | 591.3 | 22.19 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 156.146.38.169 |
| 73.16 | shadowsocks | 310.2 | 725.8 | 20.6 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 68.168.222.210 |
| 72.87 | shadowsocks | 332.8 | 804.2 | 20.07 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 37.19.198.244 |
| 72.71 | vless | 298.0 | 678.0 | 20.88 | 0.0 | 10.0 | 9.25 | 14.94 | DeltaKronecker-all | 78.153.155.112 |
| 72.61 | shadowsocks | 376.1 | 793.1 | 19.07 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 198.98.53.130 |
| 72.37 | hysteria2 | 290.5 | 727.4 | 21.05 | 0.0 | 6.8 | 10.0 | 16.52 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 71.69 | shadowsocks | 332.6 | 854.7 | 20.08 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 156.146.38.195 |
| 71.0 | vless | 368.7 | 947.3 | 19.24 | 0.0 | 10.0 | 9.25 | 14.94 | DeltaKronecker-all | 45.138.100.226 |
| 70.99 | shadowsocks | 243.1 | 576.3 | 22.15 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 156.146.38.168 |
| 70.72 | shadowsocks | 256.4 | 551.1 | 21.84 | 0.0 | 10.0 | 12.0 | 16.52 | Au1rxx-base64 | 185.236.200.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 70 | 84 | prefer |
| Au1rxx-base64 | 0.983 | 0.935 | 293 | 1269 | prefer |
| Surfboard-tg-mixed | 0.792 | 0.824 | 17 | 5390 | prefer |
| DeltaKronecker-all | 0.476 | 0.395 | 1209 | 5519 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 5118 | observe |
| xiaoji235-airport-v2ray-all | 0.282 | 0.5 | 2 | 1861 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6124 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6754 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4279 | observe |
| barry-far-vless | 0.255 | None | 0 | 4688 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5076 | observe |
| mheidari-all | 0.234 | 0.154 | 13 | 16276 | downweight |
| Au1rxx-clash | 0.226 | None | 0 | 1269 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 331 |
| speed | ClientOSError | - | 160 |
| cn-block | TimeoutError | - | 100 |
| geo | ClientOSError | - | 92 |
| speed | TimeoutError | - | 56 |
| 204 | ProxyError | - | 9 |
| 204 | ClientOSError | - | 7 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
