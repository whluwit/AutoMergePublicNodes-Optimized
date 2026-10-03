# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 03:46:29 |
| 运行耗时 | 991.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99149 |
| 去重后节点 | 27181 |
| TCP 可达 | 3000 |
| 真实可用 | 507 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27181 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.3 |
| tcp | 47.2 |
| probe | 323.1 |
| real_test | 522.5 |
| generate | 89.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60710 |
| vmess | 15590 |
| shadowsocks | 11413 |
| trojan | 8973 |
| hysteria2 | 1650 |
| http | 522 |
| shadowsocksr | 164 |
| socks | 68 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 12 |

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
| 85.09 | vless | 175.0 | 465.7 | 23.73 | 0.0 | 10.0 | 12.02 | 19.34 | mheidari-all | 47.251.108.158 |
| 84.85 | vless | 179.9 | 493.8 | 23.61 | 0.0 | 10.0 | 12.02 | 19.22 | Au1rxx-base64 | 137.175.82.40 |
| 84.53 | vless | 193.9 | 502.7 | 23.29 | 0.0 | 10.0 | 12.02 | 19.22 | Au1rxx-base64 | 172.233.139.46 |
| 84.39 | vless | 199.7 | 510.0 | 23.15 | 0.0 | 10.0 | 12.02 | 19.22 | Au1rxx-base64 | 172.235.38.85 |
| 84.28 | vless | 204.6 | 537.8 | 23.04 | 0.0 | 10.0 | 12.02 | 19.22 | Au1rxx-base64 | 172.235.43.210 |
| 83.7 | hysteria2 | 200.6 | 517.6 | 23.13 | 0.0 | 10.0 | 12.35 | 19.22 | Au1rxx-base64 | 192.255.128.123 |
| 83.66 | vless | 231.5 | 569.2 | 22.42 | 0.0 | 10.0 | 12.02 | 19.22 | Au1rxx-base64 | 15.204.97.216 |
| 83.18 | hysteria2 | 223.1 | 550.3 | 22.61 | 0.0 | 10.0 | 12.35 | 19.22 | Au1rxx-base64 | 66.94.121.46 |
| 82.28 | vless | 291.2 | 742.8 | 21.04 | 0.0 | 10.0 | 12.02 | 19.22 | Au1rxx-base64 | 195.123.240.65 |
| 81.49 | vless | 277.8 | 645.8 | 21.35 | 0.0 | 10.0 | 12.02 | 19.34 | mheidari-all | 216.227.161.95 |
| 81.36 | shadowsocks | 230.4 | 543.6 | 22.45 | 0.0 | 10.0 | 13.69 | 19.22 | Au1rxx-base64 | 173.244.56.9 |
| 80.51 | shadowsocks | 245.2 | 670.6 | 22.1 | 0.0 | 10.0 | 13.69 | 19.22 | Au1rxx-base64 | 74.201.177.54 |
| 80.34 | shadowsocks | 230.9 | 546.9 | 22.43 | 0.0 | 10.0 | 13.69 | 19.22 | Au1rxx-base64 | 173.244.56.6 |
| 79.54 | trojan | 169.8 | 473.2 | 23.85 | 0.0 | 10.0 | 13.85 | 19.34 | mheidari-all | 43.173.90.202 |
| 79.51 | shadowsocks | 288.6 | 769.5 | 21.1 | 0.0 | 10.0 | 13.69 | 19.22 | Au1rxx-base64 | 108.181.118.10 |
| 79.43 | shadowsocks | 292.0 | 750.8 | 21.02 | 0.0 | 10.0 | 13.69 | 19.22 | Au1rxx-base64 | 108.181.0.177 |
| 79.14 | vless | 210.9 | 527.8 | 22.9 | 0.0 | 10.0 | 12.02 | 19.22 | Au1rxx-base64 | 156.229.162.171 |
| 79.0 | shadowsocks | 224.3 | 599.8 | 22.59 | 0.0 | 10.0 | 13.69 | 19.22 | Au1rxx-base64 | 103.214.109.197 |
| 78.47 | trojan | 275.6 | 713.5 | 21.4 | 0.0 | 10.0 | 13.85 | 19.22 | Au1rxx-base64 | 107.149.159.190 |
| 78.39 | http | 368.1 | 1021.2 | 19.26 | 0.0 | 10.0 | 13.85 | 18.28 | ermaozi | 138.199.35.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | 0.89 | 308 | 1762 | prefer |
| Surfboard-tg-mixed | 0.928 | 0.859 | 64 | 7256 | prefer |
| mheidari-all | 0.405 | 0.324 | 487 | 23323 | observe |
| DeltaKronecker-all | 0.397 | 0.417 | 12 | 4981 | observe |
| ermaozi | 0.396 | 0.36 | 25 | 645 | observe |
| ermaozi-get_subscribe | 0.387 | 0.8 | 5 | 516 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5276 | observe |
| Epodonios-all | 0.255 | None | 0 | 7743 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9542 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5980 | observe |
| barry-far-vless | 0.255 | None | 0 | 6214 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4357 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 186 |
| speed | TimeoutError | - | 87 |
| geo | ClientOSError | - | 38 |
| cn-block | TimeoutError | - | 22 |
| speed | ClientOSError | - | 19 |
| 204 | ProxyConnectionError | - | 15 |
| 204 | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 8 |
| 204 | ProxyError | - | 6 |
| speed | ClientPayloadError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
