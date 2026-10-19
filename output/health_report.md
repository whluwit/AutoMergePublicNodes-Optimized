# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 03:10:37 |
| 运行耗时 | 792.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 97392 |
| 去重后节点 | 27686 |
| TCP 可达 | 3000 |
| 真实可用 | 503 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27686 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 48.6 |
| probe | 278.0 |
| real_test | 365.9 |
| generate | 90.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57156 |
| vmess | 16711 |
| shadowsocks | 11583 |
| trojan | 9559 |
| hysteria2 | 1336 |
| http | 761 |
| shadowsocksr | 164 |
| socks | 70 |
| anytls | 29 |
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
| 81.44 | vless | 238.7 | 598.6 | 22.25 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 195.123.235.183 |
| 80.27 | vless | 289.6 | 748.3 | 21.08 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.90 |
| 80.24 | vless | 290.8 | 711.5 | 21.05 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 66.70.179.198 |
| 80.19 | vless | 292.8 | 633.4 | 21.0 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.74 |
| 79.72 | hysteria2 | 255.2 | 670.2 | 21.87 | 0.0 | 10.0 | 11.25 | 18.1 | Au1rxx-base64 | 129.213.91.185 |
| 79.62 | vless | 305.8 | 668.0 | 20.7 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.182 |
| 79.56 | vless | 311.4 | 763.7 | 20.57 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.212 |
| 79.49 | vless | 323.0 | 849.2 | 20.3 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.231 |
| 79.4 | vless | 327.1 | 889.4 | 20.21 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 159.89.87.21 |
| 79.37 | vless | 284.8 | 740.0 | 21.18 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 195.123.235.177 |
| 79.37 | vless | 294.9 | 773.3 | 20.95 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.35 |
| 78.88 | vless | 349.3 | 863.8 | 19.69 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.184 |
| 78.85 | vless | 350.7 | 869.7 | 19.66 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.52 |
| 78.59 | vless | 351.4 | 931.9 | 19.64 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.133 |
| 78.56 | vless | 363.1 | 979.5 | 19.37 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 185.95.231.156 |
| 78.51 | vless | 316.3 | 765.9 | 20.46 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.202 |
| 78.41 | vless | 283.2 | 724.3 | 21.22 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.104 |
| 78.31 | vless | 334.3 | 747.0 | 20.04 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 169.40.42.179 |
| 78.24 | shadowsocks | 263.2 | 714.8 | 21.68 | 0.0 | 10.0 | 12.46 | 18.1 | Au1rxx-base64 | 37.19.198.160 |
| 78.24 | vless | 318.3 | 750.2 | 20.41 | 0.0 | 10.0 | 11.09 | 18.1 | Au1rxx-base64 | 5.34.178.120 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | 0.871 | 404 | 1675 | prefer |
| Surfboard-tg-mixed | 0.698 | 0.846 | 13 | 7003 | observe |
| mheidari-all | 0.525 | 0.444 | 261 | 23518 | observe |
| DeltaKronecker-all | 0.45 | 0.5 | 12 | 4750 | observe |
| ermaozi | 0.432 | 0.4 | 45 | 696 | observe |
| Epodonios-all | 0.255 | None | 0 | 7467 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9938 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5523 | observe |
| barry-far-vless | 0.255 | None | 0 | 5700 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1675 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 91 |
| geo | ClientOSError | - | 37 |
| cn-block | TimeoutError | - | 25 |
| speed | ClientOSError | - | 24 |
| 204 | ProxyError | - | 22 |
| speed | TimeoutError | - | 10 |
| 204 | ProxyConnectionError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 298 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
