# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-14 13:26:40 |
| 运行耗时 | 200.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 80436 |
| 去重后节点 | 23814 |
| TCP 可达 | 3000 |
| 真实可用 | 218 |
| Verified 输出 | 218 |
| Global 输出 | 226 |
| All 输出 | 23814 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.3 |
| tcp | 32.1 |
| probe | 46.7 |
| real_test | 77.2 |
| generate | 38.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48082 |
| trojan | 11658 |
| vmess | 10406 |
| shadowsocks | 9466 |
| hysteria2 | 505 |
| http | 138 |
| shadowsocksr | 127 |
| socks | 36 |
| hysteria | 12 |
| anytls | 4 |
| tuic | 2 |

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
| 73.37 | shadowsocks | 231.8 | 610.3 | 22.41 | 0.0 | 10.0 | 11.02 | 13.94 | mheidari-all | 198.98.53.130 |
| 72.28 | shadowsocks | 257.6 | 665.7 | 21.82 | 0.0 | 10.0 | 11.02 | 13.94 | mheidari-all | 108.181.57.93 |
| 71.45 | vmess | 319.3 | 840.3 | 20.39 | 0.0 | 10.0 | 12.5 | 13.06 | Surfboard-tg-mixed | 67.220.85.46 |
| 70.13 | trojan | 330.7 | 732.2 | 20.12 | 0.0 | 10.0 | 11.8 | 14.74 | DeltaKronecker-all | 64.94.95.115 |
| 69.18 | trojan | 381.1 | 882.1 | 18.96 | 0.0 | 10.0 | 11.8 | 14.74 | DeltaKronecker-all | 64.94.95.114 |
| 69.01 | trojan | 372.4 | 867.4 | 19.16 | 0.0 | 10.0 | 11.8 | 14.74 | DeltaKronecker-all | 64.94.95.117 |
| 68.8 | trojan | 299.6 | 650.6 | 20.84 | 0.0 | 10.0 | 11.8 | 13.94 | mheidari-all | 64.94.95.118 |
| 65.58 | http | 645.5 | 1043.1 | 12.83 | 0.0 | 9.83 | 14.61 | 19.52 | snakem982 | 193.176.84.37 |
| 65.49 | http | 652.3 | 1074.1 | 12.68 | 0.0 | 9.79 | 14.61 | 19.52 | snakem982 | 193.176.84.32 |
| 65.19 | http | 652.2 | 976.0 | 12.68 | 0.0 | 9.72 | 14.61 | 19.52 | snakem982 | 84.239.49.178 |
| 65.17 | http | 653.0 | 978.2 | 12.66 | 0.0 | 9.69 | 14.61 | 19.52 | snakem982 | 84.239.49.154 |
| 65.15 | http | 652.8 | 955.6 | 12.67 | 0.0 | 9.71 | 14.61 | 19.52 | snakem982 | 84.239.49.191 |
| 65.12 | http | 655.5 | 978.9 | 12.6 | 0.0 | 9.72 | 14.61 | 19.52 | snakem982 | 84.239.49.209 |
| 65.1 | http | 655.1 | 961.4 | 12.61 | 0.0 | 9.67 | 14.61 | 19.52 | snakem982 | 84.239.49.187 |
| 65.1 | http | 658.2 | 965.4 | 12.54 | 0.0 | 9.72 | 14.61 | 19.52 | snakem982 | 84.239.49.202 |
| 65.05 | http | 648.9 | 958.7 | 12.76 | 0.0 | 9.67 | 14.61 | 19.52 | snakem982 | 84.239.49.207 |
| 65.01 | http | 658.3 | 976.3 | 12.54 | 0.0 | 9.67 | 14.61 | 19.52 | snakem982 | 84.239.49.204 |
| 65.01 | http | 661.1 | 990.6 | 12.48 | 0.0 | 9.72 | 14.61 | 19.52 | snakem982 | 84.239.14.159 |
| 64.98 | http | 659.7 | 962.1 | 12.51 | 0.0 | 9.72 | 14.61 | 19.52 | snakem982 | 84.239.49.245 |
| 64.98 | http | 659.9 | 972.5 | 12.5 | 0.0 | 9.71 | 14.61 | 19.52 | snakem982 | 84.239.49.211 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.839 | 0.765 | 81 | 5561 | prefer |
| mheidari-all | 0.787 | 0.711 | 97 | 17504 | prefer |
| DeltaKronecker-all | 0.547 | 0.466 | 103 | 7942 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 3836 | observe |
| Au1rxx-base64 | 0.259 | 1.0 | 1 | 97 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4019 | observe |
| Epodonios-all | 0.255 | None | 0 | 6477 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6376 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4279 | observe |
| barry-far-vless | 0.255 | None | 0 | 4832 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5405 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.231 | None | 0 | 1412 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 39 |
| speed | ClientOSError | - | 15 |
| 204 | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| cn-block | TimeoutError | - | 6 |
| geo | ClientOSError | - | 4 |
| speed | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 250 | 218 | - |
| global | False | 254 | 226 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
