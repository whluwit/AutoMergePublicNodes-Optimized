# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-06 04:43:24 |
| 运行耗时 | 744.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98055 |
| 去重后节点 | 27353 |
| TCP 可达 | 3000 |
| 真实可用 | 542 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27353 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 45.9 |
| probe | 267.9 |
| real_test | 340.3 |
| generate | 81.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58054 |
| vmess | 15883 |
| shadowsocks | 11648 |
| trojan | 10167 |
| hysteria2 | 1373 |
| http | 615 |
| shadowsocksr | 165 |
| socks | 93 |
| anytls | 28 |
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
| 84.81 | vless | 178.8 | 477.7 | 23.64 | 0.0 | 10.0 | 11.87 | 19.3 | Au1rxx-base64 | 47.251.108.158 |
| 84.76 | hysteria2 | 246.1 | 568.1 | 22.08 | 0.0 | 10.0 | 14.38 | 19.3 | Au1rxx-base64 | 66.94.121.46 |
| 84.72 | vless | 182.7 | 474.2 | 23.55 | 0.0 | 10.0 | 11.87 | 19.3 | Au1rxx-base64 | 137.175.82.40 |
| 84.18 | vless | 205.8 | 534.9 | 23.01 | 0.0 | 10.0 | 11.87 | 19.3 | Au1rxx-base64 | 107.173.237.146 |
| 83.76 | vless | 224.1 | 602.9 | 22.59 | 0.0 | 10.0 | 11.87 | 19.3 | Au1rxx-base64 | 23.95.222.127 |
| 83.51 | vless | 235.0 | 573.1 | 22.34 | 0.0 | 10.0 | 11.87 | 19.3 | Au1rxx-base64 | 15.204.97.216 |
| 81.99 | trojan | 280.5 | 570.8 | 21.28 | 0.0 | 10.0 | 14.58 | 19.3 | Au1rxx-base64 | guided-ferret.rooster465.autos |
| 81.62 | trojan | 325.6 | 716.5 | 20.24 | 0.0 | 10.0 | 14.58 | 19.3 | Au1rxx-base64 | ultimate-jaguar.rooster465.autos |
| 81.55 | shadowsocks | 232.7 | 595.6 | 22.39 | 0.0 | 10.0 | 13.66 | 20.0 | Surfboard-tg-mixed | 5.78.51.123 |
| 81.21 | shadowsocks | 232.4 | 543.4 | 22.4 | 0.0 | 10.0 | 13.66 | 19.3 | Au1rxx-base64 | 173.244.56.9 |
| 81.04 | shadowsocks | 224.7 | 565.6 | 22.58 | 0.0 | 10.0 | 13.66 | 19.3 | Au1rxx-base64 | 108.181.118.10 |
| 80.9 | hysteria2 | 221.8 | 228.8 | 22.64 | 6.42 | 9.94 | 14.38 | 19.3 | Au1rxx-base64 | 45.32.10.7 |
| 80.62 | shadowsocks | 242.7 | 620.7 | 22.16 | 0.0 | 10.0 | 13.66 | 19.3 | Au1rxx-base64 | 108.181.0.177 |
| 80.01 | vless | 386.1 | 862.1 | 18.84 | 0.0 | 10.0 | 11.87 | 19.3 | Au1rxx-base64 | 154.12.38.202 |
| 79.84 | hysteria2 | 246.0 | 242.0 | 22.08 | 5.93 | 9.94 | 14.38 | 19.3 | Au1rxx-base64 | 158.101.148.79 |
| 79.56 | vless | 189.5 | 491.6 | 23.39 | 0.0 | 10.0 | 11.87 | 19.3 | Au1rxx-base64 | 154.21.94.246 |
| 78.94 | shadowsocks | 242.5 | 592.5 | 22.16 | 0.0 | 10.0 | 13.66 | 19.3 | Au1rxx-base64 | 149.22.95.183 |
| 78.58 | vless | 231.9 | 550.0 | 22.41 | 0.0 | 10.0 | 11.87 | 19.3 | Au1rxx-base64 | 15.204.97.197 |
| 78.57 | trojan | 371.1 | 941.9 | 19.19 | 0.0 | 10.0 | 14.58 | 19.3 | Au1rxx-base64 | 34.220.15.24 |
| 78.34 | vless | 328.5 | 897.7 | 20.17 | 0.0 | 10.0 | 11.87 | 19.3 | Au1rxx-base64 | 66.42.97.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | 0.908 | 371 | 1814 | prefer |
| Surfboard-tg-mixed | 0.843 | 0.767 | 133 | 7145 | prefer |
| ermaozi | 0.628 | 0.603 | 58 | 691 | observe |
| DeltaKronecker-all | 0.372 | 0.444 | 9 | 5300 | observe |
| mheidari-all | 0.342 | 0.26 | 235 | 23039 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 76 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5111 | observe |
| Epodonios-all | 0.255 | None | 0 | 7631 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9144 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5642 | observe |
| barry-far-vless | 0.255 | None | 0 | 5876 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4375 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 107 |
| speed | TimeoutError | - | 46 |
| 204 | ProxyError | - | 29 |
| geo | ClientOSError | - | 27 |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 16 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 9 |
| 204 | ProxyConnectionError | - | 7 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
