# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-14 19:15:21 |
| 运行耗时 | 194.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 81104 |
| 去重后节点 | 24292 |
| TCP 可达 | 3000 |
| 真实可用 | 238 |
| Verified 输出 | 238 |
| Global 输出 | 247 |
| All 输出 | 24292 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| geo | 1.3 |
| tcp | 32.6 |
| probe | 43.3 |
| real_test | 79.1 |
| generate | 34.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47816 |
| trojan | 11620 |
| vmess | 11007 |
| shadowsocks | 9910 |
| hysteria2 | 426 |
| http | 138 |
| shadowsocksr | 129 |
| socks | 40 |
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
| 69.27 | shadowsocks | 386.7 | 879.0 | 18.83 | 0.0 | 10.0 | 11.77 | 15.74 | mheidari-all | 185.196.61.82 |
| 68.41 | trojan | 453.2 | 1178.0 | 17.29 | 0.0 | 10.0 | 10.82 | 15.74 | mheidari-all | 64.94.95.118 |
| 68.26 | vmess | 438.1 | 1089.3 | 17.64 | 0.0 | 10.0 | 12.86 | 15.74 | mheidari-all | 67.220.95.3 |
| 66.46 | vless | 306.5 | 724.5 | 20.68 | 0.0 | 10.0 | 0.62 | 16.78 | Surfboard-tg-mixed | 47.253.226.114 |
| 65.14 | shadowsocks | 241.5 | 620.1 | 22.19 | 0.0 | 10.0 | 11.77 | 5.18 | Au1rxx-base64 | 156.146.38.168 |
| 64.57 | trojan | 488.3 | 554.9 | 16.47 | 0.0 | 10.0 | 10.82 | 16.78 | Surfboard-tg-mixed | 199.232.78.140 |
| 64.56 | shadowsocks | 266.4 | 621.5 | 21.61 | 0.0 | 10.0 | 11.77 | 5.18 | Au1rxx-base64 | 156.146.38.170 |
| 64.11 | shadowsocks | 286.0 | 727.8 | 21.16 | 0.0 | 10.0 | 11.77 | 5.18 | Au1rxx-base64 | 156.146.38.167 |
| 63.41 | http | 716.4 | 1072.2 | 11.2 | 0.0 | 9.58 | 14.61 | 19.52 | snakem982 | 193.176.84.31 |
| 62.9 | trojan | 582.0 | 909.9 | 14.3 | 0.0 | 10.0 | 10.82 | 16.78 | Surfboard-tg-mixed | 104.16.174.12 |
| 62.9 | trojan | 584.1 | 902.3 | 14.26 | 0.0 | 10.0 | 10.82 | 16.78 | Surfboard-tg-mixed | 104.16.174.44 |
| 62.81 | http | 724.3 | 1050.2 | 11.01 | 0.0 | 9.41 | 14.61 | 19.52 | snakem982 | 84.239.49.202 |
| 62.8 | http | 726.2 | 1003.6 | 10.97 | 0.0 | 9.38 | 14.61 | 19.52 | snakem982 | 84.239.49.160 |
| 62.76 | http | 729.4 | 1018.9 | 10.89 | 0.0 | 9.41 | 14.61 | 19.52 | snakem982 | 84.239.49.219 |
| 62.65 | trojan | 558.4 | 865.1 | 14.85 | 0.0 | 10.0 | 10.82 | 15.74 | mheidari-all | 104.17.121.43 |
| 62.65 | http | 733.5 | 1016.9 | 10.8 | 0.0 | 9.34 | 14.61 | 19.52 | snakem982 | 84.239.49.235 |
| 62.63 | trojan | 440.0 | 513.1 | 17.59 | 0.0 | 10.0 | 10.82 | 16.78 | Surfboard-tg-mixed | 104.18.45.104 |
| 62.6 | http | 729.9 | 1018.9 | 10.88 | 0.0 | 9.28 | 14.61 | 19.52 | snakem982 | 84.239.49.245 |
| 62.59 | http | 734.0 | 1050.5 | 10.79 | 0.0 | 9.34 | 14.61 | 19.52 | snakem982 | 84.239.49.39 |
| 62.55 | http | 743.0 | 1027.6 | 10.58 | 0.0 | 9.43 | 14.61 | 19.52 | snakem982 | 84.239.49.42 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.756 | 0.681 | 69 | 18003 | prefer |
| DeltaKronecker-all | 0.736 | 0.661 | 59 | 7942 | prefer |
| Au1rxx-base64 | 0.59 | 1.0 | 9 | 150 | observe |
| Surfboard-tg-mixed | 0.575 | 0.495 | 216 | 5662 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4019 | observe |
| Epodonios-all | 0.255 | None | 0 | 6538 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3965 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6320 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4339 | observe |
| barry-far-vless | 0.255 | None | 0 | 4852 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5187 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3836 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.231 | None | 0 | 1412 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 51 |
| speed | ClientOSError | - | 44 |
| 204 | TimeoutError | - | 15 |
| geo | ClientOSError | - | 13 |
| speed | TimeoutError | - | 8 |
| cn-block | TimeoutError | - | 8 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 218 | 238 | - |
| global | False | 226 | 247 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
