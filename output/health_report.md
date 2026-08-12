# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-12 18:59:57 |
| 运行耗时 | 251.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79762 |
| 去重后节点 | 22328 |
| TCP 可达 | 3000 |
| 真实可用 | 587 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22328 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.4 |
| tcp | 33.2 |
| probe | 55.5 |
| real_test | 124.5 |
| generate | 29.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45399 |
| vmess | 13253 |
| shadowsocks | 9740 |
| trojan | 9706 |
| hysteria2 | 1341 |
| http | 159 |
| socks | 73 |
| shadowsocksr | 73 |
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
| 84.84 | http | 195.7 | 496.8 | 23.25 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.212 |
| 84.81 | http | 197.1 | 500.0 | 23.22 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.215 |
| 84.79 | http | 197.8 | 492.1 | 23.2 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.195 |
| 84.79 | http | 197.9 | 502.3 | 23.2 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.209 |
| 84.76 | http | 198.9 | 505.8 | 23.17 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.208 |
| 84.76 | http | 199.0 | 496.5 | 23.17 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.213 |
| 84.74 | http | 199.8 | 512.6 | 23.15 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.199 |
| 84.66 | http | 203.6 | 509.2 | 23.07 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.204 |
| 84.65 | http | 193.7 | 494.1 | 23.29 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.220 |
| 84.63 | http | 204.6 | 513.2 | 23.04 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.197 |
| 84.63 | http | 204.8 | 517.8 | 23.04 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.211 |
| 84.62 | http | 205.1 | 508.2 | 23.03 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.210 |
| 84.6 | http | 206.0 | 514.3 | 23.01 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.206 |
| 83.46 | http | 196.2 | 488.1 | 23.24 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.214 |
| 81.54 | shadowsocks | 182.1 | 464.0 | 23.56 | 0.0 | 10.0 | 13.8 | 18.68 | Au1rxx-base64 | 70.39.178.204 |
| 81.0 | vless | 188.5 | 484.4 | 23.41 | 0.0 | 10.0 | 8.91 | 18.68 | Au1rxx-base64 | 179.253.240.24 |
| 80.95 | vless | 190.9 | 473.1 | 23.36 | 0.0 | 10.0 | 8.91 | 18.68 | Au1rxx-base64 | 179.255.148.66 |
| 80.08 | shadowsocks | 261.1 | 634.4 | 21.73 | 0.0 | 10.0 | 13.8 | 18.68 | Au1rxx-base64 | 156.146.38.170 |
| 80.02 | shadowsocks | 269.3 | 650.2 | 21.54 | 0.0 | 10.0 | 13.8 | 18.68 | Au1rxx-base64 | 173.244.56.9 |
| 79.71 | vless | 244.6 | 573.0 | 22.12 | 0.0 | 10.0 | 8.91 | 18.68 | Au1rxx-base64 | 216.167.37.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.934 | 0.867 | 460 | 1703 | prefer |
| mheidari-all | 0.749 | 0.923 | 13 | 16743 | prefer |
| Surfboard-tg-mixed | 0.741 | 0.667 | 57 | 5975 | prefer |
| DeltaKronecker-all | 0.602 | 0.588 | 17 | 4975 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5328 | observe |
| Epodonios-all | 0.255 | None | 0 | 6597 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7349 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4789 | observe |
| barry-far-vless | 0.255 | None | 0 | 5121 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5209 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1703 | observe |
| nscl5-all | 0.234 | None | 0 | 1481 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 9 |
| geo | TimeoutError | - | 9 |
| geo | ClientOSError | - | 6 |
| 204 | ProxyError | - | 6 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
