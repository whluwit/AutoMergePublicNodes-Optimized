# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-18 18:36:39 |
| 运行耗时 | 365.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 93063 |
| 去重后节点 | 24078 |
| TCP 可达 | 3000 |
| 真实可用 | 1172 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24078 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.1 |
| tcp | 36.6 |
| probe | 74.6 |
| real_test | 220.1 |
| generate | 27.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52167 |
| trojan | 18683 |
| shadowsocks | 10568 |
| vmess | 9568 |
| hysteria2 | 1523 |
| http | 179 |
| socks | 154 |
| shadowsocksr | 147 |
| anytls | 46 |
| tuic | 15 |
| hysteria | 13 |

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
| 81.26 | http | 287.8 | 691.6 | 21.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 81.18 | http | 291.7 | 685.1 | 21.03 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 81.14 | http | 291.8 | 693.5 | 21.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 81.04 | http | 306.5 | 722.9 | 20.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 80.93 | http | 290.1 | 683.8 | 21.06 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 80.78 | http | 290.6 | 684.1 | 21.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 80.67 | http | 304.8 | 720.5 | 20.72 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 80.49 | http | 367.6 | 919.0 | 19.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 80.41 | trojan | 290.8 | 685.4 | 21.05 | 0.0 | 10.0 | 14.75 | 20.0 | mheidari-all | 64.94.95.115 |
| 80.37 | http | 306.9 | 729.7 | 20.67 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 80.32 | http | 296.1 | 699.0 | 20.92 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 80.12 | http | 303.2 | 731.4 | 20.76 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 79.89 | http | 367.6 | 911.4 | 19.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 79.84 | http | 305.8 | 731.0 | 20.7 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 79.83 | http | 360.7 | 865.4 | 19.43 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 79.43 | http | 360.6 | 897.7 | 19.43 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 79.28 | trojan | 295.9 | 697.5 | 20.93 | 0.0 | 10.0 | 14.75 | 20.0 | mheidari-all | 64.94.95.114 |
| 79.17 | http | 352.4 | 865.4 | 19.62 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 79.12 | trojan | 337.9 | 816.0 | 19.96 | 0.0 | 10.0 | 14.75 | 20.0 | mheidari-all | 64.94.95.117 |
| 78.98 | http | 363.8 | 898.6 | 19.36 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.991 | 644 | 1643 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.922 | 0.844 | 461 | 22150 | prefer |
| Surfboard-tg-mixed | 0.801 | 1.0 | 13 | 6301 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 2992 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6329 | observe |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 5725 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5068 | observe |
| Epodonios-all | 0.255 | None | 0 | 6927 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7150 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4855 | observe |
| barry-far-vless | 0.255 | None | 0 | 5149 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4035 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 35 |
| speed | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| geo | TimeoutError | - | 6 |
| cn-block | TimeoutError | - | 5 |
| speed | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
