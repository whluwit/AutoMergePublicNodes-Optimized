# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 12:29:12 |
| 运行耗时 | 648.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98623 |
| 去重后节点 | 27377 |
| TCP 可达 | 3000 |
| 真实可用 | 412 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27377 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.4 |
| tcp | 45.3 |
| probe | 303.5 |
| real_test | 212.7 |
| generate | 79.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60500 |
| vmess | 15587 |
| shadowsocks | 11401 |
| trojan | 8934 |
| hysteria2 | 1365 |
| http | 532 |
| shadowsocksr | 174 |
| socks | 66 |
| anytls | 40 |
| hysteria | 16 |
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
| 82.18 | hysteria2 | 191.9 | 506.9 | 23.34 | 0.0 | 10.0 | 12.22 | 17.62 | Au1rxx-base64 | 192.255.128.123 |
| 80.14 | shadowsocks | 201.0 | 538.6 | 23.13 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 173.244.56.6 |
| 79.6 | shadowsocks | 202.4 | 502.7 | 23.09 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 108.181.0.177 |
| 79.51 | shadowsocks | 206.4 | 495.9 | 23.0 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 108.181.118.10 |
| 78.77 | shadowsocks | 259.8 | 633.6 | 21.76 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 156.146.38.169 |
| 78.75 | shadowsocks | 261.0 | 633.2 | 21.74 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 156.146.38.170 |
| 78.68 | shadowsocks | 264.0 | 643.5 | 21.67 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 156.146.38.167 |
| 78.08 | shadowsocks | 181.9 | 485.2 | 23.57 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 173.234.25.90 |
| 78.04 | shadowsocks | 248.2 | 677.7 | 22.03 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 173.244.56.9 |
| 77.65 | shadowsocks | 200.3 | 544.9 | 23.14 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 103.214.109.197 |
| 77.46 | vless | 200.0 | 514.4 | 23.15 | 0.0 | 10.0 | 6.69 | 17.62 | Au1rxx-base64 | 172.233.139.46 |
| 77.02 | vless | 218.9 | 550.9 | 22.71 | 0.0 | 10.0 | 6.69 | 17.62 | Au1rxx-base64 | 195.123.240.65 |
| 76.8 | shadowsocks | 262.2 | 636.2 | 21.71 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 156.146.38.168 |
| 76.79 | shadowsocks | 237.4 | 656.8 | 22.28 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 104.192.225.106 |
| 76.5 | vless | 241.6 | 656.2 | 22.19 | 0.0 | 10.0 | 6.69 | 17.62 | Au1rxx-base64 | 172.235.43.210 |
| 75.16 | shadowsocks | 287.0 | 622.7 | 21.13 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 149.22.95.183 |
| 74.99 | shadowsocks | 185.9 | 490.2 | 23.48 | 0.0 | 10.0 | 13.39 | 17.62 | Au1rxx-base64 | 74.201.177.54 |
| 74.85 | hysteria2 | 440.2 | 1117.4 | 17.59 | 0.0 | 10.0 | 12.22 | 17.62 | Au1rxx-base64 | 66.94.121.46 |
| 74.64 | trojan | 261.2 | 628.7 | 21.73 | 0.0 | 10.0 | 10.29 | 17.62 | Au1rxx-base64 | 107.149.159.190 |
| 73.82 | shadowsocks | 283.6 | 683.5 | 21.21 | 0.0 | 10.0 | 13.39 | 14.38 | Surfboard-tg-mixed | 5.78.51.123 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.899 | 0.909 | 22 | 588 | prefer |
| Au1rxx-base64 | 0.85 | 0.781 | 306 | 1767 | prefer |
| mheidari-all | 0.83 | 0.758 | 66 | 23162 | prefer |
| Surfboard-tg-mixed | 0.772 | 0.696 | 115 | 7144 | prefer |
| DeltaKronecker-all | 0.386 | 0.3 | 70 | 5603 | observe |
| tg-oneclickvpnkeys | 0.314 | 1.0 | 2 | 66 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5324 | observe |
| Epodonios-all | 0.255 | None | 0 | 7625 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9489 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5788 | observe |
| barry-far-vless | 0.255 | None | 0 | 6050 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4241 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 75 |
| 204 | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 17 |
| geo | TimeoutError | - | 12 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 6 |
| geo | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
