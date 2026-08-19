# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-19 01:04:20 |
| 运行耗时 | 417.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82078 |
| 去重后节点 | 22293 |
| TCP 可达 | 3000 |
| 真实可用 | 1365 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22293 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 34.4 |
| probe | 74.9 |
| real_test | 269.4 |
| generate | 31.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44929 |
| trojan | 17089 |
| shadowsocks | 9869 |
| vmess | 8658 |
| hysteria2 | 1128 |
| http | 179 |
| socks | 117 |
| shadowsocksr | 87 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 7 |

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
| 80.1 | http | 315.6 | 732.7 | 20.47 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 79.52 | trojan | 309.2 | 780.0 | 20.62 | 0.0 | 10.0 | 14.9 | 20.0 | Au1rxx-base64 | 172.237.131.75 |
| 79.35 | trojan | 289.3 | 662.6 | 21.08 | 0.0 | 10.0 | 14.9 | 20.0 | Au1rxx-base64 | 137.184.172.41 |
| 78.88 | http | 292.9 | 578.8 | 21.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 78.77 | http | 315.9 | 723.4 | 20.47 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 78.68 | http | 316.4 | 718.5 | 20.45 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 78.62 | http | 284.8 | 571.2 | 21.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 78.53 | http | 287.2 | 571.4 | 21.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 78.52 | http | 290.2 | 579.9 | 21.06 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 78.22 | http | 289.8 | 588.7 | 21.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 78.2 | http | 288.7 | 583.1 | 21.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 78.2 | http | 341.6 | 750.7 | 19.87 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 78.16 | http | 300.3 | 567.5 | 20.83 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 78.16 | http | 341.4 | 751.0 | 19.87 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 78.1 | http | 329.5 | 731.6 | 20.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 78.07 | http | 284.8 | 577.5 | 21.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 77.86 | http | 318.0 | 676.7 | 20.42 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 77.82 | http | 340.3 | 736.7 | 19.9 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 77.74 | vless | 270.9 | 615.2 | 21.51 | 0.0 | 10.0 | 6.23 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 77.74 | http | 336.8 | 775.2 | 19.98 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.99 | 821 | 1745 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.889 | 0.813 | 171 | 6360 | prefer |
| mheidari-all | 0.823 | 0.744 | 367 | 16675 | prefer |
| nscl5-all | 0.489 | 0.833 | 6 | 3330 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ninja-vless | 0.279 | 0.5 | 2 | 1791 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5068 | observe |
| Epodonios-all | 0.255 | None | 0 | 6993 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3983 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7100 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4899 | observe |
| barry-far-vless | 0.255 | None | 0 | 5194 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4035 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1745 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 97 |
| speed | TimeoutError | - | 41 |
| geo | ClientOSError | - | 16 |
| speed | ClientOSError | - | 13 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
