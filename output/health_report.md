# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-08 12:41:26 |
| 运行耗时 | 249.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83601 |
| 去重后节点 | 23622 |
| TCP 可达 | 3000 |
| 真实可用 | 466 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23622 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 35.3 |
| probe | 53.5 |
| real_test | 111.1 |
| generate | 42.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49123 |
| vmess | 12902 |
| trojan | 10498 |
| shadowsocks | 9568 |
| hysteria2 | 1314 |
| shadowsocksr | 73 |
| socks | 63 |
| http | 36 |
| hysteria | 13 |
| tuic | 10 |
| anytls | 1 |

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
| 82.81 | shadowsocks | 219.1 | 530.3 | 22.71 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 82.74 | shadowsocks | 221.9 | 524.7 | 22.64 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 82.68 | shadowsocks | 224.4 | 529.2 | 22.58 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 82.55 | trojan | 231.9 | 533.8 | 22.41 | 0.0 | 10.0 | 12.64 | 20.0 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 82.42 | trojan | 237.4 | 548.1 | 22.28 | 0.0 | 10.0 | 12.64 | 20.0 | Au1rxx-base64 | 35.86.90.51 |
| 81.83 | shadowsocks | 239.5 | 619.1 | 22.23 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 81.73 | trojan | 267.3 | 635.9 | 21.59 | 0.0 | 10.0 | 12.64 | 20.0 | Au1rxx-base64 | 44.242.235.129 |
| 81.72 | shadowsocks | 244.3 | 627.5 | 22.12 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 81.69 | trojan | 269.1 | 641.8 | 21.55 | 0.0 | 10.0 | 12.64 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 81.6 | trojan | 232.4 | 532.8 | 22.4 | 0.0 | 10.0 | 12.64 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 79.27 | hysteria2 | 338.3 | 734.7 | 19.95 | 0.0 | 10.0 | 13.93 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 79.14 | trojan | 219.2 | 477.7 | 22.7 | 0.0 | 6.3 | 12.64 | 20.0 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |
| 78.99 | http | 398.8 | 1119.4 | 18.55 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 78.94 | http | 401.0 | 1129.4 | 18.5 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 78.88 | http | 403.2 | 1136.7 | 18.44 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 78.87 | http | 403.9 | 1135.4 | 18.43 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 78.69 | trojan | 241.8 | 561.9 | 22.18 | 0.0 | 6.37 | 12.64 | 20.0 | Au1rxx-base64 | natural-collie.rooster465.autos |
| 78.14 | shadowsocks | 288.3 | 651.8 | 21.1 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 77.97 | shadowsocks | 282.9 | 635.2 | 21.23 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 77.9 | hysteria2 | 356.0 | 723.2 | 19.54 | 0.0 | 10.0 | 13.93 | 20.0 | Au1rxx-base64 | 159.223.157.129 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | 0.933 | 344 | 1488 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| DeltaKronecker-all | 0.569 | 0.489 | 231 | 5347 | observe |
| Surfboard-tg-mixed | 0.547 | 0.778 | 9 | 6590 | observe |
| mheidari-all | 0.4 | 0.75 | 4 | 17827 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 196 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5450 | observe |
| Epodonios-all | 0.255 | None | 0 | 7202 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7636 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5299 | observe |
| barry-far-vless | 0.255 | None | 0 | 5747 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5162 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 29 |
| 204 | TimeoutError | - | 24 |
| 204 | ProxyError | - | 23 |
| geo | TimeoutError | - | 22 |
| speed | ClientOSError | - | 13 |
| speed | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
