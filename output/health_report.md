# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-15 01:02:57 |
| 运行耗时 | 334.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 75539 |
| 去重后节点 | 20579 |
| TCP 可达 | 3000 |
| 真实可用 | 1087 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 20579 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.0 |
| tcp | 33.0 |
| probe | 64.1 |
| real_test | 205.9 |
| generate | 24.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 41574 |
| trojan | 11560 |
| vmess | 10499 |
| shadowsocks | 10152 |
| hysteria2 | 1417 |
| http | 169 |
| socks | 78 |
| shadowsocksr | 73 |
| tuic | 10 |
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
| 84.88 | hysteria2 | 238.2 | 665.8 | 22.26 | 0.0 | 10.0 | 14.12 | 19.6 | Au1rxx-base64 | 159.223.157.129 |
| 84.85 | hysteria2 | 243.8 | 679.2 | 22.13 | 0.0 | 10.0 | 14.12 | 19.6 | Au1rxx-base64 | 138.124.68.188 |
| 84.23 | http | 233.6 | 632.6 | 22.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 84.05 | http | 241.2 | 637.6 | 22.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 84.0 | http | 243.5 | 655.2 | 22.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.96 | http | 245.4 | 659.4 | 22.1 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 83.9 | http | 248.0 | 661.3 | 22.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 83.87 | http | 249.0 | 674.0 | 22.01 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 83.86 | http | 249.7 | 671.2 | 22.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 83.84 | http | 250.3 | 662.0 | 21.98 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.82 | http | 251.3 | 668.8 | 21.96 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.78 | http | 253.1 | 664.9 | 21.92 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 83.76 | http | 253.8 | 687.5 | 21.9 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.55 | http | 262.8 | 709.4 | 21.69 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 83.55 | http | 262.8 | 696.3 | 21.69 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 83.49 | http | 265.4 | 718.9 | 21.63 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 82.04 | http | 328.2 | 912.2 | 20.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 81.96 | http | 331.9 | 905.8 | 20.1 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 81.61 | http | 347.0 | 964.0 | 19.75 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 81.41 | shadowsocks | 225.3 | 622.5 | 22.56 | 0.0 | 10.0 | 13.25 | 19.6 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.973 | 659 | 1705 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| DeltaKronecker-all | 0.834 | 0.756 | 254 | 3485 | prefer |
| Surfboard-tg-mixed | 0.731 | 0.652 | 184 | 5731 | prefer |
| nscl5-all | 0.305 | 0.3 | 10 | 2081 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 160 | observe |
| Epodonios-all | 0.255 | None | 0 | 6388 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7440 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4486 | observe |
| barry-far-vless | 0.255 | None | 0 | 4816 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3992 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1705 | observe |
| mheidari-all | 0.243 | 0.182 | 11 | 15517 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 44 |
| geo | ClientOSError | - | 34 |
| speed | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 11 |
| speed | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
