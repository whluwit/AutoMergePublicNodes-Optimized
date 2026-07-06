# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-06 15:25:50 |
| 运行耗时 | 209.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 79734 |
| 去重后节点 | 24473 |
| TCP 可达 | 3000 |
| 真实可用 | 353 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24473 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.4 |
| tcp | 31.3 |
| probe | 51.1 |
| real_test | 92.9 |
| generate | 28.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46278 |
| trojan | 12673 |
| vmess | 10481 |
| shadowsocks | 9477 |
| hysteria2 | 466 |
| shadowsocksr | 148 |
| http | 139 |
| socks | 55 |
| tuic | 11 |
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
| 78.31 | shadowsocks | 215.8 | 533.4 | 22.78 | 0.0 | 10.0 | 12.71 | 17.32 | Au1rxx-base64 | 108.181.0.177 |
| 77.58 | shadowsocks | 269.1 | 649.8 | 21.55 | 0.0 | 10.0 | 12.71 | 17.32 | Au1rxx-base64 | 149.22.95.183 |
| 75.13 | shadowsocks | 196.7 | 476.2 | 23.22 | 0.0 | 10.0 | 12.71 | 17.32 | Au1rxx-base64 | 108.181.118.10 |
| 74.68 | shadowsocks | 274.4 | 282.1 | 21.43 | 4.42 | 9.94 | 12.71 | 17.32 | Au1rxx-base64 | 149.22.87.204 |
| 73.61 | shadowsocks | 288.1 | 636.5 | 21.11 | 0.0 | 10.0 | 12.71 | 17.32 | Au1rxx-base64 | 156.146.38.170 |
| 73.48 | trojan | 351.4 | 779.3 | 19.64 | 0.0 | 10.0 | 12.78 | 16.96 | DeltaKronecker-all | 45.32.195.168 |
| 73.23 | shadowsocks | 300.2 | 680.4 | 20.83 | 0.0 | 10.0 | 12.71 | 17.32 | Au1rxx-base64 | 156.146.38.168 |
| 72.81 | trojan | 359.8 | 774.1 | 19.45 | 0.0 | 10.0 | 12.78 | 16.96 | DeltaKronecker-all | 45.32.198.247 |
| 72.6 | shadowsocks | 319.2 | 625.1 | 20.39 | 0.0 | 10.0 | 12.71 | 17.32 | Au1rxx-base64 | 156.146.38.167 |
| 72.16 | trojan | 372.9 | 304.3 | 19.15 | 3.59 | 9.32 | 12.78 | 17.32 | Au1rxx-base64 | large-baboon.rooster465.autos |
| 72.12 | shadowsocks | 293.1 | 337.1 | 20.99 | 2.36 | 9.94 | 12.71 | 17.32 | Au1rxx-base64 | 149.22.87.241 |
| 71.81 | shadowsocks | 295.4 | 345.7 | 20.94 | 2.04 | 9.94 | 12.71 | 17.32 | Au1rxx-base64 | 149.22.87.240 |
| 69.69 | trojan | 397.1 | 821.4 | 18.59 | 0.0 | 10.0 | 12.78 | 16.96 | DeltaKronecker-all | 64.94.95.115 |
| 69.67 | trojan | 395.4 | 809.6 | 18.62 | 0.0 | 10.0 | 12.78 | 16.96 | DeltaKronecker-all | 64.94.95.117 |
| 69.66 | trojan | 387.1 | 789.3 | 18.82 | 0.0 | 10.0 | 12.78 | 16.96 | DeltaKronecker-all | 64.94.95.114 |
| 69.49 | shadowsocks | 369.0 | 741.0 | 19.24 | 0.0 | 10.0 | 12.71 | 17.32 | Au1rxx-base64 | 37.19.198.243 |
| 69.43 | shadowsocks | 371.8 | 744.7 | 19.17 | 0.0 | 10.0 | 12.71 | 17.32 | Au1rxx-base64 | 37.19.198.160 |
| 69.35 | shadowsocks | 387.6 | 808.6 | 18.81 | 0.0 | 10.0 | 12.71 | 17.92 | mheidari-all | 185.196.61.82 |
| 69.21 | shadowsocks | 371.0 | 743.7 | 19.19 | 0.0 | 10.0 | 12.71 | 17.32 | Au1rxx-base64 | 37.19.198.244 |
| 68.51 | trojan | 489.7 | 1073.9 | 16.44 | 0.0 | 10.0 | 12.78 | 17.32 | Au1rxx-base64 | 149.104.87.141 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.902 | 0.829 | 105 | 5986 | prefer |
| mheidari-all | 0.897 | 0.822 | 107 | 16268 | prefer |
| DeltaKronecker-all | 0.877 | 0.801 | 136 | 8330 | prefer |
| Au1rxx-base64 | 0.848 | 0.867 | 30 | 98 | prefer |
| nscl5-all | 0.377 | 1.0 | 2 | 1651 | observe |
| tg-LonUp_M | 0.327 | 0.75 | 4 | 178 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4358 | observe |
| Epodonios-all | 0.255 | None | 0 | 6989 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7108 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4436 | observe |
| barry-far-vless | 0.255 | None | 0 | 5099 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 21 |
| 204 | ClientOSError | - | 13 |
| geo | TimeoutError | - | 9 |
| 204 | TimeoutError | - | 6 |
| speed | TimeoutError | - | 5 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
