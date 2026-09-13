# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 20:21:49 |
| 运行耗时 | 614.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90439 |
| 去重后节点 | 25490 |
| TCP 可达 | 3000 |
| 真实可用 | 444 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25490 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 43.8 |
| probe | 255.6 |
| real_test | 228.6 |
| generate | 78.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55332 |
| vmess | 13459 |
| shadowsocks | 10565 |
| trojan | 8295 |
| hysteria2 | 1953 |
| http | 613 |
| shadowsocksr | 128 |
| socks | 60 |
| hysteria | 14 |
| tuic | 12 |
| anytls | 8 |

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
| 79.95 | shadowsocks | 206.7 | 500.3 | 22.99 | 0.0 | 10.0 | 13.64 | 17.82 | Au1rxx-base64 | 108.181.118.10 |
| 79.67 | shadowsocks | 213.4 | 524.7 | 22.84 | 0.0 | 9.37 | 13.64 | 17.82 | Au1rxx-base64 | 173.244.56.6 |
| 79.42 | shadowsocks | 247.7 | 598.3 | 22.04 | 0.0 | 10.0 | 13.64 | 17.82 | Au1rxx-base64 | 156.146.38.169 |
| 78.61 | shadowsocks | 259.8 | 665.5 | 21.76 | 0.0 | 9.39 | 13.64 | 17.82 | Au1rxx-base64 | 173.244.56.9 |
| 78.49 | vless | 200.8 | 500.6 | 23.13 | 0.0 | 9.51 | 8.03 | 17.82 | Au1rxx-base64 | 172.235.43.210 |
| 78.36 | hysteria2 | 242.8 | 549.1 | 22.16 | 0.0 | 9.48 | 10.8 | 17.82 | Au1rxx-base64 | 66.94.121.46 |
| 78.2 | shadowsocks | 255.0 | 614.3 | 21.87 | 0.0 | 9.39 | 13.64 | 17.82 | Au1rxx-base64 | 156.146.38.170 |
| 78.02 | shadowsocks | 261.9 | 634.1 | 21.72 | 0.0 | 9.42 | 13.64 | 17.82 | Au1rxx-base64 | 156.146.38.167 |
| 77.39 | shadowsocks | 280.0 | 615.0 | 21.3 | 0.0 | 9.44 | 13.64 | 17.82 | Au1rxx-base64 | 23.150.248.20 |
| 75.21 | shadowsocks | 277.8 | 600.5 | 21.35 | 0.0 | 9.36 | 13.64 | 17.82 | Au1rxx-base64 | 149.22.95.183 |
| 74.25 | vless | 338.9 | 791.9 | 19.93 | 0.0 | 10.0 | 8.03 | 17.82 | Au1rxx-base64 | 15.204.97.216 |
| 74.14 | hysteria2 | 290.0 | 765.7 | 21.07 | 0.0 | 9.42 | 10.8 | 17.82 | Au1rxx-base64 | 107.175.219.48 |
| 73.0 | vless | 218.7 | 511.6 | 22.71 | 0.0 | 9.44 | 8.03 | 17.82 | Au1rxx-base64 | 192.3.247.109 |
| 72.99 | trojan | 383.9 | 931.4 | 18.89 | 0.0 | 9.49 | 12.6 | 17.82 | Au1rxx-base64 | 64.94.95.118 |
| 72.99 | trojan | 393.5 | 952.2 | 18.67 | 0.0 | 9.63 | 12.6 | 17.82 | Au1rxx-base64 | 64.94.95.117 |
| 72.93 | vless | 320.3 | 722.0 | 20.36 | 0.0 | 9.46 | 8.03 | 17.82 | Au1rxx-base64 | 79.141.172.154 |
| 72.91 | vless | 204.9 | 497.7 | 23.03 | 0.0 | 9.47 | 8.03 | 17.82 | Au1rxx-base64 | 172.233.139.46 |
| 72.74 | vless | 275.7 | 437.6 | 21.39 | 0.0 | 10.0 | 8.03 | 17.82 | Au1rxx-base64 | 172.64.53.55 |
| 72.72 | trojan | 410.4 | 1014.1 | 18.28 | 0.0 | 9.63 | 12.6 | 17.82 | Au1rxx-base64 | 64.94.95.114 |
| 72.4 | vless | 267.4 | 430.7 | 21.59 | 0.0 | 9.5 | 8.03 | 17.82 | Au1rxx-base64 | 172.64.52.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | 0.912 | 307 | 1781 | prefer |
| mheidari-all | 0.868 | 0.8 | 50 | 16210 | prefer |
| Surfboard-tg-mixed | 0.758 | 0.681 | 116 | 7573 | prefer |
| DeltaKronecker-all | 0.757 | 0.69 | 29 | 5892 | prefer |
| ermaozi | 0.583 | 0.571 | 35 | 382 | observe |
| xiaoji235-airport-v2ray-all | 0.421 | 0.667 | 6 | 5301 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| Epodonios-all | 0.255 | None | 0 | 8029 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8804 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6175 | observe |
| barry-far-vless | 0.255 | None | 0 | 6390 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1781 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 28 |
| 204 | ProxyError | - | 20 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| speed | TimeoutError | - | 5 |
| geo | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | exit-country | CN | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
