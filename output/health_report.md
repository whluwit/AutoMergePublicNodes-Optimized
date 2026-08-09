# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-09 06:50:45 |
| 运行耗时 | 221.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 82780 |
| 去重后节点 | 23009 |
| TCP 可达 | 3000 |
| 真实可用 | 491 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23009 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.3 |
| tcp | 34.0 |
| probe | 49.4 |
| real_test | 96.7 |
| generate | 34.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48555 |
| vmess | 13144 |
| trojan | 9902 |
| shadowsocks | 9619 |
| hysteria2 | 1351 |
| shadowsocksr | 77 |
| socks | 65 |
| http | 43 |
| hysteria | 13 |
| tuic | 11 |

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
| 85.4 | hysteria2 | 226.9 | 631.3 | 22.53 | 0.0 | 10.0 | 13.97 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 85.06 | hysteria2 | 245.8 | 677.8 | 22.09 | 0.0 | 10.0 | 13.97 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.81 | hysteria2 | 249.7 | 698.6 | 22.0 | 0.0 | 8.84 | 13.97 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 82.34 | shadowsocks | 229.7 | 639.0 | 22.46 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 82.22 | shadowsocks | 234.7 | 656.9 | 22.34 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 82.12 | shadowsocks | 239.4 | 663.3 | 22.24 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 82.07 | shadowsocks | 241.3 | 670.3 | 22.19 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.02 | shadowsocks | 265.2 | 706.0 | 21.64 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 68.168.222.210 |
| 79.12 | shadowsocks | 282.9 | 658.8 | 21.23 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 78.48 | shadowsocks | 316.6 | 760.1 | 20.45 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 77.62 | shadowsocks | 267.7 | 616.4 | 21.58 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 77.3 | shadowsocks | 317.7 | 684.5 | 20.42 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 198.98.53.130 |
| 77.16 | shadowsocks | 307.5 | 696.4 | 20.66 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 77.13 | hysteria2 | 355.6 | 696.9 | 19.55 | 0.0 | 10.0 | 13.97 | 20.0 | Au1rxx-base64 | 62.210.124.146 |
| 76.69 | vless | 356.6 | 921.0 | 19.52 | 0.0 | 10.0 | 7.17 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 76.0 | hysteria2 | 420.5 | 882.2 | 18.04 | 0.0 | 10.0 | 13.97 | 20.0 | Au1rxx-base64 | 5.255.102.165 |
| 75.92 | shadowsocks | 278.7 | 637.4 | 21.33 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 75.87 | vless | 344.7 | 953.1 | 19.8 | 0.0 | 10.0 | 7.17 | 20.0 | Au1rxx-base64 | 45.138.100.226 |
| 75.45 | hysteria2 | 421.0 | 854.6 | 18.03 | 0.0 | 10.0 | 13.97 | 20.0 | Au1rxx-base64 | 194.180.174.69 |
| 75.37 | hysteria2 | 383.6 | 654.1 | 18.9 | 0.0 | 10.0 | 13.97 | 20.0 | Au1rxx-base64 | 31.76.113.32 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | 0.924 | 393 | 1640 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.761 | 0.684 | 114 | 6448 | prefer |
| mheidari-all | 0.344 | 0.333 | 12 | 17626 | observe |
| tg-oneclickvpnkeys | 0.318 | 1.0 | 2 | 171 | observe |
| DeltaKronecker-all | 0.283 | 0.198 | 116 | 4998 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5505 | observe |
| Epodonios-all | 0.255 | None | 0 | 7052 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7616 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5252 | observe |
| barry-far-vless | 0.255 | None | 0 | 5569 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5130 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 56 |
| geo | ClientOSError | - | 22 |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 18 |
| speed | TimeoutError | - | 18 |
| speed | ClientOSError | - | 14 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
