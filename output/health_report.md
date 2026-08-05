# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-05 02:06:13 |
| 运行耗时 | 244.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86646 |
| 去重后节点 | 24381 |
| TCP 可达 | 3000 |
| 真实可用 | 562 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24381 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.1 |
| geo | 1.4 |
| tcp | 36.8 |
| probe | 50.8 |
| real_test | 117.5 |
| generate | 27.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51014 |
| vmess | 13090 |
| trojan | 10741 |
| shadowsocks | 10236 |
| hysteria2 | 1282 |
| socks | 78 |
| http | 77 |
| shadowsocksr | 74 |
| anytls | 21 |
| hysteria | 19 |
| tuic | 14 |

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
| 82.8 | vless | 182.6 | 460.3 | 23.55 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 70.39.198.93 |
| 82.79 | vless | 183.2 | 464.4 | 23.54 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 70.39.197.13 |
| 82.78 | vless | 183.3 | 451.7 | 23.53 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 70.39.178.231 |
| 82.57 | vless | 192.7 | 494.0 | 23.32 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 167.17.68.205 |
| 80.88 | vless | 265.4 | 745.1 | 21.63 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 66.175.217.170 |
| 79.69 | vless | 273.9 | 407.3 | 21.44 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 108.162.192.9 |
| 79.66 | vless | 318.2 | 856.1 | 20.41 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 64.49.38.6 |
| 79.45 | vless | 241.0 | 455.7 | 22.2 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 176.122.164.194 |
| 79.4 | trojan | 245.9 | 561.4 | 22.09 | 0.0 | 10.0 | 14.53 | 18.62 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 79.34 | hysteria2 | 268.7 | 342.3 | 21.56 | 2.16 | 9.94 | 14.32 | 18.62 | Au1rxx-base64 | 45.76.202.45 |
| 79.29 | trojan | 244.6 | 569.6 | 22.11 | 0.0 | 10.0 | 14.53 | 18.62 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 79.17 | trojan | 234.6 | 515.7 | 22.35 | 0.0 | 10.0 | 14.53 | 18.62 | Au1rxx-base64 | sincere-gelding.rooster465.autos |
| 78.83 | vless | 238.3 | 571.6 | 22.26 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 185.164.111.48 |
| 78.79 | vless | 328.2 | 809.2 | 20.18 | 0.0 | 10.0 | 10.63 | 18.62 | Au1rxx-base64 | 52.43.158.158 |
| 78.69 | http | 424.0 | 1188.9 | 17.96 | 0.0 | 10.0 | 14.43 | 19.3 | zhangkai | 138.199.35.199 |
| 78.63 | http | 426.7 | 1171.0 | 17.9 | 0.0 | 10.0 | 14.43 | 19.3 | zhangkai | 138.199.35.213 |
| 78.63 | http | 426.9 | 1193.2 | 17.9 | 0.0 | 10.0 | 14.43 | 19.3 | zhangkai | 138.199.35.200 |
| 78.6 | http | 427.9 | 1201.6 | 17.87 | 0.0 | 10.0 | 14.43 | 19.3 | zhangkai | 138.199.35.219 |
| 78.57 | http | 429.5 | 1189.1 | 17.84 | 0.0 | 10.0 | 14.43 | 19.3 | zhangkai | 138.199.35.217 |
| 78.52 | trojan | 246.4 | 573.9 | 22.07 | 0.0 | 10.0 | 14.53 | 18.62 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.959 | 411 | 1436 | prefer |
| zhangkai | 0.965 | 0.98 | 51 | 72 | prefer |
| Surfboard-tg-mixed | 0.62 | 0.54 | 174 | 5655 | observe |
| mheidari-all | 0.309 | 0.217 | 46 | 20244 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5251 | observe |
| Epodonios-all | 0.255 | None | 0 | 6252 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7229 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4478 | observe |
| barry-far-vless | 0.255 | None | 0 | 4815 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5141 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.239 | None | 0 | 1594 | observe |
| Au1rxx-clash | 0.232 | None | 0 | 1436 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 120 |
| cn-block | TimeoutError | - | 31 |
| speed | ClientOSError | - | 28 |
| speed | TimeoutError | - | 19 |
| geo | ClientOSError | - | 17 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 7 |
| 204 | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
