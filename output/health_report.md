# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 11:08:41 |
| 运行耗时 | 528.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98889 |
| 去重后节点 | 27223 |
| TCP 可达 | 3000 |
| 真实可用 | 397 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27223 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.1 |
| tcp | 47.4 |
| probe | 258.5 |
| real_test | 179.7 |
| generate | 38.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60483 |
| vmess | 15528 |
| shadowsocks | 11398 |
| trojan | 9021 |
| hysteria2 | 1642 |
| http | 521 |
| shadowsocksr | 171 |
| socks | 66 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 12 |

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
| 84.78 | hysteria2 | 210.0 | 522.6 | 22.92 | 0.0 | 10.0 | 13.7 | 19.16 | Au1rxx-base64 | 192.255.128.123 |
| 81.96 | shadowsocks | 212.5 | 529.2 | 22.86 | 0.0 | 10.0 | 13.94 | 19.16 | Au1rxx-base64 | 173.244.56.9 |
| 81.88 | shadowsocks | 216.0 | 529.8 | 22.78 | 0.0 | 10.0 | 13.94 | 19.16 | Au1rxx-base64 | 173.244.56.6 |
| 80.98 | shadowsocks | 254.6 | 619.0 | 21.88 | 0.0 | 10.0 | 13.94 | 19.16 | Au1rxx-base64 | 156.146.38.169 |
| 80.97 | shadowsocks | 255.1 | 628.6 | 21.87 | 0.0 | 10.0 | 13.94 | 19.16 | Au1rxx-base64 | 156.146.38.167 |
| 80.91 | shadowsocks | 258.0 | 627.9 | 21.81 | 0.0 | 10.0 | 13.94 | 19.16 | Au1rxx-base64 | 156.146.38.170 |
| 80.83 | shadowsocks | 261.3 | 644.6 | 21.73 | 0.0 | 10.0 | 13.94 | 19.16 | Au1rxx-base64 | 156.146.38.168 |
| 80.79 | shadowsocks | 198.0 | 535.7 | 23.19 | 0.0 | 10.0 | 13.94 | 19.16 | Au1rxx-base64 | 103.214.109.197 |
| 79.55 | shadowsocks | 244.8 | 563.1 | 22.11 | 0.0 | 10.0 | 13.94 | 18.56 | Surfboard-tg-mixed | 5.78.51.123 |
| 79.04 | vless | 197.4 | 517.0 | 23.21 | 0.0 | 10.0 | 6.67 | 19.16 | Au1rxx-base64 | 172.233.139.46 |
| 78.97 | vless | 200.3 | 527.6 | 23.14 | 0.0 | 10.0 | 6.67 | 19.16 | Au1rxx-base64 | 172.235.38.85 |
| 78.44 | vless | 223.2 | 587.5 | 22.61 | 0.0 | 10.0 | 6.67 | 19.16 | Au1rxx-base64 | 172.235.43.210 |
| 77.25 | shadowsocks | 281.3 | 286.2 | 21.27 | 4.27 | 9.9 | 13.94 | 19.16 | Au1rxx-base64 | 149.22.87.204 |
| 77.22 | vless | 276.0 | 694.8 | 21.39 | 0.0 | 10.0 | 6.67 | 19.16 | Au1rxx-base64 | 137.175.82.40 |
| 76.91 | hysteria2 | 283.4 | 374.1 | 21.22 | 0.97 | 9.41 | 13.7 | 19.16 | Au1rxx-base64 | open.2ml.bid |
| 76.41 | shadowsocks | 283.4 | 292.8 | 21.22 | 4.02 | 9.91 | 13.94 | 18.56 | Surfboard-tg-mixed | 149.22.87.240 |
| 76.28 | hysteria2 | 406.3 | 698.4 | 18.37 | 0.0 | 10.0 | 13.7 | 19.16 | Au1rxx-base64 | 66.94.121.46 |
| 76.13 | shadowsocks | 226.7 | 610.9 | 22.53 | 0.0 | 10.0 | 13.94 | 19.16 | Au1rxx-base64 | 14.1.29.109 |
| 75.23 | vless | 271.8 | 601.8 | 21.49 | 0.0 | 10.0 | 6.67 | 19.16 | Au1rxx-base64 | 15.204.97.216 |
| 74.57 | shadowsocks | 293.0 | 645.2 | 21.0 | 0.0 | 10.0 | 13.94 | 19.16 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.935 | 246 | 1738 | prefer |
| ermaozi | 0.949 | 0.958 | 24 | 645 | prefer |
| mheidari-all | 0.807 | 0.736 | 53 | 23264 | prefer |
| Surfboard-tg-mixed | 0.787 | 0.71 | 131 | 7251 | prefer |
| DeltaKronecker-all | 0.602 | 0.588 | 17 | 5207 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5192 | observe |
| Epodonios-all | 0.255 | None | 0 | 7748 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9359 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5966 | observe |
| barry-far-vless | 0.255 | None | 0 | 6206 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4335 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1738 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 20 |
| geo | TimeoutError | - | 9 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
