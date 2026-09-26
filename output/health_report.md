# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 03:29:30 |
| 运行耗时 | 1116.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96567 |
| 去重后节点 | 26470 |
| TCP 可达 | 3000 |
| 真实可用 | 558 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26470 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.5 |
| tcp | 42.9 |
| probe | 389.3 |
| real_test | 588.7 |
| generate | 86.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58839 |
| vmess | 15103 |
| shadowsocks | 11183 |
| trojan | 8906 |
| hysteria2 | 1560 |
| http | 639 |
| shadowsocksr | 175 |
| socks | 101 |
| anytls | 32 |
| hysteria | 15 |
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
| 80.81 | vless | 245.0 | 684.9 | 22.11 | 0.0 | 8.81 | 10.77 | 19.12 | Au1rxx-base64 | 79.141.172.154 |
| 80.17 | vless | 282.8 | 741.4 | 21.23 | 0.0 | 9.05 | 10.77 | 19.12 | Au1rxx-base64 | 195.123.235.177 |
| 79.95 | vless | 272.6 | 642.1 | 21.47 | 0.0 | 8.75 | 10.77 | 19.12 | Au1rxx-base64 | 195.211.98.43 |
| 79.65 | vless | 295.1 | 774.0 | 20.95 | 0.0 | 8.81 | 10.77 | 19.12 | Au1rxx-base64 | 169.40.42.133 |
| 79.54 | vless | 299.7 | 803.3 | 20.84 | 0.0 | 8.81 | 10.77 | 19.12 | Au1rxx-base64 | 185.95.231.156 |
| 79.23 | vless | 314.2 | 762.2 | 20.5 | 0.0 | 8.84 | 10.77 | 19.12 | Au1rxx-base64 | 169.40.42.212 |
| 78.7 | vless | 337.4 | 842.4 | 19.97 | 0.0 | 8.84 | 10.77 | 19.12 | Au1rxx-base64 | 169.40.42.104 |
| 78.69 | shadowsocks | 266.7 | 727.3 | 21.6 | 0.0 | 8.87 | 13.1 | 19.12 | Au1rxx-base64 | 37.19.198.244 |
| 78.67 | vless | 341.6 | 917.5 | 19.87 | 0.0 | 8.91 | 10.77 | 19.12 | Au1rxx-base64 | 185.95.231.233 |
| 78.52 | vless | 336.8 | 831.6 | 19.98 | 0.0 | 8.81 | 10.77 | 19.12 | Au1rxx-base64 | 169.40.42.163 |
| 78.49 | shadowsocks | 286.9 | 774.8 | 21.14 | 0.0 | 9.13 | 13.1 | 19.12 | Au1rxx-base64 | 198.98.53.130 |
| 78.22 | shadowsocks | 263.7 | 713.4 | 21.67 | 0.0 | 8.83 | 13.1 | 19.12 | Au1rxx-base64 | 15.204.247.206 |
| 78.19 | vless | 322.1 | 722.5 | 20.32 | 0.0 | 8.81 | 10.77 | 19.12 | Au1rxx-base64 | 169.40.42.75 |
| 78.13 | vless | 342.4 | 860.2 | 19.85 | 0.0 | 9.1 | 10.77 | 19.12 | Au1rxx-base64 | 169.40.42.89 |
| 77.7 | shadowsocks | 264.8 | 718.5 | 21.65 | 0.0 | 8.83 | 13.1 | 19.12 | Au1rxx-base64 | 37.19.198.160 |
| 77.66 | shadowsocks | 311.1 | 821.2 | 20.58 | 0.0 | 8.86 | 13.1 | 19.12 | Au1rxx-base64 | 142.4.216.225 |
| 77.63 | vless | 367.6 | 969.0 | 19.27 | 0.0 | 8.9 | 10.77 | 19.12 | Au1rxx-base64 | 169.40.42.184 |
| 77.62 | vless | 396.3 | 1022.9 | 18.6 | 0.0 | 9.13 | 10.77 | 19.12 | Au1rxx-base64 | 169.40.42.74 |
| 77.45 | vless | 391.7 | 1058.3 | 18.71 | 0.0 | 8.85 | 10.77 | 19.12 | Au1rxx-base64 | 169.40.42.224 |
| 77.17 | shadowsocks | 316.3 | 893.6 | 20.46 | 0.0 | 8.99 | 13.1 | 19.12 | Au1rxx-base64 | 15.204.246.132 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | 0.874 | 294 | 1598 | prefer |
| Surfboard-tg-mixed | 0.686 | 0.609 | 92 | 7217 | observe |
| DeltaKronecker-all | 0.441 | 0.462 | 13 | 5452 | observe |
| mheidari-all | 0.398 | 0.317 | 697 | 22526 | observe |
| ermaozi | 0.375 | 0.353 | 34 | 352 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| ermaozi-get_subscribe | 0.272 | 0.308 | 13 | 375 | observe |
| zhangkai | 0.261 | 1.0 | 1 | 144 | observe |
| Epodonios-all | 0.255 | None | 0 | 7682 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8921 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5837 | observe |
| barry-far-vless | 0.255 | None | 0 | 6063 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4304 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 227 |
| speed | TimeoutError | - | 122 |
| cn-block | ClientOSError | - | 61 |
| geo | ClientOSError | - | 58 |
| speed | ClientOSError | - | 41 |
| 204 | ProxyError | - | 32 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 14 |
| 204 | ClientOSError | - | 8 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
