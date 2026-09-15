# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 11:07:01 |
| 运行耗时 | 709.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90100 |
| 去重后节点 | 25502 |
| TCP 可达 | 3000 |
| 真实可用 | 486 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25502 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.4 |
| tcp | 42.3 |
| probe | 342.0 |
| real_test | 249.7 |
| generate | 70.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55506 |
| vmess | 13042 |
| shadowsocks | 10032 |
| trojan | 8805 |
| hysteria2 | 1830 |
| http | 667 |
| shadowsocksr | 128 |
| socks | 61 |
| hysteria | 14 |
| anytls | 8 |
| tuic | 7 |

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
| 80.46 | shadowsocks | 253.3 | 631.4 | 21.91 | 0.0 | 10.0 | 14.31 | 18.24 | Au1rxx-base64 | 156.146.38.168 |
| 78.1 | shadowsocks | 285.2 | 652.1 | 21.18 | 0.0 | 10.0 | 14.31 | 18.24 | Au1rxx-base64 | 198.98.53.130 |
| 75.1 | hysteria2 | 356.6 | 854.9 | 19.52 | 0.0 | 10.0 | 13.85 | 18.24 | Au1rxx-base64 | 107.175.219.48 |
| 74.74 | vless | 293.8 | 757.4 | 20.98 | 0.0 | 10.0 | 5.52 | 18.24 | Au1rxx-base64 | 38.180.242.205 |
| 74.73 | shadowsocks | 250.5 | 621.0 | 21.98 | 0.0 | 10.0 | 14.31 | 12.44 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.34 | shadowsocks | 357.3 | 800.1 | 19.51 | 0.0 | 10.0 | 14.31 | 18.24 | Au1rxx-base64 | 192.3.247.109 |
| 73.55 | shadowsocks | 279.0 | 658.9 | 21.32 | 0.0 | 10.0 | 14.31 | 12.44 | Surfboard-tg-mixed | 23.150.248.20 |
| 72.83 | shadowsocks | 342.7 | 698.1 | 19.85 | 0.0 | 10.0 | 14.31 | 18.24 | Au1rxx-base64 | 108.181.0.177 |
| 72.82 | vless | 297.1 | 667.0 | 20.9 | 0.0 | 10.0 | 5.52 | 18.24 | Au1rxx-base64 | 198.251.78.29 |
| 72.71 | shadowsocks | 336.5 | 758.3 | 19.99 | 0.0 | 10.0 | 14.31 | 18.24 | Au1rxx-base64 | 108.181.57.93 |
| 71.44 | vless | 314.3 | 720.9 | 20.5 | 0.0 | 10.0 | 5.52 | 18.24 | Au1rxx-base64 | 169.40.42.212 |
| 71.38 | shadowsocks | 359.4 | 919.7 | 19.46 | 0.0 | 10.0 | 14.31 | 18.24 | Au1rxx-base64 | 166.88.130.218 |
| 71.3 | vless | 308.7 | 679.8 | 20.63 | 0.0 | 10.0 | 5.52 | 18.24 | Au1rxx-base64 | 195.123.235.177 |
| 71.26 | hysteria2 | 460.5 | 850.4 | 17.12 | 0.0 | 9.54 | 13.85 | 18.24 | Au1rxx-base64 | 45.192.12.93 |
| 71.22 | hysteria2 | 475.9 | 936.5 | 16.76 | 0.0 | 9.79 | 13.85 | 18.24 | Au1rxx-base64 | 5.129.235.85 |
| 71.18 | hysteria2 | 281.3 | 678.6 | 21.27 | 0.0 | 10.0 | 13.85 | 7.16 | mheidari-all | 159.223.157.129 |
| 70.55 | shadowsocks | 514.4 | 1259.2 | 15.87 | 0.0 | 10.0 | 14.31 | 18.24 | Au1rxx-base64 | 51.222.200.165 |
| 70.43 | shadowsocks | 332.1 | 798.1 | 20.09 | 0.0 | 10.0 | 14.31 | 12.44 | Surfboard-tg-mixed | 15.204.233.41 |
| 70.43 | vless | 337.1 | 715.8 | 19.97 | 0.0 | 10.0 | 5.52 | 18.24 | Au1rxx-base64 | 169.40.42.235 |
| 70.23 | vless | 380.8 | 922.7 | 18.96 | 0.0 | 10.0 | 5.52 | 18.24 | Au1rxx-base64 | 216.152.147.28 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.906 | 0.851 | 309 | 1440 | prefer |
| mheidari-all | 0.83 | 0.758 | 62 | 21594 | prefer |
| ermaozi | 0.684 | 0.673 | 52 | 425 | observe |
| Surfboard-tg-mixed | 0.678 | 0.6 | 125 | 7543 | observe |
| DeltaKronecker-all | 0.669 | 0.591 | 110 | 5932 | observe |
| ermaozi-get_subscribe | 0.273 | 1.0 | 1 | 447 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 8009 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8725 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6114 | observe |
| barry-far-vless | 0.255 | None | 0 | 6343 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.233 | None | 0 | 1440 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 30 |
| 204 | ProxyError | - | 29 |
| cn-block | TimeoutError | - | 28 |
| geo | ClientOSError | - | 22 |
| geo | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 14 |
| speed | TimeoutError | - | 11 |
| speed | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 4 |
| speed | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
