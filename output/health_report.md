# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 10:45:15 |
| 运行耗时 | 736.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99210 |
| 去重后节点 | 27570 |
| TCP 可达 | 3000 |
| 真实可用 | 369 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27570 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 48.4 |
| probe | 292.8 |
| real_test | 278.1 |
| generate | 107.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58375 |
| vmess | 16404 |
| shadowsocks | 11831 |
| trojan | 10331 |
| hysteria2 | 1259 |
| http | 740 |
| shadowsocksr | 165 |
| socks | 57 |
| anytls | 25 |
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
| 82.45 | hysteria2 | 200.5 | 537.8 | 23.14 | 0.0 | 10.0 | 14.25 | 16.06 | Au1rxx-base64 | 66.94.121.46 |
| 77.8 | shadowsocks | 210.5 | 564.0 | 22.91 | 0.0 | 8.86 | 13.97 | 16.06 | Au1rxx-base64 | 149.22.95.183 |
| 74.89 | hysteria2 | 346.1 | 766.6 | 19.77 | 0.0 | 10.0 | 14.25 | 16.06 | Au1rxx-base64 | 129.213.91.185 |
| 74.28 | vless | 250.6 | 613.2 | 21.98 | 0.0 | 8.49 | 7.75 | 16.06 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 74.27 | shadowsocks | 258.7 | 267.7 | 21.79 | 4.96 | 8.81 | 13.97 | 16.06 | Au1rxx-base64 | 149.22.87.204 |
| 74.16 | shadowsocks | 261.0 | 277.4 | 21.74 | 4.6 | 8.8 | 13.97 | 16.06 | Au1rxx-base64 | 149.22.87.241 |
| 74.12 | vless | 281.2 | 704.6 | 21.27 | 0.0 | 9.04 | 7.75 | 16.06 | Au1rxx-base64 | 44.248.233.99 |
| 73.54 | vless | 300.8 | 806.8 | 20.82 | 0.0 | 8.91 | 7.75 | 16.06 | Au1rxx-base64 | 51.81.203.63 |
| 71.57 | shadowsocks | 277.7 | 332.7 | 21.35 | 2.52 | 8.8 | 13.97 | 16.06 | Au1rxx-base64 | 149.22.87.240 |
| 71.18 | trojan | 309.4 | 319.0 | 20.62 | 3.04 | 9.06 | 12.14 | 16.06 | Au1rxx-base64 | 108.61.186.37 |
| 71.15 | shadowsocks | 316.9 | 681.5 | 20.44 | 0.0 | 8.85 | 13.97 | 16.06 | Au1rxx-base64 | 156.146.38.169 |
| 70.99 | shadowsocks | 327.0 | 700.8 | 20.21 | 0.0 | 8.85 | 13.97 | 16.06 | Au1rxx-base64 | 156.146.38.168 |
| 70.56 | vless | 260.8 | 564.2 | 21.74 | 0.0 | 10.0 | 7.75 | 16.06 | Au1rxx-base64 | 154.29.159.211 |
| 70.2 | vless | 328.4 | 866.4 | 20.18 | 0.0 | 9.1 | 7.75 | 16.06 | Au1rxx-base64 | 136.67.16.72 |
| 69.82 | trojan | 311.3 | 323.3 | 20.57 | 2.88 | 7.91 | 12.14 | 16.06 | Au1rxx-base64 | jp.tronsg.com |
| 69.62 | hysteria2 | 294.5 | 501.9 | 20.96 | 0.0 | 6.63 | 14.25 | 16.06 | Au1rxx-base64 | starlink-ft.251313.xyz |
| 69.36 | trojan | 310.8 | 318.2 | 20.58 | 3.07 | 8.85 | 12.14 | 16.06 | Au1rxx-base64 | 45.32.52.173 |
| 68.87 | shadowsocks | 275.8 | 575.5 | 21.39 | 0.0 | 10.0 | 13.97 | 16.06 | Au1rxx-base64 | 173.244.56.6 |
| 68.63 | vless | 319.0 | 326.3 | 20.39 | 2.76 | 8.88 | 7.75 | 16.06 | Au1rxx-base64 | 43.167.232.174 |
| 68.62 | shadowsocks | 377.4 | 797.1 | 19.04 | 0.0 | 8.85 | 13.97 | 16.06 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.849 | 0.771 | 397 | 1990 | prefer |
| ermaozi | 0.538 | 0.511 | 92 | 693 | observe |
| mheidari-all | 0.397 | 0.417 | 12 | 23871 | observe |
| Surfboard-tg-mixed | 0.344 | 0.333 | 12 | 7054 | observe |
| DeltaKronecker-all | 0.314 | 0.222 | 18 | 4946 | observe |
| ermaozi-get_subscribe | 0.291 | 0.667 | 3 | 574 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 79 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1990 | observe |
| Epodonios-all | 0.255 | None | 0 | 7568 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10065 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5573 | observe |
| barry-far-vless | 0.255 | None | 0 | 5827 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4265 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 46 |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 21 |
| speed | TimeoutError | - | 20 |
| geo | TimeoutError | - | 12 |
| speed | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 8 |
| geo | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyConnectionError | - | 5 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| cn-block | status | 530 | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
