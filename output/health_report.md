# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 21:08:38 |
| 运行耗时 | 547.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 97109 |
| 去重后节点 | 26649 |
| TCP 可达 | 3000 |
| 真实可用 | 391 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26649 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 42.8 |
| probe | 207.4 |
| real_test | 201.6 |
| generate | 87.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59659 |
| vmess | 14851 |
| shadowsocks | 11181 |
| trojan | 9029 |
| hysteria2 | 1484 |
| http | 601 |
| shadowsocksr | 171 |
| socks | 82 |
| anytls | 25 |
| hysteria | 18 |
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
| 80.14 | shadowsocks | 254.2 | 626.4 | 21.89 | 0.0 | 10.0 | 13.51 | 19.74 | Au1rxx-base64 | 156.146.38.169 |
| 79.54 | shadowsocks | 257.0 | 624.7 | 21.83 | 0.0 | 8.46 | 13.51 | 19.74 | Au1rxx-base64 | 156.146.38.168 |
| 78.34 | vless | 318.6 | 712.3 | 20.4 | 0.0 | 8.41 | 9.79 | 19.74 | Au1rxx-base64 | 23.132.28.51 |
| 77.93 | vless | 339.3 | 891.0 | 19.92 | 0.0 | 8.48 | 9.79 | 19.74 | Au1rxx-base64 | 34.85.179.6 |
| 77.6 | vless | 354.1 | 759.8 | 19.58 | 0.0 | 8.49 | 9.79 | 19.74 | Au1rxx-base64 | 169.40.42.229 |
| 77.49 | vless | 324.6 | 829.0 | 20.26 | 0.0 | 8.48 | 9.79 | 19.74 | Au1rxx-base64 | 198.251.78.29 |
| 77.23 | shadowsocks | 248.9 | 615.3 | 22.02 | 0.0 | 10.0 | 13.51 | 15.7 | Surfboard-tg-mixed | 198.98.53.130 |
| 77.15 | vless | 256.9 | 714.0 | 21.83 | 0.0 | 10.0 | 9.79 | 19.74 | Au1rxx-base64 | 195.211.98.43 |
| 76.75 | vless | 393.1 | 808.1 | 18.68 | 0.0 | 8.54 | 9.79 | 19.74 | Au1rxx-base64 | 169.40.42.74 |
| 76.71 | vless | 394.6 | 1020.2 | 18.64 | 0.0 | 8.54 | 9.79 | 19.74 | Au1rxx-base64 | 185.95.231.156 |
| 76.67 | vless | 447.0 | 1009.3 | 17.43 | 0.0 | 10.0 | 9.79 | 19.74 | Au1rxx-base64 | 169.40.42.212 |
| 76.62 | vless | 362.7 | 913.5 | 19.38 | 0.0 | 8.48 | 9.79 | 19.74 | Au1rxx-base64 | 169.40.42.232 |
| 76.43 | hysteria2 | 346.8 | 732.4 | 19.75 | 0.0 | 10.0 | 12.14 | 19.74 | Au1rxx-base64 | 66.94.121.46 |
| 76.4 | vless | 372.4 | 810.2 | 19.16 | 0.0 | 8.45 | 9.79 | 19.74 | Au1rxx-base64 | 169.40.42.95 |
| 75.8 | vless | 399.6 | 897.1 | 18.53 | 0.0 | 8.45 | 9.79 | 19.74 | Au1rxx-base64 | 169.40.42.90 |
| 75.47 | vless | 476.5 | 1121.3 | 16.75 | 0.0 | 10.0 | 9.79 | 19.74 | Au1rxx-base64 | 169.40.42.75 |
| 75.19 | vless | 299.1 | 733.8 | 20.85 | 0.0 | 10.0 | 9.79 | 19.74 | Au1rxx-base64 | 162.35.96.39 |
| 75.14 | vless | 452.9 | 910.4 | 17.29 | 0.0 | 8.55 | 9.79 | 19.74 | Au1rxx-base64 | 169.40.42.231 |
| 75.03 | shadowsocks | 306.9 | 625.1 | 20.67 | 0.0 | 10.0 | 13.51 | 19.74 | Au1rxx-base64 | 173.244.56.6 |
| 74.93 | vless | 461.4 | 1075.4 | 17.1 | 0.0 | 8.49 | 9.79 | 19.74 | Au1rxx-base64 | 169.40.42.15 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | 0.915 | 248 | 1636 | prefer |
| mheidari-all | 0.937 | 0.867 | 75 | 22531 | prefer |
| ermaozi | 0.793 | 0.8 | 30 | 291 | prefer |
| Surfboard-tg-mixed | 0.732 | 0.655 | 110 | 7072 | prefer |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4332 | observe |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 6471 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5131 | observe |
| Epodonios-all | 0.255 | None | 0 | 7534 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9136 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5711 | observe |
| barry-far-vless | 0.255 | None | 0 | 5930 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1636 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 13 |
| geo | TimeoutError | - | 6 |
| speed | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
