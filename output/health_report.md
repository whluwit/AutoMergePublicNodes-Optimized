# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 16:38:40 |
| 运行耗时 | 527.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96605 |
| 去重后节点 | 26896 |
| TCP 可达 | 3000 |
| 真实可用 | 309 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26896 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 44.9 |
| probe | 211.0 |
| real_test | 187.3 |
| generate | 77.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57453 |
| vmess | 17061 |
| shadowsocks | 11917 |
| trojan | 8548 |
| hysteria2 | 1255 |
| shadowsocksr | 161 |
| http | 110 |
| socks | 56 |
| anytls | 21 |
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
| 79.77 | hysteria2 | 267.8 | 681.1 | 21.58 | 0.0 | 9.65 | 13.12 | 16.92 | Au1rxx-base64 | 129.213.91.185 |
| 79.0 | shadowsocks | 232.8 | 589.0 | 22.39 | 0.0 | 10.0 | 13.29 | 17.32 | mheidari-all | 156.146.38.168 |
| 78.44 | shadowsocks | 239.6 | 607.1 | 22.23 | 0.0 | 10.0 | 13.29 | 16.92 | Au1rxx-base64 | 156.146.38.167 |
| 77.24 | shadowsocks | 276.2 | 707.5 | 21.38 | 0.0 | 9.65 | 13.29 | 16.92 | Au1rxx-base64 | 156.146.38.169 |
| 77.18 | shadowsocks | 278.1 | 722.2 | 21.34 | 0.0 | 9.63 | 13.29 | 16.92 | Au1rxx-base64 | 156.146.38.170 |
| 76.52 | vless | 280.5 | 631.3 | 21.29 | 0.0 | 10.0 | 10.14 | 16.92 | Au1rxx-base64 | 172.245.253.16 |
| 75.26 | shadowsocks | 321.3 | 793.0 | 20.34 | 0.0 | 9.63 | 13.29 | 16.92 | Au1rxx-base64 | 37.19.198.160 |
| 74.98 | vless | 296.7 | 742.8 | 20.91 | 0.0 | 7.01 | 10.14 | 16.92 | Au1rxx-base64 | us-4bf85a22b1.shamanapp.online |
| 74.32 | shadowsocks | 314.9 | 737.4 | 20.49 | 0.0 | 10.0 | 13.29 | 17.32 | mheidari-all | 37.19.198.236 |
| 74.16 | vless | 296.8 | 667.3 | 20.91 | 0.0 | 10.0 | 10.14 | 16.92 | Au1rxx-base64 | 195.123.235.183 |
| 74.01 | shadowsocks | 364.8 | 901.9 | 19.33 | 0.0 | 10.0 | 13.29 | 16.92 | Au1rxx-base64 | 37.19.198.244 |
| 73.99 | vless | 289.5 | 568.0 | 21.08 | 0.0 | 10.0 | 10.14 | 16.92 | Au1rxx-base64 | 45.63.53.81 |
| 73.53 | hysteria2 | 301.1 | 694.7 | 20.81 | 0.0 | 8.68 | 13.12 | 16.92 | Au1rxx-base64 | clash2.deep-links.com |
| 73.33 | vless | 325.2 | 697.5 | 20.25 | 0.0 | 10.0 | 10.14 | 17.32 | mheidari-all | 47.251.108.158 |
| 72.93 | vless | 329.9 | 744.8 | 20.14 | 0.0 | 10.0 | 10.14 | 16.92 | Au1rxx-base64 | 66.70.179.198 |
| 72.86 | shadowsocks | 312.5 | 721.8 | 20.54 | 0.0 | 9.62 | 13.29 | 16.92 | Au1rxx-base64 | 185.230.230.18 |
| 72.4 | shadowsocks | 318.4 | 718.3 | 20.41 | 0.0 | 9.62 | 13.29 | 16.92 | Au1rxx-base64 | 193.151.163.18 |
| 72.2 | shadowsocks | 308.4 | 749.4 | 20.64 | 0.0 | 9.65 | 13.29 | 16.92 | Au1rxx-base64 | 37.19.198.243 |
| 71.28 | vless | 411.5 | 991.6 | 18.25 | 0.0 | 9.69 | 10.14 | 16.92 | Au1rxx-base64 | 169.40.42.231 |
| 71.17 | vless | 338.1 | 647.9 | 19.95 | 0.0 | 10.0 | 10.14 | 16.92 | Au1rxx-base64 | 23.95.222.127 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.858 | 0.788 | 52 | 7070 | prefer |
| Au1rxx-base64 | 0.853 | 0.792 | 236 | 1568 | prefer |
| mheidari-all | 0.833 | 0.759 | 87 | 24102 | prefer |
| zhangkai | 0.484 | 0.481 | 27 | 31 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| Epodonios-all | 0.255 | None | 0 | 7559 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10165 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5554 | observe |
| barry-far-vless | 0.255 | None | 0 | 5768 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| DeltaKronecker-all | 0.24 | 0.25 | 4 | 4067 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 31 |
| cn-block | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 18 |
| speed | TimeoutError | - | 9 |
| speed | ClientOSError | - | 8 |
| geo | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:33700: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
