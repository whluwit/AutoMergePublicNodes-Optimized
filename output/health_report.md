# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 20:06:16 |
| 运行耗时 | 543.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91587 |
| 去重后节点 | 25324 |
| TCP 可达 | 3000 |
| 真实可用 | 423 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25324 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 42.6 |
| probe | 237.1 |
| real_test | 154.9 |
| generate | 101.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55100 |
| vmess | 14396 |
| shadowsocks | 11259 |
| trojan | 8793 |
| hysteria2 | 1249 |
| http | 575 |
| shadowsocksr | 129 |
| socks | 66 |
| hysteria | 10 |
| tuic | 5 |
| anytls | 5 |

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
| 80.8 | shadowsocks | 237.1 | 598.1 | 22.29 | 0.0 | 10.0 | 13.73 | 18.78 | Au1rxx-base64 | 156.146.38.170 |
| 77.94 | vless | 311.4 | 735.2 | 20.57 | 0.0 | 10.0 | 10.08 | 18.78 | Au1rxx-base64 | 79.141.172.154 |
| 76.28 | vless | 305.5 | 676.2 | 20.71 | 0.0 | 10.0 | 10.08 | 18.78 | Au1rxx-base64 | 172.235.43.210 |
| 75.92 | vless | 365.6 | 885.4 | 19.32 | 0.0 | 10.0 | 10.08 | 18.78 | Au1rxx-base64 | 15.204.97.216 |
| 75.47 | vless | 344.5 | 551.0 | 19.8 | 0.0 | 10.0 | 10.08 | 18.78 | Au1rxx-base64 | 38.180.242.205 |
| 75.25 | hysteria2 | 321.9 | 734.2 | 20.33 | 0.0 | 10.0 | 14.17 | 13.96 | mheidari-all | 159.223.157.129 |
| 75.05 | vless | 327.7 | 714.4 | 20.19 | 0.0 | 10.0 | 10.08 | 18.78 | Au1rxx-base64 | 198.251.78.29 |
| 74.82 | shadowsocks | 329.8 | 742.7 | 20.14 | 0.0 | 10.0 | 13.73 | 18.78 | Au1rxx-base64 | 37.19.198.244 |
| 74.8 | shadowsocks | 323.2 | 708.8 | 20.3 | 0.0 | 10.0 | 13.73 | 18.78 | Au1rxx-base64 | 37.19.198.236 |
| 74.51 | shadowsocks | 320.6 | 704.0 | 20.36 | 0.0 | 10.0 | 13.73 | 18.78 | Au1rxx-base64 | 173.244.56.6 |
| 74.3 | shadowsocks | 335.3 | 751.6 | 20.02 | 0.0 | 10.0 | 13.73 | 18.78 | Au1rxx-base64 | 37.19.198.160 |
| 74.26 | shadowsocks | 364.8 | 849.3 | 19.33 | 0.0 | 10.0 | 13.73 | 18.78 | Au1rxx-base64 | 198.98.53.130 |
| 73.67 | shadowsocks | 260.0 | 610.2 | 21.76 | 0.0 | 10.0 | 13.73 | 12.68 | Surfboard-tg-mixed | 23.150.248.20 |
| 73.58 | vless | 399.6 | 929.2 | 18.53 | 0.0 | 10.0 | 10.08 | 18.78 | Au1rxx-base64 | 216.152.147.28 |
| 73.57 | vless | 257.8 | 589.3 | 21.81 | 0.0 | 10.0 | 10.08 | 13.96 | mheidari-all | 47.251.108.158 |
| 73.34 | shadowsocks | 344.5 | 750.6 | 19.8 | 0.0 | 10.0 | 13.73 | 18.78 | Au1rxx-base64 | 173.244.56.9 |
| 73.31 | vless | 324.7 | 649.3 | 20.26 | 0.0 | 10.0 | 10.08 | 18.78 | Au1rxx-base64 | 198.200.42.129 |
| 73.07 | shadowsocks | 242.9 | 621.2 | 22.15 | 0.0 | 10.0 | 13.73 | 18.78 | Au1rxx-base64 | 156.146.38.168 |
| 72.61 | shadowsocks | 360.9 | 710.6 | 19.42 | 0.0 | 10.0 | 13.73 | 18.78 | Au1rxx-base64 | 108.181.57.93 |
| 72.43 | vless | 431.3 | 1078.5 | 17.79 | 0.0 | 10.0 | 10.08 | 18.78 | Au1rxx-base64 | 15.204.97.214 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.953 | 0.89 | 300 | 1650 | prefer |
| Surfboard-tg-mixed | 0.701 | 0.623 | 114 | 7303 | prefer |
| mheidari-all | 0.623 | 0.544 | 125 | 19269 | observe |
| ermaozi | 0.554 | 0.818 | 11 | 250 | observe |
| DeltaKronecker-all | 0.407 | 0.455 | 11 | 6421 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5174 | observe |
| Epodonios-all | 0.255 | None | 0 | 7761 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9227 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5863 | observe |
| barry-far-vless | 0.255 | None | 0 | 6077 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3625 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 38 |
| 204 | TimeoutError | - | 25 |
| cn-block | ClientOSError | - | 22 |
| geo | TimeoutError | - | 18 |
| speed | ClientOSError | - | 12 |
| 204 | ProxyError | - | 10 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
