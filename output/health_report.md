# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-29 04:08:51 |
| 运行耗时 | 969.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96586 |
| 去重后节点 | 26963 |
| TCP 可达 | 3000 |
| 真实可用 | 519 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26963 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.4 |
| tcp | 45.7 |
| probe | 342.9 |
| real_test | 496.8 |
| generate | 75.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59347 |
| vmess | 14835 |
| shadowsocks | 11273 |
| trojan | 8859 |
| hysteria2 | 1333 |
| http | 643 |
| shadowsocksr | 170 |
| socks | 79 |
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
| 83.25 | hysteria2 | 231.9 | 541.5 | 22.41 | 0.0 | 9.02 | 14.38 | 18.44 | Au1rxx-base64 | 192.255.128.123 |
| 82.47 | vless | 212.5 | 551.7 | 22.86 | 0.0 | 9.2 | 11.97 | 18.44 | Au1rxx-base64 | 15.204.97.216 |
| 82.2 | vless | 219.7 | 557.7 | 22.69 | 0.0 | 9.1 | 11.97 | 18.44 | Au1rxx-base64 | 51.81.203.63 |
| 80.21 | vless | 236.9 | 520.8 | 22.29 | 0.0 | 10.0 | 11.97 | 18.02 | mheidari-all | 47.251.108.158 |
| 79.6 | vless | 258.2 | 572.2 | 21.8 | 0.0 | 9.13 | 11.97 | 18.44 | Au1rxx-base64 | 172.233.139.46 |
| 79.58 | vless | 257.5 | 568.8 | 21.82 | 0.0 | 9.45 | 11.97 | 18.44 | Au1rxx-base64 | 192.3.247.109 |
| 79.52 | shadowsocks | 245.1 | 665.0 | 22.1 | 0.0 | 10.0 | 13.82 | 18.02 | mheidari-all | 149.22.95.183 |
| 78.7 | shadowsocks | 242.4 | 545.0 | 22.17 | 0.0 | 10.0 | 13.82 | 18.02 | mheidari-all | 192.3.247.109 |
| 77.69 | vless | 274.8 | 588.9 | 21.42 | 0.0 | 9.24 | 11.97 | 18.44 | Au1rxx-base64 | 195.123.240.65 |
| 76.64 | hysteria2 | 266.8 | 713.1 | 21.6 | 0.0 | 8.72 | 14.38 | 18.44 | Au1rxx-base64 | us3.xiaoliyu.cyou |
| 76.33 | vless | 318.1 | 731.3 | 20.41 | 0.0 | 9.41 | 11.97 | 18.44 | Au1rxx-base64 | 23.95.222.127 |
| 76.12 | shadowsocks | 244.3 | 666.5 | 22.12 | 0.0 | 10.0 | 13.82 | 14.68 | Surfboard-tg-mixed | 5.78.51.123 |
| 75.29 | vless | 318.0 | 328.6 | 20.42 | 2.68 | 9.11 | 11.97 | 18.44 | Au1rxx-base64 | 43.133.11.187 |
| 75.21 | hysteria2 | 295.6 | 390.9 | 20.93 | 0.34 | 7.98 | 14.38 | 18.44 | Au1rxx-base64 | open.w2m.ink |
| 75.07 | vless | 355.7 | 770.5 | 19.54 | 0.0 | 9.09 | 11.97 | 18.44 | Au1rxx-base64 | 79.141.172.154 |
| 75.05 | shadowsocks | 288.5 | 583.9 | 21.1 | 0.0 | 10.0 | 13.82 | 18.02 | mheidari-all | 173.244.56.6 |
| 73.98 | vless | 353.0 | 342.2 | 19.61 | 2.17 | 9.06 | 11.97 | 18.44 | Au1rxx-base64 | 154.31.114.248 |
| 73.85 | shadowsocks | 324.9 | 685.2 | 20.26 | 0.0 | 10.0 | 13.82 | 18.02 | mheidari-all | 156.146.38.170 |
| 73.26 | shadowsocks | 329.2 | 673.5 | 20.16 | 0.0 | 10.0 | 13.82 | 18.02 | mheidari-all | 23.150.248.20 |
| 73.15 | vless | 280.6 | 400.5 | 21.28 | 0.0 | 9.18 | 11.97 | 18.44 | Au1rxx-base64 | 108.162.198.178 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.869 | 0.81 | 358 | 1519 | prefer |
| ermaozi | 0.779 | 0.781 | 32 | 354 | prefer |
| Surfboard-tg-mixed | 0.633 | 0.579 | 19 | 7142 | observe |
| mheidari-all | 0.416 | 0.335 | 543 | 22589 | observe |
| DeltaKronecker-all | 0.389 | 0.385 | 13 | 5428 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 121 | observe |
| ermaozi-get_subscribe | 0.287 | 0.5 | 6 | 367 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5326 | observe |
| Epodonios-all | 0.255 | None | 0 | 7625 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9229 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5799 | observe |
| barry-far-vless | 0.255 | None | 0 | 6028 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4237 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 170 |
| speed | TimeoutError | - | 85 |
| speed | ClientOSError | - | 84 |
| cn-block | TimeoutError | - | 39 |
| geo | ClientOSError | - | 38 |
| 204 | ProxyError | - | 13 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyConnectionError | - | 5 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
