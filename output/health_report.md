# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 20:56:49 |
| 运行耗时 | 563.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84749 |
| 去重后节点 | 23096 |
| TCP 可达 | 3000 |
| 真实可用 | 438 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23096 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.5 |
| tcp | 37.9 |
| probe | 224.1 |
| real_test | 209.1 |
| generate | 84.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51833 |
| vmess | 12978 |
| shadowsocks | 9473 |
| trojan | 8321 |
| hysteria2 | 1321 |
| http | 624 |
| shadowsocksr | 126 |
| socks | 55 |
| hysteria | 11 |
| tuic | 5 |
| anytls | 2 |

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
| 81.94 | hysteria2 | 269.5 | 729.3 | 21.54 | 0.0 | 10.0 | 12.86 | 18.54 | Au1rxx-base64 | 107.175.219.48 |
| 80.8 | shadowsocks | 201.4 | 488.0 | 23.12 | 0.0 | 10.0 | 13.64 | 18.54 | Au1rxx-base64 | 108.181.0.177 |
| 80.72 | vless | 191.4 | 480.1 | 23.35 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 45.149.172.74 |
| 80.71 | vless | 191.6 | 489.4 | 23.34 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 172.235.38.85 |
| 80.32 | vless | 208.4 | 539.0 | 22.95 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 172.235.43.210 |
| 78.78 | hysteria2 | 214.0 | 537.7 | 22.82 | 0.0 | 10.0 | 12.86 | 16.1 | Surfboard-tg-mixed | 45.149.172.80 |
| 78.64 | vless | 242.4 | 523.5 | 22.17 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 150.241.102.181 |
| 78.25 | shadowsocks | 205.9 | 524.6 | 23.01 | 0.0 | 10.0 | 13.64 | 16.1 | Surfboard-tg-mixed | 5.78.51.123 |
| 77.83 | vless | 316.2 | 827.7 | 20.46 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 15.204.97.216 |
| 76.57 | vless | 191.5 | 495.2 | 23.34 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 45.149.172.80 |
| 76.34 | shadowsocks | 285.9 | 715.0 | 21.16 | 0.0 | 10.0 | 13.64 | 18.54 | Au1rxx-base64 | 173.244.56.6 |
| 75.74 | hysteria2 | 213.7 | 516.9 | 22.83 | 0.0 | 10.0 | 12.86 | 16.1 | Surfboard-tg-mixed | 45.149.172.74 |
| 75.57 | vless | 208.6 | 488.9 | 22.95 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 104.18.46.46 |
| 75.52 | vless | 199.9 | 516.1 | 23.15 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 192.3.247.109 |
| 75.18 | hysteria2 | 357.8 | 740.5 | 19.5 | 0.0 | 10.0 | 12.86 | 18.54 | Au1rxx-base64 | 159.223.157.129 |
| 75.11 | vless | 239.3 | 504.9 | 22.24 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 162.159.45.19 |
| 75.01 | shadowsocks | 306.2 | 663.8 | 20.69 | 0.0 | 10.0 | 13.64 | 18.54 | Au1rxx-base64 | 156.146.38.168 |
| 74.71 | vless | 216.2 | 489.7 | 22.77 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | cf6.danfeng.eu.org |
| 74.67 | vless | 286.0 | 553.1 | 21.16 | 0.0 | 10.0 | 8.83 | 18.54 | Au1rxx-base64 | 144.172.104.26 |
| 74.55 | trojan | 184.6 | 495.5 | 23.51 | 0.0 | 10.0 | 13.12 | 10.42 | mheidari-all | 100.42.228.109 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | 0.884 | 303 | 1553 | prefer |
| DeltaKronecker-all | 0.772 | 0.703 | 37 | 5932 | prefer |
| mheidari-all | 0.765 | 0.692 | 52 | 15952 | prefer |
| ermaozi | 0.748 | 0.744 | 39 | 406 | prefer |
| Surfboard-tg-mixed | 0.713 | 0.636 | 118 | 7516 | prefer |
| ermaozi-get_subscribe | 0.328 | 1.0 | 2 | 422 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 148 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7982 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8946 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6065 | observe |
| barry-far-vless | 0.255 | None | 0 | 6289 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 24 |
| geo | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 18 |
| cn-block | ClientOSError | - | 17 |
| 204 | ProxyError | - | 10 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyConnectionError | - | 7 |
| 204 | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| speed | TimeoutError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
