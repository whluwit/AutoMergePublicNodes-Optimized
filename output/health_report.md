# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-02 02:27:12 |
| 运行耗时 | 418.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78082 |
| 去重后节点 | 23287 |
| TCP 可达 | 3000 |
| 真实可用 | 988 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23287 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.4 |
| tcp | 34.7 |
| probe | 76.2 |
| real_test | 270.7 |
| generate | 28.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46597 |
| vmess | 12329 |
| shadowsocks | 10132 |
| trojan | 8068 |
| hysteria2 | 614 |
| http | 157 |
| shadowsocksr | 72 |
| socks | 65 |
| anytls | 26 |
| hysteria | 14 |
| tuic | 8 |

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
| 85.16 | http | 189.8 | 493.6 | 23.38 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.211 |
| 85.15 | http | 190.3 | 479.5 | 23.37 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.213 |
| 85.15 | http | 190.3 | 480.0 | 23.37 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.217 |
| 85.14 | http | 190.7 | 475.6 | 23.36 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.210 |
| 85.13 | http | 191.4 | 489.2 | 23.35 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.220 |
| 85.1 | http | 192.5 | 486.5 | 23.32 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.204 |
| 85.09 | http | 192.8 | 497.2 | 23.31 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.212 |
| 85.09 | http | 193.0 | 497.1 | 23.31 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.209 |
| 85.05 | http | 194.6 | 503.4 | 23.27 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.206 |
| 85.04 | http | 195.3 | 496.0 | 23.26 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.214 |
| 85.03 | http | 195.6 | 496.5 | 23.25 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.198 |
| 85.03 | http | 195.7 | 503.1 | 23.25 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.199 |
| 85.02 | http | 196.0 | 488.7 | 23.24 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.195 |
| 84.99 | http | 197.4 | 501.2 | 23.21 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.196 |
| 84.93 | http | 199.9 | 502.1 | 23.15 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.207 |
| 84.92 | http | 200.5 | 507.8 | 23.14 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.200 |
| 84.91 | http | 200.9 | 499.9 | 23.13 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.208 |
| 84.82 | http | 204.6 | 529.8 | 23.04 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.215 |
| 84.8 | http | 205.6 | 525.6 | 23.02 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.205 |
| 84.78 | http | 206.5 | 505.2 | 23.0 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.218 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 147 | 194 | prefer |
| Au1rxx-base64 | 0.937 | 0.875 | 526 | 1599 | prefer |
| Surfboard-tg-mixed | 0.625 | 0.55 | 20 | 5166 | observe |
| DeltaKronecker-all | 0.45 | 0.37 | 987 | 5502 | observe |
| xiaoji235-airport-v2ray-all | 0.343 | 0.667 | 3 | 1861 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5391 | observe |
| Epodonios-all | 0.255 | None | 0 | 5783 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6590 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4054 | observe |
| barry-far-vless | 0.255 | None | 0 | 4431 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5071 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1599 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 293 |
| speed | ClientOSError | - | 160 |
| speed | TimeoutError | - | 78 |
| geo | ClientOSError | - | 77 |
| cn-block | TimeoutError | - | 67 |
| 204 | ProxyError | - | 20 |
| cn-block | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 5 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
