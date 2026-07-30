# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-30 13:51:59 |
| 运行耗时 | 251.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79209 |
| 去重后节点 | 23080 |
| TCP 可达 | 3000 |
| 真实可用 | 408 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23080 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.5 |
| tcp | 32.7 |
| probe | 54.6 |
| real_test | 113.8 |
| generate | 42.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46270 |
| vmess | 11353 |
| shadowsocks | 10420 |
| trojan | 10297 |
| hysteria2 | 557 |
| http | 116 |
| shadowsocksr | 74 |
| socks | 62 |
| anytls | 26 |
| tuic | 20 |
| hysteria | 14 |

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
| 82.75 | http | 210.4 | 513.8 | 22.91 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.196 |
| 80.22 | http | 190.2 | 474.7 | 23.38 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.208 |
| 80.08 | http | 195.9 | 493.0 | 23.24 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.199 |
| 80.08 | http | 196.2 | 489.1 | 23.24 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.195 |
| 80.03 | http | 198.1 | 491.6 | 23.19 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.205 |
| 80.03 | http | 198.2 | 492.4 | 23.19 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.207 |
| 80.01 | http | 199.1 | 488.5 | 23.17 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.215 |
| 80.01 | http | 199.2 | 495.0 | 23.17 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.206 |
| 80.0 | http | 199.4 | 495.8 | 23.16 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.212 |
| 79.97 | http | 201.0 | 500.8 | 23.13 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.211 |
| 79.94 | http | 202.1 | 498.2 | 23.1 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.198 |
| 79.94 | http | 202.2 | 501.0 | 23.1 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.216 |
| 79.84 | http | 206.5 | 496.2 | 23.0 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.200 |
| 79.82 | http | 207.1 | 513.3 | 22.98 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.213 |
| 79.81 | http | 207.7 | 507.4 | 22.97 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.197 |
| 79.8 | http | 208.1 | 503.9 | 22.96 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.217 |
| 79.77 | http | 209.3 | 517.3 | 22.93 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.214 |
| 79.76 | http | 210.0 | 518.0 | 22.92 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.220 |
| 79.74 | http | 210.8 | 526.0 | 22.9 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.204 |
| 79.73 | http | 211.0 | 520.2 | 22.89 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | 1.0 | 113 | 129 | prefer |
| Au1rxx-base64 | 0.838 | 0.784 | 232 | 1399 | prefer |
| Surfboard-tg-mixed | 0.678 | 0.6 | 110 | 5442 | observe |
| DeltaKronecker-all | 0.625 | 0.547 | 75 | 5759 | observe |
| mheidari-all | 0.421 | 0.667 | 6 | 16336 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5342 | observe |
| Epodonios-all | 0.255 | None | 0 | 6193 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7149 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4363 | observe |
| barry-far-vless | 0.255 | None | 0 | 4667 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5029 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 33 |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 19 |
| geo | ClientOSError | - | 18 |
| speed | TimeoutError | - | 13 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
