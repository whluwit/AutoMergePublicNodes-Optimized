# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 16:25:21 |
| 运行耗时 | 611.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 94292 |
| 去重后节点 | 26477 |
| TCP 可达 | 3000 |
| 真实可用 | 318 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26477 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 22.2 |
| geo | 1.4 |
| tcp | 45.4 |
| probe | 221.1 |
| real_test | 237.6 |
| generate | 83.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56248 |
| vmess | 16827 |
| shadowsocks | 11211 |
| trojan | 8374 |
| hysteria2 | 1141 |
| http | 211 |
| shadowsocksr | 158 |
| socks | 63 |
| anytls | 36 |
| hysteria | 17 |
| tuic | 6 |

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
| 79.43 | shadowsocks | 291.0 | 739.1 | 21.04 | 0.0 | 10.0 | 13.65 | 18.74 | mheidari-all | 156.146.38.170 |
| 78.51 | shadowsocks | 264.1 | 684.1 | 21.66 | 0.0 | 10.0 | 13.65 | 17.2 | Au1rxx-base64 | 156.146.38.169 |
| 78.42 | shadowsocks | 334.5 | 881.7 | 20.03 | 0.0 | 10.0 | 13.65 | 18.74 | mheidari-all | 156.146.38.168 |
| 77.78 | vless | 272.2 | 633.7 | 21.48 | 0.0 | 10.0 | 10.58 | 17.2 | Au1rxx-base64 | 216.227.161.95 |
| 77.38 | shadowsocks | 257.6 | 632.3 | 21.81 | 0.0 | 8.72 | 13.65 | 17.2 | Au1rxx-base64 | 156.146.38.167 |
| 76.86 | shadowsocks | 318.9 | 786.3 | 20.4 | 0.0 | 10.0 | 13.65 | 18.74 | mheidari-all | 37.19.198.243 |
| 76.82 | vless | 271.1 | 547.3 | 21.5 | 0.0 | 10.0 | 10.58 | 18.74 | mheidari-all | 47.251.108.158 |
| 75.88 | vless | 288.7 | 727.2 | 21.1 | 0.0 | 10.0 | 10.58 | 17.2 | Au1rxx-base64 | 162.35.126.130 |
| 75.12 | shadowsocks | 300.5 | 739.4 | 20.82 | 0.0 | 8.69 | 13.65 | 17.2 | Au1rxx-base64 | 37.19.198.160 |
| 74.84 | vless | 298.4 | 674.9 | 20.87 | 0.0 | 10.0 | 10.58 | 17.2 | Au1rxx-base64 | 195.123.235.183 |
| 74.64 | shadowsocks | 284.7 | 567.8 | 21.19 | 0.0 | 10.0 | 13.65 | 18.74 | mheidari-all | 173.244.56.6 |
| 74.5 | shadowsocks | 305.5 | 748.0 | 20.71 | 0.0 | 10.0 | 13.65 | 18.74 | mheidari-all | 37.19.198.236 |
| 73.23 | vless | 283.9 | 669.0 | 21.21 | 0.0 | 8.74 | 10.58 | 17.2 | Au1rxx-base64 | 69.48.201.136 |
| 72.84 | vless | 287.8 | 674.4 | 21.12 | 0.0 | 8.44 | 10.58 | 17.2 | Au1rxx-base64 | uspanel.unixzone.us |
| 72.8 | trojan | 360.1 | 897.7 | 19.44 | 0.0 | 8.71 | 10.45 | 17.2 | Au1rxx-base64 | 66.23.203.21 |
| 72.53 | shadowsocks | 286.1 | 568.3 | 21.15 | 0.0 | 10.0 | 13.65 | 17.2 | Au1rxx-base64 | 173.244.56.9 |
| 72.41 | vless | 389.9 | 916.3 | 18.75 | 0.0 | 8.74 | 10.58 | 17.2 | Au1rxx-base64 | 137.184.218.169 |
| 72.34 | hysteria2 | 344.9 | 784.3 | 19.79 | 0.0 | 10.0 | 13.85 | 14.1 | Surfboard-tg-mixed | 129.213.91.185 |
| 72.11 | vless | 427.9 | 1085.6 | 17.87 | 0.0 | 8.75 | 10.58 | 17.2 | Au1rxx-base64 | 185.95.231.156 |
| 72.09 | shadowsocks | 313.4 | 621.6 | 20.52 | 0.0 | 8.69 | 13.65 | 17.2 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.806 | 0.754 | 289 | 1348 | prefer |
| mheidari-all | 0.794 | 0.721 | 68 | 23236 | prefer |
| Surfboard-tg-mixed | 0.785 | 0.714 | 42 | 6911 | prefer |
| zhangkai | 0.484 | 0.481 | 27 | 31 | observe |
| Epodonios-all | 0.335 | 1.0 | 1 | 7384 | observe |
| ermaozi-get_subscribe | 0.309 | 0.444 | 9 | 429 | observe |
| chromego_merge | 0.264 | 1.0 | 1 | 227 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 79 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10086 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5732 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 31 |
| 204 | ProxyError | - | 22 |
| 204 | TimeoutError | - | 20 |
| speed | TimeoutError | - | 18 |
| speed | ClientOSError | - | 11 |
| geo | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 4 |
| geo | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
