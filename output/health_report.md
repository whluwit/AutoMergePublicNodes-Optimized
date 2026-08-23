# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-23 06:37:38 |
| 运行耗时 | 306.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 98 |
| 原始节点 | 77583 |
| 去重后节点 | 21117 |
| TCP 可达 | 3000 |
| 真实可用 | 796 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21117 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 34.0 |
| probe | 58.5 |
| real_test | 171.7 |
| generate | 34.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47360 |
| shadowsocks | 10128 |
| vmess | 10060 |
| trojan | 8544 |
| hysteria2 | 1091 |
| http | 166 |
| shadowsocksr | 125 |
| socks | 100 |
| hysteria | 7 |
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
| 83.04 | shadowsocks | 227.1 | 585.1 | 22.52 | 0.0 | 10.0 | 14.52 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 82.83 | shadowsocks | 236.4 | 585.7 | 22.31 | 0.0 | 10.0 | 14.52 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 82.58 | shadowsocks | 247.2 | 636.1 | 22.06 | 0.0 | 10.0 | 14.52 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 82.51 | shadowsocks | 249.8 | 632.4 | 21.99 | 0.0 | 10.0 | 14.52 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 80.83 | vless | 288.9 | 673.2 | 21.09 | 0.0 | 10.0 | 9.74 | 20.0 | Au1rxx-base64 | 198.251.78.29 |
| 79.81 | shadowsocks | 252.5 | 604.0 | 21.93 | 0.0 | 10.0 | 14.52 | 17.86 | Surfboard-tg-mixed | 23.150.248.20 |
| 79.69 | vless | 282.6 | 662.7 | 21.24 | 0.0 | 10.0 | 9.74 | 20.0 | Au1rxx-base64 | 154.40.137.160 |
| 79.61 | vless | 341.5 | 907.7 | 19.87 | 0.0 | 10.0 | 9.74 | 20.0 | Au1rxx-base64 | 38.180.242.205 |
| 79.43 | shadowsocks | 276.1 | 662.6 | 21.39 | 0.0 | 10.0 | 14.52 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 78.79 | shadowsocks | 300.7 | 732.7 | 20.82 | 0.0 | 10.0 | 14.52 | 17.86 | Surfboard-tg-mixed | 37.19.198.160 |
| 77.49 | vless | 309.2 | 690.8 | 20.62 | 0.0 | 9.87 | 9.74 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 77.13 | shadowsocks | 303.0 | 537.5 | 20.76 | 0.0 | 9.65 | 14.52 | 20.0 | Au1rxx-base64 | 94.72.127.58 |
| 77.01 | shadowsocks | 295.1 | 702.9 | 20.95 | 0.0 | 10.0 | 14.52 | 17.86 | Surfboard-tg-mixed | 37.19.198.243 |
| 76.86 | shadowsocks | 450.8 | 1182.1 | 17.34 | 0.0 | 9.89 | 14.52 | 20.0 | Au1rxx-base64 | 15.204.247.175 |
| 76.73 | shadowsocks | 363.0 | 953.2 | 19.37 | 0.0 | 9.84 | 14.52 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 76.54 | vless | 361.7 | 750.0 | 19.4 | 0.0 | 10.0 | 9.74 | 20.0 | Au1rxx-base64 | 169.40.42.35 |
| 76.29 | vless | 308.4 | 652.5 | 20.64 | 0.0 | 9.86 | 9.74 | 20.0 | Au1rxx-base64 | 38.244.20.113 |
| 76.04 | shadowsocks | 429.6 | 1107.7 | 17.83 | 0.0 | 10.0 | 14.52 | 20.0 | Au1rxx-base64 | 142.4.216.225 |
| 75.64 | shadowsocks | 351.8 | 872.5 | 19.63 | 0.0 | 10.0 | 14.52 | 20.0 | Au1rxx-base64 | 38.180.135.156 |
| 75.52 | hysteria2 | 283.4 | 689.5 | 21.22 | 0.0 | 10.0 | 14.44 | 10.96 | mheidari-all | 159.223.157.129 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | 1.0 | 113 | 144 | prefer |
| Au1rxx-base64 | 0.996 | 0.924 | 490 | 1821 | prefer |
| Surfboard-tg-mixed | 0.891 | 0.815 | 146 | 6303 | prefer |
| mheidari-all | 0.631 | 0.552 | 105 | 14434 | observe |
| DeltaKronecker-all | 0.51 | 0.429 | 105 | 5288 | observe |
| nscl5-all | 0.483 | 1.0 | 5 | 1082 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 131 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4989 | observe |
| Epodonios-all | 0.255 | None | 0 | 6860 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3989 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7111 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5154 | observe |
| barry-far-vless | 0.255 | None | 0 | 5430 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4094 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 66 |
| speed | TimeoutError | - | 30 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 20 |
| speed | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 6 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
