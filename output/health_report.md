# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-16 01:06:51 |
| 运行耗时 | 395.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 79369 |
| 去重后节点 | 22340 |
| TCP 可达 | 3000 |
| 真实可用 | 1142 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22340 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 0.7 |
| tcp | 33.3 |
| probe | 68.9 |
| real_test | 249.8 |
| generate | 36.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43281 |
| trojan | 14135 |
| vmess | 10734 |
| shadowsocks | 9834 |
| hysteria2 | 1016 |
| http | 182 |
| socks | 89 |
| shadowsocksr | 79 |
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
| 84.97 | http | 189.8 | 491.6 | 23.38 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.214 |
| 84.95 | http | 191.0 | 489.1 | 23.36 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.195 |
| 84.94 | http | 191.4 | 493.7 | 23.35 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.220 |
| 84.88 | http | 193.8 | 485.3 | 23.29 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.210 |
| 84.85 | http | 195.4 | 494.4 | 23.26 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.206 |
| 84.83 | http | 196.0 | 495.4 | 23.24 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.215 |
| 84.8 | http | 197.5 | 503.1 | 23.21 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.204 |
| 84.79 | http | 197.9 | 497.9 | 23.2 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.212 |
| 84.78 | http | 198.3 | 501.1 | 23.19 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.208 |
| 84.77 | http | 198.6 | 503.0 | 23.18 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.209 |
| 84.77 | http | 198.7 | 497.1 | 23.18 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.199 |
| 84.73 | http | 200.5 | 507.1 | 23.14 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.197 |
| 84.7 | http | 201.5 | 512.6 | 23.11 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.211 |
| 84.64 | http | 204.1 | 518.1 | 23.05 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.213 |
| 84.17 | vless | 202.6 | 454.7 | 23.09 | 0.0 | 8.93 | 12.15 | 20.0 | Au1rxx-base64 | 70.39.198.183 |
| 83.88 | trojan | 237.4 | 541.0 | 22.28 | 0.0 | 9.15 | 14.95 | 20.0 | Au1rxx-base64 | 44.243.85.47 |
| 83.84 | trojan | 275.8 | 660.0 | 21.39 | 0.0 | 10.0 | 14.95 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 83.73 | vless | 267.8 | 599.6 | 21.58 | 0.0 | 10.0 | 12.15 | 20.0 | Au1rxx-base64 | 216.36.124.176 |
| 83.71 | trojan | 219.4 | 493.6 | 22.7 | 0.0 | 8.56 | 14.95 | 20.0 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |
| 83.67 | trojan | 240.9 | 554.5 | 22.2 | 0.0 | 9.02 | 14.95 | 20.0 | Au1rxx-base64 | 34.221.30.108 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.976 | 745 | 1996 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.838 | 0.761 | 184 | 5693 | prefer |
| mheidari-all | 0.584 | 0.504 | 266 | 16315 | observe |
| nscl5-all | 0.391 | 1.0 | 2 | 2601 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 5113 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 145 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1996 | observe |
| Epodonios-all | 0.255 | None | 0 | 6340 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3985 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7319 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4439 | observe |
| barry-far-vless | 0.255 | None | 0 | 4782 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3935 | observe |
| DeltaKronecker-all | 0.252 | 0.161 | 62 | 5773 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 82 |
| speed | TimeoutError | - | 69 |
| geo | ClientOSError | - | 28 |
| cn-block | TimeoutError | - | 27 |
| speed | ClientOSError | - | 14 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
