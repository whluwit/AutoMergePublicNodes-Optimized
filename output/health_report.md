# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-11 18:59:46 |
| 运行耗时 | 249.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81050 |
| 去重后节点 | 23063 |
| TCP 可达 | 3000 |
| 真实可用 | 552 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23063 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 34.6 |
| probe | 55.9 |
| real_test | 123.1 |
| generate | 28.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46282 |
| vmess | 13194 |
| trojan | 10285 |
| shadowsocks | 9723 |
| hysteria2 | 1247 |
| http | 159 |
| shadowsocksr | 70 |
| socks | 68 |
| tuic | 12 |
| hysteria | 10 |

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
| 85.24 | http | 190.2 | 484.9 | 23.38 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 85.23 | http | 190.5 | 496.2 | 23.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 85.23 | http | 190.6 | 490.7 | 23.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 85.19 | http | 192.3 | 493.7 | 23.33 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 85.15 | http | 193.9 | 503.5 | 23.29 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 85.14 | http | 194.2 | 502.3 | 23.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 85.14 | http | 194.5 | 498.3 | 23.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 85.09 | http | 196.7 | 503.6 | 23.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 85.07 | http | 197.4 | 496.6 | 23.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 85.04 | http | 198.7 | 501.8 | 23.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 84.99 | http | 200.9 | 514.9 | 23.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 84.41 | http | 194.7 | 504.9 | 23.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 84.0 | http | 243.4 | 647.6 | 22.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 83.99 | http | 244.0 | 644.7 | 22.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 81.06 | vless | 191.1 | 483.3 | 23.35 | 0.0 | 10.0 | 9.63 | 18.08 | Au1rxx-base64 | 179.253.240.24 |
| 79.91 | vless | 241.0 | 632.0 | 22.2 | 0.0 | 10.0 | 9.63 | 18.08 | Au1rxx-base64 | 70.39.198.183 |
| 79.76 | shadowsocks | 240.1 | 621.0 | 22.22 | 0.0 | 10.0 | 13.46 | 18.08 | Au1rxx-base64 | 173.244.56.6 |
| 79.44 | shadowsocks | 207.7 | 512.7 | 22.97 | 0.0 | 10.0 | 13.46 | 18.08 | Au1rxx-base64 | 173.244.56.9 |
| 78.14 | shadowsocks | 265.3 | 647.2 | 21.64 | 0.0 | 10.0 | 13.46 | 18.08 | Au1rxx-base64 | 156.146.38.170 |
| 77.86 | shadowsocks | 256.0 | 619.8 | 21.85 | 0.0 | 10.0 | 13.46 | 18.08 | Au1rxx-base64 | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.998 | 1.0 | 125 | 159 | prefer |
| Au1rxx-base64 | 0.947 | 0.889 | 370 | 1503 | prefer |
| DeltaKronecker-all | 0.564 | 0.484 | 184 | 5522 | observe |
| Surfboard-tg-mixed | 0.489 | 0.667 | 9 | 6123 | observe |
| mheidari-all | 0.438 | 1.0 | 3 | 16649 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5419 | observe |
| Epodonios-all | 0.255 | None | 0 | 6762 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7634 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5008 | observe |
| barry-far-vless | 0.255 | None | 0 | 5313 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.239 | None | 0 | 1607 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1503 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 43 |
| 204 | TimeoutError | - | 27 |
| speed | TimeoutError | - | 18 |
| geo | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 12 |
| speed | ClientOSError | - | 11 |
| geo | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
