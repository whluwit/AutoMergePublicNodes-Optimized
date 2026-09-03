# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-03 15:45:26 |
| 运行耗时 | 302.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 81969 |
| 去重后节点 | 22562 |
| TCP 可达 | 3000 |
| 真实可用 | 642 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22562 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.5 |
| tcp | 38.0 |
| probe | 77.8 |
| real_test | 140.7 |
| generate | 40.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51091 |
| vmess | 11461 |
| shadowsocks | 9824 |
| trojan | 7614 |
| hysteria2 | 1603 |
| http | 140 |
| shadowsocksr | 130 |
| socks | 84 |
| tuic | 11 |
| hysteria | 10 |
| anytls | 1 |

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
| 81.93 | hysteria2 | 307.3 | 775.7 | 20.66 | 0.0 | 10.0 | 12.75 | 19.52 | Au1rxx-base64 | 66.94.121.46 |
| 81.48 | shadowsocks | 239.8 | 615.3 | 22.23 | 0.0 | 10.0 | 13.73 | 19.52 | Au1rxx-base64 | 156.146.38.167 |
| 81.41 | shadowsocks | 242.5 | 622.4 | 22.16 | 0.0 | 10.0 | 13.73 | 19.52 | Au1rxx-base64 | 156.146.38.170 |
| 81.03 | http | 267.3 | 532.8 | 21.59 | 0.0 | 10.0 | 14.38 | 19.24 | zhangkai | 138.199.35.198 |
| 80.78 | http | 245.8 | 540.3 | 22.09 | 0.0 | 10.0 | 14.38 | 19.24 | zhangkai | 138.199.35.216 |
| 80.45 | shadowsocks | 262.5 | 624.7 | 21.7 | 0.0 | 10.0 | 13.73 | 19.52 | Au1rxx-base64 | 23.150.248.20 |
| 80.38 | vless | 261.7 | 550.2 | 21.72 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 172.239.67.231 |
| 79.82 | vless | 276.6 | 588.5 | 21.37 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 172.236.252.35 |
| 79.79 | vless | 267.3 | 556.1 | 21.59 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 172.239.67.156 |
| 79.22 | vless | 272.4 | 571.4 | 21.47 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 172.235.38.85 |
| 79.12 | vless | 297.1 | 584.2 | 20.9 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 172.233.139.46 |
| 79.01 | vless | 289.2 | 552.5 | 21.08 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 172.235.43.210 |
| 78.8 | vless | 306.9 | 226.4 | 20.67 | 6.51 | 8.76 | 11.86 | 19.52 | Au1rxx-base64 | hk2-r.link-t7.com |
| 78.49 | vless | 272.6 | 591.8 | 21.47 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 172.233.156.123 |
| 77.83 | vless | 291.5 | 555.2 | 21.03 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 172.233.156.118 |
| 77.16 | hysteria2 | 307.3 | 678.2 | 20.66 | 0.0 | 10.0 | 12.75 | 19.52 | Au1rxx-base64 | 159.223.157.129 |
| 76.42 | shadowsocks | 267.6 | 597.4 | 21.58 | 0.0 | 10.0 | 13.73 | 16.46 | DeltaKronecker-all | 84.32.131.61 |
| 76.23 | vless | 369.8 | 768.2 | 19.22 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 23.237.192.18 |
| 76.19 | vless | 338.8 | 712.7 | 19.93 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 216.152.147.28 |
| 75.4 | vless | 425.1 | 1028.3 | 17.94 | 0.0 | 10.0 | 11.86 | 19.52 | Au1rxx-base64 | 45.138.100.226 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.942 | 363 | 1770 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| mheidari-all | 0.932 | 0.858 | 106 | 15770 | prefer |
| DeltaKronecker-all | 0.823 | 0.75 | 72 | 6335 | prefer |
| Surfboard-tg-mixed | 0.802 | 0.724 | 174 | 7139 | prefer |
| tg-oneclickvpnkeys | 0.445 | 1.0 | 5 | 145 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4671 | observe |
| Epodonios-all | 0.255 | None | 0 | 7586 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7805 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6006 | observe |
| barry-far-vless | 0.255 | None | 0 | 6219 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4081 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 24 |
| 204 | TimeoutError | - | 21 |
| geo | ClientOSError | - | 19 |
| 204 | ProxyError | - | 11 |
| speed | ClientOSError | - | 8 |
| geo | TimeoutError | - | 7 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
