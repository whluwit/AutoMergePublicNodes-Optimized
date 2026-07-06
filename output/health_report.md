# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-06 19:53:12 |
| 运行耗时 | 207.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80333 |
| 去重后节点 | 24569 |
| TCP 可达 | 3000 |
| 真实可用 | 289 |
| Verified 输出 | 289 |
| Global 输出 | 298 |
| All 输出 | 24569 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.3 |
| tcp | 31.6 |
| probe | 48.8 |
| real_test | 80.9 |
| generate | 40.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46953 |
| trojan | 12458 |
| vmess | 10473 |
| shadowsocks | 9621 |
| hysteria2 | 478 |
| shadowsocksr | 146 |
| http | 139 |
| socks | 50 |
| tuic | 9 |
| hysteria | 6 |

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
| 79.48 | trojan | 277.8 | 654.7 | 21.35 | 0.0 | 10.0 | 13.59 | 17.54 | DeltaKronecker-all | 64.94.95.114 |
| 78.32 | trojan | 349.5 | 902.8 | 19.69 | 0.0 | 10.0 | 13.59 | 17.54 | DeltaKronecker-all | 149.28.241.235 |
| 78.03 | trojan | 362.1 | 940.3 | 19.4 | 0.0 | 10.0 | 13.59 | 17.54 | DeltaKronecker-all | 45.32.198.247 |
| 77.98 | shadowsocks | 245.4 | 613.6 | 22.1 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 156.146.38.167 |
| 77.94 | trojan | 344.0 | 800.4 | 19.81 | 0.0 | 10.0 | 13.59 | 17.54 | DeltaKronecker-all | 64.94.95.115 |
| 77.72 | trojan | 364.1 | 951.4 | 19.35 | 0.0 | 10.0 | 13.59 | 17.54 | DeltaKronecker-all | 45.32.195.168 |
| 76.59 | trojan | 367.8 | 917.4 | 19.26 | 0.0 | 10.0 | 13.59 | 17.94 | mheidari-all | 64.94.95.118 |
| 76.36 | shadowsocks | 246.7 | 642.9 | 22.07 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 156.146.38.168 |
| 76.26 | shadowsocks | 294.7 | 767.7 | 20.96 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 156.146.38.170 |
| 74.62 | shadowsocks | 296.6 | 687.2 | 20.91 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 37.19.198.244 |
| 74.52 | shadowsocks | 248.8 | 607.7 | 22.02 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 156.146.38.169 |
| 74.51 | shadowsocks | 294.6 | 701.0 | 20.96 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 37.19.198.243 |
| 74.44 | trojan | 338.6 | 889.1 | 19.94 | 0.0 | 10.0 | 13.59 | 17.54 | DeltaKronecker-all | 64.94.95.117 |
| 72.98 | shadowsocks | 335.4 | 802.8 | 20.01 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 37.19.198.236 |
| 72.39 | shadowsocks | 276.0 | 527.6 | 21.39 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 108.181.0.177 |
| 71.73 | shadowsocks | 294.1 | 531.7 | 20.97 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 108.181.118.10 |
| 71.69 | shadowsocks | 351.9 | 861.6 | 19.63 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 185.196.61.82 |
| 71.66 | shadowsocks | 308.2 | 638.8 | 20.64 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 149.22.95.183 |
| 70.71 | shadowsocks | 372.6 | 651.9 | 19.15 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 108.181.57.93 |
| 70.65 | shadowsocks | 371.1 | 903.2 | 19.19 | 0.0 | 10.0 | 12.92 | 16.96 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.781 | 0.786 | 56 | 121 | prefer |
| Surfboard-tg-mixed | 0.777 | 0.7 | 130 | 6111 | prefer |
| mheidari-all | 0.777 | 0.703 | 64 | 16332 | prefer |
| DeltaKronecker-all | 0.548 | 0.468 | 154 | 8330 | observe |
| nscl5-all | 0.321 | 1.0 | 1 | 1651 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4358 | observe |
| Epodonios-all | 0.255 | None | 0 | 7164 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7234 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4506 | observe |
| barry-far-vless | 0.255 | None | 0 | 5174 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5338 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.226 | None | 0 | 1268 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 37 |
| 204 | ClientOSError | - | 24 |
| 204 | ProxyError | - | 22 |
| cn-block | ProxyError | - | 14 |
| cn-block | TimeoutError | - | 11 |
| geo | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| geo | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 7 |
| geo | ProxyError | - | 6 |
| speed | TimeoutError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 289 | - |
| global | False | 300 | 298 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
