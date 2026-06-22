# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-22 20:43:50 |
| 运行耗时 | 239.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 78135 |
| 去重后节点 | 22708 |
| TCP 可达 | 3000 |
| 真实可用 | 463 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22708 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.3 |
| tcp | 31.1 |
| probe | 52.5 |
| real_test | 112.3 |
| generate | 37.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47157 |
| trojan | 10490 |
| vmess | 10020 |
| shadowsocks | 9821 |
| hysteria2 | 246 |
| http | 170 |
| shadowsocksr | 166 |
| socks | 57 |
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
| 80.57 | shadowsocks | 249.6 | 615.6 | 22.0 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 156.146.38.168 |
| 80.43 | shadowsocks | 256.6 | 632.6 | 21.84 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 156.146.38.169 |
| 80.41 | shadowsocks | 257.3 | 636.1 | 21.82 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 156.146.38.170 |
| 79.72 | shadowsocks | 275.6 | 637.1 | 21.4 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 37.19.198.244 |
| 79.71 | shadowsocks | 277.0 | 675.1 | 21.37 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 37.19.198.160 |
| 79.41 | shadowsocks | 279.8 | 685.1 | 21.3 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 37.19.198.236 |
| 79.32 | shadowsocks | 304.6 | 777.5 | 20.73 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 198.98.53.130 |
| 78.51 | shadowsocks | 329.1 | 833.3 | 20.16 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 37.19.198.243 |
| 76.46 | vless | 311.2 | 772.7 | 20.57 | 0.0 | 10.0 | 9.49 | 17.22 | mheidari-all | 47.253.226.114 |
| 75.38 | shadowsocks | 258.7 | 639.7 | 21.79 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 156.146.38.167 |
| 74.83 | vless | 304.8 | 825.2 | 20.72 | 0.0 | 10.0 | 9.49 | 17.22 | mheidari-all | 185.156.47.96 |
| 74.75 | vless | 372.1 | 910.7 | 19.16 | 0.0 | 10.0 | 9.49 | 18.54 | Au1rxx-base64 | 15.223.121.250 |
| 73.73 | shadowsocks | 299.7 | 530.6 | 20.84 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 108.181.0.177 |
| 73.35 | shadowsocks | 284.3 | 560.6 | 21.2 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 173.244.56.6 |
| 73.29 | shadowsocks | 302.4 | 531.1 | 20.78 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 108.181.118.10 |
| 73.08 | trojan | 474.6 | 1217.6 | 16.79 | 0.0 | 10.0 | 13.26 | 17.22 | mheidari-all | 64.94.95.118 |
| 72.51 | shadowsocks | 319.6 | 595.6 | 20.38 | 0.0 | 10.0 | 14.05 | 18.54 | Au1rxx-base64 | 149.22.95.183 |
| 71.24 | vless | 403.5 | 868.5 | 18.44 | 0.0 | 10.0 | 9.49 | 18.54 | Au1rxx-base64 | 15.204.97.219 |
| 71.02 | shadowsocks | 290.7 | 692.3 | 21.05 | 0.0 | 10.0 | 14.05 | 13.16 | DeltaKronecker-all | 142.93.183.235 |
| 70.84 | hysteria2 | 411.3 | 730.3 | 18.26 | 0.0 | 9.83 | 12.0 | 18.54 | Au1rxx-base64 | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.987 | 1.0 | 58 | 95 | prefer |
| mheidari-all | 0.864 | 0.785 | 317 | 15541 | prefer |
| Au1rxx-base64 | 0.836 | 0.837 | 104 | 150 | prefer |
| DeltaKronecker-all | 0.596 | 0.516 | 122 | 7452 | observe |
| Surfboard-tg-mixed | 0.48 | 1.0 | 4 | 5324 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4466 | observe |
| Epodonios-all | 0.255 | None | 0 | 8275 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3980 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7495 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4148 | observe |
| barry-far-vless | 0.255 | None | 0 | 5180 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4547 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.23 | None | 0 | 1364 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 34 |
| 204 | ProxyError | - | 33 |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 15 |
| cn-block | ProxyError | - | 8 |
| speed | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| geo | ProxyError | - | 6 |
| geo | ClientOSError | - | 5 |
| geo | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
