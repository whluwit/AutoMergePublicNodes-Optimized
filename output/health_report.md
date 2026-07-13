# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-13 14:26:54 |
| 运行耗时 | 194.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 77657 |
| 去重后节点 | 23879 |
| TCP 可达 | 3000 |
| 真实可用 | 226 |
| Verified 输出 | 226 |
| Global 输出 | 239 |
| All 输出 | 23879 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.4 |
| tcp | 32.1 |
| probe | 43.9 |
| real_test | 78.5 |
| generate | 34.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45068 |
| trojan | 11438 |
| vmess | 10821 |
| shadowsocks | 9635 |
| hysteria2 | 381 |
| shadowsocksr | 142 |
| http | 138 |
| socks | 26 |
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
| 70.93 | trojan | 298.9 | 647.4 | 20.86 | 0.0 | 10.0 | 11.37 | 14.72 | DeltaKronecker-all | 64.94.95.115 |
| 70.91 | trojan | 297.1 | 648.6 | 20.9 | 0.0 | 10.0 | 11.37 | 14.72 | DeltaKronecker-all | 64.94.95.117 |
| 70.53 | vmess | 446.0 | 1262.0 | 17.45 | 0.0 | 10.0 | 12.86 | 14.72 | DeltaKronecker-all | 67.220.85.46 |
| 68.82 | trojan | 385.6 | 887.4 | 18.85 | 0.0 | 10.0 | 11.37 | 15.02 | mheidari-all | 64.94.95.118 |
| 67.51 | trojan | 295.3 | 642.4 | 20.94 | 0.0 | 10.0 | 11.37 | 14.72 | DeltaKronecker-all | 64.94.95.114 |
| 65.65 | http | 635.3 | 956.6 | 13.07 | 0.0 | 9.69 | 14.61 | 19.52 | snakem982 | 84.239.49.185 |
| 65.52 | shadowsocks | 418.5 | 768.7 | 18.09 | 0.0 | 10.0 | 12.84 | 15.44 | Surfboard-tg-mixed | 82.38.31.29 |
| 65.51 | http | 640.1 | 964.8 | 12.96 | 0.0 | 9.67 | 14.61 | 19.52 | snakem982 | 84.239.14.160 |
| 65.5 | http | 643.9 | 968.5 | 12.87 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.49.157 |
| 65.48 | http | 638.0 | 980.5 | 13.01 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.49.253 |
| 65.44 | shadowsocks | 418.2 | 739.0 | 18.1 | 0.0 | 10.0 | 12.84 | 15.44 | Surfboard-tg-mixed | 82.38.31.32 |
| 65.44 | http | 648.4 | 970.0 | 12.77 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.49.247 |
| 65.42 | http | 646.8 | 953.9 | 12.81 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.49.178 |
| 65.38 | http | 648.4 | 995.2 | 12.77 | 0.0 | 9.76 | 14.61 | 19.52 | snakem982 | 84.239.49.160 |
| 65.36 | http | 651.4 | 985.1 | 12.7 | 0.0 | 9.76 | 14.61 | 19.52 | snakem982 | 84.239.49.202 |
| 65.35 | http | 651.9 | 961.3 | 12.69 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.49.211 |
| 65.34 | http | 650.2 | 995.7 | 12.73 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.49.39 |
| 65.27 | http | 655.9 | 994.0 | 12.59 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.49.154 |
| 65.26 | http | 654.1 | 978.7 | 12.64 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.49.234 |
| 65.25 | http | 650.6 | 985.8 | 12.72 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.14.149 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.778 | 0.706 | 51 | 16239 | prefer |
| Surfboard-tg-mixed | 0.725 | 0.647 | 119 | 5596 | prefer |
| DeltaKronecker-all | 0.709 | 0.632 | 114 | 7926 | prefer |
| nscl5-all | 0.372 | 1.0 | 2 | 1526 | observe |
| xiaoji235-airport-v2ray-all | 0.321 | 1.0 | 1 | 1647 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Au1rxx-base64 | 0.259 | 1.0 | 1 | 109 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 3897 | observe |
| Epodonios-all | 0.255 | None | 0 | 6473 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6904 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4341 | observe |
| barry-far-vless | 0.255 | None | 0 | 4964 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5412 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 42 |
| speed | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 8 |
| cn-block | TimeoutError | - | 8 |
| 204 | ProxyError | - | 7 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 2 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 291 | 226 | - |
| global | False | 300 | 239 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
