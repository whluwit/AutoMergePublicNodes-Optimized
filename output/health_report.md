# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 10:33:31 |
| 运行耗时 | 309.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91316 |
| 去重后节点 | 25264 |
| TCP 可达 | 3000 |
| 真实可用 | 568 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25264 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.4 |
| tcp | 42.7 |
| probe | 86.9 |
| real_test | 126.5 |
| generate | 45.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57075 |
| vmess | 12449 |
| shadowsocks | 10277 |
| trojan | 8993 |
| hysteria2 | 1800 |
| http | 502 |
| shadowsocksr | 128 |
| socks | 54 |
| hysteria | 16 |
| tuic | 11 |
| anytls | 11 |

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
| 83.99 | hysteria2 | 239.5 | 650.3 | 22.23 | 0.0 | 10.0 | 14.38 | 18.48 | Surfboard-tg-mixed | 159.223.157.129 |
| 80.91 | shadowsocks | 233.9 | 638.8 | 22.36 | 0.0 | 10.0 | 14.07 | 18.48 | Surfboard-tg-mixed | 37.19.198.160 |
| 80.89 | shadowsocks | 234.9 | 646.3 | 22.34 | 0.0 | 10.0 | 14.07 | 18.48 | Surfboard-tg-mixed | 37.19.198.236 |
| 80.65 | shadowsocks | 245.2 | 678.2 | 22.1 | 0.0 | 10.0 | 14.07 | 18.48 | Surfboard-tg-mixed | 37.19.198.244 |
| 78.02 | http | 298.5 | 815.9 | 20.87 | 0.0 | 10.0 | 14.75 | 19.9 | ermaozi | 147.182.216.4 |
| 77.63 | shadowsocks | 354.0 | 907.1 | 19.58 | 0.0 | 10.0 | 14.07 | 18.48 | Surfboard-tg-mixed | 51.79.64.198 |
| 77.54 | shadowsocks | 357.8 | 938.6 | 19.49 | 0.0 | 10.0 | 14.07 | 18.48 | Surfboard-tg-mixed | 51.222.200.165 |
| 77.31 | vless | 250.0 | 666.5 | 21.99 | 0.0 | 10.0 | 6.3 | 19.02 | Au1rxx-base64 | 195.123.235.177 |
| 77.3 | shadowsocks | 368.5 | 966.3 | 19.25 | 0.0 | 10.0 | 14.07 | 18.48 | Surfboard-tg-mixed | 51.222.155.113 |
| 77.29 | vless | 250.9 | 664.3 | 21.97 | 0.0 | 10.0 | 6.3 | 19.02 | Au1rxx-base64 | 169.40.42.15 |
| 76.95 | vless | 265.6 | 698.0 | 21.63 | 0.0 | 10.0 | 6.3 | 19.02 | Au1rxx-base64 | 169.40.42.212 |
| 76.95 | shadowsocks | 367.6 | 990.9 | 19.27 | 0.0 | 9.09 | 14.07 | 19.02 | Au1rxx-base64 | 38.180.135.156 |
| 76.93 | vless | 266.5 | 645.3 | 21.61 | 0.0 | 10.0 | 6.3 | 19.02 | Au1rxx-base64 | 169.40.42.104 |
| 76.78 | shadowsocks | 370.2 | 1064.3 | 19.21 | 0.0 | 8.98 | 14.07 | 19.02 | Au1rxx-base64 | 15.204.246.189 |
| 76.53 | vless | 269.8 | 653.5 | 21.53 | 0.0 | 10.0 | 6.3 | 19.02 | Au1rxx-base64 | 169.40.42.52 |
| 76.47 | shadowsocks | 284.6 | 643.5 | 21.19 | 0.0 | 10.0 | 14.07 | 18.48 | Surfboard-tg-mixed | 23.150.248.20 |
| 76.38 | vless | 250.5 | 652.6 | 21.98 | 0.0 | 9.08 | 6.3 | 19.02 | Au1rxx-base64 | 169.40.42.35 |
| 76.36 | shadowsocks | 345.8 | 973.2 | 19.77 | 0.0 | 10.0 | 14.07 | 19.02 | Au1rxx-base64 | 15.204.246.108 |
| 76.19 | shadowsocks | 222.0 | 594.8 | 22.64 | 0.0 | 10.0 | 14.07 | 18.48 | Surfboard-tg-mixed | 198.98.53.130 |
| 76.09 | vless | 302.8 | 749.1 | 20.77 | 0.0 | 10.0 | 6.3 | 19.02 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.982 | 0.981 | 54 | 450 | prefer |
| Au1rxx-base64 | 0.935 | 0.869 | 327 | 1726 | prefer |
| ermaozi-get_subscribe | 0.894 | 0.947 | 19 | 470 | prefer |
| Surfboard-tg-mixed | 0.852 | 0.775 | 178 | 7431 | prefer |
| mheidari-all | 0.755 | 0.679 | 78 | 22334 | prefer |
| DeltaKronecker-all | 0.605 | 0.526 | 38 | 6097 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 212 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| Epodonios-all | 0.255 | None | 0 | 7885 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8811 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6201 | observe |
| barry-far-vless | 0.255 | None | 0 | 6423 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4209 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 23 |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 21 |
| speed | TimeoutError | - | 19 |
| 204 | ProxyError | - | 13 |
| cn-block | ClientOSError | - | 11 |
| geo | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
