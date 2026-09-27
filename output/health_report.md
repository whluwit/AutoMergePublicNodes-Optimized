# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 03:31:01 |
| 运行耗时 | 781.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 95995 |
| 去重后节点 | 26622 |
| TCP 可达 | 3000 |
| 真实可用 | 522 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26622 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.5 |
| tcp | 43.4 |
| probe | 279.0 |
| real_test | 380.3 |
| generate | 71.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58459 |
| vmess | 14870 |
| shadowsocks | 11284 |
| trojan | 9001 |
| hysteria2 | 1406 |
| http | 677 |
| shadowsocksr | 171 |
| socks | 79 |
| anytls | 26 |
| hysteria | 15 |
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
| 82.58 | vless | 198.8 | 525.8 | 23.18 | 0.0 | 9.32 | 11.18 | 18.9 | Au1rxx-base64 | 192.3.247.109 |
| 82.45 | vless | 200.6 | 526.6 | 23.14 | 0.0 | 9.23 | 11.18 | 18.9 | Au1rxx-base64 | 172.235.43.210 |
| 82.27 | vless | 211.0 | 529.3 | 22.89 | 0.0 | 9.3 | 11.18 | 18.9 | Au1rxx-base64 | 195.123.240.65 |
| 79.1 | vless | 346.8 | 890.3 | 19.75 | 0.0 | 9.27 | 11.18 | 18.9 | Au1rxx-base64 | 137.175.82.40 |
| 78.76 | vless | 302.5 | 710.4 | 20.78 | 0.0 | 9.34 | 11.18 | 18.9 | Au1rxx-base64 | 5.78.159.214 |
| 78.5 | vless | 272.9 | 604.0 | 21.46 | 0.0 | 9.3 | 11.18 | 18.9 | Au1rxx-base64 | 15.204.97.216 |
| 78.02 | vless | 234.1 | 590.3 | 22.36 | 0.0 | 9.27 | 11.18 | 18.9 | Au1rxx-base64 | 38.244.20.25 |
| 77.06 | vless | 321.6 | 735.5 | 20.33 | 0.0 | 9.24 | 11.18 | 18.9 | Au1rxx-base64 | 79.141.172.154 |
| 75.77 | vless | 258.9 | 490.0 | 21.78 | 0.0 | 9.3 | 11.18 | 18.9 | Au1rxx-base64 | 104.18.46.234 |
| 75.72 | vless | 276.3 | 439.0 | 21.38 | 0.0 | 9.27 | 11.18 | 18.9 | Au1rxx-base64 | 162.159.0.169 |
| 75.57 | shadowsocks | 228.4 | 541.1 | 22.49 | 0.0 | 10.0 | 12.38 | 14.7 | Surfboard-tg-mixed | 173.244.56.6 |
| 75.2 | shadowsocks | 222.9 | 510.8 | 22.62 | 0.0 | 10.0 | 12.38 | 14.7 | Surfboard-tg-mixed | 108.181.0.177 |
| 75.01 | shadowsocks | 252.7 | 621.1 | 21.93 | 0.0 | 10.0 | 12.38 | 14.7 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.87 | shadowsocks | 237.0 | 521.6 | 22.29 | 0.0 | 10.0 | 12.38 | 14.7 | Surfboard-tg-mixed | 108.181.118.10 |
| 74.53 | trojan | 245.3 | 535.6 | 22.1 | 0.0 | 10.0 | 12.35 | 13.24 | mheidari-all | 100.42.228.109 |
| 74.27 | vless | 355.5 | 874.4 | 19.55 | 0.0 | 9.3 | 11.18 | 18.9 | Au1rxx-base64 | 23.95.222.127 |
| 74.15 | shadowsocks | 205.3 | 522.2 | 23.03 | 0.0 | 10.0 | 12.38 | 13.24 | mheidari-all | 192.3.247.109 |
| 73.64 | hysteria2 | 270.1 | 338.4 | 21.52 | 2.31 | 8.07 | 9.81 | 18.9 | Au1rxx-base64 | open.w2m.ink |
| 73.5 | trojan | 318.4 | 876.9 | 20.41 | 0.0 | 10.0 | 12.35 | 13.24 | mheidari-all | 34.94.125.227 |
| 73.27 | shadowsocks | 264.8 | 640.9 | 21.65 | 0.0 | 10.0 | 12.38 | 13.24 | mheidari-all | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.916 | 0.854 | 280 | 1632 | prefer |
| Surfboard-tg-mixed | 0.824 | 0.747 | 217 | 7113 | prefer |
| ermaozi | 0.778 | 0.781 | 32 | 338 | prefer |
| ermaozi-get_subscribe | 0.423 | 0.833 | 6 | 361 | observe |
| mheidari-all | 0.377 | 0.295 | 288 | 22408 | observe |
| DeltaKronecker-all | 0.373 | 0.6 | 5 | 5512 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 149 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7583 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8903 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5686 | observe |
| barry-far-vless | 0.255 | None | 0 | 5907 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 136 |
| speed | TimeoutError | - | 46 |
| geo | ClientOSError | - | 33 |
| speed | ClientOSError | - | 32 |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 15 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
