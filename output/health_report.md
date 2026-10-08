# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-08 12:51:36 |
| 运行耗时 | 594.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98612 |
| 去重后节点 | 27531 |
| TCP 可达 | 3000 |
| 真实可用 | 464 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27531 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 46.6 |
| probe | 235.4 |
| real_test | 216.5 |
| generate | 88.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58372 |
| vmess | 15780 |
| shadowsocks | 11948 |
| trojan | 10308 |
| hysteria2 | 1468 |
| http | 420 |
| shadowsocksr | 170 |
| socks | 87 |
| anytls | 34 |
| hysteria | 16 |
| tuic | 9 |

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
| 84.01 | hysteria2 | 231.3 | 249.4 | 22.42 | 5.65 | 9.47 | 13.8 | 20.0 | Au1rxx-base64 | open.2ml.bid |
| 83.82 | hysteria2 | 231.5 | 243.5 | 22.42 | 5.87 | 9.89 | 13.8 | 20.0 | Au1rxx-base64 | 158.101.148.79 |
| 79.96 | shadowsocks | 234.3 | 585.7 | 22.35 | 0.0 | 10.0 | 12.11 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 79.75 | shadowsocks | 243.8 | 607.6 | 22.14 | 0.0 | 10.0 | 12.11 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 78.95 | shadowsocks | 278.3 | 736.8 | 21.34 | 0.0 | 10.0 | 12.11 | 20.0 | Au1rxx-base64 | 5.78.51.123 |
| 78.28 | shadowsocks | 281.0 | 590.3 | 21.27 | 0.0 | 10.0 | 12.11 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 78.01 | hysteria2 | 345.9 | 768.7 | 19.77 | 0.0 | 10.0 | 13.8 | 20.0 | Au1rxx-base64 | 129.213.91.185 |
| 76.78 | vless | 169.8 | 460.2 | 23.85 | 0.0 | 10.0 | 2.93 | 20.0 | Au1rxx-base64 | 137.175.82.40 |
| 76.73 | vless | 172.0 | 462.1 | 23.8 | 0.0 | 10.0 | 2.93 | 20.0 | Au1rxx-base64 | 47.251.108.158 |
| 76.69 | shadowsocks | 273.5 | 282.5 | 21.45 | 4.41 | 9.9 | 12.11 | 20.0 | Au1rxx-base64 | 149.22.87.241 |
| 76.57 | hysteria2 | 368.9 | 677.0 | 19.24 | 0.0 | 10.0 | 13.8 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 76.52 | shadowsocks | 291.7 | 643.3 | 21.02 | 0.0 | 10.0 | 12.11 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 76.46 | shadowsocks | 275.6 | 288.6 | 21.4 | 4.18 | 9.93 | 12.11 | 20.0 | Au1rxx-base64 | 149.22.87.240 |
| 76.27 | shadowsocks | 279.3 | 288.2 | 21.31 | 4.19 | 9.9 | 12.11 | 20.0 | Au1rxx-base64 | 149.22.87.204 |
| 76.03 | shadowsocks | 188.2 | 500.6 | 23.42 | 0.0 | 10.0 | 12.11 | 20.0 | Au1rxx-base64 | 216.105.168.158 |
| 75.95 | vless | 205.5 | 532.6 | 23.02 | 0.0 | 10.0 | 2.93 | 20.0 | Au1rxx-base64 | 107.173.237.146 |
| 75.73 | shadowsocks | 284.6 | 644.4 | 21.19 | 0.0 | 10.0 | 12.11 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 75.39 | vless | 229.7 | 561.8 | 22.46 | 0.0 | 10.0 | 2.93 | 20.0 | Au1rxx-base64 | 15.204.97.197 |
| 75.36 | vless | 231.0 | 566.2 | 22.43 | 0.0 | 10.0 | 2.93 | 20.0 | Au1rxx-base64 | 15.204.97.216 |
| 74.95 | shadowsocks | 308.0 | 709.0 | 20.65 | 0.0 | 10.0 | 12.11 | 20.0 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| mheidari-all | 0.947 | 0.884 | 43 | 23417 | prefer |
| Au1rxx-base64 | 0.929 | 0.858 | 345 | 1824 | prefer |
| Surfboard-tg-mixed | 0.752 | 0.675 | 126 | 7320 | prefer |
| DeltaKronecker-all | 0.625 | 0.548 | 31 | 5197 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ermaozi | 0.258 | 1.0 | 1 | 66 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5081 | observe |
| Epodonios-all | 0.255 | None | 0 | 7669 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9654 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5776 | observe |
| barry-far-vless | 0.255 | None | 0 | 5968 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4431 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 28 |
| 204 | ProxyError | - | 22 |
| 204 | TimeoutError | - | 19 |
| geo | TimeoutError | - | 15 |
| speed | ClientOSError | - | 14 |
| geo | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 6 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 240 | 300 | - |
| global | False | 249 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
