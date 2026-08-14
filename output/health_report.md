# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-14 18:51:49 |
| 运行耗时 | 318.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78224 |
| 去重后节点 | 22433 |
| TCP 可达 | 3000 |
| 真实可用 | 816 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22433 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 11.5 |
| geo | 1.1 |
| tcp | 34.9 |
| probe | 65.5 |
| real_test | 167.4 |
| generate | 37.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44237 |
| trojan | 11694 |
| vmess | 10391 |
| shadowsocks | 10247 |
| hysteria2 | 1319 |
| http | 168 |
| socks | 77 |
| shadowsocksr | 72 |
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
| 83.9 | hysteria2 | 267.6 | 725.5 | 21.58 | 0.0 | 10.0 | 13.42 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 83.77 | hysteria2 | 277.5 | 749.3 | 21.35 | 0.0 | 10.0 | 13.42 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.73 | http | 255.1 | 677.3 | 21.87 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.71 | http | 256.2 | 679.5 | 21.85 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 83.67 | http | 257.9 | 678.5 | 21.81 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 83.58 | http | 261.8 | 688.2 | 21.72 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.57 | http | 261.9 | 700.1 | 21.71 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 83.52 | http | 264.1 | 699.8 | 21.66 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 83.44 | vless | 249.9 | 677.1 | 21.99 | 0.0 | 10.0 | 11.45 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 83.34 | http | 272.2 | 722.0 | 21.48 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.26 | vless | 258.0 | 681.8 | 21.81 | 0.0 | 10.0 | 11.45 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 83.24 | http | 276.6 | 718.3 | 21.38 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 83.23 | http | 276.8 | 724.7 | 21.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 83.21 | http | 277.9 | 720.5 | 21.35 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 83.17 | http | 279.4 | 723.4 | 21.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 82.69 | vless | 282.4 | 695.8 | 21.24 | 0.0 | 10.0 | 11.45 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 82.42 | http | 311.6 | 851.4 | 20.56 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 81.87 | vless | 271.1 | 629.2 | 21.5 | 0.0 | 10.0 | 11.45 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 81.28 | http | 319.1 | 873.2 | 20.39 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 81.19 | shadowsocks | 274.2 | 746.8 | 21.43 | 0.0 | 10.0 | 13.76 | 20.0 | Au1rxx-base64 | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Au1rxx-base64 | 0.98 | 0.913 | 676 | 1715 | prefer |
| DeltaKronecker-all | 0.673 | 0.596 | 52 | 5969 | observe |
| Surfboard-tg-mixed | 0.665 | 0.587 | 63 | 5725 | observe |
| mheidari-all | 0.438 | 1.0 | 3 | 15859 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 145 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5157 | observe |
| Epodonios-all | 0.255 | None | 0 | 6388 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7685 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4488 | observe |
| barry-far-vless | 0.255 | None | 0 | 4814 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3992 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.246 | None | 0 | 1768 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 37 |
| geo | ClientOSError | - | 16 |
| geo | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 11 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 9 |
| speed | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
