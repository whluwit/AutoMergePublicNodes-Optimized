# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 21:07:51 |
| 运行耗时 | 322.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 90678 |
| 去重后节点 | 25159 |
| TCP 可达 | 3000 |
| 真实可用 | 569 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25159 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 41.9 |
| probe | 88.1 |
| real_test | 142.1 |
| generate | 42.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56352 |
| vmess | 12678 |
| shadowsocks | 10771 |
| trojan | 8913 |
| hysteria2 | 1595 |
| http | 138 |
| shadowsocksr | 128 |
| socks | 59 |
| hysteria | 17 |
| anytls | 16 |
| tuic | 11 |

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
| 85.9 | hysteria2 | 209.4 | 526.6 | 22.93 | 0.0 | 10.0 | 13.97 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 83.48 | vless | 208.1 | 484.4 | 22.96 | 0.0 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 83.32 | vless | 214.9 | 500.4 | 22.8 | 0.0 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 82.43 | shadowsocks | 203.9 | 485.1 | 23.06 | 0.0 | 10.0 | 13.87 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 81.85 | vless | 278.4 | 739.5 | 21.33 | 0.0 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 23.94.227.94 |
| 81.84 | vless | 278.9 | 743.1 | 21.32 | 0.0 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 38.209.125.45 |
| 80.92 | vless | 318.5 | 517.4 | 20.4 | 0.0 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 38.246.229.58 |
| 80.57 | vless | 204.3 | 515.2 | 23.05 | 0.0 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 38.244.20.160 |
| 78.83 | vless | 214.8 | 476.5 | 22.81 | 0.0 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 104.18.46.234 |
| 78.14 | vless | 195.4 | 484.4 | 23.25 | 0.0 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 31.58.50.200 |
| 78.1 | shadowsocks | 203.1 | 495.1 | 23.08 | 0.0 | 10.0 | 13.87 | 16.52 | Surfboard-tg-mixed | 108.181.118.10 |
| 77.6 | trojan | 206.6 | 545.3 | 23.0 | 0.0 | 10.0 | 12.1 | 20.0 | Au1rxx-base64 | 100.42.228.109 |
| 76.57 | vless | 256.0 | 296.3 | 21.85 | 3.89 | 9.93 | 10.52 | 16.52 | Surfboard-tg-mixed | 31.76.91.72 |
| 76.51 | shadowsocks | 287.5 | 643.8 | 21.12 | 0.0 | 10.0 | 13.87 | 16.52 | Surfboard-tg-mixed | 173.244.56.9 |
| 76.05 | vless | 369.3 | 378.7 | 19.23 | 0.8 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 172.64.229.170 |
| 75.5 | shadowsocks | 321.2 | 636.8 | 20.34 | 0.0 | 10.0 | 13.87 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 75.37 | vless | 334.2 | 336.9 | 20.04 | 2.37 | 9.93 | 10.52 | 20.0 | Au1rxx-base64 | 13.231.156.101 |
| 75.21 | vless | 338.6 | 338.9 | 19.94 | 2.29 | 9.92 | 10.52 | 20.0 | Au1rxx-base64 | 13.114.124.85 |
| 75.14 | vless | 211.0 | 468.1 | 22.89 | 0.0 | 10.0 | 10.52 | 20.0 | Au1rxx-base64 | 104.18.39.218 |
| 75.1 | vless | 335.6 | 343.9 | 20.01 | 2.11 | 9.93 | 10.52 | 20.0 | Au1rxx-base64 | 13.231.19.51 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.941 | 373 | 1703 | prefer |
| xiaoji235-airport-v2ray-all | 0.937 | 0.885 | 26 | 5750 | prefer |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| mheidari-all | 0.848 | 0.774 | 93 | 16413 | prefer |
| DeltaKronecker-all | 0.817 | 0.789 | 19 | 6417 | prefer |
| Surfboard-tg-mixed | 0.712 | 0.634 | 131 | 7444 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| Epodonios-all | 0.255 | None | 0 | 7899 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8993 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6179 | observe |
| barry-far-vless | 0.255 | None | 0 | 6394 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4218 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 26 |
| cn-block | TimeoutError | - | 16 |
| geo | ClientOSError | - | 13 |
| cn-block | ClientOSError | - | 9 |
| speed | ClientOSError | - | 9 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyError | - | 6 |
| geo | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ServerDisconnectedError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
