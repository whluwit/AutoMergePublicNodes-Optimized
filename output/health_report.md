# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-17 08:06:05 |
| 运行耗时 | 255.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 98 |
| 原始节点 | 79440 |
| 去重后节点 | 24736 |
| TCP 可达 | 3000 |
| 真实可用 | 468 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24736 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.1 |
| tcp | 32.6 |
| probe | 52.0 |
| real_test | 125.7 |
| generate | 38.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45715 |
| trojan | 12619 |
| vmess | 10827 |
| shadowsocks | 9788 |
| hysteria2 | 272 |
| shadowsocksr | 130 |
| http | 51 |
| socks | 27 |
| hysteria | 8 |
| tuic | 3 |

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
| 78.9 | shadowsocks | 240.0 | 609.3 | 22.22 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 156.146.38.167 |
| 78.87 | shadowsocks | 241.4 | 619.4 | 22.19 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 156.146.38.168 |
| 78.85 | shadowsocks | 242.1 | 619.0 | 22.17 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 156.146.38.169 |
| 77.78 | shadowsocks | 288.3 | 760.7 | 21.1 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 156.146.38.170 |
| 75.99 | trojan | 245.1 | 601.0 | 22.1 | 0.0 | 10.0 | 14.39 | 12.5 | DeltaKronecker-all | 64.94.95.117 |
| 74.78 | shadowsocks | 258.4 | 540.8 | 21.8 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 108.181.0.177 |
| 74.31 | shadowsocks | 281.8 | 553.4 | 21.25 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 173.244.56.9 |
| 74.25 | trojan | 320.3 | 816.5 | 20.36 | 0.0 | 10.0 | 14.39 | 12.5 | DeltaKronecker-all | 64.94.95.114 |
| 73.79 | shadowsocks | 278.5 | 552.1 | 21.33 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 173.244.56.6 |
| 73.69 | trojan | 341.5 | 883.6 | 19.87 | 0.0 | 10.0 | 14.39 | 12.5 | DeltaKronecker-all | 64.94.95.115 |
| 73.54 | shadowsocks | 273.3 | 542.8 | 21.45 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 108.181.118.10 |
| 73.37 | shadowsocks | 306.2 | 302.1 | 20.69 | 3.67 | 9.79 | 14.14 | 16.54 | Au1rxx-base64 | 149.22.87.241 |
| 72.3 | shadowsocks | 352.3 | 818.8 | 19.62 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 37.19.198.160 |
| 72.25 | shadowsocks | 357.1 | 814.0 | 19.51 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 37.19.198.244 |
| 71.25 | shadowsocks | 406.2 | 978.5 | 18.37 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 50.114.177.235 |
| 71.24 | trojan | 487.8 | 571.9 | 16.49 | 0.0 | 10.0 | 14.39 | 20.0 | Surfboard-tg-mixed | 151.101.1.194 |
| 71.2 | shadowsocks | 360.2 | 830.5 | 19.44 | 0.0 | 10.0 | 14.14 | 16.54 | Au1rxx-base64 | 37.19.198.243 |
| 70.85 | trojan | 372.5 | 367.0 | 19.16 | 1.24 | 9.79 | 14.39 | 16.54 | Au1rxx-base64 | 43.207.117.135 |
| 70.85 | trojan | 373.4 | 365.8 | 19.13 | 1.28 | 9.78 | 14.39 | 16.54 | Au1rxx-base64 | 13.115.229.63 |
| 70.75 | trojan | 372.6 | 369.2 | 19.15 | 1.15 | 9.78 | 14.39 | 16.54 | Au1rxx-base64 | 52.194.192.245 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.975 | 1.0 | 35 | 61 | prefer |
| Au1rxx-base64 | 0.947 | 0.95 | 100 | 149 | prefer |
| DeltaKronecker-all | 0.631 | 0.551 | 292 | 8967 | observe |
| Surfboard-tg-mixed | 0.617 | 0.537 | 313 | 5358 | observe |
| mheidari-all | 0.515 | 0.636 | 11 | 16487 | observe |
| nscl5-all | 0.328 | 1.0 | 1 | 1821 | observe |
| xiaoji235-airport-v2ray-all | 0.322 | 1.0 | 1 | 1680 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4428 | observe |
| Epodonios-all | 0.255 | None | 0 | 6542 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7000 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4115 | observe |
| barry-far-vless | 0.255 | None | 0 | 4764 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5208 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 112 |
| geo | TimeoutError | - | 103 |
| cn-block | TimeoutError | - | 24 |
| 204 | TimeoutError | - | 21 |
| 204 | ProxyError | - | 8 |
| geo | ClientOSError | - | 6 |
| speed | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
