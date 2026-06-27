# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-27 08:35:25 |
| 运行耗时 | 243.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 77211 |
| 去重后节点 | 22988 |
| TCP 可达 | 3000 |
| 真实可用 | 438 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22988 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 30.2 |
| probe | 57.1 |
| real_test | 105.2 |
| generate | 44.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43354 |
| trojan | 12500 |
| vmess | 11324 |
| shadowsocks | 9470 |
| hysteria2 | 250 |
| shadowsocksr | 162 |
| http | 79 |
| socks | 61 |
| hysteria | 8 |
| tuic | 2 |
| anytls | 1 |

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
| 75.28 | trojan | 346.0 | 552.7 | 19.77 | 0.0 | 10.0 | 13.33 | 18.18 | Surfboard-tg-mixed | 94.140.0.100 |
| 75.04 | shadowsocks | 195.1 | 479.1 | 23.26 | 0.0 | 10.0 | 13.48 | 12.8 | Au1rxx-base64 | 108.181.118.10 |
| 74.76 | shadowsocks | 229.0 | 517.3 | 22.48 | 0.0 | 10.0 | 13.48 | 12.8 | Au1rxx-base64 | 173.244.56.9 |
| 74.68 | shadowsocks | 232.3 | 548.0 | 22.4 | 0.0 | 10.0 | 13.48 | 12.8 | Au1rxx-base64 | 149.22.95.183 |
| 74.51 | trojan | 297.9 | 748.6 | 20.88 | 0.0 | 10.0 | 13.33 | 12.8 | Au1rxx-base64 | 45.61.52.243 |
| 74.36 | trojan | 304.6 | 774.6 | 20.73 | 0.0 | 10.0 | 13.33 | 12.8 | Au1rxx-base64 | 207.126.167.150 |
| 73.92 | shadowsocks | 243.5 | 620.5 | 22.14 | 0.0 | 10.0 | 13.48 | 12.8 | Au1rxx-base64 | 108.181.0.177 |
| 73.62 | vless | 248.1 | 567.8 | 22.04 | 0.0 | 10.0 | 6.8 | 14.78 | mheidari-all | 34.213.172.16 |
| 70.81 | trojan | 376.7 | 871.4 | 19.06 | 0.0 | 10.0 | 13.33 | 14.78 | mheidari-all | 64.94.95.118 |
| 70.8 | trojan | 420.5 | 766.8 | 18.04 | 0.0 | 10.0 | 13.33 | 12.8 | Au1rxx-base64 | 207.126.167.162 |
| 70.38 | shadowsocks | 287.0 | 640.4 | 21.13 | 0.0 | 10.0 | 13.48 | 12.8 | Au1rxx-base64 | 156.146.38.170 |
| 70.37 | shadowsocks | 293.1 | 339.2 | 20.99 | 2.28 | 9.95 | 13.48 | 14.78 | mheidari-all | 149.22.87.204 |
| 70.22 | shadowsocks | 291.5 | 662.2 | 21.03 | 0.0 | 10.0 | 13.48 | 12.8 | Au1rxx-base64 | 156.146.38.169 |
| 70.03 | vless | 317.5 | 840.1 | 20.43 | 0.0 | 10.0 | 6.8 | 12.8 | Au1rxx-base64 | 15.204.97.214 |
| 70.03 | vless | 317.6 | 842.2 | 20.43 | 0.0 | 10.0 | 6.8 | 12.8 | Au1rxx-base64 | 15.204.97.219 |
| 69.93 | shadowsocks | 295.2 | 348.4 | 20.94 | 1.94 | 9.95 | 13.48 | 14.78 | mheidari-all | 149.22.87.241 |
| 69.74 | shadowsocks | 287.5 | 637.5 | 21.12 | 0.0 | 10.0 | 13.48 | 12.8 | Au1rxx-base64 | 156.146.38.168 |
| 69.67 | shadowsocks | 328.5 | 772.1 | 20.17 | 0.0 | 10.0 | 13.48 | 12.8 | Au1rxx-base64 | 156.146.38.167 |
| 69.16 | shadowsocks | 254.7 | 635.8 | 21.88 | 0.0 | 10.0 | 13.48 | 12.8 | Au1rxx-base64 | 173.244.56.6 |
| 69.04 | trojan | 411.2 | 532.4 | 18.26 | 0.0 | 10.0 | 13.33 | 18.18 | Surfboard-tg-mixed | 45.131.4.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.89 | 1.0 | 18 | 39 | prefer |
| Au1rxx-base64 | 0.809 | 0.824 | 34 | 91 | prefer |
| Surfboard-tg-mixed | 0.806 | 0.728 | 261 | 5179 | prefer |
| mheidari-all | 0.713 | 0.634 | 216 | 16368 | prefer |
| DeltaKronecker-all | 0.678 | 0.6 | 105 | 6822 | observe |
| nscl5-all | 0.302 | 1.0 | 1 | 1186 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4579 | observe |
| Epodonios-all | 0.255 | None | 0 | 7835 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3979 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7359 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3796 | observe |
| barry-far-vless | 0.255 | None | 0 | 4577 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5283 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 84 |
| geo | TimeoutError | - | 32 |
| 204 | ClientOSError | - | 22 |
| 204 | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 13 |
| 204 | ProxyError | - | 11 |
| geo | ClientOSError | - | 10 |
| speed | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
