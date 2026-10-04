# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-04 16:29:18 |
| 运行耗时 | 521.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99560 |
| 去重后节点 | 27313 |
| TCP 可达 | 3000 |
| 真实可用 | 375 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27313 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.2 |
| tcp | 47.1 |
| probe | 205.3 |
| real_test | 174.0 |
| generate | 86.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59644 |
| vmess | 15937 |
| shadowsocks | 11485 |
| trojan | 10193 |
| hysteria2 | 1484 |
| http | 522 |
| shadowsocksr | 171 |
| socks | 74 |
| anytls | 27 |
| hysteria | 16 |
| tuic | 7 |

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
| 81.67 | hysteria2 | 289.7 | 596.8 | 21.07 | 0.0 | 10.0 | 12.0 | 19.6 | Au1rxx-base64 | 66.94.121.46 |
| 80.69 | shadowsocks | 238.4 | 614.6 | 22.26 | 0.0 | 10.0 | 12.83 | 19.6 | Au1rxx-base64 | 156.146.38.169 |
| 79.4 | shadowsocks | 243.6 | 564.5 | 22.14 | 0.0 | 10.0 | 12.83 | 19.6 | Au1rxx-base64 | 5.78.51.123 |
| 77.96 | hysteria2 | 270.9 | 316.2 | 21.51 | 3.14 | 9.05 | 12.0 | 19.6 | Au1rxx-base64 | open.w2m.ink |
| 77.42 | shadowsocks | 250.0 | 606.5 | 21.99 | 0.0 | 10.0 | 12.83 | 19.6 | Au1rxx-base64 | 156.146.38.167 |
| 77.09 | vless | 274.1 | 605.5 | 21.43 | 0.0 | 10.0 | 11.96 | 19.6 | Au1rxx-base64 | 15.204.97.216 |
| 76.69 | shadowsocks | 268.0 | 566.3 | 21.57 | 0.0 | 10.0 | 12.83 | 19.6 | Au1rxx-base64 | 173.244.56.6 |
| 76.54 | hysteria2 | 316.5 | 726.0 | 20.45 | 0.0 | 10.0 | 12.0 | 17.26 | Surfboard-tg-mixed | 129.213.91.185 |
| 76.06 | vless | 372.1 | 790.4 | 19.16 | 0.0 | 10.0 | 11.96 | 19.6 | Au1rxx-base64 | 66.70.179.198 |
| 75.46 | shadowsocks | 284.6 | 575.5 | 21.19 | 0.0 | 10.0 | 12.83 | 19.6 | Au1rxx-base64 | 108.181.118.10 |
| 75.45 | trojan | 290.6 | 598.2 | 21.05 | 0.0 | 8.2 | 13.89 | 19.6 | Au1rxx-base64 | happy-gibbon.rooster465.autos |
| 75.2 | shadowsocks | 304.5 | 299.8 | 20.73 | 3.76 | 9.79 | 12.83 | 19.6 | Au1rxx-base64 | 149.22.87.241 |
| 74.99 | vless | 270.1 | 599.0 | 21.53 | 0.0 | 10.0 | 11.96 | 19.6 | Au1rxx-base64 | 15.204.97.195 |
| 74.71 | shadowsocks | 308.3 | 310.4 | 20.64 | 3.36 | 9.79 | 12.83 | 19.6 | Au1rxx-base64 | 149.22.87.240 |
| 74.41 | shadowsocks | 341.2 | 774.6 | 19.88 | 0.0 | 10.0 | 12.83 | 19.6 | Au1rxx-base64 | 37.19.198.243 |
| 74.33 | shadowsocks | 339.3 | 777.1 | 19.92 | 0.0 | 10.0 | 12.83 | 19.6 | Au1rxx-base64 | 37.19.198.236 |
| 74.23 | vless | 530.7 | 1368.5 | 15.49 | 0.0 | 10.0 | 11.96 | 19.6 | Au1rxx-base64 | 51.81.203.63 |
| 73.62 | shadowsocks | 343.9 | 786.9 | 19.82 | 0.0 | 10.0 | 12.83 | 19.6 | Au1rxx-base64 | 37.19.198.160 |
| 73.42 | vless | 388.8 | 888.3 | 18.78 | 0.0 | 10.0 | 11.96 | 19.6 | Au1rxx-base64 | 34.29.203.135 |
| 73.08 | shadowsocks | 239.9 | 618.2 | 22.22 | 0.0 | 10.0 | 12.83 | 19.6 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.949 | 0.878 | 295 | 1831 | prefer |
| mheidari-all | 0.895 | 0.827 | 52 | 23366 | prefer |
| Surfboard-tg-mixed | 0.846 | 0.773 | 75 | 7225 | prefer |
| ermaozi | 0.471 | 0.44 | 25 | 653 | observe |
| DeltaKronecker-all | 0.349 | 0.667 | 3 | 5267 | observe |
| ermaozi-get_subscribe | 0.261 | 0.5 | 4 | 518 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5173 | observe |
| Epodonios-all | 0.255 | None | 0 | 7759 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9833 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5815 | observe |
| barry-far-vless | 0.255 | None | 0 | 6063 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1831 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyConnectionError | - | 15 |
| 204 | TimeoutError | - | 15 |
| speed | TimeoutError | - | 9 |
| geo | TimeoutError | - | 9 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ClientOSError | - | 2 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
