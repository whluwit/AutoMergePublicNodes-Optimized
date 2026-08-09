# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-09 12:43:43 |
| 运行耗时 | 257.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85466 |
| 去重后节点 | 23881 |
| TCP 可达 | 3000 |
| 真实可用 | 463 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23881 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 12.3 |
| geo | 1.4 |
| tcp | 36.1 |
| probe | 55.1 |
| real_test | 107.2 |
| generate | 45.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51193 |
| vmess | 13124 |
| trojan | 9945 |
| shadowsocks | 9524 |
| hysteria2 | 1447 |
| shadowsocksr | 72 |
| socks | 68 |
| http | 39 |
| anytls | 26 |
| hysteria | 16 |
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
| 82.74 | shadowsocks | 197.2 | 529.2 | 23.21 | 0.0 | 9.4 | 14.39 | 19.74 | Au1rxx-base64 | 149.22.95.183 |
| 82.42 | trojan | 198.8 | 468.6 | 23.18 | 0.0 | 9.17 | 12.83 | 19.74 | Au1rxx-base64 | 44.242.235.129 |
| 82.07 | trojan | 214.9 | 516.4 | 22.8 | 0.0 | 9.2 | 12.83 | 19.74 | Au1rxx-base64 | 44.244.3.114 |
| 81.06 | trojan | 258.2 | 651.9 | 21.8 | 0.0 | 9.19 | 12.83 | 19.74 | Au1rxx-base64 | 44.246.163.102 |
| 79.4 | shadowsocks | 256.7 | 265.1 | 21.83 | 5.06 | 9.4 | 14.39 | 19.74 | Au1rxx-base64 | 149.22.87.241 |
| 79.33 | http | 260.1 | 553.8 | 21.76 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.214 |
| 78.73 | vless | 247.6 | 539.8 | 22.05 | 0.0 | 10.0 | 8.26 | 19.74 | Au1rxx-base64 | 179.255.148.66 |
| 78.51 | http | 259.1 | 543.6 | 21.78 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.199 |
| 78.34 | http | 261.2 | 553.1 | 21.73 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.217 |
| 78.11 | trojan | 209.6 | 504.0 | 22.93 | 0.0 | 5.11 | 12.83 | 19.74 | Au1rxx-base64 | natural-collie.rooster465.autos |
| 77.93 | http | 257.0 | 546.6 | 21.83 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.207 |
| 77.75 | vless | 253.3 | 549.5 | 21.91 | 0.0 | 10.0 | 8.26 | 19.74 | Au1rxx-base64 | 186.241.106.97 |
| 77.72 | shadowsocks | 266.6 | 565.8 | 21.61 | 0.0 | 9.59 | 14.39 | 19.74 | Au1rxx-base64 | 173.244.56.6 |
| 77.62 | shadowsocks | 269.2 | 559.8 | 21.55 | 0.0 | 9.41 | 14.39 | 19.74 | Au1rxx-base64 | 173.244.56.9 |
| 77.26 | vless | 256.3 | 552.0 | 21.84 | 0.0 | 10.0 | 8.26 | 19.74 | Au1rxx-base64 | 167.17.68.205 |
| 76.7 | shadowsocks | 258.0 | 263.8 | 21.81 | 5.11 | 9.58 | 14.39 | 19.74 | Au1rxx-base64 | 149.22.87.204 |
| 76.38 | hysteria2 | 342.4 | 707.6 | 19.85 | 0.0 | 9.21 | 12.6 | 19.74 | Au1rxx-base64 | 159.223.157.129 |
| 76.34 | trojan | 312.0 | 316.2 | 20.55 | 3.14 | 10.0 | 12.83 | 19.74 | Au1rxx-base64 | 3.112.15.214 |
| 76.29 | trojan | 312.1 | 315.7 | 20.55 | 3.16 | 10.0 | 12.83 | 19.74 | Au1rxx-base64 | 13.231.232.184 |
| 76.25 | hysteria2 | 348.6 | 759.1 | 19.71 | 0.0 | 9.3 | 12.6 | 19.74 | Au1rxx-base64 | 138.124.68.188 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | 0.914 | 409 | 1704 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.622 | 0.543 | 94 | 6537 | observe |
| mheidari-all | 0.587 | 0.526 | 19 | 20170 | observe |
| DeltaKronecker-all | 0.388 | 0.292 | 24 | 4998 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 77 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5505 | observe |
| Epodonios-all | 0.255 | None | 0 | 7128 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7369 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5349 | observe |
| barry-far-vless | 0.255 | None | 0 | 5659 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5130 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1704 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 20 |
| speed | TimeoutError | - | 14 |
| 204 | ProxyError | - | 11 |
| geo | ClientOSError | - | 10 |
| speed | ClientOSError | - | 8 |
| geo | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
