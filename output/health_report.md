# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-12 13:01:48 |
| 运行耗时 | 245.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 80185 |
| 去重后节点 | 22267 |
| TCP 可达 | 3000 |
| 真实可用 | 596 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22267 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.3 |
| tcp | 32.8 |
| probe | 50.4 |
| real_test | 122.4 |
| generate | 30.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46294 |
| vmess | 13265 |
| shadowsocks | 9533 |
| trojan | 9475 |
| hysteria2 | 1296 |
| http | 159 |
| shadowsocksr | 73 |
| socks | 71 |
| tuic | 11 |
| hysteria | 7 |
| anytls | 1 |

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
| 83.83 | http | 239.3 | 635.3 | 22.24 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.41 |
| 83.69 | http | 245.3 | 640.6 | 22.1 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.8 |
| 83.65 | http | 246.8 | 654.8 | 22.06 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.25 |
| 83.54 | http | 251.5 | 665.5 | 21.95 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.23 |
| 83.53 | http | 252.4 | 666.4 | 21.94 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.21 |
| 83.5 | http | 253.5 | 669.9 | 21.91 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.5 |
| 83.05 | http | 272.8 | 702.0 | 21.46 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.33 |
| 82.76 | http | 242.4 | 644.0 | 22.17 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.39 |
| 82.68 | http | 245.9 | 646.4 | 22.09 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.19 |
| 82.55 | http | 251.4 | 657.4 | 21.96 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.9 |
| 82.54 | http | 251.6 | 668.7 | 21.95 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.10 |
| 82.52 | hysteria2 | 239.2 | 645.2 | 22.24 | 0.0 | 10.0 | 13.42 | 17.96 | Au1rxx-base64 | 159.223.157.129 |
| 82.51 | http | 253.0 | 652.7 | 21.92 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.27 |
| 82.48 | http | 254.5 | 668.7 | 21.89 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.34 |
| 82.47 | http | 254.9 | 674.3 | 21.88 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.11 |
| 82.45 | http | 255.8 | 678.2 | 21.86 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.31 |
| 82.44 | http | 256.0 | 670.0 | 21.85 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.4 |
| 82.35 | http | 260.0 | 686.5 | 21.76 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.15 |
| 81.99 | http | 275.4 | 721.1 | 21.4 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.28 |
| 79.85 | shadowsocks | 231.2 | 634.8 | 22.43 | 0.0 | 10.0 | 13.46 | 17.96 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 0.992 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.934 | 0.869 | 428 | 1660 | prefer |
| Surfboard-tg-mixed | 0.64 | 0.562 | 89 | 6040 | observe |
| mheidari-all | 0.606 | 0.889 | 9 | 16658 | observe |
| DeltaKronecker-all | 0.513 | 0.432 | 88 | 4975 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5328 | observe |
| Epodonios-all | 0.255 | None | 0 | 6671 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7619 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4924 | observe |
| barry-far-vless | 0.255 | None | 0 | 5264 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1660 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 32 |
| geo | ClientOSError | - | 30 |
| 204 | TimeoutError | - | 20 |
| geo | TimeoutError | - | 18 |
| speed | ClientOSError | - | 15 |
| cn-block | TimeoutError | - | 14 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
