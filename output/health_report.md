# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-04 02:41:37 |
| 运行耗时 | 312.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82381 |
| 去重后节点 | 22756 |
| TCP 可达 | 3000 |
| 真实可用 | 719 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22756 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.6 |
| tcp | 37.8 |
| probe | 74.1 |
| real_test | 161.0 |
| generate | 33.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51244 |
| vmess | 11559 |
| shadowsocks | 9798 |
| trojan | 7879 |
| hysteria2 | 1539 |
| http | 140 |
| shadowsocksr | 131 |
| socks | 65 |
| tuic | 15 |
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
| 86.0 | hysteria2 | 224.5 | 534.2 | 22.58 | 0.0 | 10.0 | 14.42 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 82.49 | trojan | 250.9 | 599.7 | 21.97 | 0.0 | 10.0 | 13.52 | 20.0 | Au1rxx-base64 | 64.94.95.117 |
| 82.35 | trojan | 257.1 | 587.5 | 21.83 | 0.0 | 10.0 | 13.52 | 20.0 | Au1rxx-base64 | 64.94.95.115 |
| 82.01 | shadowsocks | 232.7 | 589.6 | 22.39 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.6 | vless | 269.8 | 558.0 | 21.53 | 0.0 | 10.0 | 13.31 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 81.42 | vless | 263.9 | 554.8 | 21.67 | 0.0 | 10.0 | 13.31 | 20.0 | Au1rxx-base64 | 172.233.156.123 |
| 81.31 | vless | 276.1 | 590.2 | 21.39 | 0.0 | 10.0 | 13.31 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 81.3 | vless | 275.1 | 574.6 | 21.41 | 0.0 | 10.0 | 13.31 | 20.0 | Au1rxx-base64 | 172.236.252.35 |
| 80.9 | vless | 274.4 | 584.7 | 21.42 | 0.0 | 10.0 | 13.31 | 20.0 | Au1rxx-base64 | 172.233.156.118 |
| 80.33 | vless | 293.1 | 581.7 | 20.99 | 0.0 | 10.0 | 13.31 | 20.0 | Au1rxx-base64 | 172.235.43.210 |
| 80.28 | shadowsocks | 256.5 | 616.3 | 21.84 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 84.32.131.61 |
| 80.25 | shadowsocks | 243.0 | 623.7 | 22.15 | 0.0 | 10.0 | 13.62 | 18.48 | Surfboard-tg-mixed | 156.146.38.168 |
| 79.84 | vless | 276.0 | 595.3 | 21.39 | 0.0 | 10.0 | 13.31 | 18.48 | Surfboard-tg-mixed | 172.233.156.42 |
| 79.6 | vless | 270.8 | 582.9 | 21.51 | 0.0 | 10.0 | 13.31 | 20.0 | Au1rxx-base64 | 172.239.67.231 |
| 79.56 | shadowsocks | 273.0 | 715.2 | 21.46 | 0.0 | 10.0 | 13.62 | 18.48 | Surfboard-tg-mixed | 156.146.38.167 |
| 79.5 | vless | 294.2 | 641.9 | 20.97 | 0.0 | 10.0 | 13.31 | 18.48 | Surfboard-tg-mixed | 38.127.121.44 |
| 79.15 | shadowsocks | 268.9 | 637.4 | 21.55 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 78.71 | trojan | 336.5 | 869.3 | 19.99 | 0.0 | 10.0 | 13.52 | 18.2 | mheidari-all | 64.94.95.118 |
| 78.38 | vless | 277.5 | 564.0 | 21.35 | 0.0 | 10.0 | 13.31 | 20.0 | Au1rxx-base64 | 172.239.67.156 |
| 78.38 | vless | 326.3 | 624.9 | 20.22 | 0.0 | 10.0 | 13.31 | 20.0 | Au1rxx-base64 | 162.159.0.53 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.955 | 382 | 1739 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.842 | 0.764 | 229 | 7237 | prefer |
| mheidari-all | 0.788 | 0.717 | 46 | 15793 | prefer |
| DeltaKronecker-all | 0.532 | 0.452 | 261 | 6335 | observe |
| tg-oneclickvpnkeys | 0.403 | 1.0 | 4 | 71 | observe |
| Epodonios-all | 0.255 | None | 0 | 7701 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7945 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6022 | observe |
| barry-far-vless | 0.255 | None | 0 | 6237 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4133 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1739 | observe |
| 10ium-ScrapeCategorize-Vless | 0.24 | 0.25 | 4 | 4671 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 98 |
| geo | ClientOSError | - | 43 |
| speed | ClientOSError | - | 28 |
| speed | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 9 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
