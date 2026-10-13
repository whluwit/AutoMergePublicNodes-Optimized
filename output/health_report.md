# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-13 22:24:40 |
| 运行耗时 | 660.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98450 |
| 去重后节点 | 27350 |
| TCP 可达 | 3000 |
| 真实可用 | 476 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27350 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.4 |
| tcp | 47.7 |
| probe | 250.7 |
| real_test | 286.1 |
| generate | 70.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58300 |
| vmess | 15969 |
| shadowsocks | 11827 |
| trojan | 10374 |
| hysteria2 | 1275 |
| http | 424 |
| shadowsocksr | 170 |
| socks | 61 |
| anytls | 26 |
| hysteria | 18 |
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
| 82.63 | vless | 270.6 | 663.9 | 21.51 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 147.45.60.160 |
| 80.64 | shadowsocks | 236.9 | 617.7 | 22.3 | 0.0 | 10.0 | 13.16 | 19.18 | Au1rxx-base64 | 156.146.38.169 |
| 80.3 | vless | 259.7 | 658.1 | 21.77 | 0.0 | 10.0 | 12.27 | 16.26 | mheidari-all | 195.211.98.43 |
| 80.1 | vless | 309.8 | 689.0 | 20.61 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 169.40.42.35 |
| 79.41 | vless | 419.0 | 1072.4 | 18.08 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 136.107.170.196 |
| 79.39 | shadowsocks | 251.5 | 649.8 | 21.96 | 0.0 | 10.0 | 13.16 | 19.18 | Au1rxx-base64 | 156.146.38.168 |
| 78.6 | vless | 279.2 | 565.7 | 21.31 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 47.251.108.158 |
| 78.46 | hysteria2 | 286.7 | 727.3 | 21.14 | 0.0 | 10.0 | 9.64 | 19.18 | Au1rxx-base64 | 129.213.91.185 |
| 78.3 | vless | 384.7 | 934.5 | 18.87 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 169.40.42.163 |
| 78.12 | vless | 388.1 | 936.1 | 18.79 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 159.89.87.21 |
| 78.03 | shadowsocks | 233.7 | 604.7 | 22.37 | 0.0 | 10.0 | 13.16 | 19.18 | Au1rxx-base64 | 156.146.38.170 |
| 77.9 | shadowsocks | 305.6 | 749.3 | 20.7 | 0.0 | 10.0 | 13.16 | 19.18 | Au1rxx-base64 | 37.19.198.243 |
| 77.29 | shadowsocks | 310.5 | 705.9 | 20.59 | 0.0 | 10.0 | 13.16 | 19.18 | Au1rxx-base64 | 140.82.63.79 |
| 77.27 | vless | 300.5 | 765.7 | 20.82 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 38.180.137.143 |
| 77.26 | vless | 316.4 | 605.3 | 20.45 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 195.123.240.65 |
| 77.0 | vless | 337.9 | 702.8 | 19.96 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 169.40.42.231 |
| 76.74 | shadowsocks | 313.0 | 768.5 | 20.53 | 0.0 | 10.0 | 13.16 | 19.18 | Au1rxx-base64 | 37.19.198.160 |
| 76.73 | vless | 414.6 | 890.7 | 18.18 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 169.40.42.95 |
| 76.66 | vless | 295.6 | 696.0 | 20.94 | 0.0 | 9.72 | 12.27 | 19.18 | Au1rxx-base64 | uspanel.unixzone.us |
| 76.59 | vless | 327.1 | 687.6 | 20.21 | 0.0 | 10.0 | 12.27 | 19.18 | Au1rxx-base64 | 169.40.42.212 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.992 | 0.92 | 100 | 23973 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.965 | 0.895 | 362 | 1816 | prefer |
| Surfboard-tg-mixed | 0.785 | 0.714 | 42 | 7123 | prefer |
| ermaozi-get_subscribe | 0.362 | 0.667 | 6 | 534 | observe |
| Au1rxx-clash | 0.327 | 1.0 | 1 | 1806 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| DeltaKronecker-all | 0.259 | 0.333 | 3 | 5076 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5086 | observe |
| Epodonios-all | 0.255 | None | 0 | 7631 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9832 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5683 | observe |
| barry-far-vless | 0.255 | None | 0 | 5929 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 9 |
| speed | ClientOSError | - | 7 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyError | - | 3 |
| geo | ClientOSError | - | 3 |
| geo | TimeoutError | - | 2 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
