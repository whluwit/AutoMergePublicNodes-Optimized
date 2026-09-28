# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-28 12:54:09 |
| 运行耗时 | 624.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 95986 |
| 去重后节点 | 26747 |
| TCP 可达 | 3000 |
| 真实可用 | 435 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26747 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.5 |
| tcp | 44.2 |
| probe | 273.8 |
| real_test | 211.7 |
| generate | 85.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58293 |
| vmess | 14907 |
| shadowsocks | 11455 |
| trojan | 8882 |
| hysteria2 | 1542 |
| http | 617 |
| shadowsocksr | 169 |
| socks | 74 |
| anytls | 24 |
| hysteria | 15 |
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
| 82.27 | hysteria2 | 258.8 | 570.0 | 21.79 | 0.0 | 9.27 | 13.75 | 18.46 | Au1rxx-base64 | 66.94.121.46 |
| 81.23 | hysteria2 | 197.7 | 517.8 | 23.2 | 0.0 | 8.83 | 13.75 | 18.46 | Au1rxx-base64 | 192.255.128.123 |
| 79.32 | shadowsocks | 248.4 | 597.8 | 22.03 | 0.0 | 8.86 | 13.97 | 18.46 | Au1rxx-base64 | 149.22.95.183 |
| 78.95 | shadowsocks | 263.4 | 690.7 | 21.68 | 0.0 | 8.84 | 13.97 | 18.46 | Au1rxx-base64 | 173.244.56.9 |
| 77.45 | vless | 173.8 | 474.6 | 23.75 | 0.0 | 9.0 | 6.24 | 18.46 | Au1rxx-base64 | 137.175.82.40 |
| 77.09 | vless | 198.4 | 523.3 | 23.18 | 0.0 | 9.21 | 6.24 | 18.46 | Au1rxx-base64 | 172.233.139.46 |
| 76.95 | vless | 205.4 | 508.7 | 23.02 | 0.0 | 9.23 | 6.24 | 18.46 | Au1rxx-base64 | 192.3.247.109 |
| 76.29 | shadowsocks | 320.4 | 868.5 | 20.36 | 0.0 | 10.0 | 13.97 | 16.46 | Surfboard-tg-mixed | 5.78.51.123 |
| 76.22 | vless | 227.2 | 545.7 | 22.52 | 0.0 | 9.0 | 6.24 | 18.46 | Au1rxx-base64 | 195.123.240.65 |
| 76.06 | vless | 191.0 | 503.1 | 23.36 | 0.0 | 10.0 | 6.24 | 16.46 | Surfboard-tg-mixed | 172.235.38.85 |
| 75.95 | shadowsocks | 275.5 | 280.9 | 21.4 | 4.47 | 8.82 | 13.97 | 18.46 | Au1rxx-base64 | 149.22.87.240 |
| 75.76 | vless | 200.1 | 509.2 | 23.14 | 0.0 | 8.88 | 6.24 | 18.46 | Au1rxx-base64 | 172.235.43.210 |
| 75.35 | vless | 267.9 | 672.3 | 21.58 | 0.0 | 9.07 | 6.24 | 18.46 | Au1rxx-base64 | 15.204.97.216 |
| 74.85 | vless | 289.2 | 798.0 | 21.08 | 0.0 | 9.07 | 6.24 | 18.46 | Au1rxx-base64 | 23.95.222.127 |
| 74.11 | shadowsocks | 292.7 | 662.5 | 21.0 | 0.0 | 10.0 | 13.97 | 16.46 | Surfboard-tg-mixed | 156.146.38.167 |
| 73.56 | shadowsocks | 293.6 | 334.3 | 20.98 | 2.46 | 8.9 | 13.97 | 18.46 | Au1rxx-base64 | 149.22.87.241 |
| 73.15 | shadowsocks | 380.5 | 912.3 | 18.97 | 0.0 | 9.03 | 13.97 | 18.46 | Au1rxx-base64 | 156.146.38.170 |
| 72.73 | vless | 205.1 | 525.6 | 23.03 | 0.0 | 10.0 | 6.24 | 18.46 | Au1rxx-base64 | 143.246.61.211 |
| 72.58 | shadowsocks | 298.8 | 792.7 | 20.86 | 0.0 | 10.0 | 13.97 | 16.46 | Surfboard-tg-mixed | 108.181.0.177 |
| 71.27 | hysteria2 | 351.6 | 613.3 | 19.64 | 0.0 | 7.84 | 13.75 | 18.46 | Au1rxx-base64 | open.w2m.ink |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.924 | 0.863 | 285 | 1596 | prefer |
| mheidari-all | 0.866 | 0.796 | 54 | 22474 | prefer |
| Surfboard-tg-mixed | 0.811 | 0.734 | 143 | 7046 | prefer |
| ermaozi | 0.68 | 0.673 | 52 | 344 | observe |
| DeltaKronecker-all | 0.4 | 0.75 | 4 | 5428 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 149 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 80 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5326 | observe |
| Epodonios-all | 0.255 | None | 0 | 7414 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9417 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5638 | observe |
| barry-far-vless | 0.255 | None | 0 | 5752 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4185 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 25 |
| 204 | ProxyError | - | 18 |
| speed | ClientOSError | - | 18 |
| 204 | TimeoutError | - | 15 |
| geo | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 7 |
| speed | TimeoutError | - | 6 |
| geo | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
