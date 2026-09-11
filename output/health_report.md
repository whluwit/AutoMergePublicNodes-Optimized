# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 10:41:15 |
| 运行耗时 | 677.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84419 |
| 去重后节点 | 23232 |
| TCP 可达 | 3000 |
| 真实可用 | 427 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23232 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.6 |
| tcp | 38.6 |
| probe | 266.3 |
| real_test | 287.2 |
| generate | 77.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51479 |
| vmess | 12335 |
| shadowsocks | 10039 |
| trojan | 8108 |
| hysteria2 | 1598 |
| http | 650 |
| shadowsocksr | 132 |
| socks | 56 |
| tuic | 12 |
| hysteria | 8 |
| anytls | 2 |

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
| 79.58 | shadowsocks | 280.9 | 671.5 | 21.28 | 0.0 | 10.0 | 14.32 | 17.98 | Au1rxx-base64 | 173.244.56.6 |
| 79.44 | shadowsocks | 266.0 | 594.3 | 21.62 | 0.0 | 10.0 | 14.32 | 17.5 | mheidari-all | 149.22.95.183 |
| 78.9 | trojan | 178.9 | 485.4 | 23.64 | 0.0 | 10.0 | 9.78 | 17.98 | Au1rxx-base64 | 100.42.228.109 |
| 78.42 | shadowsocks | 246.3 | 628.1 | 22.08 | 0.0 | 10.0 | 14.32 | 16.52 | Surfboard-tg-mixed | 108.181.118.10 |
| 78.18 | vless | 199.1 | 504.7 | 23.17 | 0.0 | 10.0 | 7.03 | 17.98 | Au1rxx-base64 | 172.235.38.85 |
| 77.84 | vless | 213.8 | 523.4 | 22.83 | 0.0 | 10.0 | 7.03 | 17.98 | Au1rxx-base64 | 172.236.233.59 |
| 77.32 | trojan | 225.3 | 569.4 | 22.56 | 0.0 | 10.0 | 9.78 | 17.98 | Au1rxx-base64 | 107.150.105.84 |
| 76.8 | shadowsocks | 291.9 | 662.1 | 21.02 | 0.0 | 10.0 | 14.32 | 17.98 | Au1rxx-base64 | 156.146.38.168 |
| 76.28 | hysteria2 | 338.8 | 712.5 | 19.94 | 0.0 | 10.0 | 14.12 | 17.98 | Au1rxx-base64 | 159.223.157.129 |
| 76.18 | shadowsocks | 213.3 | 516.9 | 22.84 | 0.0 | 10.0 | 14.32 | 16.52 | Surfboard-tg-mixed | 5.78.51.123 |
| 75.88 | shadowsocks | 288.7 | 651.7 | 21.09 | 0.0 | 10.0 | 14.32 | 17.5 | mheidari-all | 156.146.38.169 |
| 75.61 | vless | 213.0 | 522.5 | 22.85 | 0.0 | 10.0 | 7.03 | 17.98 | Au1rxx-base64 | 31.58.50.200 |
| 75.35 | vless | 321.4 | 852.6 | 20.34 | 0.0 | 10.0 | 7.03 | 17.98 | Au1rxx-base64 | 15.204.97.216 |
| 75.08 | shadowsocks | 234.1 | 556.2 | 22.36 | 0.0 | 10.0 | 14.32 | 17.98 | Au1rxx-base64 | 173.244.56.9 |
| 74.98 | shadowsocks | 287.5 | 646.3 | 21.12 | 0.0 | 10.0 | 14.32 | 16.52 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.73 | vless | 212.2 | 514.9 | 22.87 | 0.0 | 10.0 | 7.03 | 17.98 | Au1rxx-base64 | 172.233.139.46 |
| 74.65 | vless | 222.0 | 491.7 | 22.64 | 0.0 | 10.0 | 7.03 | 17.98 | Au1rxx-base64 | 216.36.124.176 |
| 74.24 | shadowsocks | 247.1 | 592.4 | 22.06 | 0.0 | 10.0 | 14.32 | 17.98 | Au1rxx-base64 | 129.146.122.135 |
| 74.07 | shadowsocks | 292.7 | 664.1 | 21.0 | 0.0 | 10.0 | 14.32 | 17.98 | Au1rxx-base64 | 156.146.38.170 |
| 73.53 | http | 196.6 | 492.8 | 23.23 | 0.0 | 10.0 | 9.1 | 14.2 | ermaozi | 138.199.35.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.947 | 0.879 | 280 | 1772 | prefer |
| Surfboard-tg-mixed | 0.778 | 0.701 | 127 | 7422 | prefer |
| ermaozi | 0.728 | 0.721 | 43 | 431 | prefer |
| mheidari-all | 0.641 | 0.562 | 64 | 15701 | observe |
| DeltaKronecker-all | 0.549 | 0.468 | 47 | 6070 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ermaozi-get_subscribe | 0.273 | 1.0 | 1 | 461 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 199 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7889 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8749 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5995 | observe |
| barry-far-vless | 0.255 | None | 0 | 6213 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 31 |
| 204 | TimeoutError | - | 20 |
| speed | TimeoutError | - | 20 |
| 204 | ProxyError | - | 18 |
| geo | TimeoutError | - | 12 |
| speed | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 9 |
| cn-block | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36936: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
