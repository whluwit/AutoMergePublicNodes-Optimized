# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-04 11:51:59 |
| 运行耗时 | 604.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99550 |
| 去重后节点 | 27349 |
| TCP 可达 | 3000 |
| 真实可用 | 369 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27349 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.0 |
| tcp | 47.2 |
| probe | 308.2 |
| real_test | 155.7 |
| generate | 84.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59735 |
| vmess | 15754 |
| shadowsocks | 11569 |
| trojan | 10116 |
| hysteria2 | 1563 |
| http | 521 |
| shadowsocksr | 172 |
| socks | 70 |
| anytls | 27 |
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
| 81.08 | shadowsocks | 256.6 | 633.2 | 21.84 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 156.146.38.168 |
| 80.57 | shadowsocks | 278.3 | 723.7 | 21.33 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 37.19.198.236 |
| 80.57 | shadowsocks | 278.5 | 723.8 | 21.33 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 37.19.198.243 |
| 80.44 | shadowsocks | 284.1 | 739.9 | 21.2 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 37.19.198.244 |
| 79.6 | shadowsocks | 253.9 | 628.6 | 21.9 | 0.0 | 10.0 | 13.44 | 18.26 | Surfboard-tg-mixed | 156.146.38.169 |
| 79.21 | hysteria2 | 408.3 | 1100.7 | 18.33 | 0.0 | 10.0 | 14.12 | 18.26 | Surfboard-tg-mixed | 129.213.91.185 |
| 78.78 | shadowsocks | 287.1 | 680.5 | 21.13 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 140.82.63.79 |
| 78.19 | shadowsocks | 251.8 | 630.1 | 21.95 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 156.146.38.170 |
| 77.59 | shadowsocks | 380.7 | 987.7 | 18.97 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 51.222.200.165 |
| 76.61 | shadowsocks | 212.0 | 609.2 | 22.87 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 66.23.204.210 |
| 76.47 | vless | 316.1 | 729.2 | 20.46 | 0.0 | 10.0 | 6.35 | 19.8 | Au1rxx-base64 | 169.40.42.133 |
| 76.15 | vless | 316.5 | 763.7 | 20.45 | 0.0 | 10.0 | 6.35 | 19.8 | Au1rxx-base64 | 66.70.179.198 |
| 75.22 | vless | 363.9 | 938.7 | 19.35 | 0.0 | 10.0 | 6.35 | 19.8 | Au1rxx-base64 | 185.95.231.156 |
| 74.34 | shadowsocks | 306.0 | 553.3 | 20.69 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 108.181.118.10 |
| 74.07 | shadowsocks | 351.4 | 781.0 | 19.64 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 5.78.51.123 |
| 73.81 | shadowsocks | 299.4 | 596.8 | 20.85 | 0.0 | 10.0 | 13.44 | 18.26 | Surfboard-tg-mixed | 173.244.56.6 |
| 73.69 | shadowsocks | 338.1 | 890.0 | 19.95 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 66.23.202.50 |
| 73.45 | vless | 258.2 | 645.2 | 21.8 | 0.0 | 10.0 | 6.35 | 19.8 | Au1rxx-base64 | 69.48.201.136 |
| 73.27 | hysteria2 | 401.2 | 607.9 | 18.49 | 0.0 | 8.92 | 14.12 | 19.8 | Au1rxx-base64 | open.w2m.ink |
| 73.02 | shadowsocks | 570.5 | 963.5 | 14.57 | 0.0 | 10.0 | 13.44 | 19.8 | Au1rxx-base64 | 15.204.246.132 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | 0.91 | 279 | 1816 | prefer |
| Surfboard-tg-mixed | 0.863 | 0.791 | 67 | 7269 | prefer |
| mheidari-all | 0.834 | 0.764 | 55 | 23332 | prefer |
| ermaozi | 0.641 | 0.625 | 24 | 646 | observe |
| DeltaKronecker-all | 0.344 | 0.333 | 12 | 5267 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5173 | observe |
| Epodonios-all | 0.255 | None | 0 | 7796 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9804 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5821 | observe |
| barry-far-vless | 0.255 | None | 0 | 6148 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1816 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyConnectionError | - | 16 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 5 |
| speed | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
