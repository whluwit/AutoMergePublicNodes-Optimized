# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 03:12:51 |
| 运行耗时 | 646.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 89722 |
| 去重后节点 | 25406 |
| TCP 可达 | 3000 |
| 真实可用 | 479 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25406 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.4 |
| tcp | 42.6 |
| probe | 233.4 |
| real_test | 323.4 |
| generate | 38.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54632 |
| vmess | 13396 |
| shadowsocks | 10577 |
| trojan | 8391 |
| hysteria2 | 1828 |
| http | 669 |
| shadowsocksr | 131 |
| socks | 57 |
| tuic | 18 |
| hysteria | 14 |
| anytls | 9 |

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
| 82.92 | vless | 238.7 | 628.5 | 22.25 | 0.0 | 9.47 | 11.58 | 19.62 | Au1rxx-base64 | 195.123.235.177 |
| 82.76 | vless | 232.4 | 665.0 | 22.4 | 0.0 | 9.16 | 11.58 | 19.62 | Au1rxx-base64 | 79.141.172.154 |
| 82.54 | vless | 248.5 | 651.3 | 22.03 | 0.0 | 9.31 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.224 |
| 82.36 | vless | 254.1 | 653.0 | 21.9 | 0.0 | 9.26 | 11.58 | 19.62 | Au1rxx-base64 | 167.17.69.171 |
| 82.36 | vless | 254.1 | 722.2 | 21.9 | 0.0 | 9.26 | 11.58 | 19.62 | Au1rxx-base64 | 47.253.226.114 |
| 82.29 | vless | 254.5 | 664.7 | 21.89 | 0.0 | 9.2 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.184 |
| 82.28 | hysteria2 | 242.2 | 635.7 | 22.17 | 0.0 | 10.0 | 13.85 | 17.36 | mheidari-all | 159.223.157.129 |
| 82.25 | vless | 252.3 | 659.8 | 21.94 | 0.0 | 9.11 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.179 |
| 81.58 | vless | 296.7 | 821.5 | 20.91 | 0.0 | 9.47 | 11.58 | 19.62 | Au1rxx-base64 | 185.95.231.156 |
| 80.99 | vless | 320.4 | 823.3 | 20.36 | 0.0 | 9.43 | 11.58 | 19.62 | Au1rxx-base64 | 66.70.179.198 |
| 80.89 | vless | 313.1 | 699.1 | 20.53 | 0.0 | 9.16 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.163 |
| 80.81 | vless | 318.2 | 855.4 | 20.41 | 0.0 | 9.2 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.95 |
| 80.79 | vless | 317.5 | 720.8 | 20.43 | 0.0 | 9.16 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.89 |
| 80.72 | vless | 335.8 | 779.8 | 20.0 | 0.0 | 9.52 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.74 |
| 80.35 | vless | 334.2 | 912.5 | 20.04 | 0.0 | 9.11 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.35 |
| 80.31 | vless | 338.1 | 857.5 | 19.95 | 0.0 | 9.16 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.229 |
| 79.96 | vless | 354.6 | 920.4 | 19.57 | 0.0 | 9.19 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.223 |
| 79.82 | vless | 256.3 | 667.8 | 21.84 | 0.0 | 9.43 | 11.58 | 19.62 | Au1rxx-base64 | 169.40.42.225 |
| 79.47 | shadowsocks | 228.7 | 629.9 | 22.48 | 0.0 | 10.0 | 13.63 | 17.36 | mheidari-all | 37.19.198.244 |
| 79.45 | vless | 297.8 | 666.2 | 20.89 | 0.0 | 9.18 | 11.58 | 19.62 | Au1rxx-base64 | 198.251.78.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.901 | 0.838 | 346 | 1616 | prefer |
| Surfboard-tg-mixed | 0.853 | 0.779 | 95 | 7482 | prefer |
| mheidari-all | 0.653 | 0.574 | 101 | 15963 | observe |
| ermaozi | 0.583 | 0.571 | 28 | 417 | observe |
| ermaozi-get_subscribe | 0.427 | 0.667 | 9 | 444 | observe |
| DeltaKronecker-all | 0.391 | 0.307 | 101 | 5892 | observe |
| Epodonios-all | 0.255 | None | 0 | 7945 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8882 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6107 | observe |
| barry-far-vless | 0.255 | None | 0 | 6350 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4222 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1616 | observe |
| xiaoji235-airport-v2ray-all | 0.236 | 0.133 | 30 | 5301 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 66 |
| speed | TimeoutError | - | 35 |
| speed | ClientOSError | - | 33 |
| geo | ClientOSError | - | 33 |
| cn-block | ClientOSError | - | 19 |
| 204 | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 12 |
| 204 | ProxyConnectionError | - | 11 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
