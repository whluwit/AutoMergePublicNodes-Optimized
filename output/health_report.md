# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 02:59:09 |
| 运行耗时 | 902.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99173 |
| 去重后节点 | 27840 |
| TCP 可达 | 3000 |
| 真实可用 | 551 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27840 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 49.1 |
| probe | 285.9 |
| real_test | 426.3 |
| generate | 135.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58502 |
| vmess | 16716 |
| shadowsocks | 11818 |
| trojan | 9833 |
| hysteria2 | 1277 |
| http | 755 |
| shadowsocksr | 160 |
| socks | 65 |
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
| 80.55 | vless | 261.1 | 677.4 | 21.73 | 0.0 | 10.0 | 10.9 | 17.92 | Au1rxx-base64 | 147.45.60.160 |
| 80.17 | shadowsocks | 226.1 | 598.3 | 22.54 | 0.0 | 10.0 | 13.71 | 17.92 | Au1rxx-base64 | 156.146.38.169 |
| 80.15 | shadowsocks | 227.1 | 595.4 | 22.52 | 0.0 | 10.0 | 13.71 | 17.92 | Au1rxx-base64 | 156.146.38.168 |
| 80.03 | shadowsocks | 232.3 | 617.2 | 22.4 | 0.0 | 10.0 | 13.71 | 17.92 | Au1rxx-base64 | 156.146.38.170 |
| 80.0 | shadowsocks | 233.6 | 615.3 | 22.37 | 0.0 | 10.0 | 13.71 | 17.92 | Au1rxx-base64 | 156.146.38.167 |
| 79.99 | hysteria2 | 289.9 | 721.2 | 21.07 | 0.0 | 10.0 | 12.5 | 17.92 | Au1rxx-base64 | 129.213.91.185 |
| 78.3 | hysteria2 | 287.5 | 640.3 | 21.12 | 0.0 | 10.0 | 12.5 | 17.92 | Au1rxx-base64 | 66.94.121.46 |
| 77.86 | vless | 251.6 | 549.2 | 21.95 | 0.0 | 10.0 | 10.9 | 17.92 | Au1rxx-base64 | 45.63.53.81 |
| 77.49 | vless | 277.3 | 577.8 | 21.36 | 0.0 | 10.0 | 10.9 | 17.92 | Au1rxx-base64 | 195.123.240.65 |
| 77.4 | shadowsocks | 250.2 | 549.8 | 21.98 | 0.0 | 10.0 | 13.71 | 17.92 | Au1rxx-base64 | 173.244.56.6 |
| 77.27 | vless | 264.1 | 567.7 | 21.67 | 0.0 | 10.0 | 10.9 | 17.92 | Au1rxx-base64 | 176.122.183.26 |
| 75.98 | vless | 242.6 | 620.5 | 22.16 | 0.0 | 10.0 | 10.9 | 17.92 | Au1rxx-base64 | 181.214.152.137 |
| 75.89 | vless | 331.2 | 760.1 | 20.11 | 0.0 | 10.0 | 10.9 | 17.92 | Au1rxx-base64 | 5.34.178.120 |
| 75.48 | vless | 277.0 | 575.1 | 21.37 | 0.0 | 9.66 | 10.9 | 17.92 | Au1rxx-base64 | 154.40.55.185 |
| 75.48 | vless | 289.5 | 522.9 | 21.08 | 0.0 | 10.0 | 10.9 | 17.92 | Au1rxx-base64 | 45.32.69.110 |
| 75.35 | vless | 257.9 | 553.4 | 21.81 | 0.0 | 10.0 | 10.9 | 17.92 | Au1rxx-base64 | 67.209.184.133 |
| 75.3 | shadowsocks | 255.7 | 563.9 | 21.86 | 0.0 | 10.0 | 13.71 | 17.92 | Au1rxx-base64 | 173.244.56.9 |
| 75.17 | shadowsocks | 327.3 | 769.8 | 20.2 | 0.0 | 10.0 | 13.71 | 17.92 | Au1rxx-base64 | 37.19.198.160 |
| 75.09 | vless | 319.7 | 696.4 | 20.38 | 0.0 | 10.0 | 10.9 | 17.92 | Au1rxx-base64 | 212.104.141.233 |
| 75.07 | shadowsocks | 328.9 | 772.9 | 20.17 | 0.0 | 10.0 | 13.71 | 17.92 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | 0.887 | 444 | 1798 | prefer |
| Surfboard-tg-mixed | 0.854 | 0.793 | 29 | 7181 | prefer |
| ermaozi | 0.577 | 0.55 | 100 | 710 | observe |
| DeltaKronecker-all | 0.45 | 0.5 | 12 | 4999 | observe |
| mheidari-all | 0.393 | 0.312 | 231 | 23946 | observe |
| ermaozi-get_subscribe | 0.279 | 1.0 | 1 | 599 | observe |
| Epodonios-all | 0.255 | None | 0 | 7667 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9951 | observe |
| barry-far-vless | 0.255 | None | 0 | 5884 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1798 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 103 |
| 204 | ProxyError | - | 58 |
| geo | ClientOSError | - | 31 |
| speed | ClientOSError | - | 28 |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 10 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
