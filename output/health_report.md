# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-04 04:14:08 |
| 运行耗时 | 945.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99137 |
| 去重后节点 | 27362 |
| TCP 可达 | 3000 |
| 真实可用 | 506 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27362 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 47.8 |
| probe | 340.5 |
| real_test | 476.1 |
| generate | 72.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59937 |
| vmess | 15659 |
| shadowsocks | 11492 |
| trojan | 9577 |
| hysteria2 | 1665 |
| http | 521 |
| shadowsocksr | 166 |
| socks | 70 |
| anytls | 27 |
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
| 82.19 | vless | 247.2 | 615.2 | 22.05 | 0.0 | 10.0 | 12.41 | 18.02 | mheidari-all | 216.227.161.95 |
| 79.96 | shadowsocks | 274.4 | 720.1 | 21.43 | 0.0 | 10.0 | 13.23 | 19.3 | Au1rxx-base64 | 156.146.38.168 |
| 79.77 | vless | 274.0 | 597.7 | 21.44 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 172.235.38.85 |
| 79.73 | hysteria2 | 308.4 | 226.7 | 20.64 | 6.5 | 8.18 | 13.42 | 19.3 | Au1rxx-base64 | open.2ml.bid |
| 79.57 | vless | 271.9 | 574.1 | 21.48 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 195.123.240.65 |
| 79.56 | hysteria2 | 258.3 | 250.3 | 21.8 | 5.62 | 9.04 | 13.42 | 19.3 | Au1rxx-base64 | vp3.yysyy.online |
| 78.24 | vless | 284.3 | 612.1 | 21.2 | 0.0 | 10.0 | 12.41 | 18.02 | mheidari-all | 47.251.108.158 |
| 78.14 | hysteria2 | 290.4 | 723.6 | 21.06 | 0.0 | 10.0 | 13.42 | 16.16 | Surfboard-tg-mixed | 129.213.91.185 |
| 78.06 | vless | 337.8 | 752.9 | 19.96 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 137.184.218.169 |
| 77.54 | shadowsocks | 228.5 | 585.8 | 22.49 | 0.0 | 10.0 | 13.23 | 19.3 | Au1rxx-base64 | 156.146.38.169 |
| 77.21 | vless | 292.4 | 650.3 | 21.01 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 172.235.43.210 |
| 76.46 | vless | 400.3 | 943.9 | 18.51 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 159.89.87.21 |
| 76.21 | vless | 277.5 | 582.3 | 21.35 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 172.233.139.46 |
| 76.09 | hysteria2 | 461.8 | 1008.8 | 17.09 | 0.0 | 10.0 | 13.42 | 18.02 | mheidari-all | 159.223.157.129 |
| 76.08 | vless | 372.9 | 794.5 | 19.15 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 66.70.179.198 |
| 76.05 | vless | 339.7 | 654.6 | 19.92 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 15.204.97.216 |
| 75.89 | shadowsocks | 237.5 | 515.2 | 22.28 | 0.0 | 10.0 | 13.23 | 16.16 | Surfboard-tg-mixed | 216.105.168.18 |
| 75.86 | shadowsocks | 325.9 | 766.5 | 20.23 | 0.0 | 10.0 | 13.23 | 19.3 | Au1rxx-base64 | 37.19.198.243 |
| 75.76 | shadowsocks | 329.6 | 774.5 | 20.15 | 0.0 | 10.0 | 13.23 | 19.3 | Au1rxx-base64 | 37.19.198.236 |
| 75.67 | vless | 365.2 | 753.6 | 19.32 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | 0.921 | 303 | 1800 | prefer |
| Surfboard-tg-mixed | 0.913 | 0.842 | 76 | 7320 | prefer |
| ermaozi | 0.718 | 0.708 | 24 | 646 | prefer |
| mheidari-all | 0.392 | 0.312 | 459 | 23371 | observe |
| ermaozi-get_subscribe | 0.331 | 1.0 | 2 | 505 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5192 | observe |
| Epodonios-all | 0.255 | None | 0 | 7797 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9367 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5893 | observe |
| barry-far-vless | 0.255 | None | 0 | 6122 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4285 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1800 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 179 |
| speed | TimeoutError | - | 80 |
| geo | ClientOSError | - | 34 |
| speed | ClientOSError | - | 18 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 12 |
| 204 | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
