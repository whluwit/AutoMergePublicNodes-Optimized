# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-10 13:00:29 |
| 运行耗时 | 233.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 87155 |
| 去重后节点 | 24814 |
| TCP 可达 | 3000 |
| 真实可用 | 497 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24814 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.3 |
| tcp | 35.4 |
| probe | 49.5 |
| real_test | 104.8 |
| generate | 35.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52434 |
| vmess | 13396 |
| trojan | 10021 |
| shadowsocks | 9710 |
| hysteria2 | 1367 |
| shadowsocksr | 76 |
| socks | 63 |
| http | 40 |
| anytls | 26 |
| hysteria | 14 |
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
| 83.79 | http | 191.2 | 483.0 | 23.35 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 83.73 | http | 193.7 | 497.8 | 23.29 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 83.68 | http | 195.9 | 508.3 | 23.24 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 83.17 | http | 218.2 | 577.0 | 22.73 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 80.05 | trojan | 237.3 | 546.7 | 22.29 | 0.0 | 10.0 | 12.68 | 17.58 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 79.98 | trojan | 240.2 | 553.0 | 22.22 | 0.0 | 10.0 | 12.68 | 17.58 | Au1rxx-base64 | 44.244.3.114 |
| 79.88 | trojan | 244.6 | 563.2 | 22.12 | 0.0 | 10.0 | 12.68 | 17.58 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 79.67 | trojan | 221.3 | 494.1 | 22.66 | 0.0 | 9.25 | 12.68 | 17.58 | Au1rxx-base64 | 44.246.163.102 |
| 79.64 | trojan | 222.2 | 501.9 | 22.63 | 0.0 | 9.25 | 12.68 | 17.58 | Au1rxx-base64 | 35.86.90.51 |
| 79.58 | trojan | 218.1 | 491.7 | 22.73 | 0.0 | 9.09 | 12.68 | 17.58 | Au1rxx-base64 | natural-collie.rooster465.autos |
| 79.31 | vless | 186.2 | 468.1 | 23.47 | 0.0 | 10.0 | 8.26 | 17.58 | Au1rxx-base64 | 186.241.106.97 |
| 79.31 | vless | 186.3 | 483.9 | 23.47 | 0.0 | 10.0 | 8.26 | 17.58 | Au1rxx-base64 | 179.255.148.66 |
| 78.92 | shadowsocks | 186.8 | 482.3 | 23.45 | 0.0 | 9.23 | 13.16 | 17.58 | Au1rxx-base64 | 108.181.118.10 |
| 78.9 | vless | 203.7 | 537.2 | 23.06 | 0.0 | 10.0 | 8.26 | 17.58 | Au1rxx-base64 | jyvlryz.cvewfjg.shop |
| 78.76 | shadowsocks | 193.7 | 467.9 | 23.29 | 0.0 | 9.23 | 13.16 | 17.58 | Au1rxx-base64 | 108.181.0.177 |
| 78.59 | vless | 217.0 | 560.6 | 22.75 | 0.0 | 10.0 | 8.26 | 17.58 | Au1rxx-base64 | 172.247.109.66 |
| 78.19 | vless | 234.5 | 625.0 | 22.35 | 0.0 | 10.0 | 8.26 | 17.58 | Au1rxx-base64 | 70.39.197.13 |
| 78.07 | vless | 206.7 | 540.8 | 22.99 | 0.0 | 9.24 | 8.26 | 17.58 | Au1rxx-base64 | 167.17.68.205 |
| 77.63 | shadowsocks | 264.1 | 654.0 | 21.66 | 0.0 | 9.23 | 13.16 | 17.58 | Au1rxx-base64 | 173.244.56.9 |
| 77.45 | shadowsocks | 272.2 | 638.7 | 21.48 | 0.0 | 9.23 | 13.16 | 17.58 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | 0.909 | 463 | 1696 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| DeltaKronecker-all | 0.673 | 0.6 | 25 | 5881 | observe |
| Surfboard-tg-mixed | 0.636 | 0.558 | 52 | 6528 | observe |
| mheidari-all | 0.425 | 0.4 | 15 | 20526 | observe |
| tg-oneclickvpnkeys | 0.405 | 1.0 | 4 | 122 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7165 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5435 | observe |
| barry-far-vless | 0.255 | None | 0 | 5695 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5191 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 18 |
| speed | TimeoutError | - | 11 |
| geo | ClientOSError | - | 10 |
| 204 | ProxyError | - | 10 |
| geo | TimeoutError | - | 8 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
