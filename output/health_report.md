# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-10 01:24:11 |
| 运行耗时 | 263.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86098 |
| 去重后节点 | 23943 |
| TCP 可达 | 3000 |
| 真实可用 | 543 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23943 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 34.6 |
| probe | 52.7 |
| real_test | 126.9 |
| generate | 43.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51745 |
| vmess | 13254 |
| trojan | 9803 |
| shadowsocks | 9605 |
| hysteria2 | 1474 |
| socks | 71 |
| shadowsocksr | 66 |
| http | 31 |
| anytls | 26 |
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
| 83.93 | trojan | 237.3 | 535.4 | 22.29 | 0.0 | 10.0 | 14.3 | 19.84 | Au1rxx-base64 | 35.86.90.51 |
| 83.88 | http | 188.6 | 486.8 | 23.41 | 0.0 | 10.0 | 14.35 | 19.12 | zhangkai | 138.199.35.207 |
| 83.75 | http | 194.4 | 491.9 | 23.28 | 0.0 | 10.0 | 14.35 | 19.12 | zhangkai | 138.199.35.214 |
| 83.69 | http | 196.8 | 510.3 | 23.22 | 0.0 | 10.0 | 14.35 | 19.12 | zhangkai | 138.199.35.199 |
| 83.66 | http | 198.3 | 510.6 | 23.19 | 0.0 | 10.0 | 14.35 | 19.12 | zhangkai | 138.199.35.217 |
| 83.65 | trojan | 213.4 | 476.3 | 22.84 | 0.0 | 9.17 | 14.3 | 19.84 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 83.27 | trojan | 215.3 | 483.2 | 22.79 | 0.0 | 9.0 | 14.3 | 19.84 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 82.82 | vless | 185.9 | 477.6 | 23.47 | 0.0 | 10.0 | 9.51 | 19.84 | Au1rxx-base64 | 179.255.148.66 |
| 82.75 | trojan | 262.9 | 616.2 | 21.69 | 0.0 | 9.42 | 14.3 | 19.84 | Au1rxx-base64 | 44.242.235.129 |
| 82.75 | trojan | 263.9 | 623.7 | 21.67 | 0.0 | 9.44 | 14.3 | 19.84 | Au1rxx-base64 | 44.244.3.114 |
| 82.43 | shadowsocks | 219.1 | 514.7 | 22.71 | 0.0 | 10.0 | 13.88 | 19.84 | Au1rxx-base64 | 173.244.56.9 |
| 82.07 | vless | 195.3 | 502.3 | 23.26 | 0.0 | 9.46 | 9.51 | 19.84 | Au1rxx-base64 | 70.39.178.231 |
| 81.92 | trojan | 299.3 | 731.6 | 20.85 | 0.0 | 9.43 | 14.3 | 19.84 | Au1rxx-base64 | 44.246.163.102 |
| 81.81 | vless | 186.3 | 487.4 | 23.46 | 0.0 | 10.0 | 9.51 | 19.84 | Au1rxx-base64 | 64.23.143.23 |
| 81.7 | vless | 191.4 | 487.1 | 23.35 | 0.0 | 10.0 | 9.51 | 19.84 | Au1rxx-base64 | 179.253.240.24 |
| 81.67 | vless | 179.3 | 485.6 | 23.63 | 0.0 | 8.69 | 9.51 | 19.84 | Au1rxx-base64 | t18.qifei.app |
| 81.63 | vless | 237.5 | 623.6 | 22.28 | 0.0 | 10.0 | 9.51 | 19.84 | Au1rxx-base64 | 70.39.197.13 |
| 81.34 | shadowsocks | 250.4 | 593.2 | 21.98 | 0.0 | 10.0 | 13.88 | 19.84 | Au1rxx-base64 | 149.22.95.183 |
| 81.32 | trojan | 214.8 | 478.7 | 22.81 | 0.0 | 7.06 | 14.3 | 19.84 | Au1rxx-base64 | natural-collie.rooster465.autos |
| 81.24 | vless | 254.5 | 680.2 | 21.89 | 0.0 | 10.0 | 9.51 | 19.84 | Au1rxx-base64 | 186.241.106.97 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Au1rxx-base64 | 0.953 | 0.887 | 443 | 1698 | prefer |
| Surfboard-tg-mixed | 0.711 | 0.633 | 139 | 6612 | prefer |
| mheidari-all | 0.27 | 0.186 | 177 | 20202 | observe |
| nscl5-all | 0.265 | 0.5 | 2 | 1442 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5505 | observe |
| Epodonios-all | 0.255 | None | 0 | 7220 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7572 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5465 | observe |
| barry-far-vless | 0.255 | None | 0 | 5808 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5189 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1698 | observe |
| DeltaKronecker-all | 0.228 | 0.136 | 59 | 4998 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 122 |
| speed | TimeoutError | - | 58 |
| geo | ClientOSError | - | 48 |
| cn-block | TimeoutError | - | 30 |
| speed | ClientOSError | - | 22 |
| 204 | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
