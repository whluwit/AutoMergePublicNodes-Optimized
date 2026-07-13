# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-13 19:21:49 |
| 运行耗时 | 171.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 77324 |
| 去重后节点 | 23912 |
| TCP 可达 | 3000 |
| 真实可用 | 150 |
| Verified 输出 | 150 |
| Global 输出 | 160 |
| All 输出 | 23912 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.5 |
| tcp | 32.5 |
| probe | 45.1 |
| real_test | 52.5 |
| generate | 34.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44922 |
| trojan | 11357 |
| vmess | 10767 |
| shadowsocks | 9516 |
| hysteria2 | 449 |
| shadowsocksr | 141 |
| http | 138 |
| socks | 27 |
| hysteria | 6 |
| tuic | 1 |

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
| 73.37 | trojan | 275.7 | 648.8 | 21.4 | 0.0 | 10.0 | 10.79 | 14.18 | DeltaKronecker-all | 64.94.95.114 |
| 71.16 | shadowsocks | 304.3 | 652.1 | 20.73 | 0.0 | 10.0 | 12.98 | 15.56 | mheidari-all | 198.98.53.130 |
| 69.27 | shadowsocks | 392.6 | 930.4 | 18.69 | 0.0 | 10.0 | 12.98 | 15.56 | mheidari-all | 172.245.235.84 |
| 68.07 | shadowsocks | 407.6 | 907.5 | 18.34 | 0.0 | 10.0 | 12.98 | 15.56 | mheidari-all | 185.196.61.82 |
| 67.88 | shadowsocks | 370.8 | 734.0 | 19.19 | 0.0 | 10.0 | 12.98 | 15.56 | mheidari-all | 108.181.57.93 |
| 66.52 | vless | 276.5 | 527.1 | 21.38 | 0.0 | 10.0 | 3.95 | 15.56 | mheidari-all | 104.16.9.20 |
| 66.19 | vless | 385.0 | 969.0 | 18.86 | 0.0 | 10.0 | 3.95 | 14.18 | DeltaKronecker-all | 20.84.155.134 |
| 65.16 | shadowsocks | 335.6 | 720.5 | 20.01 | 0.0 | 10.0 | 12.98 | 15.56 | mheidari-all | 147.90.234.133 |
| 64.14 | trojan | 623.6 | 1637.8 | 13.34 | 0.0 | 10.0 | 10.79 | 15.56 | mheidari-all | 64.94.95.118 |
| 61.64 | trojan | 530.0 | 1436.1 | 15.51 | 0.0 | 10.0 | 10.79 | 14.18 | DeltaKronecker-all | 64.94.95.117 |
| 61.51 | http | 775.9 | 1085.7 | 9.82 | 0.0 | 9.26 | 14.61 | 19.52 | snakem982 | 84.239.49.207 |
| 61.49 | trojan | 529.9 | 1442.8 | 15.51 | 0.0 | 10.0 | 10.79 | 14.18 | DeltaKronecker-all | 64.94.95.115 |
| 61.4 | http | 770.7 | 1054.5 | 9.94 | 0.0 | 9.06 | 14.61 | 19.52 | snakem982 | 84.239.49.154 |
| 61.34 | http | 780.5 | 1076.8 | 9.71 | 0.0 | 9.23 | 14.61 | 19.52 | snakem982 | 84.239.49.202 |
| 61.29 | http | 780.8 | 1090.8 | 9.7 | 0.0 | 9.21 | 14.61 | 19.52 | snakem982 | 84.239.49.211 |
| 61.27 | http | 783.9 | 1095.1 | 9.63 | 0.0 | 9.25 | 14.61 | 19.52 | snakem982 | 84.239.49.209 |
| 61.21 | http | 783.2 | 1069.2 | 9.65 | 0.0 | 9.18 | 14.61 | 19.52 | snakem982 | 84.239.49.204 |
| 61.16 | http | 777.0 | 1087.3 | 9.79 | 0.0 | 9.24 | 14.61 | 19.52 | snakem982 | 84.239.49.196 |
| 60.94 | trojan | 374.5 | 377.0 | 19.11 | 0.86 | 9.78 | 10.79 | 14.18 | DeltaKronecker-all | 43.207.192.70 |
| 60.67 | shadowsocks | 453.9 | 435.9 | 17.27 | 0.0 | 9.1 | 12.98 | 14.18 | DeltaKronecker-all | 167.150.100.115 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.722 | 0.646 | 79 | 5561 | prefer |
| DeltaKronecker-all | 0.627 | 0.548 | 62 | 7926 | observe |
| mheidari-all | 0.617 | 0.538 | 52 | 16297 | observe |
| Au1rxx-base64 | 0.259 | 1.0 | 1 | 91 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 3897 | observe |
| Epodonios-all | 0.255 | None | 0 | 6496 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6673 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4279 | observe |
| barry-far-vless | 0.255 | None | 0 | 4810 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5454 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.241 | None | 0 | 1647 | observe |
| nscl5-all | 0.236 | None | 0 | 1526 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 21 |
| speed | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 6 |
| speed | TimeoutError | - | 4 |
| geo | ClientOSError | - | 3 |
| 204 | ProxyError | - | 2 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 226 | 150 | - |
| global | False | 239 | 160 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
