# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-09 04:32:53 |
| 运行耗时 | 1064.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98011 |
| 去重后节点 | 27733 |
| TCP 可达 | 3000 |
| 真实可用 | 545 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27733 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.4 |
| tcp | 47.1 |
| probe | 343.8 |
| real_test | 578.5 |
| generate | 87.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57711 |
| vmess | 15585 |
| shadowsocks | 12073 |
| trojan | 10394 |
| hysteria2 | 1442 |
| http | 480 |
| shadowsocksr | 174 |
| socks | 92 |
| anytls | 31 |
| hysteria | 17 |
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
| 82.53 | hysteria2 | 278.0 | 711.3 | 21.34 | 0.0 | 10.0 | 13.27 | 19.42 | Au1rxx-base64 | 129.213.91.185 |
| 81.88 | shadowsocks | 240.2 | 601.2 | 22.22 | 0.0 | 10.0 | 14.24 | 19.42 | Au1rxx-base64 | 156.146.38.168 |
| 81.73 | shadowsocks | 246.5 | 608.2 | 22.07 | 0.0 | 10.0 | 14.24 | 19.42 | Au1rxx-base64 | 156.146.38.170 |
| 81.58 | shadowsocks | 253.1 | 634.9 | 21.92 | 0.0 | 10.0 | 14.24 | 19.42 | Au1rxx-base64 | 156.146.38.169 |
| 80.33 | shadowsocks | 250.8 | 611.8 | 21.97 | 0.0 | 10.0 | 14.24 | 19.42 | Au1rxx-base64 | 156.146.38.167 |
| 80.28 | hysteria2 | 269.7 | 264.5 | 21.54 | 5.08 | 9.61 | 13.27 | 19.42 | Au1rxx-base64 | 45.32.10.7 |
| 80.02 | shadowsocks | 305.8 | 753.6 | 20.7 | 0.0 | 10.0 | 14.24 | 19.42 | Au1rxx-base64 | 37.19.198.244 |
| 79.85 | hysteria2 | 286.0 | 274.2 | 21.16 | 4.72 | 9.0 | 13.27 | 19.42 | Au1rxx-base64 | open.2ml.bid |
| 79.34 | shadowsocks | 310.9 | 760.1 | 20.58 | 0.0 | 10.0 | 14.24 | 19.42 | Au1rxx-base64 | 37.19.198.236 |
| 79.01 | shadowsocks | 307.1 | 749.8 | 20.67 | 0.0 | 10.0 | 14.24 | 19.42 | Au1rxx-base64 | 37.19.198.243 |
| 78.83 | vless | 307.2 | 685.2 | 20.67 | 0.0 | 10.0 | 11.36 | 19.42 | Au1rxx-base64 | 195.123.235.177 |
| 78.63 | hysteria2 | 295.2 | 612.9 | 20.95 | 0.0 | 10.0 | 13.27 | 19.42 | Au1rxx-base64 | 66.94.121.46 |
| 78.62 | shadowsocks | 291.5 | 708.7 | 21.03 | 0.0 | 10.0 | 14.24 | 19.42 | Au1rxx-base64 | 140.82.63.79 |
| 78.58 | hysteria2 | 306.2 | 306.6 | 20.69 | 3.5 | 9.52 | 13.27 | 19.42 | Au1rxx-base64 | 158.101.148.79 |
| 78.53 | vless | 325.7 | 696.0 | 20.24 | 0.0 | 10.0 | 11.36 | 19.42 | Au1rxx-base64 | 169.40.42.184 |
| 78.46 | vless | 348.0 | 751.3 | 19.72 | 0.0 | 10.0 | 11.36 | 19.42 | Au1rxx-base64 | 169.40.42.89 |
| 77.61 | vless | 273.8 | 556.8 | 21.44 | 0.0 | 10.0 | 11.36 | 19.42 | Au1rxx-base64 | 47.251.108.158 |
| 77.52 | http | 289.8 | 590.7 | 21.07 | 0.0 | 10.0 | 14.38 | 19.28 | zhangkai | 138.199.35.216 |
| 77.43 | vless | 377.2 | 698.0 | 19.05 | 0.0 | 10.0 | 11.36 | 19.42 | Au1rxx-base64 | 66.70.179.198 |
| 77.4 | vless | 361.8 | 790.2 | 19.4 | 0.0 | 10.0 | 11.36 | 19.42 | Au1rxx-base64 | 169.40.42.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.996 | 0.928 | 363 | 1756 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.766 | 0.694 | 49 | 7069 | prefer |
| ermaozi-get_subscribe | 0.604 | 0.583 | 48 | 607 | observe |
| mheidari-all | 0.37 | 0.289 | 412 | 23125 | observe |
| DeltaKronecker-all | 0.305 | 0.3 | 10 | 5197 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5081 | observe |
| Epodonios-all | 0.255 | None | 0 | 7569 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9901 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5581 | observe |
| barry-far-vless | 0.255 | None | 0 | 5823 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4362 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 171 |
| speed | TimeoutError | - | 74 |
| geo | ClientOSError | - | 34 |
| speed | ClientOSError | - | 29 |
| 204 | ProxyError | - | 22 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 5 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
