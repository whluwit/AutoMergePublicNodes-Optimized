# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-06 10:14:29 |
| 运行耗时 | 296.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96060 |
| 去重后节点 | 25350 |
| TCP 可达 | 3000 |
| 真实可用 | 548 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25350 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 42.0 |
| probe | 85.7 |
| real_test | 115.7 |
| generate | 44.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60549 |
| vmess | 12590 |
| shadowsocks | 11216 |
| trojan | 9272 |
| hysteria2 | 2031 |
| http | 138 |
| shadowsocksr | 125 |
| socks | 61 |
| anytls | 48 |
| hysteria | 18 |
| tuic | 12 |

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
| 82.27 | shadowsocks | 247.9 | 610.9 | 22.04 | 0.0 | 10.0 | 14.51 | 19.72 | Au1rxx-base64 | 156.146.38.168 |
| 81.81 | shadowsocks | 240.4 | 635.3 | 22.21 | 0.0 | 9.37 | 14.51 | 19.72 | Au1rxx-base64 | 156.146.38.169 |
| 81.61 | hysteria2 | 253.2 | 554.9 | 21.92 | 0.0 | 9.03 | 13.45 | 19.72 | Au1rxx-base64 | 66.94.121.46 |
| 81.19 | shadowsocks | 228.7 | 600.5 | 22.48 | 0.0 | 10.0 | 14.51 | 18.2 | Surfboard-tg-mixed | 156.146.38.170 |
| 80.83 | shadowsocks | 244.2 | 619.5 | 22.12 | 0.0 | 10.0 | 14.51 | 18.2 | Surfboard-tg-mixed | 156.146.38.167 |
| 80.11 | shadowsocks | 254.1 | 611.8 | 21.9 | 0.0 | 10.0 | 14.51 | 18.2 | Surfboard-tg-mixed | 23.150.248.20 |
| 79.68 | shadowsocks | 283.8 | 670.1 | 21.21 | 0.0 | 10.0 | 14.51 | 18.2 | Surfboard-tg-mixed | 37.19.198.243 |
| 76.91 | http | 294.7 | 602.3 | 20.96 | 0.0 | 10.0 | 14.48 | 19.24 | zhangkai | 138.199.35.198 |
| 76.52 | shadowsocks | 376.4 | 900.1 | 19.06 | 0.0 | 9.11 | 14.51 | 19.72 | Au1rxx-base64 | 38.180.135.156 |
| 76.25 | shadowsocks | 303.9 | 668.3 | 20.74 | 0.0 | 10.0 | 14.51 | 18.2 | Surfboard-tg-mixed | 198.98.53.130 |
| 75.79 | shadowsocks | 309.2 | 610.2 | 20.62 | 0.0 | 9.27 | 14.51 | 19.72 | Au1rxx-base64 | 149.22.95.183 |
| 75.28 | shadowsocks | 347.3 | 855.6 | 19.74 | 0.0 | 10.0 | 14.51 | 18.2 | Surfboard-tg-mixed | 15.204.247.244 |
| 75.2 | shadowsocks | 311.1 | 538.6 | 20.58 | 0.0 | 9.05 | 14.51 | 19.72 | Au1rxx-base64 | 108.181.0.177 |
| 74.82 | vless | 356.3 | 700.8 | 19.53 | 0.0 | 9.13 | 6.82 | 19.72 | Au1rxx-base64 | 38.180.242.205 |
| 74.74 | http | 293.8 | 604.3 | 20.98 | 0.0 | 10.0 | 14.48 | 19.24 | zhangkai | 138.199.35.216 |
| 74.43 | shadowsocks | 287.5 | 589.5 | 21.12 | 0.0 | 10.0 | 14.51 | 18.2 | Surfboard-tg-mixed | 108.181.118.10 |
| 74.19 | shadowsocks | 413.0 | 1033.4 | 18.22 | 0.0 | 10.0 | 14.51 | 18.2 | Surfboard-tg-mixed | 15.204.246.108 |
| 74.04 | trojan | 299.6 | 619.2 | 20.84 | 0.0 | 9.28 | 11.25 | 19.72 | Au1rxx-base64 | 107.150.105.84 |
| 73.34 | vless | 320.3 | 730.1 | 20.36 | 0.0 | 9.15 | 6.82 | 19.72 | Au1rxx-base64 | 204.48.20.223 |
| 72.95 | vless | 282.9 | 577.6 | 21.23 | 0.0 | 9.01 | 6.82 | 19.72 | Au1rxx-base64 | 172.235.38.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | 0.896 | 366 | 1781 | prefer |
| zhangkai | 0.886 | 0.913 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.88 | 0.804 | 153 | 7318 | prefer |
| mheidari-all | 0.818 | 0.744 | 78 | 22388 | prefer |
| DeltaKronecker-all | 0.745 | 0.765 | 17 | 5856 | prefer |
| tg-oneclickvpnkeys | 0.363 | 1.0 | 3 | 133 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6965 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4791 | observe |
| Epodonios-all | 0.255 | None | 0 | 7771 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8223 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6005 | observe |
| barry-far-vless | 0.255 | None | 0 | 6223 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4111 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 23 |
| cn-block | ClientOSError | - | 17 |
| geo | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 12 |
| speed | ClientOSError | - | 7 |
| 204 | ProxyError | - | 6 |
| speed | TimeoutError | - | 6 |
| geo | TimeoutError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
