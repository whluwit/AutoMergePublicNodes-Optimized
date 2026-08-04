# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-04 19:28:50 |
| 运行耗时 | 237.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86061 |
| 去重后节点 | 24512 |
| TCP 可达 | 3000 |
| 真实可用 | 478 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24512 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.2 |
| tcp | 37.4 |
| probe | 52.0 |
| real_test | 110.3 |
| generate | 29.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51289 |
| vmess | 13127 |
| shadowsocks | 10205 |
| trojan | 10003 |
| hysteria2 | 1168 |
| socks | 80 |
| shadowsocksr | 69 |
| http | 67 |
| anytls | 21 |
| hysteria | 19 |
| tuic | 13 |

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
| 79.78 | trojan | 258.8 | 622.0 | 21.79 | 0.0 | 10.0 | 13.7 | 18.04 | Au1rxx-base64 | 163.245.196.68 |
| 78.47 | shadowsocks | 238.6 | 611.2 | 22.26 | 0.0 | 10.0 | 12.17 | 18.04 | Au1rxx-base64 | 156.146.38.167 |
| 78.41 | shadowsocks | 241.1 | 620.5 | 22.2 | 0.0 | 10.0 | 12.17 | 18.04 | Au1rxx-base64 | 156.146.38.169 |
| 78.39 | shadowsocks | 241.7 | 619.9 | 22.18 | 0.0 | 10.0 | 12.17 | 18.04 | Au1rxx-base64 | 156.146.38.170 |
| 78.03 | shadowsocks | 257.3 | 608.9 | 21.82 | 0.0 | 10.0 | 12.17 | 18.04 | Au1rxx-base64 | 156.146.38.168 |
| 77.66 | http | 444.8 | 1145.7 | 17.48 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.198 |
| 77.4 | hysteria2 | 316.6 | 711.2 | 20.45 | 0.0 | 10.0 | 12.75 | 18.04 | Au1rxx-base64 | 159.223.157.129 |
| 76.86 | http | 450.4 | 1158.2 | 17.35 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.199 |
| 76.82 | http | 441.9 | 1137.3 | 17.55 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.217 |
| 76.66 | http | 447.6 | 1153.7 | 17.42 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.200 |
| 76.34 | http | 451.8 | 1163.5 | 17.32 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.207 |
| 75.92 | http | 446.7 | 1152.5 | 17.44 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.219 |
| 75.89 | http | 447.3 | 1153.7 | 17.42 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.213 |
| 74.96 | http | 451.4 | 1161.0 | 17.33 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.214 |
| 74.82 | hysteria2 | 331.6 | 721.8 | 20.1 | 0.0 | 10.0 | 12.75 | 18.04 | Au1rxx-base64 | 138.124.68.188 |
| 74.75 | shadowsocks | 271.3 | 545.6 | 21.5 | 0.0 | 10.0 | 12.17 | 18.04 | Au1rxx-base64 | 173.244.56.9 |
| 74.58 | vless | 282.1 | 574.2 | 21.25 | 0.0 | 10.0 | 9.62 | 18.04 | Au1rxx-base64 | 167.17.68.205 |
| 74.49 | trojan | 283.7 | 698.3 | 21.21 | 0.0 | 10.0 | 13.7 | 18.04 | Au1rxx-base64 | 64.94.95.115 |
| 74.41 | shadowsocks | 264.7 | 560.5 | 21.65 | 0.0 | 10.0 | 12.17 | 18.04 | Au1rxx-base64 | 173.244.56.6 |
| 73.96 | trojan | 326.5 | 844.3 | 20.22 | 0.0 | 10.0 | 13.7 | 18.04 | Au1rxx-base64 | 64.94.95.114 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.965 | 0.98 | 51 | 72 | prefer |
| Au1rxx-base64 | 0.931 | 0.87 | 431 | 1560 | prefer |
| Surfboard-tg-mixed | 0.586 | 0.506 | 77 | 5570 | observe |
| DeltaKronecker-all | 0.474 | 0.6 | 10 | 5788 | observe |
| mheidari-all | 0.461 | 0.545 | 11 | 19967 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 58 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5251 | observe |
| Epodonios-all | 0.255 | None | 0 | 6154 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6965 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4451 | observe |
| barry-far-vless | 0.255 | None | 0 | 4787 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5141 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 4655 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 22 |
| geo | TimeoutError | - | 21 |
| geo | ClientOSError | - | 20 |
| 204 | ProxyError | - | 15 |
| cn-block | TimeoutError | - | 7 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
