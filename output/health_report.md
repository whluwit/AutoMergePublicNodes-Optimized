# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 02:37:40 |
| 运行耗时 | 337.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 93994 |
| 去重后节点 | 24749 |
| TCP 可达 | 3000 |
| 真实可用 | 630 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24749 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 42.0 |
| probe | 77.9 |
| real_test | 173.3 |
| generate | 38.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58594 |
| vmess | 12707 |
| shadowsocks | 11224 |
| trojan | 9059 |
| hysteria2 | 2025 |
| http | 136 |
| shadowsocksr | 126 |
| socks | 61 |
| anytls | 29 |
| hysteria | 19 |
| tuic | 14 |

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
| 83.17 | hysteria2 | 251.5 | 553.4 | 21.96 | 0.0 | 9.97 | 13.93 | 19.32 | Au1rxx-base64 | 66.94.121.46 |
| 80.23 | vless | 310.2 | 742.2 | 20.6 | 0.0 | 10.0 | 10.68 | 19.32 | Au1rxx-base64 | 38.180.242.205 |
| 78.4 | shadowsocks | 245.1 | 647.5 | 22.1 | 0.0 | 10.0 | 14.16 | 16.14 | Surfboard-tg-mixed | 156.146.38.170 |
| 78.39 | shadowsocks | 240.4 | 610.2 | 22.21 | 0.0 | 10.0 | 14.16 | 16.14 | Surfboard-tg-mixed | 156.146.38.168 |
| 78.0 | shadowsocks | 250.6 | 625.1 | 21.98 | 0.0 | 10.0 | 14.16 | 16.14 | Surfboard-tg-mixed | 156.146.38.167 |
| 77.21 | trojan | 257.1 | 633.5 | 21.83 | 0.0 | 10.0 | 10.0 | 19.32 | Au1rxx-base64 | 64.94.95.117 |
| 77.19 | trojan | 257.8 | 614.9 | 21.81 | 0.0 | 10.0 | 10.0 | 19.32 | Au1rxx-base64 | 64.94.95.118 |
| 77.16 | vless | 347.8 | 795.4 | 19.73 | 0.0 | 9.99 | 10.68 | 19.32 | Au1rxx-base64 | 169.40.42.16 |
| 76.92 | vless | 289.5 | 603.5 | 21.08 | 0.0 | 10.0 | 10.68 | 19.32 | Au1rxx-base64 | 172.235.43.210 |
| 76.82 | vless | 327.7 | 736.4 | 20.19 | 0.0 | 10.0 | 10.68 | 19.32 | Au1rxx-base64 | 137.184.218.169 |
| 76.8 | vless | 349.8 | 790.7 | 19.68 | 0.0 | 10.0 | 10.68 | 19.32 | Au1rxx-base64 | 169.40.42.212 |
| 76.68 | shadowsocks | 302.8 | 730.4 | 20.77 | 0.0 | 10.0 | 14.16 | 16.14 | Surfboard-tg-mixed | 37.19.198.243 |
| 76.63 | vless | 287.1 | 585.1 | 21.13 | 0.0 | 9.98 | 10.68 | 19.32 | Au1rxx-base64 | 172.233.139.46 |
| 76.55 | shadowsocks | 279.9 | 669.5 | 21.3 | 0.0 | 10.0 | 14.16 | 16.14 | Surfboard-tg-mixed | 37.19.198.244 |
| 76.22 | vless | 382.1 | 971.5 | 18.93 | 0.0 | 10.0 | 10.68 | 19.32 | Au1rxx-base64 | 216.152.147.28 |
| 76.18 | vless | 317.1 | 594.8 | 20.44 | 0.0 | 9.98 | 10.68 | 19.32 | Au1rxx-base64 | 23.94.227.94 |
| 76.16 | trojan | 256.3 | 638.4 | 21.84 | 0.0 | 10.0 | 10.0 | 19.32 | Au1rxx-base64 | 64.94.95.115 |
| 76.12 | vless | 325.9 | 739.0 | 20.23 | 0.0 | 9.99 | 10.68 | 19.32 | Au1rxx-base64 | 130.94.115.231 |
| 76.11 | vless | 339.2 | 746.9 | 19.93 | 0.0 | 10.0 | 10.68 | 19.32 | Au1rxx-base64 | 66.70.179.198 |
| 75.99 | vless | 389.3 | 851.7 | 18.77 | 0.0 | 10.0 | 10.68 | 19.32 | Au1rxx-base64 | 169.40.42.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.943 | 317 | 1835 | prefer |
| zhangkai | 0.926 | 0.957 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.846 | 0.769 | 216 | 7305 | prefer |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 5750 | observe |
| mheidari-all | 0.373 | 0.292 | 469 | 21249 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 176 | observe |
| Epodonios-all | 0.255 | None | 0 | 7766 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8335 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6046 | observe |
| barry-far-vless | 0.255 | None | 0 | 6261 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1835 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| tg-oneclickvpnkeys | 0.212 | 0.5 | 2 | 121 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 108 |
| cn-block | ClientOSError | - | 80 |
| geo | ClientOSError | - | 73 |
| speed | TimeoutError | - | 70 |
| speed | ClientOSError | - | 33 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 11 |
| 204 | ClientOSError | - | 10 |
| 204 | ProxyError | - | 9 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
