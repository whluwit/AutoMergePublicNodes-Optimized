# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-01 09:42:08 |
| 运行耗时 | 226.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 75612 |
| 去重后节点 | 23071 |
| TCP 可达 | 3000 |
| 真实可用 | 425 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23071 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| geo | 1.5 |
| tcp | 30.6 |
| probe | 56.9 |
| real_test | 105.2 |
| generate | 28.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42712 |
| trojan | 12689 |
| vmess | 10273 |
| shadowsocks | 9331 |
| hysteria2 | 254 |
| shadowsocksr | 153 |
| http | 135 |
| socks | 58 |
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
| 77.75 | shadowsocks | 251.1 | 614.5 | 21.97 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 156.146.38.170 |
| 77.66 | shadowsocks | 254.7 | 634.5 | 21.88 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 156.146.38.167 |
| 77.63 | shadowsocks | 256.2 | 639.7 | 21.85 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 37.19.198.243 |
| 77.6 | shadowsocks | 257.5 | 633.5 | 21.82 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 156.146.38.169 |
| 77.41 | shadowsocks | 265.4 | 663.3 | 21.63 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 37.19.198.160 |
| 77.28 | shadowsocks | 271.3 | 665.2 | 21.5 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 37.19.198.244 |
| 77.13 | shadowsocks | 277.5 | 681.9 | 21.35 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 37.19.198.236 |
| 76.8 | shadowsocks | 292.0 | 739.6 | 21.02 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 156.146.38.168 |
| 74.71 | shadowsocks | 346.6 | 882.4 | 19.76 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 108.181.57.93 |
| 73.48 | shadowsocks | 327.2 | 959.9 | 20.2 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 172.234.202.34 |
| 72.39 | shadowsocks | 271.6 | 670.5 | 21.49 | 0.0 | 10.0 | 13.62 | 13.86 | mheidari-all | 198.98.53.130 |
| 72.12 | vless | 304.0 | 771.7 | 20.74 | 0.0 | 10.0 | 7.52 | 13.86 | mheidari-all | 47.253.226.114 |
| 71.34 | shadowsocks | 323.7 | 689.6 | 20.28 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 173.244.56.6 |
| 71.34 | shadowsocks | 352.1 | 745.1 | 19.63 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 108.181.0.177 |
| 70.95 | shadowsocks | 322.4 | 587.6 | 20.31 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 108.181.118.10 |
| 70.58 | shadowsocks | 313.4 | 636.5 | 20.52 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 149.22.95.183 |
| 70.5 | shadowsocks | 377.1 | 847.0 | 19.05 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | 173.244.56.9 |
| 70.18 | vless | 301.7 | 579.0 | 20.79 | 0.0 | 10.0 | 7.52 | 16.54 | Surfboard-tg-mixed | 64.23.143.23 |
| 68.64 | trojan | 358.9 | 902.3 | 19.47 | 0.0 | 10.0 | 12.32 | 13.86 | mheidari-all | 64.94.95.118 |
| 68.48 | shadowsocks | 283.3 | 686.5 | 21.22 | 0.0 | 10.0 | 13.62 | 16.16 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.957 | 0.976 | 42 | 61 | prefer |
| Au1rxx-base64 | 0.83 | 0.836 | 61 | 115 | prefer |
| Surfboard-tg-mixed | 0.675 | 0.596 | 267 | 5595 | observe |
| DeltaKronecker-all | 0.673 | 0.595 | 121 | 7631 | observe |
| mheidari-all | 0.524 | 0.444 | 223 | 15660 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4308 | observe |
| Epodonios-all | 0.255 | None | 0 | 6487 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6549 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4151 | observe |
| barry-far-vless | 0.255 | None | 0 | 4743 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5331 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.227 | None | 0 | 1298 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 159 |
| geo | TimeoutError | - | 28 |
| 204 | ProxyError | - | 27 |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 12 |
| geo | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 10 |
| speed | ProxyError | - | 5 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
