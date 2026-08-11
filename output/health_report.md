# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-11 07:02:05 |
| 运行耗时 | 229.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 84699 |
| 去重后节点 | 24202 |
| TCP 可达 | 3000 |
| 真实可用 | 471 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24202 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 36.1 |
| probe | 50.7 |
| real_test | 101.9 |
| generate | 34.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49122 |
| vmess | 13337 |
| trojan | 10814 |
| shadowsocks | 9847 |
| hysteria2 | 1304 |
| shadowsocksr | 77 |
| socks | 74 |
| http | 73 |
| anytls | 26 |
| hysteria | 13 |
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
| 84.54 | hysteria2 | 230.2 | 638.5 | 22.45 | 0.0 | 10.0 | 14.21 | 18.98 | Au1rxx-base64 | 159.223.157.129 |
| 80.93 | shadowsocks | 251.4 | 693.7 | 21.96 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 37.19.198.243 |
| 79.53 | shadowsocks | 311.7 | 878.5 | 20.56 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 37.19.198.160 |
| 78.48 | shadowsocks | 279.8 | 648.3 | 21.3 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 156.146.38.167 |
| 77.1 | shadowsocks | 331.4 | 798.0 | 20.11 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 156.146.38.168 |
| 76.82 | trojan | 295.9 | 646.8 | 20.93 | 0.0 | 10.0 | 13.09 | 18.98 | Au1rxx-base64 | 64.94.95.117 |
| 76.71 | trojan | 296.8 | 637.9 | 20.91 | 0.0 | 10.0 | 13.09 | 18.98 | Au1rxx-base64 | 64.94.95.114 |
| 76.57 | hysteria2 | 347.8 | 679.3 | 19.73 | 0.0 | 10.0 | 14.21 | 18.98 | Au1rxx-base64 | 62.210.124.146 |
| 76.37 | shadowsocks | 232.4 | 646.1 | 22.4 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 37.19.198.244 |
| 76.36 | shadowsocks | 232.8 | 645.4 | 22.39 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 37.19.198.236 |
| 75.68 | shadowsocks | 384.9 | 964.6 | 18.87 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 156.146.38.169 |
| 75.46 | hysteria2 | 382.7 | 738.9 | 18.92 | 0.0 | 10.0 | 14.21 | 18.98 | Au1rxx-base64 | 144.31.207.60 |
| 75.25 | trojan | 356.1 | 570.3 | 19.53 | 0.0 | 10.0 | 13.09 | 18.98 | Au1rxx-base64 | 64.94.95.115 |
| 74.75 | hysteria2 | 423.2 | 849.7 | 17.98 | 0.0 | 10.0 | 14.21 | 18.98 | Au1rxx-base64 | 5.255.102.165 |
| 74.22 | shadowsocks | 440.2 | 1123.8 | 17.59 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 156.146.38.170 |
| 74.05 | shadowsocks | 315.5 | 597.4 | 20.48 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 149.22.95.183 |
| 73.89 | shadowsocks | 311.4 | 600.8 | 20.57 | 0.0 | 10.0 | 13.99 | 18.98 | Au1rxx-base64 | 173.244.56.9 |
| 73.84 | hysteria2 | 449.0 | 904.1 | 17.38 | 0.0 | 9.95 | 14.21 | 18.98 | Au1rxx-base64 | 91.196.32.163 |
| 73.03 | vless | 350.3 | 827.6 | 19.67 | 0.0 | 10.0 | 4.26 | 19.1 | Surfboard-tg-mixed | 169.40.42.179 |
| 72.88 | vless | 356.7 | 908.9 | 19.52 | 0.0 | 10.0 | 4.26 | 19.1 | Surfboard-tg-mixed | 169.40.42.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | 1.0 | 49 | 67 | prefer |
| Au1rxx-base64 | 0.969 | 0.915 | 352 | 1414 | prefer |
| Surfboard-tg-mixed | 0.781 | 0.705 | 105 | 6265 | prefer |
| mheidari-all | 0.49 | 0.405 | 37 | 20272 | observe |
| DeltaKronecker-all | 0.396 | 0.306 | 36 | 5522 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5419 | observe |
| Epodonios-all | 0.255 | None | 0 | 6871 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7464 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5103 | observe |
| barry-far-vless | 0.255 | None | 0 | 5410 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5209 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.239 | None | 0 | 1607 | observe |
| Au1rxx-clash | 0.232 | None | 0 | 1414 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 29 |
| 204 | ProxyError | - | 16 |
| 204 | TimeoutError | - | 13 |
| geo | ClientOSError | - | 12 |
| speed | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 9 |
| speed | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
