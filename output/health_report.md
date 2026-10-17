# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 02:57:53 |
| 运行耗时 | 908.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99804 |
| 去重后节点 | 27729 |
| TCP 可达 | 3000 |
| 真实可用 | 557 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27729 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 48.6 |
| probe | 337.8 |
| real_test | 435.2 |
| generate | 77.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58531 |
| vmess | 16676 |
| shadowsocks | 12083 |
| trojan | 10189 |
| hysteria2 | 1339 |
| http | 717 |
| shadowsocksr | 158 |
| socks | 62 |
| anytls | 26 |
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
| 80.72 | hysteria2 | 251.9 | 575.1 | 21.95 | 0.0 | 10.0 | 13.93 | 17.18 | Au1rxx-base64 | 66.94.121.46 |
| 80.26 | vless | 216.6 | 509.3 | 22.76 | 0.0 | 10.0 | 10.32 | 17.18 | Au1rxx-base64 | 47.251.108.158 |
| 79.55 | vless | 217.9 | 560.8 | 22.73 | 0.0 | 9.32 | 10.32 | 17.18 | Au1rxx-base64 | 154.29.159.211 |
| 77.53 | vless | 305.8 | 817.2 | 20.7 | 0.0 | 9.33 | 10.32 | 17.18 | Au1rxx-base64 | 154.9.241.170 |
| 77.39 | vless | 283.3 | 674.2 | 21.22 | 0.0 | 9.25 | 10.32 | 17.18 | Au1rxx-base64 | 147.45.60.160 |
| 77.34 | hysteria2 | 321.3 | 743.6 | 20.34 | 0.0 | 9.43 | 13.93 | 17.18 | Au1rxx-base64 | 129.213.91.185 |
| 77.16 | vless | 190.7 | 490.3 | 23.36 | 0.0 | 9.3 | 10.32 | 17.18 | Au1rxx-base64 | 131.143.180.110 |
| 77.05 | shadowsocks | 262.9 | 640.1 | 21.69 | 0.0 | 9.31 | 12.87 | 17.18 | Au1rxx-base64 | 156.146.38.169 |
| 77.04 | shadowsocks | 215.5 | 535.5 | 22.79 | 0.0 | 9.2 | 12.87 | 17.18 | Au1rxx-base64 | 173.244.56.6 |
| 76.96 | shadowsocks | 262.2 | 640.6 | 21.71 | 0.0 | 9.2 | 12.87 | 17.18 | Au1rxx-base64 | 156.146.38.168 |
| 75.95 | vless | 234.8 | 572.2 | 22.34 | 0.0 | 9.28 | 10.32 | 17.18 | Au1rxx-base64 | 154.40.55.185 |
| 75.88 | shadowsocks | 286.5 | 434.2 | 21.15 | 0.0 | 9.18 | 12.87 | 17.18 | Au1rxx-base64 | 103.11.76.248 |
| 75.07 | vless | 196.2 | 500.1 | 23.24 | 0.0 | 9.33 | 10.32 | 17.18 | Au1rxx-base64 | 45.63.53.81 |
| 75.02 | vless | 199.3 | 503.4 | 23.16 | 0.0 | 9.36 | 10.32 | 17.18 | Au1rxx-base64 | 176.122.183.26 |
| 74.06 | shadowsocks | 256.9 | 621.7 | 21.83 | 0.0 | 9.18 | 12.87 | 17.18 | Au1rxx-base64 | 156.146.38.167 |
| 73.83 | shadowsocks | 279.4 | 283.5 | 21.31 | 4.37 | 9.33 | 12.87 | 17.18 | Au1rxx-base64 | 149.22.87.204 |
| 73.76 | shadowsocks | 279.5 | 281.2 | 21.31 | 4.46 | 9.16 | 12.87 | 17.18 | Au1rxx-base64 | 149.22.87.241 |
| 73.42 | shadowsocks | 284.0 | 293.4 | 21.2 | 4.0 | 9.46 | 12.87 | 17.18 | Au1rxx-base64 | 149.22.87.240 |
| 73.11 | shadowsocks | 288.3 | 618.8 | 21.11 | 0.0 | 9.17 | 12.87 | 17.18 | Au1rxx-base64 | 149.22.95.183 |
| 73.03 | shadowsocks | 217.9 | 545.4 | 22.73 | 0.0 | 9.25 | 12.87 | 17.18 | Au1rxx-base64 | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | 0.886 | 528 | 1993 | prefer |
| ermaozi | 0.473 | 0.442 | 52 | 702 | observe |
| Surfboard-tg-mixed | 0.446 | 0.625 | 8 | 7128 | observe |
| ermaozi-get_subscribe | 0.335 | 1.0 | 2 | 601 | observe |
| mheidari-all | 0.333 | 0.251 | 223 | 24092 | observe |
| DeltaKronecker-all | 0.286 | 0.231 | 13 | 4946 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1993 | observe |
| Epodonios-all | 0.255 | None | 0 | 7692 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10040 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5602 | observe |
| barry-far-vless | 0.255 | None | 0 | 5904 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 113 |
| speed | ClientOSError | - | 49 |
| geo | ClientOSError | - | 26 |
| 204 | ProxyError | - | 23 |
| speed | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyConnectionError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
