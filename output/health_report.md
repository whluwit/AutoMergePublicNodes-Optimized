# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-09 01:22:00 |
| 运行耗时 | 234.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83131 |
| 去重后节点 | 23580 |
| TCP 可达 | 3000 |
| 真实可用 | 494 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23580 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 34.7 |
| probe | 53.1 |
| real_test | 107.8 |
| generate | 31.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48960 |
| vmess | 13233 |
| trojan | 9837 |
| shadowsocks | 9584 |
| hysteria2 | 1309 |
| shadowsocksr | 74 |
| socks | 71 |
| http | 40 |
| hysteria | 13 |
| tuic | 10 |

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
| 83.85 | http | 188.5 | 486.3 | 23.41 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 83.85 | http | 188.8 | 489.7 | 23.41 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 83.8 | http | 190.8 | 491.6 | 23.36 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 83.79 | http | 191.3 | 497.4 | 23.35 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 82.18 | shadowsocks | 232.8 | 518.0 | 22.39 | 0.0 | 10.0 | 13.79 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 81.95 | shadowsocks | 242.7 | 571.1 | 22.16 | 0.0 | 10.0 | 13.79 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 81.66 | shadowsocks | 233.8 | 605.8 | 22.37 | 0.0 | 10.0 | 13.79 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 81.3 | trojan | 350.0 | 878.2 | 19.68 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 81.22 | shadowsocks | 274.4 | 643.2 | 21.43 | 0.0 | 10.0 | 13.79 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 80.79 | trojan | 220.0 | 495.2 | 22.69 | 0.0 | 6.48 | 14.12 | 20.0 | Au1rxx-base64 | natural-collie.rooster465.autos |
| 80.46 | shadowsocks | 285.5 | 737.3 | 21.17 | 0.0 | 10.0 | 13.79 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 80.41 | trojan | 235.2 | 541.0 | 22.33 | 0.0 | 6.46 | 14.12 | 20.0 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 80.35 | trojan | 285.2 | 668.5 | 21.18 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 44.242.235.129 |
| 79.71 | vless | 236.6 | 633.2 | 22.3 | 0.0 | 10.0 | 7.66 | 20.0 | Au1rxx-base64 | 70.39.178.231 |
| 79.67 | trojan | 223.1 | 499.7 | 22.61 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 79.42 | vless | 259.8 | 692.1 | 21.76 | 0.0 | 10.0 | 7.66 | 20.0 | Au1rxx-base64 | 186.241.106.97 |
| 79.25 | trojan | 237.3 | 535.8 | 22.28 | 0.0 | 6.5 | 14.12 | 20.0 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |
| 79.07 | vless | 188.9 | 493.0 | 23.41 | 0.0 | 10.0 | 7.66 | 20.0 | Au1rxx-base64 | 179.255.148.66 |
| 78.59 | trojan | 244.6 | 562.5 | 22.11 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 78.14 | hysteria2 | 342.1 | 718.6 | 19.86 | 0.0 | 10.0 | 13.2 | 20.0 | Au1rxx-base64 | 159.223.157.129 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.945 | 347 | 1540 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.726 | 0.648 | 142 | 6513 | prefer |
| DeltaKronecker-all | 0.438 | 0.355 | 107 | 5347 | observe |
| mheidari-all | 0.322 | 0.233 | 60 | 17775 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 123 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5450 | observe |
| Epodonios-all | 0.255 | None | 0 | 7127 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7538 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5322 | observe |
| barry-far-vless | 0.255 | None | 0 | 5644 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5127 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1540 | observe |
| nscl5-all | 0.235 | None | 0 | 1506 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 80 |
| speed | TimeoutError | - | 33 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 16 |
| 204 | ProxyError | - | 8 |
| 204 | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | status | 403 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
