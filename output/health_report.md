# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-21 23:42:41 |
| 运行耗时 | 229.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 73413 |
| 去重后节点 | 22044 |
| TCP 可达 | 3000 |
| 真实可用 | 784 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22044 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.3 |
| tcp | 29.3 |
| probe | 50.4 |
| real_test | 122.8 |
| generate | 20.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42927 |
| trojan | 10017 |
| shadowsocks | 9953 |
| vmess | 9861 |
| hysteria2 | 250 |
| http | 182 |
| shadowsocksr | 160 |
| socks | 55 |
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
| 78.35 | vless | 257.4 | 619.2 | 21.82 | 0.0 | 10.0 | 11.93 | 19.6 | mheidari-all | 77.110.125.101 |
| 77.24 | shadowsocks | 220.9 | 594.0 | 22.67 | 0.0 | 10.0 | 13.97 | 19.6 | mheidari-all | 198.98.53.130 |
| 77.15 | vless | 241.6 | 658.5 | 22.18 | 0.0 | 10.0 | 11.93 | 18.04 | Au1rxx-base64 | 137.184.218.169 |
| 76.84 | vless | 255.0 | 718.8 | 21.87 | 0.0 | 10.0 | 11.93 | 18.04 | Au1rxx-base64 | 47.253.226.114 |
| 75.59 | shadowsocks | 224.7 | 612.4 | 22.58 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 37.19.198.160 |
| 75.55 | shadowsocks | 226.2 | 621.4 | 22.54 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 37.19.198.244 |
| 74.38 | shadowsocks | 276.9 | 771.2 | 21.37 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 37.19.198.243 |
| 74.15 | shadowsocks | 265.1 | 738.4 | 21.64 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 69.164.240.83 |
| 74.07 | shadowsocks | 290.1 | 815.6 | 21.06 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 37.19.198.236 |
| 73.98 | shadowsocks | 339.9 | 955.5 | 19.91 | 0.0 | 10.0 | 13.97 | 19.6 | mheidari-all | 161.129.71.148 |
| 72.96 | vless | 315.6 | 769.1 | 20.47 | 0.0 | 10.0 | 11.93 | 19.6 | mheidari-all | 185.156.47.96 |
| 71.76 | shadowsocks | 287.4 | 659.5 | 21.12 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 156.146.38.169 |
| 71.73 | shadowsocks | 284.2 | 643.5 | 21.2 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 156.146.38.168 |
| 71.7 | trojan | 347.4 | 859.2 | 19.74 | 0.0 | 10.0 | 13.4 | 18.04 | Au1rxx-base64 | 130.94.114.217 |
| 71.32 | shadowsocks | 387.4 | 1100.5 | 18.81 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 69.164.240.86 |
| 71.26 | shadowsocks | 390.2 | 1098.5 | 18.75 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 205.209.104.91 |
| 71.06 | shadowsocks | 315.0 | 784.1 | 20.49 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 107.172.250.161 |
| 70.79 | shadowsocks | 275.1 | 626.3 | 21.41 | 0.0 | 10.0 | 13.97 | 18.04 | Au1rxx-base64 | 156.146.38.170 |
| 70.4 | shadowsocks | 240.4 | 658.3 | 22.21 | 0.0 | 10.0 | 13.97 | 13.72 | DeltaKronecker-all | 142.93.183.235 |
| 70.37 | shadowsocks | 242.0 | 646.8 | 22.18 | 0.0 | 10.0 | 13.97 | 13.72 | DeltaKronecker-all | 108.181.57.93 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.991 | 1.0 | 69 | 131 | prefer |
| mheidari-all | 0.99 | 0.913 | 322 | 15086 | prefer |
| Au1rxx-base64 | 0.943 | 0.946 | 93 | 145 | prefer |
| DeltaKronecker-all | 0.929 | 0.857 | 84 | 6748 | prefer |
| Surfboard-tg-mixed | 0.89 | 0.812 | 319 | 4776 | prefer |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4494 | observe |
| Epodonios-all | 0.255 | None | 0 | 7251 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3978 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6970 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3678 | observe |
| barry-far-vless | 0.255 | None | 0 | 4524 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4505 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 36 |
| geo | TimeoutError | - | 18 |
| speed | TimeoutError | - | 11 |
| cn-block | TimeoutError | - | 11 |
| 204 | ProxyError | - | 8 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 4 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
