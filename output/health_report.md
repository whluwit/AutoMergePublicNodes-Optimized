# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 15:55:34 |
| 运行耗时 | 710.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91308 |
| 去重后节点 | 24428 |
| TCP 可达 | 3000 |
| 真实可用 | 403 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24428 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.4 |
| tcp | 42.4 |
| probe | 317.1 |
| real_test | 269.8 |
| generate | 75.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55359 |
| vmess | 13253 |
| shadowsocks | 11138 |
| trojan | 8830 |
| hysteria2 | 1902 |
| http | 608 |
| shadowsocksr | 127 |
| socks | 58 |
| hysteria | 15 |
| tuic | 10 |
| anytls | 8 |

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
| 83.29 | hysteria2 | 271.1 | 671.5 | 21.5 | 0.0 | 10.0 | 14.38 | 18.7 | Au1rxx-base64 | 159.223.157.129 |
| 80.47 | shadowsocks | 252.1 | 642.8 | 21.94 | 0.0 | 9.99 | 13.84 | 18.7 | Au1rxx-base64 | 156.146.38.169 |
| 79.34 | shadowsocks | 301.0 | 772.4 | 20.81 | 0.0 | 9.99 | 13.84 | 18.7 | Au1rxx-base64 | 156.146.38.168 |
| 79.01 | vless | 286.3 | 702.2 | 21.15 | 0.0 | 10.0 | 9.16 | 18.7 | Au1rxx-base64 | 79.141.172.154 |
| 78.62 | shadowsocks | 261.0 | 663.2 | 21.74 | 0.0 | 10.0 | 13.84 | 17.04 | Surfboard-tg-mixed | 156.146.38.167 |
| 77.26 | shadowsocks | 314.6 | 743.0 | 20.49 | 0.0 | 9.99 | 13.84 | 18.7 | Au1rxx-base64 | 37.19.198.244 |
| 76.54 | vless | 318.0 | 760.4 | 20.42 | 0.0 | 10.0 | 9.16 | 18.7 | Au1rxx-base64 | 47.253.226.114 |
| 75.86 | shadowsocks | 399.7 | 933.1 | 18.53 | 0.0 | 9.97 | 13.84 | 18.7 | Au1rxx-base64 | 15.204.247.206 |
| 75.45 | shadowsocks | 298.2 | 710.6 | 20.88 | 0.0 | 10.0 | 13.84 | 17.04 | Surfboard-tg-mixed | 37.19.198.236 |
| 75.25 | shadowsocks | 337.2 | 868.5 | 19.97 | 0.0 | 10.0 | 13.84 | 17.04 | Surfboard-tg-mixed | 23.150.248.20 |
| 74.76 | vless | 344.1 | 758.6 | 19.81 | 0.0 | 10.0 | 9.16 | 18.7 | Au1rxx-base64 | 169.40.42.75 |
| 74.47 | shadowsocks | 295.4 | 772.1 | 20.94 | 0.0 | 9.99 | 13.84 | 18.7 | Au1rxx-base64 | 156.146.38.170 |
| 74.35 | shadowsocks | 300.9 | 666.5 | 20.81 | 0.0 | 9.99 | 13.84 | 18.7 | Au1rxx-base64 | 198.98.53.130 |
| 73.96 | vless | 324.5 | 651.6 | 20.27 | 0.0 | 9.98 | 9.16 | 18.7 | Au1rxx-base64 | 172.233.139.46 |
| 73.93 | vless | 277.2 | 653.6 | 21.36 | 0.0 | 10.0 | 9.16 | 18.7 | Au1rxx-base64 | 188.137.243.243 |
| 73.76 | shadowsocks | 310.4 | 554.6 | 20.59 | 0.0 | 9.95 | 13.84 | 18.7 | Au1rxx-base64 | 108.181.0.177 |
| 73.67 | hysteria2 | 296.4 | 688.5 | 20.92 | 0.0 | 9.95 | 14.38 | 18.7 | Au1rxx-base64 | 108.59.244.158 |
| 73.59 | vless | 302.6 | 669.5 | 20.77 | 0.0 | 10.0 | 9.16 | 18.7 | Au1rxx-base64 | 195.123.235.177 |
| 73.57 | vless | 363.8 | 826.3 | 19.36 | 0.0 | 10.0 | 9.16 | 18.7 | Au1rxx-base64 | 169.40.42.95 |
| 73.23 | vless | 323.7 | 675.0 | 20.28 | 0.0 | 10.0 | 9.16 | 18.7 | Au1rxx-base64 | 172.235.43.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.873 | 0.807 | 270 | 1693 | prefer |
| ermaozi | 0.824 | 0.833 | 24 | 405 | prefer |
| Surfboard-tg-mixed | 0.805 | 0.728 | 147 | 7191 | prefer |
| mheidari-all | 0.533 | 0.452 | 126 | 19266 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 196 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7902 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9189 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5790 | observe |
| barry-far-vless | 0.255 | None | 0 | 6248 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3508 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1693 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 49 |
| geo | ClientOSError | - | 48 |
| cn-block | TimeoutError | - | 18 |
| geo | TimeoutError | - | 13 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 9 |
| speed | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
