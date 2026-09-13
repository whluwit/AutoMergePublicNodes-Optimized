# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 15:40:49 |
| 运行耗时 | 640.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 95123 |
| 去重后节点 | 25317 |
| TCP 可达 | 3000 |
| 真实可用 | 413 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25317 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.4 |
| tcp | 42.8 |
| probe | 272.9 |
| real_test | 237.7 |
| generate | 79.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58645 |
| vmess | 13653 |
| shadowsocks | 10959 |
| trojan | 8802 |
| hysteria2 | 2251 |
| http | 584 |
| shadowsocksr | 126 |
| socks | 60 |
| hysteria | 17 |
| anytls | 14 |
| tuic | 12 |

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
| 80.07 | shadowsocks | 254.5 | 615.8 | 21.89 | 0.0 | 10.0 | 13.74 | 18.44 | mheidari-all | 156.146.38.168 |
| 79.87 | vless | 244.5 | 606.3 | 22.12 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 198.251.78.29 |
| 79.53 | hysteria2 | 295.7 | 752.4 | 20.93 | 0.0 | 10.0 | 12.6 | 17.1 | Au1rxx-base64 | 159.223.157.129 |
| 79.36 | vless | 266.5 | 692.0 | 21.61 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 79.141.172.154 |
| 79.3 | shadowsocks | 287.7 | 736.1 | 21.12 | 0.0 | 10.0 | 13.74 | 18.44 | mheidari-all | 37.19.198.244 |
| 79.2 | vless | 273.4 | 704.4 | 21.45 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 216.152.147.28 |
| 78.5 | shadowsocks | 264.1 | 654.1 | 21.66 | 0.0 | 10.0 | 13.74 | 17.1 | Au1rxx-base64 | 156.146.38.170 |
| 78.45 | vless | 305.7 | 781.1 | 20.7 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 47.253.226.114 |
| 78.28 | shadowsocks | 244.7 | 593.5 | 22.11 | 0.0 | 9.33 | 13.74 | 17.1 | Au1rxx-base64 | 156.146.38.169 |
| 78.16 | shadowsocks | 248.6 | 616.6 | 22.02 | 0.0 | 9.3 | 13.74 | 17.1 | Au1rxx-base64 | 198.98.53.130 |
| 77.8 | vless | 333.9 | 848.8 | 20.05 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 47.89.186.170 |
| 77.49 | vless | 347.1 | 865.0 | 19.74 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 137.184.218.169 |
| 77.49 | vless | 347.2 | 762.0 | 19.74 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 169.40.42.229 |
| 77.02 | shadowsocks | 250.5 | 612.2 | 21.98 | 0.0 | 10.0 | 13.74 | 16.3 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.87 | vless | 309.5 | 733.4 | 20.61 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 2.24.124.64 |
| 76.84 | vless | 320.0 | 673.7 | 20.37 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 169.40.42.15 |
| 76.7 | vless | 381.4 | 996.1 | 18.95 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 185.95.231.156 |
| 75.92 | vless | 380.4 | 967.4 | 18.97 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 195.123.235.177 |
| 75.91 | vless | 314.5 | 777.4 | 20.5 | 0.0 | 10.0 | 10.65 | 17.1 | Au1rxx-base64 | 169.40.42.95 |
| 75.87 | hysteria2 | 262.4 | 547.5 | 21.7 | 0.0 | 9.32 | 12.6 | 17.1 | Au1rxx-base64 | 66.94.121.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.891 | 0.826 | 304 | 1678 | prefer |
| Surfboard-tg-mixed | 0.775 | 0.7 | 80 | 7605 | prefer |
| ermaozi | 0.654 | 0.647 | 34 | 382 | observe |
| mheidari-all | 0.489 | 0.408 | 201 | 20611 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5301 | observe |
| DeltaKronecker-all | 0.259 | 0.333 | 3 | 5892 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7899 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9265 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6236 | observe |
| barry-far-vless | 0.255 | None | 0 | 6452 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4221 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1678 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 61 |
| cn-block | ClientOSError | - | 46 |
| speed | ClientOSError | - | 24 |
| 204 | ProxyError | - | 23 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 16 |
| speed | TimeoutError | - | 12 |
| geo | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
