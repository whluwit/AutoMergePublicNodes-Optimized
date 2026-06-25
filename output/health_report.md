# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-25 19:57:13 |
| 运行耗时 | 241.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 82452 |
| 去重后节点 | 22858 |
| TCP 可达 | 3000 |
| 真实可用 | 302 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22858 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.3 |
| tcp | 29.9 |
| probe | 57.4 |
| real_test | 104.8 |
| generate | 42.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45800 |
| trojan | 14918 |
| vmess | 11018 |
| shadowsocks | 10105 |
| hysteria2 | 264 |
| shadowsocksr | 154 |
| http | 118 |
| socks | 67 |
| hysteria | 6 |
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
| 77.95 | shadowsocks | 252.2 | 610.0 | 21.94 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 156.146.38.168 |
| 77.89 | shadowsocks | 254.7 | 617.2 | 21.88 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 156.146.38.167 |
| 77.82 | shadowsocks | 257.7 | 641.4 | 21.81 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 198.98.53.130 |
| 77.55 | shadowsocks | 269.6 | 661.0 | 21.54 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 37.19.198.160 |
| 77.51 | shadowsocks | 271.1 | 650.7 | 21.5 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 37.19.198.243 |
| 77.37 | shadowsocks | 276.0 | 666.2 | 21.39 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 37.19.198.244 |
| 76.7 | shadowsocks | 284.8 | 702.1 | 21.19 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 108.181.57.93 |
| 75.57 | shadowsocks | 266.7 | 656.4 | 21.6 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 37.19.198.236 |
| 75.25 | shadowsocks | 256.0 | 622.9 | 21.85 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 156.146.38.170 |
| 74.5 | shadowsocks | 252.2 | 616.4 | 21.94 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 156.146.38.169 |
| 72.01 | shadowsocks | 286.8 | 581.7 | 21.14 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 149.22.95.183 |
| 71.89 | shadowsocks | 298.5 | 586.7 | 20.87 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 173.244.56.6 |
| 70.32 | shadowsocks | 309.6 | 567.4 | 20.61 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 173.244.56.9 |
| 68.95 | shadowsocks | 284.7 | 569.8 | 21.19 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | 216.105.168.18 |
| 68.89 | vmess | 370.7 | 960.3 | 19.2 | 0.0 | 10.0 | 12.5 | 12.54 | mheidari-all | 67.220.95.3 |
| 68.2 | vless | 302.1 | 761.0 | 20.79 | 0.0 | 10.0 | 4.87 | 12.54 | mheidari-all | 47.253.226.114 |
| 67.46 | shadowsocks | 340.0 | 868.5 | 19.91 | 0.0 | 10.0 | 12.15 | 17.86 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 66.51 | shadowsocks | 380.5 | 405.0 | 18.97 | 0.0 | 9.48 | 12.15 | 17.86 | Au1rxx-base64 | 149.22.87.240 |
| 66.22 | shadowsocks | 392.2 | 430.9 | 18.7 | 0.0 | 9.46 | 12.15 | 17.86 | Au1rxx-base64 | 149.22.87.241 |
| 66.19 | shadowsocks | 394.1 | 429.7 | 18.66 | 0.0 | 9.46 | 12.15 | 17.86 | Au1rxx-base64 | 149.22.87.204 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | 1.0 | 36 | 82 | prefer |
| Au1rxx-base64 | 0.828 | 0.837 | 49 | 104 | prefer |
| mheidari-all | 0.739 | 0.661 | 177 | 16098 | prefer |
| Surfboard-tg-mixed | 0.665 | 0.587 | 92 | 5257 | observe |
| DeltaKronecker-all | 0.544 | 0.464 | 110 | 12590 | observe |
| nscl5-all | 0.357 | 1.0 | 2 | 1136 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4787 | observe |
| Epodonios-all | 0.255 | None | 0 | 7883 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7166 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3824 | observe |
| barry-far-vless | 0.255 | None | 0 | 4620 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5117 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 51 |
| 204 | TimeoutError | - | 27 |
| 204 | ProxyError | - | 20 |
| cn-block | TimeoutError | - | 17 |
| 204 | ClientOSError | - | 15 |
| geo | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 6 |
| geo | ProxyError | - | 5 |
| geo | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
