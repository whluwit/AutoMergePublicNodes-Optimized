# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-05 14:00:15 |
| 运行耗时 | 215.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86793 |
| 去重后节点 | 24110 |
| TCP 可达 | 3000 |
| 真实可用 | 494 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24110 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 35.4 |
| probe | 46.2 |
| real_test | 92.0 |
| generate | 33.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51340 |
| vmess | 13076 |
| trojan | 10675 |
| shadowsocks | 10122 |
| hysteria2 | 1337 |
| socks | 77 |
| shadowsocksr | 73 |
| http | 39 |
| anytls | 21 |
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
| 83.76 | hysteria2 | 236.4 | 641.3 | 22.31 | 0.0 | 9.08 | 13.57 | 19.9 | Au1rxx-base64 | 159.223.157.129 |
| 83.52 | hysteria2 | 250.3 | 684.4 | 21.98 | 0.0 | 9.07 | 13.57 | 19.9 | Au1rxx-base64 | 138.124.68.188 |
| 83.16 | hysteria2 | 251.4 | 673.1 | 21.96 | 0.0 | 8.73 | 13.57 | 19.9 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.2 | vless | 241.3 | 674.4 | 22.19 | 0.0 | 10.0 | 9.11 | 19.9 | Au1rxx-base64 | 47.253.226.114 |
| 80.84 | shadowsocks | 228.7 | 629.7 | 22.48 | 0.0 | 9.17 | 13.29 | 19.9 | Au1rxx-base64 | 37.19.198.244 |
| 80.7 | shadowsocks | 235.5 | 646.6 | 22.33 | 0.0 | 9.18 | 13.29 | 19.9 | Au1rxx-base64 | 37.19.198.236 |
| 80.48 | shadowsocks | 244.2 | 678.0 | 22.12 | 0.0 | 9.17 | 13.29 | 19.9 | Au1rxx-base64 | 37.19.198.160 |
| 78.53 | vless | 309.1 | 826.6 | 20.62 | 0.0 | 10.0 | 9.11 | 19.9 | Au1rxx-base64 | 45.138.100.226 |
| 78.16 | vless | 372.9 | 934.5 | 19.15 | 0.0 | 10.0 | 9.11 | 19.9 | Au1rxx-base64 | 169.40.42.95 |
| 77.64 | shadowsocks | 284.8 | 655.7 | 21.19 | 0.0 | 9.16 | 13.29 | 19.9 | Au1rxx-base64 | 156.146.38.170 |
| 77.05 | shadowsocks | 272.1 | 626.0 | 21.48 | 0.0 | 9.16 | 13.29 | 19.9 | Au1rxx-base64 | 156.146.38.169 |
| 77.0 | shadowsocks | 287.2 | 666.9 | 21.13 | 0.0 | 9.17 | 13.29 | 19.9 | Au1rxx-base64 | 156.146.38.168 |
| 76.97 | vless | 336.4 | 613.5 | 19.99 | 0.0 | 10.0 | 9.11 | 19.9 | Au1rxx-base64 | 104.17.3.81 |
| 76.88 | shadowsocks | 378.4 | 980.4 | 19.02 | 0.0 | 9.17 | 13.29 | 19.9 | Au1rxx-base64 | 68.168.222.210 |
| 76.5 | vless | 356.6 | 915.2 | 19.52 | 0.0 | 10.0 | 9.11 | 19.9 | Au1rxx-base64 | 169.40.42.15 |
| 76.32 | shadowsocks | 278.3 | 628.2 | 21.34 | 0.0 | 9.17 | 13.29 | 19.9 | Au1rxx-base64 | 156.146.38.167 |
| 76.06 | vless | 290.6 | 627.2 | 21.05 | 0.0 | 10.0 | 9.11 | 19.9 | Au1rxx-base64 | 104.16.117.43 |
| 75.96 | vless | 403.8 | 1058.3 | 18.43 | 0.0 | 10.0 | 9.11 | 19.9 | Au1rxx-base64 | 158.69.112.254 |
| 75.82 | shadowsocks | 316.3 | 891.3 | 20.46 | 0.0 | 9.17 | 13.29 | 19.9 | Au1rxx-base64 | 37.19.198.243 |
| 75.63 | vless | 338.8 | 642.3 | 19.93 | 0.0 | 10.0 | 9.11 | 19.9 | Au1rxx-base64 | 162.159.0.8 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.989 | 0.929 | 409 | 1544 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.698 | 0.62 | 129 | 5783 | observe |
| mheidari-all | 0.541 | 0.474 | 19 | 20132 | observe |
| DeltaKronecker-all | 0.337 | 0.429 | 7 | 5316 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 4655 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5260 | observe |
| Epodonios-all | 0.255 | None | 0 | 6386 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7119 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4628 | observe |
| barry-far-vless | 0.255 | None | 0 | 4943 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5147 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 14 |
| speed | TimeoutError | - | 11 |
| 204 | ProxyError | - | 9 |
| geo | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
