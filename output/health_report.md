# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 16:09:41 |
| 运行耗时 | 706.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99256 |
| 去重后节点 | 27687 |
| TCP 可达 | 3000 |
| 真实可用 | 388 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27687 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 48.0 |
| probe | 280.3 |
| real_test | 277.4 |
| generate | 91.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58455 |
| vmess | 16392 |
| shadowsocks | 12089 |
| trojan | 10070 |
| hysteria2 | 1313 |
| http | 662 |
| shadowsocksr | 164 |
| socks | 59 |
| anytls | 29 |
| hysteria | 17 |
| tuic | 6 |

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
| 80.96 | hysteria2 | 239.4 | 687.3 | 22.24 | 0.0 | 10.0 | 13.24 | 16.98 | Au1rxx-base64 | 129.213.91.185 |
| 79.58 | vless | 241.9 | 643.0 | 22.18 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 147.45.60.160 |
| 79.05 | vless | 264.7 | 620.1 | 21.65 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 195.211.98.43 |
| 77.41 | shadowsocks | 258.0 | 707.9 | 21.8 | 0.0 | 10.0 | 12.63 | 16.98 | Au1rxx-base64 | 37.19.198.244 |
| 77.35 | shadowsocks | 260.9 | 719.6 | 21.74 | 0.0 | 10.0 | 12.63 | 16.98 | Au1rxx-base64 | 37.19.198.243 |
| 76.9 | vless | 357.7 | 673.5 | 19.5 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 169.40.42.15 |
| 76.72 | shadowsocks | 287.9 | 800.2 | 21.11 | 0.0 | 10.0 | 12.63 | 16.98 | Au1rxx-base64 | 37.19.198.236 |
| 76.29 | vless | 384.0 | 1045.8 | 18.89 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 185.95.231.156 |
| 76.02 | shadowsocks | 318.4 | 893.0 | 20.41 | 0.0 | 10.0 | 12.63 | 16.98 | Au1rxx-base64 | 37.19.198.160 |
| 75.91 | vless | 400.4 | 741.4 | 18.51 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 169.40.42.224 |
| 75.03 | shadowsocks | 276.3 | 635.8 | 21.38 | 0.0 | 10.0 | 12.63 | 16.98 | Au1rxx-base64 | 156.146.38.169 |
| 74.8 | vless | 330.2 | 614.7 | 20.13 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 169.40.42.52 |
| 74.4 | shadowsocks | 314.1 | 747.1 | 20.51 | 0.0 | 10.0 | 12.63 | 16.98 | Au1rxx-base64 | 156.146.38.168 |
| 74.07 | hysteria2 | 352.5 | 720.8 | 19.62 | 0.0 | 10.0 | 13.24 | 16.98 | Au1rxx-base64 | 66.94.121.46 |
| 73.95 | trojan | 328.6 | 899.0 | 20.17 | 0.0 | 10.0 | 9.8 | 16.98 | Au1rxx-base64 | 69.164.240.85 |
| 73.74 | vless | 363.5 | 862.5 | 19.36 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 198.23.169.170 |
| 73.34 | vless | 295.3 | 653.2 | 20.94 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 67.220.73.204 |
| 73.2 | vless | 517.6 | 1417.1 | 15.8 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 66.70.179.198 |
| 72.63 | vless | 347.5 | 952.2 | 19.73 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 104.243.33.154 |
| 72.01 | vless | 289.7 | 700.1 | 21.07 | 0.0 | 10.0 | 10.42 | 16.98 | Au1rxx-base64 | 169.40.42.235 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.836 | 0.757 | 449 | 1991 | prefer |
| mheidari-all | 0.668 | 0.594 | 32 | 23974 | observe |
| ermaozi | 0.408 | 0.379 | 58 | 618 | observe |
| Surfboard-tg-mixed | 0.382 | 0.357 | 14 | 7090 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 79 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1991 | observe |
| Epodonios-all | 0.255 | None | 0 | 7602 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10100 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5572 | observe |
| barry-far-vless | 0.255 | None | 0 | 5822 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4265 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 43 |
| 204 | TimeoutError | - | 40 |
| cn-block | TimeoutError | - | 23 |
| speed | TimeoutError | - | 18 |
| speed | ClientOSError | - | 15 |
| 204 | ClientOSError | - | 10 |
| geo | TimeoutError | - | 9 |
| geo | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
