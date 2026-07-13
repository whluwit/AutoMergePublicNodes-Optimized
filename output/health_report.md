# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-13 09:20:10 |
| 运行耗时 | 185.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 76605 |
| 去重后节点 | 23706 |
| TCP 可达 | 3000 |
| 真实可用 | 291 |
| Verified 输出 | 291 |
| Global 输出 | 300 |
| All 输出 | 23706 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.4 |
| tcp | 31.5 |
| probe | 46.2 |
| real_test | 77.1 |
| generate | 24.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43868 |
| trojan | 11540 |
| vmess | 10736 |
| shadowsocks | 9754 |
| hysteria2 | 389 |
| shadowsocksr | 146 |
| http | 137 |
| socks | 26 |
| hysteria | 6 |
| tuic | 3 |

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
| 72.48 | trojan | 275.9 | 461.0 | 21.39 | 0.0 | 10.0 | 14.28 | 14.54 | Surfboard-tg-mixed | 162.159.38.62 |
| 71.62 | trojan | 203.0 | 493.0 | 23.08 | 0.0 | 10.0 | 14.28 | 12.04 | DeltaKronecker-all | 104.16.97.215 |
| 70.69 | trojan | 304.0 | 662.6 | 20.74 | 0.0 | 10.0 | 14.28 | 12.04 | DeltaKronecker-all | 64.94.95.114 |
| 70.47 | trojan | 307.7 | 665.2 | 20.66 | 0.0 | 10.0 | 14.28 | 12.04 | DeltaKronecker-all | 64.94.95.117 |
| 69.9 | trojan | 338.6 | 627.3 | 19.94 | 0.0 | 10.0 | 14.28 | 12.04 | DeltaKronecker-all | 64.94.95.115 |
| 69.43 | trojan | 307.8 | 668.3 | 20.65 | 0.0 | 10.0 | 14.28 | 10.88 | mheidari-all | 64.94.95.118 |
| 67.2 | vless | 260.0 | 702.2 | 21.76 | 0.0 | 10.0 | 5.4 | 14.54 | Surfboard-tg-mixed | 104.18.42.163 |
| 66.95 | vless | 162.8 | 441.2 | 24.01 | 0.0 | 10.0 | 5.4 | 12.04 | DeltaKronecker-all | 92.223.71.246 |
| 64.98 | trojan | 544.0 | 946.8 | 15.18 | 0.0 | 10.0 | 14.28 | 12.04 | DeltaKronecker-all | 5.10.215.9 |
| 64.18 | trojan | 452.8 | 618.6 | 17.3 | 0.0 | 10.0 | 14.28 | 14.54 | Surfboard-tg-mixed | 172.64.53.65 |
| 63.61 | trojan | 425.8 | 353.4 | 17.92 | 1.75 | 9.46 | 14.28 | 10.88 | mheidari-all | 119.246.1.143 |
| 62.66 | trojan | 394.0 | 472.1 | 18.66 | 0.0 | 10.0 | 14.28 | 14.54 | Surfboard-tg-mixed | 104.17.122.62 |
| 62.42 | shadowsocks | 481.5 | 744.3 | 16.63 | 0.0 | 9.58 | 13.99 | 14.54 | Surfboard-tg-mixed | 45.77.232.213 |
| 62.16 | shadowsocks | 453.0 | 424.6 | 17.29 | 0.0 | 9.2 | 13.99 | 14.54 | Surfboard-tg-mixed | 103.106.229.69 |
| 61.94 | trojan | 548.8 | 654.7 | 15.07 | 0.0 | 10.0 | 14.28 | 12.04 | DeltaKronecker-all | 172.67.149.1 |
| 61.08 | trojan | 611.8 | 913.3 | 13.62 | 0.0 | 10.0 | 14.28 | 14.54 | Surfboard-tg-mixed | 104.16.174.12 |
| 60.69 | trojan | 361.5 | 406.3 | 19.41 | 0.0 | 9.94 | 14.28 | 12.04 | DeltaKronecker-all | 18.179.120.96 |
| 60.63 | shadowsocks | 559.5 | 862.5 | 14.83 | 0.0 | 9.36 | 13.99 | 14.54 | Surfboard-tg-mixed | 82.38.31.57 |
| 60.58 | trojan | 615.5 | 907.5 | 13.53 | 0.0 | 10.0 | 14.28 | 12.04 | DeltaKronecker-all | 104.18.15.230 |
| 60.55 | shadowsocks | 559.6 | 868.6 | 14.82 | 0.0 | 9.32 | 13.99 | 14.54 | Surfboard-tg-mixed | 82.38.31.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.772 | 0.696 | 115 | 5436 | prefer |
| mheidari-all | 0.751 | 0.676 | 68 | 16299 | prefer |
| DeltaKronecker-all | 0.736 | 0.658 | 193 | 7926 | prefer |
| nscl5-all | 0.316 | 1.0 | 1 | 1526 | observe |
| xiaoji235-airport-v2ray-all | 0.273 | 0.5 | 2 | 1647 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 3897 | observe |
| Epodonios-all | 0.255 | None | 0 | 6476 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3979 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6409 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4097 | observe |
| barry-far-vless | 0.255 | None | 0 | 4724 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5412 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 40 |
| speed | ClientOSError | - | 23 |
| cn-block | ClientOSError | - | 11 |
| 204 | ProxyError | - | 10 |
| 204 | TimeoutError | - | 9 |
| geo | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 7 |
| speed | TimeoutError | - | 5 |
| speed | ProxyError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 291 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
