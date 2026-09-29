# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-29 18:09:32 |
| 运行耗时 | 490.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96917 |
| 去重后节点 | 27000 |
| TCP 可达 | 3000 |
| 真实可用 | 328 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27000 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 45.8 |
| probe | 202.0 |
| real_test | 143.4 |
| generate | 90.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59019 |
| vmess | 15161 |
| shadowsocks | 11353 |
| trojan | 9093 |
| hysteria2 | 1414 |
| http | 584 |
| shadowsocksr | 168 |
| socks | 78 |
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
| 79.59 | hysteria2 | 303.3 | 738.2 | 20.76 | 0.0 | 9.63 | 13.27 | 18.06 | Au1rxx-base64 | 192.255.128.123 |
| 79.22 | shadowsocks | 245.9 | 616.8 | 22.09 | 0.0 | 9.74 | 13.33 | 18.06 | Au1rxx-base64 | 156.146.38.168 |
| 77.37 | vless | 276.8 | 608.5 | 21.37 | 0.0 | 10.0 | 10.62 | 18.06 | Au1rxx-base64 | 15.204.97.216 |
| 77.13 | vless | 244.3 | 524.5 | 22.12 | 0.0 | 10.0 | 10.62 | 16.78 | mheidari-all | 47.251.108.158 |
| 76.81 | hysteria2 | 280.9 | 310.7 | 21.28 | 3.35 | 8.33 | 13.27 | 18.06 | Au1rxx-base64 | open.w2m.ink |
| 76.52 | vless | 279.4 | 599.1 | 21.31 | 0.0 | 10.0 | 10.62 | 18.06 | Au1rxx-base64 | 195.123.240.65 |
| 76.23 | vless | 275.7 | 665.8 | 21.4 | 0.0 | 10.0 | 10.62 | 16.78 | mheidari-all | 216.227.161.95 |
| 76.22 | vless | 276.1 | 579.0 | 21.39 | 0.0 | 9.67 | 10.62 | 18.06 | Au1rxx-base64 | 172.235.43.210 |
| 76.05 | shadowsocks | 243.5 | 617.3 | 22.14 | 0.0 | 10.0 | 13.33 | 14.58 | Surfboard-tg-mixed | 156.146.38.169 |
| 76.05 | shadowsocks | 243.7 | 628.9 | 22.14 | 0.0 | 10.0 | 13.33 | 14.58 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.02 | shadowsocks | 245.0 | 623.0 | 22.11 | 0.0 | 10.0 | 13.33 | 14.58 | Surfboard-tg-mixed | 156.146.38.170 |
| 75.45 | vless | 296.2 | 553.3 | 20.92 | 0.0 | 9.69 | 10.62 | 18.06 | Au1rxx-base64 | 137.175.82.40 |
| 75.24 | shadowsocks | 255.3 | 558.0 | 21.87 | 0.0 | 10.0 | 13.33 | 16.78 | mheidari-all | 192.3.247.109 |
| 74.53 | vless | 305.5 | 580.8 | 20.71 | 0.0 | 9.76 | 10.62 | 18.06 | Au1rxx-base64 | 23.95.222.127 |
| 74.37 | hysteria2 | 369.1 | 888.6 | 19.23 | 0.0 | 10.0 | 13.27 | 16.78 | mheidari-all | 159.223.157.129 |
| 73.82 | vless | 309.1 | 716.0 | 20.62 | 0.0 | 9.69 | 10.62 | 18.06 | Au1rxx-base64 | 79.141.172.154 |
| 73.79 | shadowsocks | 271.7 | 572.6 | 21.49 | 0.0 | 10.0 | 13.33 | 16.78 | mheidari-all | 173.244.56.6 |
| 73.73 | vless | 346.4 | 777.7 | 19.76 | 0.0 | 9.72 | 10.62 | 18.06 | Au1rxx-base64 | 47.90.153.88 |
| 73.59 | shadowsocks | 277.2 | 588.0 | 21.36 | 0.0 | 10.0 | 13.33 | 16.78 | mheidari-all | 173.244.56.9 |
| 73.54 | shadowsocks | 318.4 | 674.4 | 20.41 | 0.0 | 9.69 | 13.33 | 18.06 | Au1rxx-base64 | 108.181.118.10 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.875 | 0.889 | 18 | 7053 | prefer |
| Au1rxx-base64 | 0.864 | 0.799 | 288 | 1683 | prefer |
| mheidari-all | 0.856 | 0.783 | 83 | 22753 | prefer |
| ermaozi | 0.553 | 0.545 | 22 | 291 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 5528 | observe |
| ermaozi-get_subscribe | 0.323 | 1.0 | 2 | 293 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5314 | observe |
| Epodonios-all | 0.255 | None | 0 | 7546 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9402 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5690 | observe |
| barry-far-vless | 0.255 | None | 0 | 5930 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 23 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 14 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 8 |
| 204 | ProxyConnectionError | - | 5 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
