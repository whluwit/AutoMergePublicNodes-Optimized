# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-25 08:05:51 |
| 运行耗时 | 352.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78504 |
| 去重后节点 | 21833 |
| TCP 可达 | 3000 |
| 真实可用 | 892 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21833 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.1 |
| tcp | 30.4 |
| probe | 68.7 |
| real_test | 196.7 |
| generate | 51.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45151 |
| trojan | 13290 |
| vmess | 9827 |
| shadowsocks | 9654 |
| hysteria2 | 357 |
| socks | 73 |
| shadowsocksr | 69 |
| http | 50 |
| tuic | 17 |
| hysteria | 15 |
| anytls | 1 |

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
| 73.06 | vless | 202.6 | 568.6 | 23.09 | 0.0 | 10.0 | 4.77 | 15.2 | Surfboard-tg-mixed | 64.23.143.23 |
| 72.83 | vless | 169.4 | 450.6 | 23.86 | 0.0 | 10.0 | 4.77 | 15.2 | Surfboard-tg-mixed | 198.41.209.87 |
| 72.58 | shadowsocks | 219.1 | 520.4 | 22.71 | 0.0 | 10.0 | 12.27 | 11.6 | Au1rxx-base64 | 149.22.95.183 |
| 72.49 | shadowsocks | 223.0 | 502.1 | 22.62 | 0.0 | 10.0 | 12.27 | 11.6 | Au1rxx-base64 | 173.244.56.6 |
| 72.41 | shadowsocks | 226.3 | 509.9 | 22.54 | 0.0 | 10.0 | 12.27 | 11.6 | Au1rxx-base64 | 173.244.56.9 |
| 72.08 | vless | 171.6 | 461.6 | 23.81 | 0.0 | 10.0 | 4.77 | 14.5 | DeltaKronecker-all | 104.25.161.29 |
| 72.02 | vless | 174.2 | 453.3 | 23.75 | 0.0 | 10.0 | 4.77 | 14.5 | DeltaKronecker-all | 172.67.209.126 |
| 71.65 | shadowsocks | 237.6 | 608.9 | 22.28 | 0.0 | 10.0 | 12.27 | 11.6 | Au1rxx-base64 | 108.181.118.10 |
| 70.72 | trojan | 324.8 | 327.9 | 20.26 | 2.7 | 9.95 | 14.25 | 13.46 | mheidari-all | 31.223.184.164 |
| 70.72 | trojan | 327.2 | 326.3 | 20.2 | 2.76 | 9.95 | 14.25 | 13.46 | mheidari-all | 95.85.94.112 |
| 70.65 | trojan | 323.7 | 328.9 | 20.28 | 2.67 | 9.95 | 14.25 | 13.46 | mheidari-all | 95.85.94.165 |
| 70.58 | trojan | 325.8 | 332.6 | 20.24 | 2.53 | 9.95 | 14.25 | 14.5 | DeltaKronecker-all | 95.85.94.51 |
| 70.52 | trojan | 328.4 | 329.0 | 20.17 | 2.66 | 9.94 | 14.25 | 13.46 | mheidari-all | 31.223.184.82 |
| 70.5 | trojan | 325.3 | 332.5 | 20.25 | 2.53 | 9.94 | 14.25 | 13.46 | mheidari-all | 31.223.184.43 |
| 70.23 | trojan | 305.9 | 666.9 | 20.7 | 0.0 | 10.0 | 14.25 | 11.6 | Au1rxx-base64 | 64.94.95.117 |
| 70.17 | shadowsocks | 301.4 | 788.9 | 20.8 | 0.0 | 10.0 | 12.27 | 11.6 | Au1rxx-base64 | 108.181.0.177 |
| 68.77 | trojan | 339.5 | 370.1 | 19.92 | 1.12 | 9.94 | 14.25 | 13.46 | mheidari-all | 95.85.94.199 |
| 68.62 | shadowsocks | 272.5 | 281.1 | 21.47 | 4.46 | 9.94 | 12.27 | 11.6 | Au1rxx-base64 | 149.22.87.204 |
| 68.6 | trojan | 383.0 | 434.6 | 18.91 | 0.0 | 10.0 | 14.25 | 15.2 | Surfboard-tg-mixed | 151.101.1.194 |
| 68.44 | shadowsocks | 274.5 | 284.0 | 21.42 | 4.35 | 9.94 | 12.27 | 11.6 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.979 | 0.901 | 413 | 16592 | prefer |
| Au1rxx-base64 | 0.83 | 0.817 | 126 | 432 | prefer |
| zhangkai | 0.792 | 0.806 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.679 | 0.599 | 302 | 5473 | observe |
| DeltaKronecker-all | 0.653 | 0.574 | 359 | 5838 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4879 | observe |
| Epodonios-all | 0.255 | None | 0 | 6614 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6714 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4256 | observe |
| barry-far-vless | 0.255 | None | 0 | 4927 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5009 | observe |
| nscl5-all | 0.255 | None | 0 | 2974 | observe |
| xiaoji235-airport-v2ray-all | 0.24 | None | 0 | 1624 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 155 |
| speed | ClientOSError | - | 47 |
| cn-block | TimeoutError | - | 32 |
| 204 | ProxyError | - | 26 |
| 204 | TimeoutError | - | 24 |
| geo | ClientOSError | - | 21 |
| speed | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 13 |
| cn-block | ProxyError | - | 7 |
| speed | ProxyError | - | 5 |
| 204 | ClientOSError | - | 5 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
