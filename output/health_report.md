# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-13 13:03:06 |
| 运行耗时 | 295.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79755 |
| 去重后节点 | 22396 |
| TCP 可达 | 3000 |
| 真实可用 | 763 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22396 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.2 |
| tcp | 33.2 |
| probe | 56.1 |
| real_test | 162.0 |
| generate | 37.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43816 |
| vmess | 13403 |
| trojan | 11168 |
| shadowsocks | 9886 |
| hysteria2 | 1151 |
| http | 160 |
| socks | 77 |
| shadowsocksr | 77 |
| tuic | 8 |
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
| 84.18 | http | 235.8 | 615.4 | 22.32 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 84.17 | http | 236.0 | 632.0 | 22.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 84.13 | http | 238.0 | 635.3 | 22.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 84.12 | http | 238.6 | 635.4 | 22.26 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 84.11 | http | 238.7 | 640.7 | 22.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 84.1 | http | 239.1 | 637.1 | 22.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.92 | http | 247.2 | 666.3 | 22.06 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.84 | http | 250.4 | 664.5 | 21.98 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 83.82 | http | 251.1 | 674.4 | 21.96 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 83.75 | http | 254.2 | 683.8 | 21.89 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 83.73 | http | 255.2 | 676.6 | 21.87 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.69 | http | 256.9 | 688.1 | 21.83 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 82.95 | hysteria2 | 299.1 | 825.1 | 20.85 | 0.0 | 10.0 | 13.57 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 82.49 | shadowsocks | 233.4 | 631.3 | 22.38 | 0.0 | 10.0 | 14.11 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 82.26 | hysteria2 | 349.3 | 821.8 | 19.69 | 0.0 | 10.0 | 13.57 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 82.25 | http | 319.2 | 873.5 | 20.39 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 81.61 | http | 347.0 | 953.9 | 19.75 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 81.55 | http | 349.4 | 969.8 | 19.69 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 81.45 | http | 353.9 | 956.2 | 19.59 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 81.43 | http | 354.4 | 794.8 | 19.57 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.94 | 520 | 1576 | prefer |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Surfboard-tg-mixed | 0.838 | 0.763 | 118 | 5953 | prefer |
| mheidari-all | 0.688 | 0.61 | 77 | 17032 | observe |
| DeltaKronecker-all | 0.547 | 0.5 | 18 | 4878 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5203 | observe |
| Epodonios-all | 0.255 | None | 0 | 6610 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7445 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4665 | observe |
| barry-far-vless | 0.255 | None | 0 | 5031 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5197 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.241 | None | 0 | 1654 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1576 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 17 |
| geo | TimeoutError | - | 14 |
| geo | ClientOSError | - | 13 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
