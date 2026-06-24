# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-24 02:52:31 |
| 运行耗时 | 241.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 76548 |
| 去重后节点 | 22515 |
| TCP 可达 | 3000 |
| 真实可用 | 568 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22515 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 29.4 |
| probe | 53.9 |
| real_test | 129.8 |
| generate | 22.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45332 |
| trojan | 10548 |
| vmess | 10163 |
| shadowsocks | 9854 |
| hysteria2 | 234 |
| shadowsocksr | 164 |
| http | 159 |
| socks | 86 |
| hysteria | 6 |
| tuic | 2 |

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
| 75.91 | shadowsocks | 246.2 | 644.5 | 22.08 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 156.146.38.167 |
| 75.73 | shadowsocks | 250.5 | 648.0 | 21.98 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 156.146.38.170 |
| 75.67 | shadowsocks | 251.3 | 618.9 | 21.96 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 156.146.38.168 |
| 73.5 | shadowsocks | 300.8 | 692.6 | 20.82 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 37.19.198.243 |
| 72.76 | shadowsocks | 299.9 | 702.8 | 20.84 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 37.19.198.236 |
| 72.43 | shadowsocks | 298.7 | 679.0 | 20.86 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 37.19.198.160 |
| 72.07 | shadowsocks | 304.1 | 701.1 | 20.74 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 37.19.198.244 |
| 70.85 | shadowsocks | 248.7 | 608.5 | 22.02 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 156.146.38.169 |
| 69.98 | shadowsocks | 349.7 | 793.2 | 19.68 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 216.105.168.18 |
| 69.84 | shadowsocks | 330.1 | 694.9 | 20.14 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 173.244.56.6 |
| 69.58 | shadowsocks | 275.0 | 632.9 | 21.41 | 0.0 | 10.0 | 12.73 | 11.12 | mheidari-all | 198.98.53.130 |
| 69.44 | vless | 326.3 | 714.4 | 20.22 | 0.0 | 10.0 | 7.72 | 16.22 | Surfboard-tg-mixed | 137.184.218.169 |
| 69.29 | shadowsocks | 336.7 | 703.1 | 19.98 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 108.181.0.177 |
| 69.11 | vless | 319.7 | 584.0 | 20.38 | 0.0 | 10.0 | 7.72 | 16.22 | Surfboard-tg-mixed | 34.213.172.16 |
| 68.96 | shadowsocks | 293.3 | 550.3 | 20.99 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 149.22.95.183 |
| 68.87 | shadowsocks | 284.3 | 573.0 | 21.2 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 173.244.56.9 |
| 67.96 | shadowsocks | 396.9 | 834.3 | 18.59 | 0.0 | 10.0 | 12.73 | 15.1 | Au1rxx-base64 | 108.181.118.10 |
| 65.58 | vless | 425.3 | 924.5 | 17.93 | 0.0 | 10.0 | 7.72 | 15.1 | Au1rxx-base64 | 15.204.97.214 |
| 65.54 | vless | 423.6 | 909.6 | 17.97 | 0.0 | 10.0 | 7.72 | 15.1 | Au1rxx-base64 | 15.204.97.219 |
| 65.22 | shadowsocks | 325.8 | 685.9 | 20.24 | 0.0 | 10.0 | 12.73 | 9.5 | DeltaKronecker-all | 108.181.57.93 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | 1.0 | 50 | 73 | prefer |
| Surfboard-tg-mixed | 0.906 | 0.828 | 325 | 5422 | prefer |
| Au1rxx-base64 | 0.695 | 0.694 | 85 | 133 | observe |
| mheidari-all | 0.636 | 0.557 | 221 | 15461 | observe |
| DeltaKronecker-all | 0.596 | 0.516 | 124 | 6437 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| nscl5-all | 0.301 | 1.0 | 1 | 1140 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4576 | observe |
| Epodonios-all | 0.255 | None | 0 | 8143 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3979 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7420 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4123 | observe |
| barry-far-vless | 0.255 | None | 0 | 4932 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4664 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 95 |
| geo | TimeoutError | - | 61 |
| speed | TimeoutError | - | 26 |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 16 |
| geo | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyError | - | 1 |
| geo | status | 403 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
