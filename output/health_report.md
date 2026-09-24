# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 16:30:52 |
| 运行耗时 | 525.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 96369 |
| 去重后节点 | 26302 |
| TCP 可达 | 3000 |
| 真实可用 | 369 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26302 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.5 |
| tcp | 43.2 |
| probe | 234.1 |
| real_test | 163.0 |
| generate | 76.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59001 |
| vmess | 14744 |
| shadowsocks | 11216 |
| trojan | 8999 |
| hysteria2 | 1560 |
| http | 550 |
| shadowsocksr | 173 |
| socks | 79 |
| anytls | 22 |
| hysteria | 18 |
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
| 79.41 | shadowsocks | 258.5 | 715.5 | 21.79 | 0.0 | 8.78 | 13.58 | 19.26 | Au1rxx-base64 | 37.19.198.244 |
| 79.24 | vless | 259.1 | 632.1 | 21.78 | 0.0 | 8.79 | 9.41 | 19.26 | Au1rxx-base64 | 195.211.98.43 |
| 78.83 | hysteria2 | 372.2 | 1051.2 | 19.16 | 0.0 | 8.88 | 12.63 | 19.26 | Au1rxx-base64 | 159.223.157.129 |
| 78.47 | vless | 292.3 | 714.5 | 21.01 | 0.0 | 8.79 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.35 |
| 78.39 | vless | 296.4 | 663.5 | 20.92 | 0.0 | 8.8 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.173 |
| 78.19 | vless | 303.8 | 753.3 | 20.75 | 0.0 | 8.77 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.89 |
| 77.77 | vless | 323.2 | 896.1 | 20.3 | 0.0 | 8.8 | 9.41 | 19.26 | Au1rxx-base64 | 185.95.231.156 |
| 77.21 | vless | 347.4 | 817.9 | 19.74 | 0.0 | 8.8 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.212 |
| 77.07 | vless | 405.0 | 1053.9 | 18.4 | 0.0 | 10.0 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.104 |
| 76.97 | vless | 357.4 | 982.7 | 19.5 | 0.0 | 8.8 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.90 |
| 76.94 | vless | 359.0 | 940.5 | 19.47 | 0.0 | 8.8 | 9.41 | 19.26 | Au1rxx-base64 | 66.70.179.198 |
| 76.88 | vless | 364.2 | 1008.1 | 19.35 | 0.0 | 8.86 | 9.41 | 19.26 | Au1rxx-base64 | 185.95.231.233 |
| 76.8 | vless | 363.5 | 938.7 | 19.36 | 0.0 | 8.77 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.235 |
| 76.04 | vless | 433.6 | 1120.5 | 17.74 | 0.0 | 10.0 | 9.41 | 19.26 | Au1rxx-base64 | 209.200.246.148 |
| 75.97 | vless | 340.9 | 784.6 | 19.89 | 0.0 | 8.76 | 9.41 | 19.26 | Au1rxx-base64 | 198.251.78.29 |
| 75.94 | vless | 404.5 | 994.6 | 18.41 | 0.0 | 8.86 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.16 |
| 75.83 | shadowsocks | 390.3 | 1044.4 | 18.74 | 0.0 | 8.75 | 13.58 | 19.26 | Au1rxx-base64 | 38.180.135.156 |
| 75.62 | vless | 415.4 | 1145.4 | 18.16 | 0.0 | 8.79 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.75 |
| 75.55 | vless | 418.9 | 1154.2 | 18.08 | 0.0 | 8.8 | 9.41 | 19.26 | Au1rxx-base64 | 169.40.42.133 |
| 75.47 | shadowsocks | 409.4 | 772.0 | 18.3 | 0.0 | 8.83 | 13.58 | 19.26 | Au1rxx-base64 | 15.204.247.206 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.989 | 0.925 | 253 | 1697 | prefer |
| mheidari-all | 0.713 | 0.636 | 88 | 22258 | prefer |
| Surfboard-tg-mixed | 0.668 | 0.589 | 95 | 7027 | observe |
| ermaozi | 0.618 | 0.613 | 31 | 298 | observe |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 5845 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 71 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5307 | observe |
| Epodonios-all | 0.255 | None | 0 | 7498 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9120 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5676 | observe |
| barry-far-vless | 0.255 | None | 0 | 5901 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4305 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 28 |
| 204 | ProxyError | - | 20 |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 18 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| geo | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
