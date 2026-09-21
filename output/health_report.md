# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 11:58:16 |
| 运行耗时 | 554.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84502 |
| 去重后节点 | 23399 |
| TCP 可达 | 3000 |
| 真实可用 | 464 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23399 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 38.1 |
| probe | 214.2 |
| real_test | 215.7 |
| generate | 78.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51048 |
| vmess | 13394 |
| shadowsocks | 9649 |
| trojan | 8413 |
| hysteria2 | 1120 |
| http | 638 |
| shadowsocksr | 146 |
| socks | 77 |
| hysteria | 8 |
| anytls | 5 |
| tuic | 4 |

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
| 79.88 | vless | 245.5 | 693.4 | 22.1 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 47.253.226.114 |
| 79.43 | shadowsocks | 371.3 | 1015.7 | 19.18 | 0.0 | 10.0 | 14.61 | 19.64 | Au1rxx-base64 | 142.4.216.225 |
| 79.0 | vless | 297.1 | 724.6 | 20.9 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.223 |
| 78.92 | vless | 300.7 | 739.1 | 20.82 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.133 |
| 78.9 | shadowsocks | 280.2 | 710.6 | 21.29 | 0.0 | 7.86 | 14.61 | 19.64 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 78.85 | vless | 303.6 | 808.3 | 20.75 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.173 |
| 78.69 | vless | 310.4 | 859.6 | 20.59 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 137.184.218.169 |
| 78.55 | vless | 316.7 | 856.3 | 20.45 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.35 |
| 78.35 | hysteria2 | 316.2 | 636.4 | 20.46 | 0.0 | 10.0 | 13.42 | 19.64 | Au1rxx-base64 | 66.94.121.46 |
| 78.2 | vless | 331.6 | 845.1 | 20.1 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.212 |
| 77.86 | shadowsocks | 258.5 | 711.5 | 21.79 | 0.0 | 10.0 | 14.61 | 15.46 | Surfboard-tg-mixed | 37.19.198.243 |
| 77.81 | vless | 348.4 | 900.7 | 19.71 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 209.200.246.148 |
| 77.73 | shadowsocks | 293.2 | 631.3 | 20.99 | 0.0 | 10.0 | 14.61 | 19.64 | Au1rxx-base64 | 23.150.248.20 |
| 77.51 | vless | 361.5 | 1000.8 | 19.41 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.15 |
| 77.39 | vless | 366.5 | 874.4 | 19.29 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.90 |
| 77.2 | vless | 291.1 | 777.4 | 21.04 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.75 |
| 77.1 | vless | 379.3 | 914.8 | 19.0 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.104 |
| 77.09 | vless | 367.0 | 944.1 | 19.28 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.182 |
| 77.03 | vless | 339.0 | 972.1 | 19.93 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 34.85.179.6 |
| 76.99 | vless | 383.8 | 1056.9 | 18.89 | 0.0 | 10.0 | 8.46 | 19.64 | Au1rxx-base64 | 169.40.42.235 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.944 | 0.881 | 42 | 16192 | prefer |
| Au1rxx-base64 | 0.919 | 0.856 | 277 | 1649 | prefer |
| Surfboard-tg-mixed | 0.685 | 0.606 | 213 | 7246 | observe |
| DeltaKronecker-all | 0.667 | 0.59 | 61 | 6181 | observe |
| ermaozi | 0.6 | 0.59 | 39 | 355 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 108 | observe |
| Epodonios-all | 0.255 | None | 0 | 7697 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8880 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5845 | observe |
| barry-far-vless | 0.255 | None | 0 | 6061 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1650 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| barry-far-Sub1 | 0.195 | None | 0 | 492 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 32 |
| geo | TimeoutError | - | 31 |
| 204 | TimeoutError | - | 27 |
| 204 | ProxyError | - | 19 |
| cn-block | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 13 |
| speed | TimeoutError | - | 13 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyConnectionError | - | 9 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
