# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-28 08:51:17 |
| 运行耗时 | 300.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 75951 |
| 去重后节点 | 22914 |
| TCP 可达 | 3000 |
| 真实可用 | 558 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22914 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 30.1 |
| probe | 65.6 |
| real_test | 161.1 |
| generate | 37.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42105 |
| trojan | 12645 |
| vmess | 11273 |
| shadowsocks | 9348 |
| hysteria2 | 232 |
| shadowsocksr | 160 |
| http | 135 |
| socks | 45 |
| hysteria | 6 |
| tuic | 2 |

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
| 79.51 | trojan | 245.2 | 642.4 | 22.1 | 0.0 | 10.0 | 12.27 | 17.64 | Surfboard-tg-mixed | 45.61.58.89 |
| 75.8 | shadowsocks | 210.7 | 502.8 | 22.9 | 0.0 | 10.0 | 12.68 | 14.22 | Au1rxx-base64 | 173.244.56.9 |
| 74.31 | vless | 289.8 | 690.1 | 21.07 | 0.0 | 10.0 | 8.56 | 14.68 | mheidari-all | 34.213.172.16 |
| 73.96 | trojan | 337.2 | 884.7 | 19.97 | 0.0 | 10.0 | 12.27 | 14.22 | Au1rxx-base64 | 45.61.52.243 |
| 73.83 | trojan | 342.9 | 907.7 | 19.84 | 0.0 | 10.0 | 12.27 | 14.22 | Au1rxx-base64 | 207.126.167.150 |
| 73.77 | shadowsocks | 255.4 | 640.2 | 21.87 | 0.0 | 10.0 | 12.68 | 14.22 | Au1rxx-base64 | 173.244.56.6 |
| 73.61 | shadowsocks | 283.7 | 741.2 | 21.21 | 0.0 | 10.0 | 12.68 | 14.22 | Au1rxx-base64 | 108.181.0.177 |
| 73.44 | shadowsocks | 291.0 | 768.2 | 21.04 | 0.0 | 10.0 | 12.68 | 14.22 | Au1rxx-base64 | 108.181.118.10 |
| 73.31 | vless | 289.2 | 628.4 | 21.08 | 0.0 | 10.0 | 8.56 | 17.64 | Surfboard-tg-mixed | 162.159.18.241 |
| 72.99 | vless | 217.3 | 553.1 | 22.75 | 0.0 | 10.0 | 8.56 | 14.68 | mheidari-all | 38.244.21.164 |
| 71.27 | shadowsocks | 291.5 | 658.1 | 21.03 | 0.0 | 10.0 | 12.68 | 14.22 | Au1rxx-base64 | 156.146.38.167 |
| 70.7 | shadowsocks | 293.7 | 659.1 | 20.98 | 0.0 | 10.0 | 12.68 | 14.22 | Au1rxx-base64 | 156.146.38.168 |
| 70.51 | shadowsocks | 289.2 | 648.4 | 21.08 | 0.0 | 10.0 | 12.68 | 14.22 | Au1rxx-base64 | 156.146.38.170 |
| 70.38 | trojan | 315.2 | 678.7 | 20.48 | 0.0 | 10.0 | 12.27 | 14.68 | mheidari-all | 64.94.95.118 |
| 70.32 | http | 176.6 | 491.5 | 23.69 | 0.0 | 0.0 | 14.61 | 19.52 | snakem982 | 9420e530-te8ao0-tfnl0i-au6.fmtdc1.sghuawei.com |
| 69.22 | trojan | 395.2 | 859.4 | 18.63 | 0.0 | 10.0 | 12.27 | 14.22 | Au1rxx-base64 | 207.126.167.162 |
| 68.54 | trojan | 418.7 | 938.1 | 18.09 | 0.0 | 10.0 | 12.27 | 14.22 | Au1rxx-base64 | 207.126.167.241 |
| 68.48 | vless | 343.8 | 391.0 | 19.82 | 0.34 | 9.97 | 8.56 | 17.64 | Surfboard-tg-mixed | 96.62.214.87 |
| 68.47 | trojan | 405.4 | 442.2 | 18.39 | 0.0 | 10.0 | 12.27 | 17.64 | Surfboard-tg-mixed | 45.131.4.118 |
| 68.25 | shadowsocks | 297.6 | 354.7 | 20.89 | 1.7 | 9.94 | 12.68 | 14.22 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | 1.0 | 37 | 61 | prefer |
| Au1rxx-base64 | 0.825 | 0.838 | 37 | 117 | prefer |
| mheidari-all | 0.807 | 0.728 | 353 | 16289 | prefer |
| Surfboard-tg-mixed | 0.803 | 0.724 | 254 | 5004 | prefer |
| DeltaKronecker-all | 0.678 | 0.6 | 80 | 6788 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7560 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6985 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3679 | observe |
| barry-far-vless | 0.255 | None | 0 | 4456 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5325 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.225 | None | 0 | 1261 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 72 |
| speed | TimeoutError | - | 37 |
| cn-block | TimeoutError | - | 20 |
| 204 | ClientOSError | - | 18 |
| 204 | TimeoutError | - | 16 |
| geo | TimeoutError | - | 15 |
| geo | ClientOSError | - | 11 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 4 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
