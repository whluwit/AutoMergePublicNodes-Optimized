# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-07 12:56:44 |
| 运行耗时 | 252.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82494 |
| 去重后节点 | 23342 |
| TCP 可达 | 3000 |
| 真实可用 | 476 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23342 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 35.4 |
| probe | 55.2 |
| real_test | 117.3 |
| generate | 37.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47382 |
| vmess | 12759 |
| trojan | 11151 |
| shadowsocks | 9701 |
| hysteria2 | 1309 |
| shadowsocksr | 72 |
| socks | 64 |
| http | 35 |
| hysteria | 13 |
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
| 83.44 | trojan | 247.1 | 621.7 | 22.06 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 83.23 | trojan | 255.9 | 648.9 | 21.85 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 83.21 | trojan | 256.9 | 653.5 | 21.83 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 35.91.251.124 |
| 81.3 | trojan | 259.3 | 659.6 | 21.77 | 0.0 | 8.49 | 13.88 | 20.0 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 81.1 | shadowsocks | 203.7 | 548.0 | 23.06 | 0.0 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 81.05 | trojan | 205.1 | 492.4 | 23.03 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 35.86.90.51 |
| 79.93 | shadowsocks | 256.0 | 268.1 | 21.85 | 4.95 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 149.22.87.204 |
| 78.62 | trojan | 455.4 | 1238.7 | 17.24 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 44.242.235.129 |
| 78.43 | shadowsocks | 275.2 | 554.6 | 21.41 | 0.0 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 78.22 | hysteria2 | 339.2 | 721.9 | 19.92 | 0.0 | 10.0 | 13.42 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 78.03 | hysteria2 | 350.1 | 754.2 | 19.67 | 0.0 | 10.0 | 13.42 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 77.9 | trojan | 343.2 | 288.7 | 19.83 | 4.18 | 9.96 | 13.88 | 20.0 | Au1rxx-base64 | 35.72.13.34 |
| 77.85 | trojan | 343.2 | 289.9 | 19.83 | 4.13 | 9.96 | 13.88 | 20.0 | Au1rxx-base64 | 3.113.1.131 |
| 77.79 | shadowsocks | 283.2 | 648.5 | 21.22 | 0.0 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 77.75 | trojan | 310.7 | 314.6 | 20.58 | 3.2 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 43.207.140.98 |
| 77.74 | trojan | 309.8 | 314.2 | 20.61 | 3.22 | 9.99 | 13.88 | 20.0 | Au1rxx-base64 | 43.207.139.153 |
| 77.71 | trojan | 310.6 | 315.7 | 20.59 | 3.16 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 13.230.118.96 |
| 77.68 | trojan | 364.0 | 282.4 | 19.35 | 4.41 | 9.98 | 13.88 | 20.0 | Au1rxx-base64 | 18.179.31.199 |
| 77.65 | shadowsocks | 285.2 | 621.2 | 21.18 | 0.0 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 77.62 | trojan | 309.8 | 318.8 | 20.61 | 3.04 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 54.199.202.238 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.959 | 343 | 1509 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| DeltaKronecker-all | 0.598 | 0.518 | 226 | 5326 | observe |
| mheidari-all | 0.418 | 0.5 | 10 | 17690 | observe |
| Surfboard-tg-mixed | 0.344 | 0.333 | 12 | 6339 | observe |
| nscl5-all | 0.326 | 1.0 | 1 | 1772 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5282 | observe |
| Epodonios-all | 0.255 | None | 0 | 6987 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7526 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5136 | observe |
| barry-far-vless | 0.255 | None | 0 | 5458 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5247 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1509 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 40 |
| geo | TimeoutError | - | 27 |
| geo | ClientOSError | - | 17 |
| 204 | TimeoutError | - | 16 |
| cn-block | TimeoutError | - | 13 |
| speed | ClientOSError | - | 8 |
| speed | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
