# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-02 13:15:17 |
| 运行耗时 | 314.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78300 |
| 去重后节点 | 22849 |
| TCP 可达 | 3000 |
| 真实可用 | 639 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22849 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.4 |
| tcp | 34.6 |
| probe | 67.2 |
| real_test | 166.9 |
| generate | 36.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46863 |
| vmess | 12622 |
| shadowsocks | 10170 |
| trojan | 7683 |
| hysteria2 | 617 |
| http | 165 |
| shadowsocksr | 74 |
| socks | 64 |
| anytls | 26 |
| hysteria | 12 |
| tuic | 4 |

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
| 85.21 | http | 185.4 | 478.0 | 23.49 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.212 |
| 85.19 | http | 186.0 | 481.1 | 23.47 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.213 |
| 85.15 | http | 187.7 | 480.3 | 23.43 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.204 |
| 85.12 | http | 189.2 | 492.2 | 23.4 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.202 |
| 85.11 | http | 189.6 | 486.5 | 23.39 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.215 |
| 85.05 | http | 192.3 | 491.9 | 23.33 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.206 |
| 85.02 | http | 193.5 | 489.0 | 23.3 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.207 |
| 85.01 | http | 194.0 | 495.7 | 23.29 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.208 |
| 85.0 | http | 194.3 | 499.0 | 23.28 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.216 |
| 84.99 | http | 194.8 | 494.5 | 23.27 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.210 |
| 84.94 | http | 196.8 | 495.7 | 23.22 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.200 |
| 84.92 | http | 197.7 | 505.0 | 23.2 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.195 |
| 84.87 | http | 200.0 | 509.4 | 23.15 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.217 |
| 84.81 | http | 202.6 | 503.2 | 23.09 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.209 |
| 84.79 | http | 203.3 | 514.9 | 23.07 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.211 |
| 84.78 | http | 203.7 | 521.2 | 23.06 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.205 |
| 84.78 | http | 204.0 | 518.6 | 23.06 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.218 |
| 84.77 | http | 204.2 | 515.0 | 23.05 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.198 |
| 84.6 | http | 211.6 | 535.6 | 22.88 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.214 |
| 84.55 | http | 213.8 | 543.8 | 22.83 | 0.0 | 10.0 | 14.9 | 19.82 | zhangkai | 138.199.35.197 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 142 | 344 | prefer |
| Au1rxx-base64 | 0.769 | 0.703 | 562 | 1670 | prefer |
| Surfboard-tg-mixed | 0.69 | 0.612 | 121 | 5249 | observe |
| DeltaKronecker-all | 0.423 | 0.338 | 65 | 4549 | observe |
| mheidari-all | 0.4 | 0.75 | 4 | 16891 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| nscl5-all | 0.262 | 0.5 | 2 | 1354 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5486 | observe |
| Epodonios-all | 0.255 | None | 0 | 5857 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3975 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6807 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4140 | observe |
| barry-far-vless | 0.255 | None | 0 | 4517 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5071 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 92 |
| speed | TimeoutError | - | 43 |
| 204 | TimeoutError | - | 29 |
| cn-block | TimeoutError | - | 28 |
| speed | ClientOSError | - | 24 |
| geo | ClientOSError | - | 19 |
| 204 | ClientOSError | - | 9 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
