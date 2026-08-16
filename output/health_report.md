# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-16 18:26:20 |
| 运行耗时 | 332.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 79830 |
| 去重后节点 | 21997 |
| TCP 可达 | 3000 |
| 真实可用 | 1071 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21997 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.1 |
| tcp | 33.1 |
| probe | 62.2 |
| real_test | 192.5 |
| generate | 37.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43749 |
| trojan | 14361 |
| vmess | 10862 |
| shadowsocks | 9374 |
| hysteria2 | 1146 |
| http | 170 |
| socks | 75 |
| shadowsocksr | 74 |
| tuic | 10 |
| hysteria | 7 |
| anytls | 2 |

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
| 83.28 | vless | 223.5 | 601.9 | 22.6 | 0.0 | 9.75 | 10.93 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 83.2 | vless | 222.9 | 601.4 | 22.62 | 0.0 | 9.65 | 10.93 | 20.0 | Au1rxx-base64 | 195.211.99.45 |
| 82.28 | http | 309.8 | 716.7 | 20.61 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 82.09 | vless | 286.0 | 691.7 | 21.16 | 0.0 | 10.0 | 10.93 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 82.03 | http | 282.6 | 678.9 | 21.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 81.68 | http | 306.5 | 752.0 | 20.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 81.37 | http | 355.6 | 905.7 | 19.55 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 81.32 | http | 305.2 | 730.5 | 20.71 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 81.19 | vless | 324.6 | 868.4 | 20.26 | 0.0 | 10.0 | 10.93 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 81.12 | hysteria2 | 264.4 | 662.4 | 21.66 | 0.0 | 10.0 | 12.86 | 17.7 | mheidari-all | 159.223.157.129 |
| 81.08 | http | 351.0 | 866.1 | 19.65 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 81.07 | trojan | 370.9 | 923.0 | 19.19 | 0.0 | 10.0 | 14.88 | 20.0 | Au1rxx-base64 | 64.74.163.118 |
| 80.75 | http | 352.0 | 886.0 | 19.63 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 80.67 | hysteria2 | 288.3 | 740.6 | 21.11 | 0.0 | 10.0 | 12.86 | 17.7 | mheidari-all | 138.124.68.188 |
| 80.24 | http | 358.9 | 920.6 | 19.47 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 80.19 | shadowsocks | 321.2 | 834.3 | 20.34 | 0.0 | 9.59 | 14.26 | 20.0 | Au1rxx-base64 | 142.4.216.225 |
| 80.14 | http | 291.3 | 714.0 | 21.03 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 80.02 | http | 339.6 | 857.6 | 19.92 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 79.68 | shadowsocks | 265.2 | 678.3 | 21.64 | 0.0 | 9.78 | 14.26 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 79.62 | shadowsocks | 264.1 | 670.4 | 21.66 | 0.0 | 10.0 | 14.26 | 17.7 | mheidari-all | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.954 | 765 | 1997 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.933 | 0.86 | 114 | 5794 | prefer |
| mheidari-all | 0.856 | 0.779 | 145 | 17005 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.287 | 0.5 | 2 | 4990 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 174 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1997 | observe |
| Epodonios-all | 0.255 | None | 0 | 6468 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3985 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7449 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4518 | observe |
| barry-far-vless | 0.255 | None | 0 | 4856 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4025 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 17 |
| speed | TimeoutError | - | 15 |
| geo | TimeoutError | - | 11 |
| 204 | ProxyError | - | 9 |
| geo | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 6 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
