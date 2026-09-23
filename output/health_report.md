# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 10:49:30 |
| 运行耗时 | 585.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96830 |
| 去重后节点 | 26481 |
| TCP 可达 | 3000 |
| 真实可用 | 427 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26481 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.3 |
| tcp | 43.0 |
| probe | 278.1 |
| real_test | 187.9 |
| generate | 71.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59309 |
| vmess | 14978 |
| shadowsocks | 11141 |
| trojan | 8828 |
| hysteria2 | 1622 |
| http | 651 |
| shadowsocksr | 174 |
| socks | 77 |
| anytls | 24 |
| hysteria | 18 |
| tuic | 8 |

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
| 82.16 | hysteria2 | 268.3 | 743.2 | 21.57 | 0.0 | 9.37 | 14.42 | 17.8 | Au1rxx-base64 | 66.94.121.46 |
| 74.78 | hysteria2 | 399.5 | 868.0 | 18.53 | 0.0 | 9.39 | 14.42 | 17.8 | Au1rxx-base64 | 159.223.157.129 |
| 73.45 | shadowsocks | 321.8 | 684.4 | 20.33 | 0.0 | 9.41 | 14.58 | 17.8 | Au1rxx-base64 | 156.146.38.168 |
| 72.9 | vless | 294.0 | 793.6 | 20.97 | 0.0 | 9.41 | 4.72 | 17.8 | Au1rxx-base64 | 15.204.97.216 |
| 71.22 | vless | 263.5 | 575.7 | 21.68 | 0.0 | 9.38 | 4.72 | 17.8 | Au1rxx-base64 | 172.235.43.210 |
| 70.31 | vless | 271.4 | 573.1 | 21.5 | 0.0 | 9.38 | 4.72 | 17.8 | Au1rxx-base64 | 195.123.240.65 |
| 70.21 | shadowsocks | 360.0 | 543.0 | 19.45 | 0.0 | 9.36 | 14.58 | 17.8 | Au1rxx-base64 | 149.22.87.204 |
| 69.95 | vless | 275.9 | 613.6 | 21.39 | 0.0 | 9.43 | 4.72 | 17.8 | Au1rxx-base64 | 70.39.196.142 |
| 69.53 | shadowsocks | 460.1 | 1075.5 | 17.13 | 0.0 | 9.42 | 14.58 | 17.8 | Au1rxx-base64 | 185.156.47.97 |
| 69.52 | http | 275.3 | 585.4 | 21.41 | 0.0 | 10.0 | 10.0 | 14.02 | ermaozi | 138.199.35.216 |
| 69.47 | http | 270.1 | 579.1 | 21.53 | 0.0 | 10.0 | 10.0 | 14.02 | ermaozi | 138.199.35.204 |
| 69.38 | shadowsocks | 281.3 | 595.4 | 21.27 | 0.0 | 10.0 | 14.58 | 11.08 | Surfboard-tg-mixed | 173.244.56.9 |
| 69.19 | http | 270.7 | 578.4 | 21.51 | 0.0 | 10.0 | 10.0 | 14.02 | ermaozi | 138.199.35.207 |
| 69.18 | http | 268.6 | 577.1 | 21.56 | 0.0 | 10.0 | 10.0 | 14.02 | ermaozi | 138.199.35.213 |
| 68.95 | http | 270.6 | 580.2 | 21.51 | 0.0 | 10.0 | 10.0 | 14.02 | ermaozi | 138.199.35.211 |
| 68.93 | http | 273.0 | 581.7 | 21.46 | 0.0 | 10.0 | 10.0 | 14.02 | ermaozi | 138.199.35.202 |
| 68.76 | http | 271.3 | 578.4 | 21.5 | 0.0 | 10.0 | 10.0 | 14.02 | ermaozi | 138.199.35.220 |
| 68.76 | shadowsocks | 403.5 | 362.6 | 18.44 | 1.4 | 9.25 | 14.58 | 17.8 | Au1rxx-base64 | 167.150.100.93 |
| 68.73 | shadowsocks | 255.0 | 702.2 | 21.87 | 0.0 | 10.0 | 14.58 | 6.28 | mheidari-all | 149.22.95.183 |
| 68.31 | http | 266.8 | 573.3 | 21.6 | 0.0 | 10.0 | 10.0 | 14.02 | ermaozi | 138.199.35.214 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.899 | 0.837 | 246 | 1602 | prefer |
| mheidari-all | 0.811 | 0.736 | 91 | 22242 | prefer |
| ermaozi | 0.76 | 0.754 | 57 | 346 | prefer |
| Surfboard-tg-mixed | 0.625 | 0.546 | 185 | 7036 | observe |
| DeltaKronecker-all | 0.425 | 0.4 | 15 | 6471 | observe |
| ermaozi-get_subscribe | 0.307 | 0.444 | 9 | 372 | observe |
| Epodonios-all | 0.255 | None | 0 | 7633 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9065 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5755 | observe |
| barry-far-vless | 0.255 | None | 0 | 5975 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4187 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1602 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 52 |
| 204 | ProxyError | - | 29 |
| geo | ClientOSError | - | 27 |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 15 |
| geo | TimeoutError | - | 13 |
| speed | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
