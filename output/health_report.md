# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 20:54:31 |
| 运行耗时 | 551.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 95925 |
| 去重后节点 | 26706 |
| TCP 可达 | 3000 |
| 真实可用 | 368 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26706 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 44.1 |
| probe | 236.1 |
| real_test | 181.2 |
| generate | 81.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58530 |
| vmess | 14862 |
| shadowsocks | 11297 |
| trojan | 8909 |
| hysteria2 | 1468 |
| http | 573 |
| shadowsocksr | 170 |
| socks | 69 |
| anytls | 24 |
| hysteria | 15 |
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
| 81.24 | vless | 217.0 | 560.6 | 22.76 | 0.0 | 9.19 | 11.49 | 17.8 | Au1rxx-base64 | 15.204.97.216 |
| 80.13 | vless | 234.4 | 523.2 | 22.35 | 0.0 | 9.13 | 11.49 | 17.8 | Au1rxx-base64 | 137.175.82.40 |
| 79.99 | vless | 268.8 | 733.2 | 21.56 | 0.0 | 9.14 | 11.49 | 17.8 | Au1rxx-base64 | 5.78.159.214 |
| 79.07 | shadowsocks | 214.4 | 570.5 | 22.81 | 0.0 | 10.0 | 13.1 | 17.16 | mheidari-all | 149.22.95.183 |
| 79.05 | shadowsocks | 216.4 | 587.3 | 22.77 | 0.0 | 10.0 | 13.1 | 17.68 | Surfboard-tg-mixed | 5.78.51.123 |
| 78.88 | vless | 253.2 | 563.8 | 21.92 | 0.0 | 9.38 | 11.49 | 17.8 | Au1rxx-base64 | 192.3.247.109 |
| 78.59 | vless | 255.3 | 551.7 | 21.87 | 0.0 | 9.07 | 11.49 | 17.8 | Au1rxx-base64 | 23.95.222.127 |
| 77.49 | vless | 266.7 | 586.4 | 21.6 | 0.0 | 9.07 | 11.49 | 17.8 | Au1rxx-base64 | 172.235.43.210 |
| 77.41 | vless | 377.3 | 942.2 | 19.04 | 0.0 | 9.08 | 11.49 | 17.8 | Au1rxx-base64 | 51.81.203.63 |
| 77.36 | shadowsocks | 242.5 | 559.3 | 22.16 | 0.0 | 10.0 | 13.1 | 17.68 | Surfboard-tg-mixed | 192.3.247.109 |
| 76.81 | vless | 273.8 | 584.1 | 21.44 | 0.0 | 9.13 | 11.49 | 17.8 | Au1rxx-base64 | 195.123.240.65 |
| 74.51 | vless | 313.4 | 321.2 | 20.52 | 2.96 | 9.03 | 11.49 | 17.8 | Au1rxx-base64 | 43.133.11.187 |
| 74.08 | vless | 316.9 | 333.5 | 20.44 | 2.49 | 9.16 | 11.49 | 17.8 | Au1rxx-base64 | 18.183.215.124 |
| 73.99 | vless | 351.8 | 772.1 | 19.63 | 0.0 | 9.07 | 11.49 | 17.8 | Au1rxx-base64 | 79.141.172.154 |
| 73.55 | shadowsocks | 280.4 | 583.0 | 21.29 | 0.0 | 10.0 | 13.1 | 17.16 | mheidari-all | 173.244.56.9 |
| 73.43 | shadowsocks | 311.6 | 701.0 | 20.56 | 0.0 | 10.0 | 13.1 | 17.16 | mheidari-all | 108.181.118.10 |
| 73.31 | vless | 345.8 | 695.7 | 19.77 | 0.0 | 9.09 | 11.49 | 17.8 | Au1rxx-base64 | 195.211.98.43 |
| 73.04 | shadowsocks | 277.0 | 327.0 | 21.37 | 2.74 | 9.06 | 13.1 | 17.8 | Au1rxx-base64 | 149.22.87.240 |
| 72.61 | shadowsocks | 320.9 | 683.2 | 20.35 | 0.0 | 10.0 | 13.1 | 17.68 | Surfboard-tg-mixed | 156.146.38.167 |
| 72.15 | vless | 382.0 | 754.1 | 18.93 | 0.0 | 9.05 | 11.49 | 17.8 | Au1rxx-base64 | 198.251.78.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.955 | 0.883 | 94 | 22680 | prefer |
| Au1rxx-base64 | 0.869 | 0.806 | 242 | 1652 | prefer |
| Surfboard-tg-mixed | 0.783 | 0.708 | 89 | 7039 | prefer |
| ermaozi | 0.633 | 0.629 | 35 | 289 | observe |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 5466 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
| ermaozi-get_subscribe | 0.267 | 1.0 | 1 | 299 | observe |
| tg-oneclickvpnkeys | 0.256 | 1.0 | 1 | 13 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7540 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9014 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5608 | observe |
| barry-far-vless | 0.255 | None | 0 | 5845 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4185 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 14 |
| geo | TimeoutError | - | 14 |
| speed | ClientOSError | - | 13 |
| 204 | ProxyError | - | 11 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
