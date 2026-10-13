# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-13 00:25:20 |
| 运行耗时 | 1292.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 100509 |
| 去重后节点 | 27884 |
| TCP 可达 | 3000 |
| 真实可用 | 501 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27884 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.5 |
| tcp | 48.1 |
| probe | 469.5 |
| real_test | 694.0 |
| generate | 73.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59005 |
| vmess | 15921 |
| shadowsocks | 12124 |
| trojan | 11065 |
| hysteria2 | 1448 |
| http | 655 |
| shadowsocksr | 176 |
| socks | 66 |
| anytls | 26 |
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
| 83.89 | hysteria2 | 255.1 | 583.2 | 21.87 | 0.0 | 10.0 | 13.42 | 19.6 | Au1rxx-base64 | 66.94.121.46 |
| 83.78 | vless | 205.8 | 519.8 | 23.01 | 0.0 | 10.0 | 11.17 | 19.6 | Au1rxx-base64 | 154.29.145.196 |
| 83.3 | vless | 226.6 | 518.0 | 22.53 | 0.0 | 10.0 | 11.17 | 19.6 | Au1rxx-base64 | 195.123.240.65 |
| 83.1 | vless | 235.5 | 564.0 | 22.33 | 0.0 | 10.0 | 11.17 | 19.6 | Au1rxx-base64 | 154.12.38.202 |
| 82.71 | vless | 252.3 | 637.1 | 21.94 | 0.0 | 10.0 | 11.17 | 19.6 | Au1rxx-base64 | 154.12.38.159 |
| 81.7 | vless | 252.4 | 547.8 | 21.94 | 0.0 | 10.0 | 11.17 | 19.6 | Au1rxx-base64 | 23.95.222.127 |
| 80.22 | vless | 286.9 | 679.1 | 21.14 | 0.0 | 10.0 | 11.17 | 19.6 | Au1rxx-base64 | 147.45.60.160 |
| 79.42 | shadowsocks | 258.4 | 623.7 | 21.8 | 0.0 | 10.0 | 12.02 | 19.6 | Au1rxx-base64 | 156.146.38.169 |
| 79.34 | vless | 236.5 | 503.8 | 22.3 | 0.0 | 10.0 | 11.17 | 16.94 | mheidari-all | 47.251.108.158 |
| 79.15 | hysteria2 | 326.0 | 747.5 | 20.23 | 0.0 | 10.0 | 13.42 | 19.6 | Au1rxx-base64 | 129.213.91.185 |
| 78.48 | shadowsocks | 264.0 | 642.5 | 21.67 | 0.0 | 10.0 | 12.02 | 19.6 | Au1rxx-base64 | 156.146.38.170 |
| 78.38 | shadowsocks | 235.8 | 536.4 | 22.32 | 0.0 | 10.0 | 12.02 | 19.6 | Au1rxx-base64 | 173.244.56.9 |
| 78.06 | shadowsocks | 235.8 | 542.8 | 22.32 | 0.0 | 10.0 | 12.02 | 19.6 | Au1rxx-base64 | 173.244.56.6 |
| 78.02 | vless | 293.9 | 569.7 | 20.98 | 0.0 | 10.0 | 11.17 | 19.6 | Au1rxx-base64 | 154.29.149.140 |
| 77.27 | hysteria2 | 255.9 | 313.4 | 21.85 | 3.25 | 9.54 | 13.42 | 19.6 | Au1rxx-base64 | open.2ml.cc.cd |
| 76.13 | shadowsocks | 266.1 | 645.8 | 21.62 | 0.0 | 10.0 | 12.02 | 19.6 | Au1rxx-base64 | 156.146.38.167 |
| 76.06 | vless | 350.3 | 645.8 | 19.67 | 0.0 | 10.0 | 11.17 | 19.6 | Au1rxx-base64 | 95.111.212.241 |
| 75.95 | shadowsocks | 279.9 | 284.0 | 21.3 | 4.35 | 9.91 | 12.02 | 19.6 | Au1rxx-base64 | 149.22.87.204 |
| 75.92 | vless | 451.5 | 1127.8 | 17.33 | 0.0 | 10.0 | 11.17 | 19.6 | Au1rxx-base64 | 51.81.203.63 |
| 75.7 | vless | 335.6 | 333.7 | 20.01 | 2.49 | 9.91 | 11.17 | 19.6 | Au1rxx-base64 | 142.91.108.25 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.999 | 0.928 | 347 | 1844 | prefer |
| ermaozi | 0.527 | 0.5 | 26 | 675 | observe |
| Surfboard-tg-mixed | 0.421 | 0.667 | 6 | 7208 | observe |
| mheidari-all | 0.363 | 0.282 | 546 | 23897 | observe |
| DeltaKronecker-all | 0.344 | 0.333 | 12 | 5701 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5028 | observe |
| Epodonios-all | 0.255 | None | 0 | 7736 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10128 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5678 | observe |
| barry-far-vless | 0.255 | None | 0 | 6023 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 200 |
| speed | TimeoutError | - | 109 |
| geo | ClientOSError | - | 45 |
| speed | ClientOSError | - | 37 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 15 |
| 204 | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
