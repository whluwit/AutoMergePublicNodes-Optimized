# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 15:51:31 |
| 运行耗时 | 562.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83888 |
| 去重后节点 | 23080 |
| TCP 可达 | 3000 |
| 真实可用 | 400 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23080 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 37.9 |
| probe | 213.3 |
| real_test | 223.4 |
| generate | 80.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50395 |
| vmess | 13230 |
| shadowsocks | 10059 |
| trojan | 8148 |
| hysteria2 | 1258 |
| http | 588 |
| shadowsocksr | 128 |
| socks | 65 |
| hysteria | 8 |
| anytls | 7 |
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
| 79.13 | shadowsocks | 241.7 | 634.5 | 22.18 | 0.0 | 10.0 | 13.25 | 17.7 | Au1rxx-base64 | 37.19.198.160 |
| 77.98 | vless | 291.7 | 741.2 | 21.03 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.52 |
| 77.38 | vless | 317.4 | 850.8 | 20.43 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 137.184.218.169 |
| 76.92 | vless | 337.1 | 832.7 | 19.97 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.163 |
| 76.42 | vless | 358.8 | 804.6 | 19.47 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.225 |
| 76.29 | vless | 364.7 | 982.5 | 19.34 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 185.95.231.156 |
| 76.03 | vless | 353.8 | 857.8 | 19.59 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.35 |
| 75.89 | vless | 362.6 | 734.6 | 19.39 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.229 |
| 75.87 | shadowsocks | 236.6 | 631.2 | 22.3 | 0.0 | 10.0 | 13.25 | 14.32 | mheidari-all | 37.19.198.236 |
| 75.75 | vless | 387.8 | 1036.0 | 18.8 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.179 |
| 75.66 | shadowsocks | 307.1 | 720.7 | 20.67 | 0.0 | 10.0 | 13.25 | 17.7 | Au1rxx-base64 | 156.146.38.170 |
| 75.5 | vless | 302.4 | 662.4 | 20.78 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 198.251.78.29 |
| 75.39 | vless | 379.7 | 1009.4 | 18.99 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.133 |
| 75.32 | vless | 406.4 | 1096.6 | 18.37 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.235 |
| 74.76 | vless | 234.4 | 590.0 | 22.35 | 0.0 | 10.0 | 9.25 | 13.16 | Surfboard-tg-mixed | 88.216.57.128 |
| 74.56 | vless | 423.9 | 1084.7 | 17.97 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.168 |
| 74.45 | shadowsocks | 298.0 | 813.2 | 20.88 | 0.0 | 10.0 | 13.25 | 14.32 | mheidari-all | 37.19.198.243 |
| 74.43 | shadowsocks | 228.9 | 595.7 | 22.48 | 0.0 | 10.0 | 13.25 | 17.7 | Au1rxx-base64 | 198.98.53.130 |
| 74.39 | shadowsocks | 250.3 | 673.5 | 21.98 | 0.0 | 10.0 | 13.25 | 13.16 | Surfboard-tg-mixed | 37.19.198.244 |
| 74.37 | vless | 361.4 | 916.3 | 19.41 | 0.0 | 10.0 | 9.25 | 17.7 | Au1rxx-base64 | 169.40.42.212 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.926 | 0.865 | 260 | 1596 | prefer |
| ermaozi | 0.791 | 0.8 | 25 | 325 | prefer |
| Surfboard-tg-mixed | 0.733 | 0.655 | 148 | 7397 | prefer |
| mheidari-all | 0.726 | 0.651 | 63 | 15758 | prefer |
| DeltaKronecker-all | 0.551 | 0.469 | 32 | 6040 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5076 | observe |
| Epodonios-all | 0.255 | None | 0 | 7860 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8961 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5909 | observe |
| barry-far-vless | 0.255 | None | 0 | 6127 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1596 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 25 |
| geo | ClientOSError | - | 21 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 16 |
| geo | TimeoutError | - | 16 |
| speed | ClientOSError | - | 13 |
| cn-block | ClientOSError | - | 9 |
| speed | TimeoutError | - | 8 |
| cn-block | ProxyError | - | 4 |
| 204 | ProxyConnectionError | - | 3 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:38166: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
