# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-28 03:32:01 |
| 运行耗时 | 1012.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 95076 |
| 去重后节点 | 26767 |
| TCP 可达 | 3000 |
| 真实可用 | 568 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26767 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.5 |
| tcp | 43.7 |
| probe | 337.4 |
| real_test | 532.8 |
| generate | 87.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57471 |
| vmess | 14761 |
| shadowsocks | 11537 |
| trojan | 8915 |
| hysteria2 | 1476 |
| http | 620 |
| shadowsocksr | 173 |
| socks | 76 |
| anytls | 24 |
| hysteria | 15 |
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
| 83.57 | vless | 177.3 | 475.3 | 23.67 | 0.0 | 10.0 | 10.8 | 19.1 | mheidari-all | 47.251.108.158 |
| 82.02 | hysteria2 | 227.3 | 581.6 | 22.52 | 0.0 | 10.0 | 13.12 | 17.38 | Au1rxx-base64 | 66.94.121.46 |
| 81.87 | vless | 176.5 | 479.7 | 23.69 | 0.0 | 10.0 | 10.8 | 17.38 | Au1rxx-base64 | 137.175.82.40 |
| 81.52 | shadowsocks | 193.7 | 511.1 | 23.29 | 0.0 | 10.0 | 13.63 | 19.1 | mheidari-all | 192.3.247.109 |
| 81.26 | vless | 202.8 | 525.5 | 23.08 | 0.0 | 10.0 | 10.8 | 17.38 | Au1rxx-base64 | 172.235.43.210 |
| 81.02 | vless | 213.4 | 564.2 | 22.84 | 0.0 | 10.0 | 10.8 | 17.38 | Au1rxx-base64 | 172.235.38.85 |
| 80.89 | vless | 219.0 | 548.5 | 22.71 | 0.0 | 10.0 | 10.8 | 17.38 | Au1rxx-base64 | 195.123.240.65 |
| 80.82 | hysteria2 | 279.1 | 740.1 | 21.32 | 0.0 | 10.0 | 13.12 | 17.38 | Au1rxx-base64 | 192.255.128.123 |
| 80.58 | vless | 232.4 | 572.5 | 22.4 | 0.0 | 10.0 | 10.8 | 17.38 | Au1rxx-base64 | 15.204.97.216 |
| 79.87 | vless | 263.0 | 676.5 | 21.69 | 0.0 | 10.0 | 10.8 | 17.38 | Au1rxx-base64 | 5.78.159.214 |
| 78.28 | shadowsocks | 277.9 | 694.1 | 21.34 | 0.0 | 10.0 | 13.63 | 17.38 | Au1rxx-base64 | 173.244.56.9 |
| 77.69 | shadowsocks | 210.5 | 529.6 | 22.9 | 0.0 | 10.0 | 13.63 | 15.66 | Surfboard-tg-mixed | 5.78.51.123 |
| 77.55 | vless | 291.1 | 657.2 | 21.04 | 0.0 | 10.0 | 10.8 | 19.1 | mheidari-all | 216.227.161.95 |
| 77.04 | shadowsocks | 238.7 | 589.7 | 22.25 | 0.0 | 10.0 | 13.63 | 15.66 | Surfboard-tg-mixed | 108.181.0.177 |
| 77.02 | shadowsocks | 335.7 | 824.5 | 20.01 | 0.0 | 10.0 | 13.63 | 17.38 | Au1rxx-base64 | 173.244.56.6 |
| 76.77 | shadowsocks | 183.3 | 460.8 | 23.54 | 0.0 | 10.0 | 13.63 | 19.1 | mheidari-all | 43.173.90.202 |
| 76.6 | shadowsocks | 257.7 | 654.4 | 21.81 | 0.0 | 10.0 | 13.63 | 15.66 | Surfboard-tg-mixed | 108.181.118.10 |
| 76.23 | vless | 423.5 | 624.9 | 17.97 | 0.0 | 10.0 | 10.8 | 19.1 | mheidari-all | 172.67.130.144 |
| 75.4 | shadowsocks | 273.3 | 284.1 | 21.45 | 4.35 | 9.95 | 13.63 | 17.38 | Au1rxx-base64 | 149.22.87.241 |
| 75.27 | vless | 223.3 | 475.7 | 22.61 | 0.0 | 10.0 | 10.8 | 19.1 | mheidari-all | 104.21.45.213 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.923 | 0.867 | 339 | 1437 | prefer |
| Surfboard-tg-mixed | 0.823 | 0.75 | 72 | 7018 | prefer |
| ermaozi | 0.696 | 0.69 | 42 | 347 | observe |
| mheidari-all | 0.388 | 0.307 | 615 | 22305 | observe |
| Epodonios-all | 0.255 | None | 0 | 7506 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8964 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5592 | observe |
| barry-far-vless | 0.255 | None | 0 | 5817 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4185 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.232 | None | 0 | 1437 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.207 | 0.0 | 1 | 5327 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 196 |
| speed | TimeoutError | - | 98 |
| geo | ClientOSError | - | 78 |
| speed | ClientOSError | - | 76 |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyError | - | 11 |
| 204 | ProxyConnectionError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
