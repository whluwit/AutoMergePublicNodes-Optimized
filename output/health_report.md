# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-13 19:02:23 |
| 运行耗时 | 332.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 80477 |
| 去重后节点 | 22570 |
| TCP 可达 | 3000 |
| 真实可用 | 850 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22570 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 34.9 |
| probe | 67.8 |
| real_test | 181.5 |
| generate | 40.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45188 |
| vmess | 13377 |
| trojan | 10227 |
| shadowsocks | 10028 |
| hysteria2 | 1338 |
| http | 152 |
| socks | 78 |
| shadowsocksr | 72 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 2 |

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
| 82.56 | http | 251.3 | 561.5 | 21.96 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 82.31 | http | 248.8 | 545.7 | 22.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 82.1 | http | 246.1 | 539.7 | 22.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 82.0 | http | 243.7 | 538.7 | 22.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 81.75 | http | 252.1 | 548.9 | 21.94 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 81.68 | http | 248.4 | 553.3 | 22.03 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 81.52 | http | 252.3 | 554.0 | 21.94 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 81.46 | http | 251.3 | 544.3 | 21.96 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 81.32 | http | 243.0 | 528.0 | 22.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 81.3 | http | 247.4 | 547.4 | 22.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 81.18 | http | 241.7 | 537.0 | 22.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 81.17 | http | 247.5 | 559.1 | 22.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 80.9 | shadowsocks | 264.3 | 618.1 | 21.66 | 0.0 | 10.0 | 13.74 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 80.8 | http | 253.3 | 566.9 | 21.92 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 79.37 | trojan | 284.1 | 575.9 | 21.2 | 0.0 | 10.0 | 14.49 | 20.0 | Au1rxx-base64 | 35.86.90.51 |
| 79.33 | hysteria2 | 309.7 | 696.8 | 20.61 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 78.34 | hysteria2 | 321.5 | 609.3 | 20.34 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 150.241.102.127 |
| 78.18 | trojan | 333.1 | 719.5 | 20.07 | 0.0 | 10.0 | 14.49 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 77.89 | hysteria2 | 327.1 | 747.1 | 20.2 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 77.58 | vless | 263.5 | 543.9 | 21.68 | 0.0 | 10.0 | 10.07 | 20.0 | Au1rxx-base64 | 179.253.240.24 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.975 | 0.911 | 618 | 1639 | prefer |
| mheidari-all | 0.883 | 0.809 | 115 | 16814 | prefer |
| Surfboard-tg-mixed | 0.821 | 0.75 | 56 | 6036 | prefer |
| DeltaKronecker-all | 0.734 | 0.667 | 24 | 4878 | prefer |
| ninja-vless | 0.56 | 0.875 | 8 | 1791 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5203 | observe |
| Epodonios-all | 0.255 | None | 0 | 6692 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7892 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4739 | observe |
| barry-far-vless | 0.255 | None | 0 | 5103 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5197 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1639 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 27 |
| geo | TimeoutError | - | 16 |
| cn-block | TimeoutError | - | 13 |
| geo | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 8 |
| 204 | ProxyError | - | 7 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
