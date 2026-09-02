# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-02 15:55:41 |
| 运行耗时 | 261.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82533 |
| 去重后节点 | 23511 |
| TCP 可达 | 3000 |
| 真实可用 | 590 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23511 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.7 |
| geo | 1.5 |
| tcp | 38.2 |
| probe | 67.4 |
| real_test | 119.9 |
| generate | 31.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51747 |
| vmess | 11166 |
| shadowsocks | 9965 |
| trojan | 7703 |
| hysteria2 | 1581 |
| http | 143 |
| shadowsocksr | 130 |
| socks | 80 |
| tuic | 11 |
| hysteria | 7 |

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
| 82.46 | vless | 277.6 | 660.8 | 21.35 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 195.211.99.49 |
| 81.27 | hysteria2 | 253.7 | 557.6 | 21.9 | 0.0 | 10.0 | 13.64 | 19.34 | Au1rxx-base64 | 66.94.121.46 |
| 81.23 | shadowsocks | 243.7 | 616.0 | 22.14 | 0.0 | 10.0 | 13.75 | 19.34 | Au1rxx-base64 | 156.146.38.169 |
| 81.01 | shadowsocks | 252.9 | 616.5 | 21.92 | 0.0 | 10.0 | 13.75 | 19.34 | Au1rxx-base64 | 156.146.38.167 |
| 80.92 | shadowsocks | 244.8 | 624.7 | 22.11 | 0.0 | 10.0 | 13.75 | 19.34 | Au1rxx-base64 | 156.146.38.168 |
| 79.94 | vless | 258.9 | 632.6 | 21.78 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 195.211.99.45 |
| 78.72 | shadowsocks | 245.5 | 603.2 | 22.09 | 0.0 | 10.0 | 13.75 | 19.34 | Au1rxx-base64 | 23.150.248.20 |
| 78.62 | shadowsocks | 334.5 | 863.6 | 20.03 | 0.0 | 10.0 | 13.75 | 19.34 | Au1rxx-base64 | 84.32.131.61 |
| 78.43 | vless | 285.2 | 564.1 | 21.18 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 172.233.156.123 |
| 78.33 | vless | 315.5 | 699.8 | 20.47 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 204.48.20.223 |
| 78.04 | vless | 293.2 | 580.0 | 20.99 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 172.239.67.231 |
| 77.67 | vless | 294.7 | 624.1 | 20.95 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 172.236.252.35 |
| 77.64 | vless | 310.1 | 676.0 | 20.6 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 130.107.73.148 |
| 77.47 | vless | 293.1 | 599.2 | 20.99 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 172.239.67.156 |
| 77.43 | vless | 360.6 | 218.9 | 19.43 | 6.79 | 9.58 | 11.77 | 17.3 | Surfboard-tg-mixed | 31.76.91.72 |
| 77.33 | shadowsocks | 289.1 | 692.5 | 21.09 | 0.0 | 10.0 | 13.75 | 19.34 | Au1rxx-base64 | 37.19.198.236 |
| 77.03 | vless | 308.9 | 592.8 | 20.63 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 45.79.103.108 |
| 76.96 | vless | 304.8 | 605.3 | 20.72 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 45.33.62.166 |
| 76.91 | vless | 336.6 | 696.4 | 19.99 | 0.0 | 10.0 | 11.77 | 19.34 | Au1rxx-base64 | 169.40.42.225 |
| 76.88 | shadowsocks | 238.7 | 608.8 | 22.25 | 0.0 | 10.0 | 13.75 | 14.88 | mheidari-all | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | 0.909 | 353 | 1740 | prefer |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| mheidari-all | 0.926 | 0.851 | 121 | 15532 | prefer |
| DeltaKronecker-all | 0.813 | 0.75 | 28 | 7295 | prefer |
| Surfboard-tg-mixed | 0.811 | 0.733 | 165 | 7112 | prefer |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 103 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4765 | observe |
| Epodonios-all | 0.255 | None | 0 | 7553 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7750 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5992 | observe |
| barry-far-vless | 0.255 | None | 0 | 6200 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4066 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 17 |
| geo | ClientOSError | - | 16 |
| cn-block | ClientOSError | - | 14 |
| speed | TimeoutError | - | 8 |
| speed | ClientOSError | - | 7 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
