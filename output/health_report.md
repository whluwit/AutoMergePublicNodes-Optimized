# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-12 07:22:09 |
| 运行耗时 | 300.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 88199 |
| 去重后节点 | 23601 |
| TCP 可达 | 3000 |
| 真实可用 | 587 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23601 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 18.9 |
| geo | 1.4 |
| tcp | 35.3 |
| probe | 59.0 |
| real_test | 136.8 |
| generate | 49.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51695 |
| vmess | 13912 |
| trojan | 10646 |
| shadowsocks | 10120 |
| hysteria2 | 1446 |
| http | 159 |
| socks | 100 |
| shadowsocksr | 74 |
| tuic | 19 |
| hysteria | 16 |
| anytls | 12 |

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
| 81.61 | trojan | 210.0 | 507.2 | 22.92 | 0.0 | 10.0 | 12.39 | 18.8 | Au1rxx-base64 | 44.242.235.129 |
| 81.39 | shadowsocks | 181.8 | 486.2 | 23.57 | 0.0 | 9.27 | 13.75 | 18.8 | Au1rxx-base64 | 149.22.95.183 |
| 80.73 | http | 259.5 | 546.9 | 21.77 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 80.61 | trojan | 252.9 | 638.0 | 21.92 | 0.0 | 10.0 | 12.39 | 18.8 | Au1rxx-base64 | 44.246.163.102 |
| 80.48 | http | 262.0 | 552.7 | 21.71 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 80.43 | http | 266.8 | 560.6 | 21.6 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 80.28 | http | 260.3 | 554.4 | 21.75 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 80.25 | http | 262.6 | 558.8 | 21.7 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 80.23 | http | 264.7 | 562.6 | 21.65 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 80.21 | http | 269.3 | 575.8 | 21.54 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 80.19 | http | 264.7 | 569.3 | 21.65 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 80.16 | http | 254.9 | 539.1 | 21.88 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 80.09 | http | 262.3 | 558.2 | 21.71 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 80.07 | http | 274.3 | 582.4 | 21.43 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 79.95 | trojan | 281.7 | 724.7 | 21.26 | 0.0 | 10.0 | 12.39 | 18.8 | Au1rxx-base64 | 35.86.90.51 |
| 79.89 | http | 262.8 | 559.8 | 21.7 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 79.57 | http | 289.5 | 634.1 | 21.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 79.44 | http | 293.1 | 651.1 | 20.99 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 78.45 | trojan | 346.3 | 911.8 | 19.76 | 0.0 | 10.0 | 12.39 | 18.8 | Au1rxx-base64 | 44.244.3.114 |
| 77.89 | shadowsocks | 256.4 | 262.3 | 21.84 | 5.16 | 9.26 | 13.75 | 18.8 | Au1rxx-base64 | 149.22.87.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 0.992 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.898 | 0.834 | 429 | 1632 | prefer |
| Surfboard-tg-mixed | 0.693 | 0.615 | 109 | 5943 | observe |
| DeltaKronecker-all | 0.497 | 0.412 | 34 | 4975 | observe |
| mheidari-all | 0.343 | 0.257 | 74 | 20330 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 4568 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5328 | observe |
| Epodonios-all | 0.255 | None | 0 | 6602 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7652 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4919 | observe |
| barry-far-vless | 0.255 | None | 0 | 5202 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1632 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 42 |
| geo | ClientOSError | - | 38 |
| speed | TimeoutError | - | 38 |
| speed | ClientOSError | - | 20 |
| 204 | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 11 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
