# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 16:31:32 |
| 运行耗时 | 558.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97423 |
| 去重后节点 | 26456 |
| TCP 可达 | 3000 |
| 真实可用 | 369 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26456 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.4 |
| tcp | 43.6 |
| probe | 257.3 |
| real_test | 175.4 |
| generate | 75.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59603 |
| vmess | 15140 |
| shadowsocks | 11278 |
| trojan | 8914 |
| hysteria2 | 1598 |
| http | 597 |
| shadowsocksr | 170 |
| socks | 74 |
| anytls | 27 |
| hysteria | 15 |
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
| 81.64 | vless | 198.8 | 511.8 | 23.17 | 0.0 | 9.26 | 10.57 | 18.64 | Au1rxx-base64 | 192.3.247.109 |
| 81.62 | vless | 198.5 | 514.2 | 23.18 | 0.0 | 9.23 | 10.57 | 18.64 | Au1rxx-base64 | 172.235.43.210 |
| 81.31 | vless | 212.1 | 531.3 | 22.87 | 0.0 | 9.23 | 10.57 | 18.64 | Au1rxx-base64 | 195.123.240.65 |
| 80.1 | vless | 200.6 | 520.5 | 23.13 | 0.0 | 10.0 | 10.57 | 16.4 | mheidari-all | 172.233.139.46 |
| 78.93 | shadowsocks | 260.7 | 636.4 | 21.74 | 0.0 | 9.28 | 13.63 | 18.64 | Au1rxx-base64 | 156.146.38.169 |
| 78.79 | shadowsocks | 195.1 | 517.2 | 23.26 | 0.0 | 10.0 | 13.63 | 16.4 | mheidari-all | 192.3.247.109 |
| 77.4 | vless | 213.7 | 533.9 | 22.83 | 0.0 | 10.0 | 10.57 | 14.0 | Surfboard-tg-mixed | 172.235.38.85 |
| 76.65 | vless | 222.5 | 495.4 | 22.63 | 0.0 | 9.31 | 10.57 | 18.64 | Au1rxx-base64 | 172.64.154.8 |
| 76.59 | vless | 335.4 | 800.8 | 20.01 | 0.0 | 9.31 | 10.57 | 18.64 | Au1rxx-base64 | 5.78.159.214 |
| 76.4 | shadowsocks | 282.1 | 287.5 | 21.25 | 4.22 | 9.9 | 13.63 | 18.64 | Au1rxx-base64 | 149.22.87.240 |
| 76.26 | shadowsocks | 222.3 | 561.1 | 22.63 | 0.0 | 10.0 | 13.63 | 14.0 | Surfboard-tg-mixed | 173.244.56.9 |
| 76.23 | vless | 248.7 | 588.8 | 22.02 | 0.0 | 10.0 | 10.57 | 18.64 | Au1rxx-base64 | 38.244.20.25 |
| 75.94 | shadowsocks | 402.8 | 1046.7 | 18.45 | 0.0 | 9.22 | 13.63 | 18.64 | Au1rxx-base64 | 173.244.56.6 |
| 75.33 | vless | 335.3 | 766.4 | 20.02 | 0.0 | 9.26 | 10.57 | 18.64 | Au1rxx-base64 | 79.141.172.154 |
| 74.84 | shadowsocks | 224.0 | 533.2 | 22.59 | 0.0 | 10.0 | 13.63 | 16.4 | mheidari-all | 108.181.118.10 |
| 74.57 | shadowsocks | 285.4 | 633.1 | 21.17 | 0.0 | 10.0 | 13.63 | 16.4 | mheidari-all | 23.150.248.20 |
| 74.56 | vless | 287.4 | 707.1 | 21.12 | 0.0 | 9.23 | 10.57 | 18.64 | Au1rxx-base64 | 137.175.82.40 |
| 74.33 | vless | 329.9 | 716.5 | 20.14 | 0.0 | 9.22 | 10.57 | 18.64 | Au1rxx-base64 | 136.117.218.86 |
| 74.12 | shadowsocks | 244.5 | 621.6 | 22.12 | 0.0 | 10.0 | 13.63 | 14.0 | Surfboard-tg-mixed | 108.181.0.177 |
| 73.92 | shadowsocks | 289.3 | 627.6 | 21.08 | 0.0 | 10.0 | 13.63 | 16.4 | mheidari-all | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | 0.907 | 269 | 1699 | prefer |
| Surfboard-tg-mixed | 0.83 | 0.762 | 42 | 7258 | prefer |
| mheidari-all | 0.636 | 0.557 | 140 | 22782 | observe |
| ermaozi | 0.573 | 0.611 | 18 | 304 | observe |
| DeltaKronecker-all | 0.352 | 0.5 | 6 | 5452 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 177 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7757 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9237 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5857 | observe |
| barry-far-vless | 0.255 | None | 0 | 6083 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4324 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1699 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 32 |
| 204 | TimeoutError | - | 23 |
| 204 | ProxyError | - | 17 |
| cn-block | TimeoutError | - | 17 |
| geo | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
