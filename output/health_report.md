# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 22:24:29 |
| 运行耗时 | 531.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98428 |
| 去重后节点 | 27519 |
| TCP 可达 | 3000 |
| 真实可用 | 378 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27519 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.5 |
| tcp | 45.8 |
| probe | 255.2 |
| real_test | 150.1 |
| generate | 71.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60580 |
| vmess | 15344 |
| shadowsocks | 11563 |
| trojan | 8953 |
| hysteria2 | 1304 |
| http | 378 |
| shadowsocksr | 171 |
| socks | 60 |
| anytls | 52 |
| hysteria | 16 |
| tuic | 7 |

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
| 81.4 | hysteria2 | 267.6 | 675.4 | 21.58 | 0.0 | 10.0 | 14.32 | 16.6 | mheidari-all | 159.223.157.129 |
| 80.23 | hysteria2 | 256.5 | 541.1 | 21.84 | 0.0 | 10.0 | 14.32 | 17.0 | Au1rxx-base64 | 192.255.128.123 |
| 77.7 | shadowsocks | 253.0 | 631.0 | 21.92 | 0.0 | 10.0 | 12.78 | 17.0 | Au1rxx-base64 | 156.146.38.168 |
| 77.69 | shadowsocks | 253.5 | 630.3 | 21.91 | 0.0 | 10.0 | 12.78 | 17.0 | Au1rxx-base64 | 156.146.38.170 |
| 77.59 | shadowsocks | 257.9 | 633.3 | 21.81 | 0.0 | 10.0 | 12.78 | 17.0 | Au1rxx-base64 | 156.146.38.167 |
| 76.77 | shadowsocks | 293.2 | 747.6 | 20.99 | 0.0 | 10.0 | 12.78 | 17.0 | Au1rxx-base64 | 37.19.198.236 |
| 76.57 | vless | 258.2 | 649.2 | 21.8 | 0.0 | 10.0 | 8.91 | 17.0 | Au1rxx-base64 | 198.251.78.29 |
| 76.56 | shadowsocks | 285.2 | 719.0 | 21.18 | 0.0 | 10.0 | 12.78 | 16.6 | mheidari-all | 37.19.198.244 |
| 76.3 | shadowsocks | 291.9 | 685.9 | 21.02 | 0.0 | 10.0 | 12.78 | 17.0 | Au1rxx-base64 | 140.82.63.79 |
| 76.15 | shadowsocks | 252.8 | 635.1 | 21.93 | 0.0 | 10.0 | 12.78 | 15.44 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.59 | shadowsocks | 322.6 | 880.8 | 20.31 | 0.0 | 10.0 | 12.78 | 17.0 | Au1rxx-base64 | 185.156.47.97 |
| 75.54 | hysteria2 | 303.7 | 661.8 | 20.75 | 0.0 | 10.0 | 14.32 | 17.0 | Au1rxx-base64 | 66.94.121.46 |
| 75.43 | vless | 303.6 | 717.9 | 20.75 | 0.0 | 10.0 | 8.91 | 17.0 | Au1rxx-base64 | 66.70.179.198 |
| 74.89 | shadowsocks | 262.1 | 704.3 | 21.71 | 0.0 | 9.9 | 12.78 | 17.0 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 74.63 | vless | 312.1 | 719.8 | 20.55 | 0.0 | 10.0 | 8.91 | 17.0 | Au1rxx-base64 | 169.40.42.184 |
| 74.58 | shadowsocks | 366.4 | 919.2 | 19.3 | 0.0 | 10.0 | 12.78 | 17.0 | Au1rxx-base64 | 15.204.246.132 |
| 74.5 | vless | 285.7 | 692.8 | 21.17 | 0.0 | 10.0 | 8.91 | 17.0 | Au1rxx-base64 | 169.40.42.232 |
| 74.43 | shadowsocks | 327.0 | 855.3 | 20.21 | 0.0 | 10.0 | 12.78 | 15.44 | Surfboard-tg-mixed | 198.98.53.130 |
| 73.77 | vless | 315.1 | 653.9 | 20.48 | 0.0 | 10.0 | 8.91 | 17.0 | Au1rxx-base64 | 169.40.42.235 |
| 73.11 | vless | 223.5 | 607.6 | 22.6 | 0.0 | 10.0 | 8.91 | 16.6 | mheidari-all | 195.211.98.43 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.98 | 0.907 | 108 | 22987 | prefer |
| Au1rxx-base64 | 0.931 | 0.861 | 267 | 1818 | prefer |
| Surfboard-tg-mixed | 0.835 | 0.766 | 47 | 7183 | prefer |
| zhangkai | 0.614 | 0.619 | 21 | 144 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 5603 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5324 | observe |
| Epodonios-all | 0.255 | None | 0 | 7711 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9539 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5811 | observe |
| barry-far-vless | 0.255 | None | 0 | 6097 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4310 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1818 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 9 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | TimeoutError | - | 2 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
