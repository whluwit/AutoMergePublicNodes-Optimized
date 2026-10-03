# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 20:39:56 |
| 运行耗时 | 544.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99459 |
| 去重后节点 | 27313 |
| TCP 可达 | 3000 |
| 真实可用 | 408 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27313 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.0 |
| tcp | 47.6 |
| probe | 226.9 |
| real_test | 173.5 |
| generate | 88.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60567 |
| vmess | 15692 |
| shadowsocks | 11385 |
| trojan | 9459 |
| hysteria2 | 1552 |
| http | 522 |
| shadowsocksr | 167 |
| socks | 68 |
| anytls | 24 |
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
| 78.42 | hysteria2 | 293.3 | 696.3 | 20.99 | 0.0 | 10.0 | 13.12 | 16.78 | mheidari-all | 159.223.157.129 |
| 78.12 | hysteria2 | 294.0 | 257.8 | 20.97 | 5.33 | 8.42 | 13.12 | 18.12 | Au1rxx-base64 | open.2ml.bid |
| 77.9 | shadowsocks | 291.9 | 747.4 | 21.02 | 0.0 | 10.0 | 12.2 | 18.68 | Surfboard-tg-mixed | 156.146.38.169 |
| 77.22 | vless | 343.0 | 804.2 | 19.84 | 0.0 | 10.0 | 11.91 | 18.12 | Au1rxx-base64 | 66.70.179.198 |
| 76.56 | vless | 300.7 | 598.7 | 20.82 | 0.0 | 10.0 | 11.91 | 18.12 | Au1rxx-base64 | 172.233.139.46 |
| 76.45 | shadowsocks | 308.9 | 712.1 | 20.63 | 0.0 | 10.0 | 12.2 | 18.12 | Au1rxx-base64 | 198.98.53.130 |
| 76.44 | vless | 311.7 | 641.6 | 20.56 | 0.0 | 10.0 | 11.91 | 18.12 | Au1rxx-base64 | 172.235.43.210 |
| 76.35 | vless | 295.1 | 597.2 | 20.95 | 0.0 | 10.0 | 11.91 | 18.12 | Au1rxx-base64 | 172.235.38.85 |
| 76.26 | shadowsocks | 303.3 | 748.1 | 20.76 | 0.0 | 10.0 | 12.2 | 18.12 | Au1rxx-base64 | 37.19.198.243 |
| 76.22 | hysteria2 | 425.9 | 1115.5 | 17.92 | 0.0 | 10.0 | 13.12 | 18.68 | Surfboard-tg-mixed | 129.213.91.185 |
| 75.64 | vless | 470.2 | 1187.1 | 16.89 | 0.0 | 10.0 | 11.91 | 18.12 | Au1rxx-base64 | 198.251.78.29 |
| 75.37 | shadowsocks | 355.6 | 925.5 | 19.55 | 0.0 | 10.0 | 12.2 | 18.12 | Au1rxx-base64 | 185.156.47.97 |
| 75.36 | shadowsocks | 304.0 | 738.6 | 20.74 | 0.0 | 10.0 | 12.2 | 18.12 | Au1rxx-base64 | 37.19.198.236 |
| 75.27 | shadowsocks | 255.8 | 548.5 | 21.86 | 0.0 | 10.0 | 12.2 | 18.12 | Au1rxx-base64 | 103.214.109.197 |
| 75.23 | hysteria2 | 317.0 | 636.7 | 20.44 | 0.0 | 10.0 | 13.12 | 18.12 | Au1rxx-base64 | 66.94.121.46 |
| 75.09 | vless | 346.8 | 750.6 | 19.75 | 0.0 | 10.0 | 11.91 | 18.12 | Au1rxx-base64 | 169.40.42.90 |
| 74.99 | vless | 324.3 | 644.5 | 20.27 | 0.0 | 10.0 | 11.91 | 18.12 | Au1rxx-base64 | 15.204.97.216 |
| 74.86 | vless | 411.0 | 1025.0 | 18.26 | 0.0 | 10.0 | 11.91 | 18.12 | Au1rxx-base64 | 185.95.231.233 |
| 74.7 | vless | 445.2 | 1101.9 | 17.47 | 0.0 | 10.0 | 11.91 | 18.12 | Au1rxx-base64 | 137.184.218.169 |
| 74.68 | shadowsocks | 336.8 | 831.7 | 19.98 | 0.0 | 10.0 | 12.2 | 18.12 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | 0.895 | 334 | 1802 | prefer |
| mheidari-all | 0.901 | 0.838 | 37 | 23599 | prefer |
| Surfboard-tg-mixed | 0.808 | 0.734 | 79 | 7340 | prefer |
| ermaozi | 0.804 | 0.8 | 25 | 656 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5192 | observe |
| Epodonios-all | 0.255 | None | 0 | 7819 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9376 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5938 | observe |
| barry-far-vless | 0.255 | None | 0 | 6176 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4285 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1802 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| speed | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | TimeoutError | - | 3 |
| speed | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
