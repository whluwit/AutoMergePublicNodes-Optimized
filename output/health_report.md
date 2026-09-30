# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-30 03:57:03 |
| 运行耗时 | 986.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96898 |
| 去重后节点 | 27022 |
| TCP 可达 | 3000 |
| 真实可用 | 444 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27022 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.5 |
| tcp | 45.9 |
| probe | 340.3 |
| real_test | 506.6 |
| generate | 85.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58777 |
| vmess | 15054 |
| shadowsocks | 11341 |
| trojan | 9335 |
| hysteria2 | 1448 |
| http | 642 |
| shadowsocksr | 166 |
| socks | 75 |
| anytls | 37 |
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
| 80.04 | vless | 266.5 | 640.0 | 21.61 | 0.0 | 10.0 | 11.31 | 17.12 | mheidari-all | 216.227.161.95 |
| 79.21 | hysteria2 | 245.7 | 549.9 | 22.09 | 0.0 | 8.6 | 13.75 | 17.28 | Au1rxx-base64 | 192.255.128.123 |
| 78.84 | vless | 238.9 | 507.6 | 22.25 | 0.0 | 10.0 | 11.31 | 17.12 | mheidari-all | 47.251.108.158 |
| 77.49 | vless | 267.8 | 569.3 | 21.58 | 0.0 | 10.0 | 11.31 | 17.28 | Au1rxx-base64 | 192.3.247.109 |
| 77.12 | shadowsocks | 236.7 | 610.1 | 22.3 | 0.0 | 8.63 | 12.91 | 17.28 | Au1rxx-base64 | 156.146.38.168 |
| 77.02 | shadowsocks | 241.1 | 613.9 | 22.2 | 0.0 | 8.63 | 12.91 | 17.28 | Au1rxx-base64 | 156.146.38.167 |
| 76.97 | shadowsocks | 243.1 | 627.4 | 22.15 | 0.0 | 8.63 | 12.91 | 17.28 | Au1rxx-base64 | 156.146.38.170 |
| 76.95 | shadowsocks | 243.1 | 617.4 | 22.15 | 0.0 | 8.61 | 12.91 | 17.28 | Au1rxx-base64 | 156.146.38.169 |
| 76.57 | vless | 271.5 | 583.0 | 21.49 | 0.0 | 10.0 | 11.31 | 17.28 | Au1rxx-base64 | 172.233.139.46 |
| 76.26 | vless | 304.4 | 738.3 | 20.73 | 0.0 | 8.68 | 11.31 | 17.28 | Au1rxx-base64 | 79.141.172.154 |
| 75.89 | shadowsocks | 305.9 | 750.6 | 20.7 | 0.0 | 10.0 | 12.91 | 17.5 | Surfboard-tg-mixed | 5.78.51.123 |
| 75.48 | vless | 272.3 | 583.4 | 21.48 | 0.0 | 8.63 | 11.31 | 17.28 | Au1rxx-base64 | 172.235.43.210 |
| 75.41 | vless | 299.0 | 675.1 | 20.86 | 0.0 | 8.66 | 11.31 | 17.28 | Au1rxx-base64 | 195.211.98.43 |
| 75.23 | vless | 268.4 | 584.7 | 21.56 | 0.0 | 8.71 | 11.31 | 17.28 | Au1rxx-base64 | 15.204.97.216 |
| 74.84 | vless | 314.6 | 690.2 | 20.5 | 0.0 | 8.68 | 11.31 | 17.28 | Au1rxx-base64 | 198.251.78.29 |
| 74.81 | hysteria2 | 332.9 | 727.8 | 20.07 | 0.0 | 10.0 | 13.75 | 17.28 | Au1rxx-base64 | 159.223.157.129 |
| 73.92 | shadowsocks | 302.5 | 499.7 | 20.78 | 0.0 | 10.0 | 12.91 | 17.12 | mheidari-all | 192.3.247.109 |
| 73.7 | hysteria2 | 270.9 | 213.0 | 21.51 | 7.01 | 6.36 | 13.75 | 17.28 | Au1rxx-base64 | vp3.yysyy.online |
| 73.24 | shadowsocks | 297.1 | 602.9 | 20.9 | 0.0 | 10.0 | 12.91 | 17.5 | Surfboard-tg-mixed | 108.181.0.177 |
| 72.45 | vless | 362.1 | 679.8 | 19.4 | 0.0 | 8.67 | 11.31 | 17.28 | Au1rxx-base64 | 137.175.82.40 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.861 | 0.793 | 294 | 1753 | prefer |
| ermaozi | 0.728 | 0.727 | 33 | 335 | prefer |
| Surfboard-tg-mixed | 0.699 | 0.62 | 137 | 7024 | observe |
| ermaozi-get_subscribe | 0.414 | 1.0 | 4 | 353 | observe |
| DeltaKronecker-all | 0.337 | 0.429 | 7 | 5528 | observe |
| tg-oneclickvpnkeys | 0.314 | 1.0 | 2 | 62 | observe |
| mheidari-all | 0.295 | 0.214 | 430 | 22586 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5314 | observe |
| Epodonios-all | 0.255 | None | 0 | 7591 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9347 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5656 | observe |
| barry-far-vless | 0.255 | None | 0 | 5895 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 182 |
| speed | TimeoutError | - | 87 |
| speed | ClientOSError | - | 74 |
| geo | ClientOSError | - | 58 |
| 204 | TimeoutError | - | 22 |
| 204 | ProxyError | - | 15 |
| cn-block | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
