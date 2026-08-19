# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-19 18:32:57 |
| 运行耗时 | 366.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 93094 |
| 去重后节点 | 24443 |
| TCP 可达 | 3000 |
| 真实可用 | 1229 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24443 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 0.7 |
| tcp | 37.5 |
| probe | 71.4 |
| real_test | 220.4 |
| generate | 28.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50836 |
| trojan | 19355 |
| shadowsocks | 11013 |
| vmess | 9590 |
| hysteria2 | 1734 |
| shadowsocksr | 202 |
| http | 165 |
| socks | 136 |
| anytls | 36 |
| hysteria | 15 |
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
| 85.26 | vless | 185.0 | 454.3 | 23.5 | 0.0 | 10.0 | 11.76 | 20.0 | Au1rxx-base64 | 70.39.198.183 |
| 83.7 | vless | 248.7 | 524.1 | 22.02 | 0.0 | 10.0 | 11.76 | 20.0 | Au1rxx-base64 | 150.241.102.202 |
| 83.53 | hysteria2 | 220.5 | 485.4 | 22.67 | 0.0 | 10.0 | 13.64 | 18.22 | Surfboard-tg-mixed | 150.241.102.127 |
| 83.29 | trojan | 276.0 | 744.6 | 21.39 | 0.0 | 10.0 | 14.9 | 20.0 | mheidari-all | 14.1.28.76 |
| 82.15 | trojan | 195.8 | 480.6 | 23.25 | 0.0 | 10.0 | 14.9 | 20.0 | Au1rxx-base64 | 128.14.181.220 |
| 82.12 | shadowsocks | 217.6 | 504.8 | 22.74 | 0.0 | 10.0 | 13.38 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 82.08 | trojan | 256.3 | 555.3 | 21.85 | 0.0 | 10.0 | 14.9 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 81.92 | trojan | 263.2 | 559.0 | 21.69 | 0.0 | 10.0 | 14.9 | 20.0 | Au1rxx-base64 | 34.222.243.142 |
| 81.89 | shadowsocks | 205.2 | 488.4 | 23.03 | 0.0 | 10.0 | 13.38 | 20.0 | mheidari-all | 108.181.118.10 |
| 81.81 | trojan | 270.4 | 572.5 | 21.52 | 0.0 | 10.0 | 14.9 | 20.0 | mheidari-all | 35.88.210.26 |
| 81.78 | trojan | 263.1 | 551.8 | 21.69 | 0.0 | 10.0 | 14.9 | 20.0 | Au1rxx-base64 | 34.210.213.17 |
| 81.77 | trojan | 269.0 | 592.7 | 21.55 | 0.0 | 10.0 | 14.9 | 20.0 | mheidari-all | 54.188.176.255 |
| 81.76 | trojan | 270.4 | 568.4 | 21.52 | 0.0 | 10.0 | 14.9 | 20.0 | Au1rxx-base64 | 34.220.224.252 |
| 81.74 | vless | 250.5 | 542.6 | 21.98 | 0.0 | 10.0 | 11.76 | 20.0 | Au1rxx-base64 | 150.241.82.19 |
| 81.62 | shadowsocks | 239.2 | 523.4 | 22.24 | 0.0 | 10.0 | 13.38 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 81.62 | trojan | 242.1 | 499.2 | 22.17 | 0.0 | 10.0 | 14.9 | 20.0 | mheidari-all | 44.251.158.80 |
| 81.57 | vless | 257.6 | 615.1 | 21.81 | 0.0 | 10.0 | 11.76 | 20.0 | Au1rxx-base64 | 38.244.21.216 |
| 81.56 | trojan | 269.1 | 574.8 | 21.55 | 0.0 | 10.0 | 14.9 | 20.0 | mheidari-all | 44.246.163.102 |
| 80.76 | trojan | 323.7 | 732.2 | 20.28 | 0.0 | 10.0 | 14.9 | 20.0 | Au1rxx-base64 | 100.22.163.167 |
| 80.74 | hysteria2 | 225.1 | 229.5 | 22.57 | 6.39 | 9.94 | 13.64 | 20.0 | Au1rxx-base64 | 45.32.252.144 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.983 | 654 | 1890 | prefer |
| zhangkai | 0.988 | 0.991 | 113 | 144 | prefer |
| Surfboard-tg-mixed | 0.978 | 0.912 | 57 | 6336 | prefer |
| mheidari-all | 0.904 | 0.825 | 508 | 20423 | prefer |
| nscl5-all | 0.335 | 1.0 | 1 | 3330 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| DeltaKronecker-all | 0.259 | 0.333 | 3 | 6390 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5067 | observe |
| Epodonios-all | 0.255 | None | 0 | 7060 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7318 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5003 | observe |
| barry-far-vless | 0.255 | None | 0 | 5325 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4086 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 43 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 13 |
| speed | TimeoutError | - | 12 |
| geo | TimeoutError | - | 8 |
| speed | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:43760: bind: address already in use | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
