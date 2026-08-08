# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-08 01:18:43 |
| 运行耗时 | 332.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82220 |
| 去重后节点 | 23542 |
| TCP 可达 | 3000 |
| 真实可用 | 748 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23542 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 34.8 |
| probe | 64.2 |
| real_test | 183.6 |
| generate | 43.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47707 |
| vmess | 12911 |
| trojan | 10278 |
| shadowsocks | 9853 |
| hysteria2 | 1278 |
| shadowsocksr | 71 |
| socks | 65 |
| http | 35 |
| hysteria | 13 |
| tuic | 8 |
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
| 84.43 | hysteria2 | 245.4 | 665.9 | 22.1 | 0.0 | 10.0 | 13.75 | 19.68 | Au1rxx-base64 | 159.223.157.129 |
| 84.33 | hysteria2 | 253.7 | 687.3 | 21.9 | 0.0 | 10.0 | 13.75 | 19.68 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 84.15 | hysteria2 | 261.5 | 712.7 | 21.72 | 0.0 | 10.0 | 13.75 | 19.68 | Au1rxx-base64 | 138.124.68.188 |
| 80.71 | shadowsocks | 240.1 | 638.4 | 22.22 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 37.19.198.244 |
| 80.17 | shadowsocks | 263.5 | 714.5 | 21.68 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 37.19.198.236 |
| 80.15 | shadowsocks | 264.5 | 704.0 | 21.66 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 37.19.198.160 |
| 79.86 | shadowsocks | 233.6 | 619.6 | 22.37 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 37.19.198.243 |
| 78.01 | shadowsocks | 281.0 | 637.1 | 21.27 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 156.146.38.170 |
| 77.77 | shadowsocks | 275.6 | 619.7 | 21.4 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 156.146.38.167 |
| 77.27 | shadowsocks | 277.4 | 635.1 | 21.36 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 156.146.38.168 |
| 77.06 | shadowsocks | 285.6 | 660.1 | 21.17 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 156.146.38.169 |
| 76.2 | shadowsocks | 357.2 | 881.4 | 19.51 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 185.196.61.82 |
| 76.1 | hysteria2 | 353.7 | 681.5 | 19.59 | 0.0 | 9.98 | 13.75 | 19.68 | Au1rxx-base64 | 62.210.124.146 |
| 75.64 | trojan | 440.6 | 1094.4 | 17.58 | 0.0 | 10.0 | 14.49 | 19.68 | Au1rxx-base64 | 64.94.95.117 |
| 75.63 | hysteria2 | 409.0 | 849.0 | 18.31 | 0.0 | 10.0 | 13.75 | 19.68 | Au1rxx-base64 | 5.129.235.85 |
| 75.33 | vless | 391.6 | 1060.5 | 18.71 | 0.0 | 10.0 | 8.94 | 19.68 | Au1rxx-base64 | 159.89.87.21 |
| 75.09 | hysteria2 | 355.0 | 671.0 | 19.56 | 0.0 | 10.0 | 13.75 | 19.68 | Au1rxx-base64 | 31.76.113.32 |
| 74.88 | hysteria2 | 428.3 | 879.9 | 17.86 | 0.0 | 9.97 | 13.75 | 19.68 | Au1rxx-base64 | 5.255.102.165 |
| 74.25 | shadowsocks | 303.2 | 825.3 | 20.76 | 0.0 | 10.0 | 12.81 | 19.68 | Au1rxx-base64 | 198.98.53.130 |
| 74.24 | vless | 307.2 | 642.7 | 20.67 | 0.0 | 10.0 | 8.94 | 19.68 | Au1rxx-base64 | 104.16.117.43 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | 0.937 | 444 | 1365 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.611 | 0.533 | 30 | 6430 | observe |
| mheidari-all | 0.602 | 0.588 | 17 | 17687 | observe |
| DeltaKronecker-all | 0.455 | 0.375 | 761 | 5326 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7081 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7469 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5180 | observe |
| barry-far-vless | 0.255 | None | 0 | 5509 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5175 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.241 | None | 0 | 1643 | observe |
| Au1rxx-clash | 0.23 | None | 0 | 1365 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 247 |
| geo | ClientOSError | - | 81 |
| cn-block | TimeoutError | - | 77 |
| speed | ClientOSError | - | 57 |
| speed | TimeoutError | - | 44 |
| 204 | TimeoutError | - | 6 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
