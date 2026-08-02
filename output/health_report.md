# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-02 08:19:51 |
| 运行耗时 | 340.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 77306 |
| 去重后节点 | 22691 |
| TCP 可达 | 3000 |
| 真实可用 | 781 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22691 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.6 |
| tcp | 34.5 |
| probe | 63.3 |
| real_test | 189.6 |
| generate | 45.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45704 |
| vmess | 12280 |
| shadowsocks | 10224 |
| trojan | 8128 |
| hysteria2 | 606 |
| http | 165 |
| socks | 79 |
| shadowsocksr | 72 |
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
| 82.02 | hysteria2 | 254.3 | 681.5 | 21.89 | 0.0 | 8.69 | 13.7 | 18.74 | Au1rxx-base64 | 138.124.68.188 |
| 81.15 | hysteria2 | 252.4 | 683.9 | 21.94 | 0.0 | 7.77 | 13.7 | 18.74 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 80.68 | hysteria2 | 307.8 | 856.5 | 20.65 | 0.0 | 8.69 | 13.7 | 18.74 | Au1rxx-base64 | 159.223.157.129 |
| 80.43 | http | 399.6 | 1096.8 | 18.53 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.7 |
| 80.37 | http | 402.1 | 1101.5 | 18.47 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.21 |
| 80.37 | http | 402.1 | 1088.8 | 18.47 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.20 |
| 80.11 | http | 413.3 | 1136.5 | 18.21 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.23 |
| 80.04 | http | 416.3 | 1133.3 | 18.14 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.25 |
| 79.93 | http | 421.2 | 1150.3 | 18.03 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.8 |
| 79.92 | http | 421.3 | 1151.5 | 18.02 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.5 |
| 79.76 | shadowsocks | 240.9 | 652.4 | 22.2 | 0.0 | 8.75 | 14.07 | 18.74 | Au1rxx-base64 | 37.19.198.160 |
| 79.66 | shadowsocks | 245.7 | 665.4 | 22.09 | 0.0 | 8.76 | 14.07 | 18.74 | Au1rxx-base64 | 37.19.198.236 |
| 79.5 | shadowsocks | 252.1 | 685.1 | 21.94 | 0.0 | 8.75 | 14.07 | 18.74 | Au1rxx-base64 | 37.19.198.243 |
| 78.88 | shadowsocks | 235.8 | 634.5 | 22.32 | 0.0 | 8.75 | 14.07 | 18.74 | Au1rxx-base64 | 37.19.198.244 |
| 77.58 | vless | 262.7 | 664.5 | 21.7 | 0.0 | 10.0 | 7.14 | 18.74 | Au1rxx-base64 | 167.17.69.171 |
| 77.25 | vless | 276.8 | 703.2 | 21.37 | 0.0 | 10.0 | 7.14 | 18.74 | Au1rxx-base64 | 169.40.42.179 |
| 77.11 | shadowsocks | 284.4 | 652.6 | 21.2 | 0.0 | 8.75 | 14.07 | 18.74 | Au1rxx-base64 | 156.146.38.169 |
| 76.71 | shadowsocks | 276.6 | 626.1 | 21.38 | 0.0 | 8.75 | 14.07 | 18.74 | Au1rxx-base64 | 156.146.38.170 |
| 76.32 | http | 329.5 | 604.4 | 20.15 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.217 |
| 76.24 | http | 331.4 | 607.8 | 20.11 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.220 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 0.982 | 219 | 344 | prefer |
| Au1rxx-base64 | 0.846 | 0.783 | 540 | 1589 | prefer |
| Surfboard-tg-mixed | 0.675 | 0.597 | 119 | 5162 | observe |
| DeltaKronecker-all | 0.34 | 0.258 | 267 | 4549 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5486 | observe |
| Epodonios-all | 0.255 | None | 0 | 5764 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3969 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6688 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4025 | observe |
| barry-far-vless | 0.255 | None | 0 | 4406 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5071 | observe |
| mheidari-all | 0.255 | 0.222 | 9 | 16553 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1589 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 157 |
| speed | TimeoutError | - | 71 |
| speed | ClientOSError | - | 48 |
| 204 | TimeoutError | - | 31 |
| geo | ClientOSError | - | 28 |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyError | - | 10 |
| 204 | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| speed | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
