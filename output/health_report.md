# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-15 18:26:26 |
| 运行耗时 | 335.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 78589 |
| 去重后节点 | 22397 |
| TCP 可达 | 3000 |
| 真实可用 | 1021 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22397 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.4 |
| geo | 0.7 |
| tcp | 34.1 |
| probe | 68.3 |
| real_test | 193.5 |
| generate | 29.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43026 |
| trojan | 13418 |
| vmess | 10695 |
| shadowsocks | 10011 |
| hysteria2 | 1070 |
| http | 189 |
| socks | 87 |
| shadowsocksr | 76 |
| tuic | 10 |
| hysteria | 7 |

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
| 84.04 | hysteria2 | 261.5 | 664.5 | 21.72 | 0.0 | 10.0 | 13.42 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 83.72 | hysteria2 | 279.9 | 728.6 | 21.3 | 0.0 | 10.0 | 13.42 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.14 | http | 280.5 | 667.9 | 21.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 82.75 | vless | 220.6 | 596.9 | 22.67 | 0.0 | 8.92 | 11.16 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 82.1 | http | 291.0 | 701.1 | 21.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 81.81 | shadowsocks | 259.6 | 625.1 | 21.77 | 0.0 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.79 | shadowsocks | 260.6 | 625.2 | 21.75 | 0.0 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 81.74 | vless | 264.8 | 687.8 | 21.65 | 0.0 | 8.93 | 11.16 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 81.62 | vless | 269.6 | 750.0 | 21.54 | 0.0 | 8.92 | 11.16 | 20.0 | Au1rxx-base64 | 195.211.99.45 |
| 81.62 | http | 290.8 | 713.9 | 21.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 81.62 | http | 303.0 | 743.1 | 20.76 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 81.45 | http | 347.9 | 876.9 | 19.72 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 81.17 | http | 296.0 | 706.7 | 20.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 81.08 | http | 369.6 | 920.9 | 19.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 80.93 | http | 362.4 | 905.7 | 19.39 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 80.89 | vless | 258.2 | 638.8 | 21.8 | 0.0 | 8.93 | 11.16 | 20.0 | Au1rxx-base64 | 198.251.78.29 |
| 80.72 | http | 354.7 | 891.2 | 19.57 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 80.69 | http | 302.5 | 739.3 | 20.77 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 80.56 | http | 359.6 | 885.3 | 19.45 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 80.48 | shadowsocks | 277.7 | 720.5 | 21.35 | 0.0 | 9.09 | 14.04 | 20.0 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.971 | 691 | 1997 | prefer |
| zhangkai | 0.991 | 0.992 | 127 | 159 | prefer |
| mheidari-all | 0.967 | 0.891 | 184 | 16339 | prefer |
| Surfboard-tg-mixed | 0.898 | 0.833 | 42 | 5620 | prefer |
| DeltaKronecker-all | 0.79 | 0.724 | 29 | 5773 | prefer |
| nscl5-all | 0.349 | 0.667 | 3 | 2081 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 160 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5113 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1997 | observe |
| Epodonios-all | 0.255 | None | 0 | 6266 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7464 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4366 | observe |
| barry-far-vless | 0.255 | None | 0 | 4694 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 13 |
| geo | TimeoutError | - | 9 |
| speed | TimeoutError | - | 8 |
| cn-block | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| geo | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
