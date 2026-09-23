# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 03:19:12 |
| 运行耗时 | 1178.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96683 |
| 去重后节点 | 26603 |
| TCP 可达 | 3000 |
| 真实可用 | 524 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26603 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 43.3 |
| probe | 403.4 |
| real_test | 647.5 |
| generate | 77.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59300 |
| vmess | 14860 |
| shadowsocks | 11236 |
| trojan | 8770 |
| hysteria2 | 1525 |
| http | 681 |
| shadowsocksr | 171 |
| socks | 89 |
| anytls | 24 |
| hysteria | 19 |
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
| 81.66 | hysteria2 | 240.1 | 662.0 | 22.22 | 0.0 | 8.86 | 13.5 | 18.18 | Au1rxx-base64 | 159.223.157.129 |
| 79.52 | vless | 280.3 | 712.2 | 21.29 | 0.0 | 10.0 | 10.05 | 18.18 | Au1rxx-base64 | 66.70.179.198 |
| 78.98 | vless | 253.2 | 660.9 | 21.92 | 0.0 | 8.83 | 10.05 | 18.18 | Au1rxx-base64 | 169.40.42.133 |
| 78.83 | vless | 261.6 | 635.2 | 21.72 | 0.0 | 8.88 | 10.05 | 18.18 | Au1rxx-base64 | 195.211.98.43 |
| 78.63 | vless | 270.1 | 633.7 | 21.52 | 0.0 | 8.88 | 10.05 | 18.18 | Au1rxx-base64 | 138.124.60.146 |
| 78.62 | shadowsocks | 254.4 | 712.9 | 21.89 | 0.0 | 8.9 | 13.65 | 18.18 | Au1rxx-base64 | 37.19.198.244 |
| 78.58 | vless | 270.8 | 655.7 | 21.51 | 0.0 | 8.84 | 10.05 | 18.18 | Au1rxx-base64 | 169.40.42.15 |
| 78.47 | vless | 275.5 | 738.9 | 21.4 | 0.0 | 8.84 | 10.05 | 18.18 | Au1rxx-base64 | 169.40.42.235 |
| 78.3 | vless | 283.8 | 629.5 | 21.21 | 0.0 | 8.86 | 10.05 | 18.18 | Au1rxx-base64 | 169.40.42.184 |
| 78.23 | vless | 265.6 | 648.9 | 21.63 | 0.0 | 8.85 | 10.05 | 18.18 | Au1rxx-base64 | 169.40.42.223 |
| 78.21 | vless | 286.5 | 760.4 | 21.15 | 0.0 | 8.83 | 10.05 | 18.18 | Au1rxx-base64 | 169.40.42.182 |
| 78.1 | vless | 291.6 | 650.3 | 21.03 | 0.0 | 8.84 | 10.05 | 18.18 | Au1rxx-base64 | 169.40.42.231 |
| 77.98 | vless | 298.6 | 801.5 | 20.87 | 0.0 | 8.88 | 10.05 | 18.18 | Au1rxx-base64 | 169.40.42.104 |
| 77.86 | shadowsocks | 256.1 | 716.1 | 21.85 | 0.0 | 10.0 | 13.65 | 16.36 | mheidari-all | 37.19.198.160 |
| 77.85 | shadowsocks | 256.3 | 715.5 | 21.84 | 0.0 | 10.0 | 13.65 | 16.36 | mheidari-all | 37.19.198.236 |
| 77.83 | vless | 302.4 | 623.6 | 20.78 | 0.0 | 8.82 | 10.05 | 18.18 | Au1rxx-base64 | 79.141.172.154 |
| 77.66 | vless | 310.9 | 860.8 | 20.58 | 0.0 | 8.85 | 10.05 | 18.18 | Au1rxx-base64 | 137.184.218.169 |
| 77.59 | shadowsocks | 295.4 | 794.2 | 20.94 | 0.0 | 8.82 | 13.65 | 18.18 | Au1rxx-base64 | 142.4.216.225 |
| 77.58 | vless | 316.0 | 895.0 | 20.46 | 0.0 | 8.89 | 10.05 | 18.18 | Au1rxx-base64 | 34.85.179.6 |
| 77.46 | vless | 319.0 | 860.6 | 20.39 | 0.0 | 8.84 | 10.05 | 18.18 | Au1rxx-base64 | 169.40.42.232 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.89 | 0.828 | 309 | 1598 | prefer |
| ermaozi | 0.701 | 0.7 | 30 | 346 | prefer |
| Surfboard-tg-mixed | 0.554 | 0.472 | 36 | 7168 | observe |
| DeltaKronecker-all | 0.463 | 0.381 | 194 | 6324 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| mheidari-all | 0.314 | 0.233 | 648 | 22274 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ermaozi-get_subscribe | 0.283 | 0.667 | 3 | 372 | observe |
| Epodonios-all | 0.255 | None | 0 | 7633 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8906 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5836 | observe |
| barry-far-vless | 0.255 | None | 0 | 6057 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4252 | observe |
| ninja-vless | 0.251 | 0.333 | 3 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 300 |
| speed | TimeoutError | - | 112 |
| geo | ClientOSError | - | 96 |
| speed | ClientOSError | - | 81 |
| cn-block | ClientOSError | - | 55 |
| 204 | ProxyError | - | 20 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 16 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
