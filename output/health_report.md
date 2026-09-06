# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-06 19:59:12 |
| 运行耗时 | 305.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94131 |
| 去重后节点 | 24614 |
| TCP 可达 | 3000 |
| 真实可用 | 538 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24614 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 41.0 |
| probe | 86.0 |
| real_test | 121.8 |
| generate | 49.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58712 |
| vmess | 12750 |
| shadowsocks | 11140 |
| trojan | 9073 |
| hysteria2 | 2074 |
| http | 137 |
| shadowsocksr | 125 |
| socks | 62 |
| anytls | 23 |
| hysteria | 19 |
| tuic | 16 |

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
| 80.82 | vless | 270.3 | 681.7 | 21.52 | 0.0 | 8.94 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.184 |
| 80.75 | vless | 319.2 | 825.7 | 20.39 | 0.0 | 10.0 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.202 |
| 80.57 | vless | 254.3 | 636.3 | 21.89 | 0.0 | 8.97 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.52 |
| 79.94 | vless | 309.9 | 673.4 | 20.6 | 0.0 | 8.98 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.15 |
| 79.71 | vless | 294.7 | 739.4 | 20.96 | 0.0 | 8.95 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.168 |
| 79.48 | vless | 328.3 | 852.8 | 20.18 | 0.0 | 8.94 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.75 |
| 79.42 | vless | 316.3 | 818.7 | 20.46 | 0.0 | 8.94 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.173 |
| 79.32 | vless | 351.6 | 808.1 | 19.64 | 0.0 | 10.0 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.89 |
| 78.78 | vless | 346.0 | 830.0 | 19.77 | 0.0 | 10.0 | 10.72 | 19.64 | Au1rxx-base64 | 158.69.112.254 |
| 78.64 | vless | 360.9 | 908.9 | 19.42 | 0.0 | 10.0 | 10.72 | 19.64 | Au1rxx-base64 | 216.152.147.28 |
| 78.62 | shadowsocks | 272.4 | 629.5 | 21.47 | 0.0 | 8.91 | 14.19 | 19.64 | Au1rxx-base64 | 156.146.38.167 |
| 78.45 | vless | 373.3 | 1025.2 | 19.14 | 0.0 | 8.95 | 10.72 | 19.64 | Au1rxx-base64 | 185.95.231.156 |
| 78.36 | vless | 360.6 | 951.6 | 19.43 | 0.0 | 10.0 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.16 |
| 78.1 | hysteria2 | 294.9 | 577.7 | 20.95 | 0.0 | 8.98 | 13.89 | 19.64 | Au1rxx-base64 | 66.94.121.46 |
| 77.81 | shadowsocks | 307.3 | 831.6 | 20.66 | 0.0 | 10.0 | 14.19 | 16.96 | Surfboard-tg-mixed | 198.98.53.130 |
| 77.4 | vless | 349.4 | 873.3 | 19.69 | 0.0 | 8.97 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.224 |
| 77.35 | shadowsocks | 281.0 | 659.4 | 21.27 | 0.0 | 8.95 | 14.19 | 19.64 | Au1rxx-base64 | 156.146.38.169 |
| 77.22 | vless | 379.7 | 1065.5 | 18.99 | 0.0 | 8.97 | 10.72 | 19.64 | Au1rxx-base64 | 45.138.100.226 |
| 76.83 | vless | 327.4 | 861.4 | 20.2 | 0.0 | 8.98 | 10.72 | 19.64 | Au1rxx-base64 | 169.40.42.163 |
| 76.68 | shadowsocks | 383.1 | 986.5 | 18.91 | 0.0 | 8.95 | 14.19 | 19.64 | Au1rxx-base64 | 51.222.200.165 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | 0.894 | 321 | 1861 | prefer |
| Surfboard-tg-mixed | 0.807 | 0.73 | 141 | 7357 | prefer |
| zhangkai | 0.766 | 0.783 | 23 | 144 | prefer |
| mheidari-all | 0.703 | 0.624 | 202 | 21188 | prefer |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 5750 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 5856 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4791 | observe |
| Epodonios-all | 0.255 | None | 0 | 7817 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8260 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6090 | observe |
| barry-far-vless | 0.255 | None | 0 | 6306 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1861 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 48 |
| geo | ClientOSError | - | 34 |
| cn-block | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyConnectionError | - | 10 |
| speed | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| speed | TimeoutError | - | 5 |
| geo | ProxyError | - | 4 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
