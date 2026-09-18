# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 03:09:04 |
| 运行耗时 | 1022.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84467 |
| 去重后节点 | 23106 |
| TCP 可达 | 3000 |
| 真实可用 | 579 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23106 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.5 |
| tcp | 38.7 |
| probe | 332.0 |
| real_test | 566.0 |
| generate | 77.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50757 |
| vmess | 13146 |
| shadowsocks | 10147 |
| trojan | 8246 |
| hysteria2 | 1299 |
| http | 662 |
| shadowsocksr | 126 |
| socks | 70 |
| hysteria | 8 |
| anytls | 4 |
| tuic | 2 |

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
| 81.96 | vless | 249.9 | 568.1 | 21.99 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 38.180.242.205 |
| 81.48 | hysteria2 | 301.4 | 717.4 | 20.8 | 0.0 | 10.0 | 13.42 | 18.6 | Au1rxx-base64 | 159.223.157.129 |
| 80.24 | shadowsocks | 256.5 | 621.5 | 21.84 | 0.0 | 10.0 | 13.8 | 18.6 | Au1rxx-base64 | 156.146.38.170 |
| 78.54 | shadowsocks | 284.9 | 678.4 | 21.18 | 0.0 | 10.0 | 13.8 | 18.6 | Au1rxx-base64 | 37.19.198.236 |
| 77.78 | shadowsocks | 284.9 | 677.7 | 21.18 | 0.0 | 10.0 | 13.8 | 18.6 | Au1rxx-base64 | 37.19.198.243 |
| 77.42 | vless | 230.4 | 617.2 | 22.45 | 0.0 | 10.0 | 11.37 | 15.6 | Surfboard-tg-mixed | 88.216.57.128 |
| 77.18 | shadowsocks | 259.2 | 633.0 | 21.78 | 0.0 | 10.0 | 13.8 | 18.6 | Au1rxx-base64 | 156.146.38.169 |
| 77.07 | shadowsocks | 290.0 | 687.9 | 21.07 | 0.0 | 10.0 | 13.8 | 18.6 | Au1rxx-base64 | 37.19.198.244 |
| 76.78 | shadowsocks | 290.0 | 682.7 | 21.06 | 0.0 | 10.0 | 13.8 | 18.6 | Au1rxx-base64 | 37.19.198.160 |
| 76.71 | vless | 387.9 | 950.0 | 18.8 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 185.95.231.156 |
| 75.78 | shadowsocks | 264.5 | 636.0 | 21.66 | 0.0 | 10.0 | 13.8 | 19.88 | mheidari-all | 156.146.38.168 |
| 75.67 | vless | 380.8 | 897.1 | 18.96 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 66.70.179.198 |
| 75.65 | vless | 342.0 | 708.9 | 19.86 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 169.40.42.52 |
| 75.45 | shadowsocks | 247.6 | 625.3 | 22.05 | 0.0 | 10.0 | 13.8 | 15.6 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.15 | vless | 336.6 | 742.4 | 19.99 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 169.40.42.235 |
| 74.82 | vless | 353.5 | 722.0 | 19.59 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 169.40.42.90 |
| 74.76 | vless | 400.8 | 949.7 | 18.5 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 137.184.218.169 |
| 74.72 | vless | 354.7 | 716.9 | 19.57 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 198.200.42.129 |
| 74.69 | vless | 333.8 | 695.1 | 20.05 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 169.40.42.179 |
| 74.68 | vless | 395.6 | 946.9 | 18.62 | 0.0 | 10.0 | 11.37 | 18.6 | Au1rxx-base64 | 169.40.42.95 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | 0.907 | 281 | 1648 | prefer |
| ermaozi | 0.801 | 0.808 | 26 | 378 | prefer |
| Surfboard-tg-mixed | 0.595 | 0.515 | 132 | 7509 | observe |
| mheidari-all | 0.517 | 0.435 | 85 | 15863 | observe |
| DeltaKronecker-all | 0.448 | 0.368 | 525 | 5931 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4261 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| ermaozi-get_subscribe | 0.256 | 0.5 | 4 | 402 | observe |
| Epodonios-all | 0.255 | None | 0 | 7966 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8922 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5961 | observe |
| barry-far-vless | 0.255 | None | 0 | 6180 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 212 |
| geo | ClientOSError | - | 82 |
| speed | ClientOSError | - | 74 |
| speed | TimeoutError | - | 57 |
| cn-block | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 12 |
| 204 | ProxyError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| 204 | ProxyConnectionError | - | 4 |
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
