# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-15 12:33:08 |
| 运行耗时 | 339.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 77476 |
| 去重后节点 | 22389 |
| TCP 可达 | 3000 |
| 真实可用 | 1032 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22389 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 12.7 |
| geo | 1.0 |
| tcp | 34.1 |
| probe | 65.7 |
| real_test | 193.1 |
| generate | 32.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42759 |
| trojan | 12283 |
| vmess | 10469 |
| shadowsocks | 10211 |
| hysteria2 | 1403 |
| http | 188 |
| socks | 75 |
| shadowsocksr | 73 |
| tuic | 8 |
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
| 85.07 | hysteria2 | 249.7 | 676.8 | 22.0 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 84.74 | hysteria2 | 268.3 | 692.2 | 21.57 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.64 | http | 247.4 | 633.4 | 22.05 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.31 |
| 83.44 | http | 256.0 | 647.3 | 21.85 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.10 |
| 83.32 | http | 261.4 | 672.5 | 21.73 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.23 |
| 83.2 | http | 266.4 | 686.3 | 21.61 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.4 |
| 83.19 | http | 266.7 | 693.1 | 21.6 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.33 |
| 83.15 | http | 268.6 | 697.8 | 21.56 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.25 |
| 83.14 | http | 269.2 | 701.1 | 21.55 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.27 |
| 83.12 | http | 270.0 | 699.1 | 21.53 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.9 |
| 83.11 | http | 270.2 | 694.0 | 21.52 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.15 |
| 83.05 | http | 273.1 | 718.1 | 21.46 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.8 |
| 82.96 | http | 276.8 | 715.1 | 21.37 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.21 |
| 82.92 | http | 278.4 | 717.8 | 21.33 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.28 |
| 82.9 | http | 279.3 | 727.3 | 21.31 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.19 |
| 82.9 | http | 279.6 | 733.6 | 21.31 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.39 |
| 82.87 | http | 280.5 | 729.0 | 21.28 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.5 |
| 82.85 | http | 281.6 | 738.3 | 21.26 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.11 |
| 82.8 | http | 283.6 | 727.5 | 21.21 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.41 |
| 81.73 | hysteria2 | 278.2 | 552.8 | 21.34 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 150.241.102.127 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.978 | 735 | 1659 | prefer |
| mheidari-all | 1.0 | 0.981 | 52 | 15977 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| DeltaKronecker-all | 0.783 | 0.708 | 72 | 5773 | prefer |
| Surfboard-tg-mixed | 0.741 | 0.664 | 119 | 5656 | prefer |
| nscl5-all | 0.438 | 1.0 | 3 | 2081 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 160 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5113 | observe |
| Epodonios-all | 0.255 | None | 0 | 6303 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7258 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4372 | observe |
| barry-far-vless | 0.255 | None | 0 | 4711 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3935 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 18 |
| speed | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 12 |
| geo | ClientOSError | - | 11 |
| geo | TimeoutError | - | 9 |
| 204 | ProxyError | - | 6 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
