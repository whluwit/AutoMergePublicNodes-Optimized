# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 17:52:56 |
| 运行耗时 | 542.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84761 |
| 去重后节点 | 23478 |
| TCP 可达 | 3000 |
| 真实可用 | 442 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23478 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.4 |
| tcp | 38.7 |
| probe | 194.3 |
| real_test | 217.3 |
| generate | 83.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51244 |
| vmess | 13608 |
| shadowsocks | 9673 |
| trojan | 8354 |
| hysteria2 | 1026 |
| http | 632 |
| shadowsocksr | 131 |
| socks | 74 |
| hysteria | 11 |
| tuic | 4 |
| anytls | 4 |

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
| 82.25 | hysteria2 | 269.1 | 696.1 | 21.55 | 0.0 | 10.0 | 13.42 | 18.38 | Au1rxx-base64 | 159.223.157.129 |
| 80.0 | shadowsocks | 272.7 | 715.5 | 21.47 | 0.0 | 10.0 | 13.65 | 18.88 | mheidari-all | 37.19.198.160 |
| 79.93 | shadowsocks | 275.5 | 725.7 | 21.4 | 0.0 | 10.0 | 13.65 | 18.88 | mheidari-all | 37.19.198.236 |
| 79.9 | shadowsocks | 276.8 | 726.7 | 21.37 | 0.0 | 10.0 | 13.65 | 18.88 | mheidari-all | 37.19.198.244 |
| 79.13 | vless | 305.9 | 775.5 | 20.7 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.104 |
| 78.55 | vless | 330.7 | 821.7 | 20.12 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.74 |
| 78.41 | vless | 322.3 | 784.5 | 20.32 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 195.211.98.43 |
| 78.39 | shadowsocks | 320.5 | 824.6 | 20.36 | 0.0 | 10.0 | 13.65 | 18.38 | Au1rxx-base64 | 142.4.216.225 |
| 77.82 | vless | 362.3 | 917.1 | 19.39 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.179 |
| 77.75 | vless | 365.6 | 927.0 | 19.32 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.212 |
| 77.69 | vless | 367.8 | 984.6 | 19.26 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 185.95.231.156 |
| 77.29 | vless | 339.6 | 889.0 | 19.92 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.75 |
| 77.24 | vless | 359.6 | 962.4 | 19.45 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.16 |
| 76.91 | vless | 367.6 | 924.4 | 19.27 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.173 |
| 76.87 | vless | 403.3 | 1083.1 | 18.44 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.35 |
| 76.79 | vless | 406.9 | 1105.9 | 18.36 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.163 |
| 76.56 | vless | 416.8 | 1180.9 | 18.13 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 34.85.179.6 |
| 75.9 | vless | 445.2 | 1025.0 | 17.47 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.232 |
| 75.62 | shadowsocks | 292.4 | 630.1 | 21.01 | 0.0 | 10.0 | 13.65 | 18.38 | Au1rxx-base64 | 23.150.248.20 |
| 75.4 | vless | 379.6 | 940.8 | 18.99 | 0.0 | 10.0 | 10.05 | 18.38 | Au1rxx-base64 | 169.40.42.229 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.957 | 0.892 | 268 | 1701 | prefer |
| mheidari-all | 0.769 | 0.694 | 72 | 16282 | prefer |
| Surfboard-tg-mixed | 0.721 | 0.642 | 179 | 7246 | prefer |
| DeltaKronecker-all | 0.548 | 0.467 | 60 | 6181 | observe |
| ermaozi | 0.399 | 0.375 | 24 | 350 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| Epodonios-all | 0.255 | None | 0 | 7695 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8945 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5845 | observe |
| barry-far-vless | 0.255 | None | 0 | 6062 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1702 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 40 |
| geo | ClientOSError | - | 35 |
| 204 | ProxyError | - | 22 |
| speed | TimeoutError | - | 19 |
| speed | ClientOSError | - | 18 |
| cn-block | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 8 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
