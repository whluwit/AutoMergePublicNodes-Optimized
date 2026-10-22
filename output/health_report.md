# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 21:17:19 |
| 运行耗时 | 583.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96202 |
| 去重后节点 | 26677 |
| TCP 可达 | 3000 |
| 真实可用 | 331 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26677 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.5 |
| tcp | 44.5 |
| probe | 250.0 |
| real_test | 203.5 |
| generate | 78.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57006 |
| vmess | 17172 |
| shadowsocks | 12341 |
| trojan | 7863 |
| hysteria2 | 1364 |
| http | 298 |
| socks | 58 |
| shadowsocksr | 55 |
| anytls | 22 |
| hysteria | 17 |
| tuic | 6 |

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
| 80.13 | hysteria2 | 301.9 | 751.4 | 20.79 | 0.0 | 10.0 | 14.0 | 16.84 | Au1rxx-base64 | 129.213.91.185 |
| 78.83 | shadowsocks | 252.6 | 652.7 | 21.93 | 0.0 | 10.0 | 13.2 | 18.74 | mheidari-all | 156.146.38.168 |
| 78.8 | hysteria2 | 304.2 | 714.5 | 20.74 | 0.0 | 9.22 | 14.0 | 16.84 | Au1rxx-base64 | clash2.deep-links.com |
| 77.8 | shadowsocks | 246.8 | 617.5 | 22.06 | 0.0 | 9.7 | 13.2 | 16.84 | Au1rxx-base64 | 156.146.38.169 |
| 77.6 | shadowsocks | 255.0 | 624.8 | 21.87 | 0.0 | 9.69 | 13.2 | 16.84 | Au1rxx-base64 | 156.146.38.170 |
| 77.0 | shadowsocks | 282.2 | 696.7 | 21.25 | 0.0 | 9.71 | 13.2 | 16.84 | Au1rxx-base64 | 156.146.38.167 |
| 76.3 | shadowsocks | 300.8 | 723.7 | 20.82 | 0.0 | 10.0 | 13.2 | 16.84 | Au1rxx-base64 | 37.19.198.243 |
| 75.34 | shadowsocks | 303.2 | 736.8 | 20.76 | 0.0 | 9.68 | 13.2 | 16.84 | Au1rxx-base64 | 37.19.198.236 |
| 75.25 | shadowsocks | 284.9 | 692.9 | 21.18 | 0.0 | 9.7 | 13.2 | 16.84 | Au1rxx-base64 | 185.215.132.18 |
| 75.19 | shadowsocks | 296.4 | 714.9 | 20.92 | 0.0 | 9.69 | 13.2 | 16.84 | Au1rxx-base64 | 37.19.198.160 |
| 74.33 | shadowsocks | 307.1 | 725.0 | 20.67 | 0.0 | 9.7 | 13.2 | 16.84 | Au1rxx-base64 | 185.230.230.18 |
| 74.3 | vless | 271.8 | 619.6 | 21.49 | 0.0 | 10.0 | 9.47 | 18.74 | mheidari-all | 216.227.161.95 |
| 73.78 | vless | 280.9 | 552.1 | 21.27 | 0.0 | 10.0 | 9.47 | 16.84 | Au1rxx-base64 | 45.76.172.197 |
| 73.29 | shadowsocks | 355.3 | 843.2 | 19.55 | 0.0 | 9.68 | 13.2 | 16.84 | Au1rxx-base64 | 193.151.163.18 |
| 73.01 | vless | 371.2 | 787.6 | 19.18 | 0.0 | 10.0 | 9.47 | 16.84 | Au1rxx-base64 | 169.40.42.224 |
| 73.0 | vless | 284.4 | 666.1 | 21.19 | 0.0 | 10.0 | 9.47 | 16.84 | Au1rxx-base64 | 69.48.201.136 |
| 72.8 | vless | 274.2 | 655.5 | 21.43 | 0.0 | 10.0 | 9.47 | 16.84 | Au1rxx-base64 | uspanel.unixzone.us |
| 72.73 | shadowsocks | 375.2 | 943.1 | 19.09 | 0.0 | 9.68 | 13.2 | 16.84 | Au1rxx-base64 | 45.86.51.18 |
| 72.7 | hysteria2 | 373.4 | 338.0 | 19.13 | 2.32 | 9.02 | 14.0 | 16.84 | Au1rxx-base64 | 38.175.202.26 |
| 72.03 | vless | 410.5 | 911.3 | 18.28 | 0.0 | 10.0 | 9.47 | 16.84 | Au1rxx-base64 | 169.40.42.74 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.887 | 0.815 | 81 | 23896 | prefer |
| Au1rxx-base64 | 0.856 | 0.795 | 264 | 1575 | prefer |
| Surfboard-tg-mixed | 0.82 | 0.75 | 48 | 7066 | prefer |
| ermaozi | 0.48 | 0.455 | 33 | 573 | observe |
| DeltaKronecker-all | 0.314 | 0.333 | 9 | 3641 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7550 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10034 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5426 | observe |
| barry-far-vless | 0.255 | None | 0 | 5640 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4176 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyError | - | 17 |
| speed | ClientOSError | - | 16 |
| speed | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 12 |
| geo | ClientOSError | - | 8 |
| 204 | ProxyConnectionError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
