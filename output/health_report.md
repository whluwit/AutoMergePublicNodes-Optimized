# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-16 12:34:59 |
| 运行耗时 | 344.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 79014 |
| 去重后节点 | 21913 |
| TCP 可达 | 3000 |
| 真实可用 | 1111 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21913 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 0.9 |
| tcp | 33.1 |
| probe | 66.2 |
| real_test | 209.1 |
| generate | 30.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43530 |
| trojan | 13275 |
| vmess | 10846 |
| shadowsocks | 9979 |
| hysteria2 | 1053 |
| http | 166 |
| socks | 75 |
| shadowsocksr | 71 |
| tuic | 10 |
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
| 85.37 | http | 184.4 | 474.0 | 23.51 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 85.25 | http | 189.4 | 491.5 | 23.39 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 85.17 | http | 192.9 | 495.5 | 23.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 85.17 | http | 192.9 | 489.0 | 23.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 85.15 | http | 194.0 | 495.8 | 23.29 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 85.1 | http | 196.1 | 487.1 | 23.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 85.08 | http | 197.1 | 492.1 | 23.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 85.05 | http | 198.1 | 504.6 | 23.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 85.04 | http | 198.6 | 494.8 | 23.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 85.02 | http | 199.7 | 503.2 | 23.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 85.0 | http | 200.5 | 506.8 | 23.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 84.99 | http | 200.6 | 515.4 | 23.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 84.98 | http | 201.1 | 501.3 | 23.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 84.8 | http | 209.1 | 538.1 | 22.94 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 83.42 | trojan | 264.3 | 719.7 | 21.66 | 0.0 | 10.0 | 14.76 | 20.0 | Au1rxx-base64 | 14.1.28.76 |
| 83.01 | shadowsocks | 211.1 | 511.5 | 22.89 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 82.67 | shadowsocks | 225.7 | 521.4 | 22.55 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 82.47 | shadowsocks | 200.6 | 492.2 | 23.13 | 0.0 | 9.72 | 14.12 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 82.02 | shadowsocks | 220.4 | 534.9 | 22.68 | 0.0 | 9.72 | 14.12 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 81.88 | shadowsocks | 247.8 | 605.3 | 22.04 | 0.0 | 9.72 | 14.12 | 20.0 | Au1rxx-base64 | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.961 | 800 | 1994 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.885 | 0.808 | 172 | 16375 | prefer |
| Surfboard-tg-mixed | 0.853 | 0.779 | 86 | 5800 | prefer |
| DeltaKronecker-all | 0.444 | 0.35 | 20 | 5092 | observe |
| nscl5-all | 0.335 | 1.0 | 1 | 2601 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1994 | observe |
| Epodonios-all | 0.255 | None | 0 | 6483 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7383 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4502 | observe |
| barry-far-vless | 0.255 | None | 0 | 4839 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3950 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 18 |
| speed | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 16 |
| geo | ClientOSError | - | 14 |
| 204 | TimeoutError | - | 11 |
| speed | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
