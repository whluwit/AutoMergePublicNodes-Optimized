# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 20:36:29 |
| 运行耗时 | 653.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99390 |
| 去重后节点 | 27653 |
| TCP 可达 | 3000 |
| 真实可用 | 397 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27653 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 48.1 |
| probe | 252.9 |
| real_test | 253.9 |
| generate | 90.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58384 |
| vmess | 16709 |
| shadowsocks | 12090 |
| trojan | 9988 |
| hysteria2 | 1312 |
| http | 631 |
| shadowsocksr | 166 |
| socks | 58 |
| anytls | 29 |
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
| 79.13 | vless | 221.9 | 603.9 | 22.64 | 0.0 | 10.0 | 9.77 | 16.72 | Au1rxx-base64 | 195.211.98.43 |
| 77.38 | shadowsocks | 255.8 | 624.0 | 21.86 | 0.0 | 10.0 | 12.8 | 16.72 | Au1rxx-base64 | 156.146.38.169 |
| 77.34 | vless | 299.1 | 798.3 | 20.85 | 0.0 | 10.0 | 9.77 | 16.72 | Au1rxx-base64 | 147.45.60.160 |
| 77.01 | hysteria2 | 272.1 | 686.0 | 21.48 | 0.0 | 10.0 | 10.31 | 16.72 | Au1rxx-base64 | 129.213.91.185 |
| 76.73 | shadowsocks | 283.9 | 713.3 | 21.21 | 0.0 | 10.0 | 12.8 | 16.72 | Au1rxx-base64 | 37.19.198.243 |
| 76.7 | shadowsocks | 284.9 | 727.0 | 21.18 | 0.0 | 10.0 | 12.8 | 16.72 | Au1rxx-base64 | 37.19.198.244 |
| 76.7 | shadowsocks | 284.9 | 728.9 | 21.18 | 0.0 | 10.0 | 12.8 | 16.72 | Au1rxx-base64 | 37.19.198.236 |
| 76.67 | shadowsocks | 286.5 | 726.0 | 21.15 | 0.0 | 10.0 | 12.8 | 16.72 | Au1rxx-base64 | 37.19.198.160 |
| 76.21 | shadowsocks | 254.7 | 627.1 | 21.88 | 0.0 | 10.0 | 12.8 | 16.72 | Au1rxx-base64 | 156.146.38.168 |
| 75.83 | vless | 320.7 | 654.6 | 20.35 | 0.0 | 10.0 | 9.77 | 16.72 | Au1rxx-base64 | 169.40.42.133 |
| 75.75 | vless | 367.8 | 944.2 | 19.26 | 0.0 | 10.0 | 9.77 | 16.72 | Au1rxx-base64 | 185.95.231.156 |
| 75.32 | vless | 312.4 | 728.3 | 20.55 | 0.0 | 10.0 | 9.77 | 16.72 | Au1rxx-base64 | 66.70.179.198 |
| 75.25 | vless | 372.2 | 949.3 | 19.16 | 0.0 | 10.0 | 9.77 | 16.72 | Au1rxx-base64 | 167.17.69.171 |
| 74.75 | shadowsocks | 254.3 | 624.9 | 21.89 | 0.0 | 10.0 | 12.8 | 16.72 | Au1rxx-base64 | 156.146.38.170 |
| 74.59 | vless | 299.2 | 679.9 | 20.85 | 0.0 | 10.0 | 9.77 | 16.72 | Au1rxx-base64 | 198.23.169.170 |
| 74.51 | hysteria2 | 291.7 | 617.8 | 21.03 | 0.0 | 10.0 | 10.31 | 16.72 | Au1rxx-base64 | 66.94.121.46 |
| 73.86 | vless | 255.2 | 631.7 | 21.87 | 0.0 | 10.0 | 9.77 | 16.72 | Au1rxx-base64 | 69.48.201.136 |
| 73.28 | vless | 337.1 | 747.3 | 19.97 | 0.0 | 10.0 | 9.77 | 16.72 | Au1rxx-base64 | 169.40.42.225 |
| 73.13 | shadowsocks | 288.0 | 745.2 | 21.11 | 0.0 | 10.0 | 12.8 | 16.72 | Au1rxx-base64 | 64.74.163.69 |
| 72.85 | trojan | 465.3 | 1232.1 | 17.01 | 0.0 | 10.0 | 12.12 | 16.72 | Au1rxx-base64 | 69.164.240.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.859 | 0.78 | 460 | 1995 | prefer |
| mheidari-all | 0.538 | 0.455 | 22 | 23910 | observe |
| ermaozi | 0.415 | 0.386 | 57 | 618 | observe |
| Surfboard-tg-mixed | 0.4 | 0.75 | 4 | 7222 | observe |
| ermaozi-get_subscribe | 0.274 | 1.0 | 1 | 484 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 88 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7598 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10077 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5648 | observe |
| barry-far-vless | 0.255 | None | 0 | 5818 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 38 |
| 204 | TimeoutError | - | 38 |
| speed | ClientOSError | - | 16 |
| speed | TimeoutError | - | 16 |
| cn-block | TimeoutError | - | 15 |
| 204 | ClientOSError | - | 6 |
| geo | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| geo | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 1 |
| geo | parse | TimeoutError | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
