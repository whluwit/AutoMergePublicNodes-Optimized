# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-03 02:37:23 |
| 运行耗时 | 332.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 77781 |
| 去重后节点 | 23328 |
| TCP 可达 | 3000 |
| 真实可用 | 685 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23328 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.3 |
| geo | 1.4 |
| tcp | 31.0 |
| probe | 68.9 |
| real_test | 199.2 |
| generate | 28.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44910 |
| trojan | 12640 |
| vmess | 10427 |
| shadowsocks | 9129 |
| hysteria2 | 227 |
| socks | 155 |
| shadowsocksr | 151 |
| http | 135 |
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
| 76.62 | shadowsocks | 238.8 | 614.2 | 22.25 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 156.146.38.169 |
| 76.52 | shadowsocks | 243.2 | 618.8 | 22.15 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 156.146.38.167 |
| 75.96 | shadowsocks | 239.6 | 613.3 | 22.23 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 156.146.38.168 |
| 75.55 | shadowsocks | 241.7 | 617.3 | 22.18 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 156.146.38.170 |
| 72.51 | vless | 345.1 | 833.8 | 19.79 | 0.0 | 10.0 | 7.14 | 16.72 | Au1rxx-base64 | 15.204.97.214 |
| 72.39 | shadowsocks | 273.4 | 538.2 | 21.45 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 173.244.56.9 |
| 71.63 | shadowsocks | 279.2 | 561.0 | 21.31 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 108.181.118.10 |
| 71.44 | shadowsocks | 283.8 | 543.8 | 21.21 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 108.181.0.177 |
| 70.96 | shadowsocks | 324.9 | 701.0 | 20.26 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 173.244.56.6 |
| 70.73 | shadowsocks | 316.1 | 687.2 | 20.46 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 37.19.198.243 |
| 69.92 | shadowsocks | 371.9 | 872.2 | 19.17 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 37.19.198.236 |
| 69.34 | shadowsocks | 373.2 | 840.1 | 19.14 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 37.19.198.160 |
| 68.89 | shadowsocks | 356.6 | 800.1 | 19.52 | 0.0 | 10.0 | 11.65 | 16.72 | Au1rxx-base64 | 172.245.235.84 |
| 67.52 | shadowsocks | 261.8 | 535.8 | 21.72 | 0.0 | 10.0 | 11.65 | 11.88 | DeltaKronecker-all | 107.172.219.230 |
| 67.49 | shadowsocks | 328.7 | 378.8 | 20.17 | 0.8 | 9.67 | 11.65 | 16.72 | Au1rxx-base64 | 149.22.87.240 |
| 66.99 | shadowsocks | 335.9 | 387.7 | 20.0 | 0.46 | 9.73 | 11.65 | 16.72 | Au1rxx-base64 | 149.22.87.204 |
| 66.61 | vless | 245.9 | 594.3 | 22.09 | 0.0 | 10.0 | 7.14 | 11.88 | DeltaKronecker-all | 92.223.71.246 |
| 66.48 | vless | 248.2 | 526.1 | 22.03 | 0.0 | 9.32 | 7.14 | 11.88 | DeltaKronecker-all | 112.121.184.10 |
| 66.04 | shadowsocks | 293.9 | 643.0 | 20.97 | 0.0 | 10.0 | 11.65 | 11.3 | mheidari-all | 198.98.53.130 |
| 64.25 | socks | 389.8 | 762.1 | 18.75 | 0.0 | 10.0 | 12.66 | 13.36 | Surfboard-tg-mixed | 134.122.1.61 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.909 | 0.846 | 39 | 16051 | prefer |
| Surfboard-tg-mixed | 0.786 | 0.707 | 331 | 6129 | prefer |
| Au1rxx-base64 | 0.621 | 0.625 | 32 | 73 | observe |
| DeltaKronecker-all | 0.457 | 0.376 | 959 | 7467 | observe |
| nscl5-all | 0.3 | 1.0 | 1 | 1114 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4254 | observe |
| Epodonios-all | 0.255 | None | 0 | 7003 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6660 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4550 | observe |
| barry-far-vless | 0.255 | None | 0 | 5102 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5372 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 356 |
| geo | TimeoutError | - | 189 |
| geo | ClientOSError | - | 85 |
| 204 | ProxyError | - | 30 |
| speed | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
