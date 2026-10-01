# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 03:58:50 |
| 运行耗时 | 737.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98025 |
| 去重后节点 | 27299 |
| TCP 可达 | 3000 |
| 真实可用 | 437 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27299 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 46.0 |
| probe | 264.0 |
| real_test | 343.2 |
| generate | 75.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60019 |
| vmess | 15277 |
| shadowsocks | 11438 |
| trojan | 9073 |
| hysteria2 | 1363 |
| http | 561 |
| shadowsocksr | 164 |
| socks | 66 |
| anytls | 40 |
| hysteria | 16 |
| tuic | 8 |

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
| 81.31 | vless | 269.1 | 635.7 | 21.55 | 0.0 | 10.0 | 11.57 | 18.22 | Au1rxx-base64 | 195.123.235.177 |
| 80.56 | vless | 302.8 | 744.7 | 20.77 | 0.0 | 10.0 | 11.57 | 18.22 | Au1rxx-base64 | 169.40.42.168 |
| 80.04 | hysteria2 | 341.1 | 865.6 | 19.88 | 0.0 | 10.0 | 13.04 | 18.22 | Au1rxx-base64 | 159.223.157.129 |
| 79.95 | shadowsocks | 253.1 | 629.6 | 21.92 | 0.0 | 10.0 | 13.81 | 18.22 | Au1rxx-base64 | 156.146.38.169 |
| 79.3 | shadowsocks | 248.1 | 618.6 | 22.04 | 0.0 | 10.0 | 13.81 | 18.22 | Au1rxx-base64 | 156.146.38.167 |
| 79.26 | shadowsocks | 282.8 | 729.0 | 21.23 | 0.0 | 10.0 | 13.81 | 18.22 | Au1rxx-base64 | 37.19.198.236 |
| 79.12 | shadowsocks | 287.0 | 745.8 | 21.13 | 0.0 | 10.0 | 13.81 | 18.18 | mheidari-all | 37.19.198.244 |
| 78.82 | shadowsocks | 300.0 | 771.0 | 20.83 | 0.0 | 10.0 | 13.81 | 18.18 | mheidari-all | 156.146.38.168 |
| 78.8 | shadowsocks | 302.8 | 790.4 | 20.77 | 0.0 | 10.0 | 13.81 | 18.22 | Au1rxx-base64 | 198.98.53.130 |
| 78.58 | vless | 352.9 | 876.6 | 19.61 | 0.0 | 10.0 | 11.57 | 18.22 | Au1rxx-base64 | 159.89.87.21 |
| 78.53 | vless | 300.2 | 681.1 | 20.83 | 0.0 | 10.0 | 11.57 | 18.22 | Au1rxx-base64 | 169.40.42.225 |
| 78.51 | shadowsocks | 284.6 | 666.5 | 21.19 | 0.0 | 10.0 | 13.81 | 18.22 | Au1rxx-base64 | 140.82.63.79 |
| 78.4 | vless | 396.1 | 966.3 | 18.61 | 0.0 | 10.0 | 11.57 | 18.22 | Au1rxx-base64 | 169.40.42.104 |
| 78.36 | vless | 397.8 | 1040.0 | 18.57 | 0.0 | 10.0 | 11.57 | 18.22 | Au1rxx-base64 | 185.95.231.156 |
| 78.35 | hysteria2 | 267.0 | 564.1 | 21.6 | 0.0 | 10.0 | 13.04 | 18.22 | Au1rxx-base64 | 192.255.128.123 |
| 78.28 | hysteria2 | 288.6 | 620.4 | 21.1 | 0.0 | 10.0 | 13.04 | 18.22 | Au1rxx-base64 | 66.94.121.46 |
| 78.17 | vless | 319.6 | 663.0 | 20.38 | 0.0 | 10.0 | 11.57 | 18.22 | Au1rxx-base64 | 169.40.42.231 |
| 77.91 | vless | 321.5 | 680.0 | 20.34 | 0.0 | 10.0 | 11.57 | 18.22 | Au1rxx-base64 | 169.40.42.232 |
| 77.49 | vless | 315.5 | 731.0 | 20.48 | 0.0 | 10.0 | 11.57 | 18.22 | Au1rxx-base64 | 169.40.42.229 |
| 77.32 | shadowsocks | 345.1 | 957.8 | 19.79 | 0.0 | 10.0 | 13.81 | 18.22 | Au1rxx-base64 | 185.156.47.97 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.881 | 0.812 | 287 | 1783 | prefer |
| Surfboard-tg-mixed | 0.719 | 0.64 | 189 | 7136 | prefer |
| DeltaKronecker-all | 0.515 | 0.5 | 16 | 5434 | observe |
| ermaozi | 0.376 | 0.429 | 14 | 588 | observe |
| mheidari-all | 0.352 | 0.271 | 255 | 22835 | observe |
| Epodonios-all | 0.255 | None | 0 | 7637 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9410 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5815 | observe |
| barry-far-vless | 0.255 | None | 0 | 6001 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4183 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1783 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 108 |
| speed | ClientOSError | - | 61 |
| speed | TimeoutError | - | 55 |
| geo | ClientOSError | - | 30 |
| 204 | ProxyConnectionError | - | 17 |
| cn-block | TimeoutError | - | 16 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
