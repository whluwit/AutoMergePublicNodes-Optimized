# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-24 14:25:38 |
| 运行耗时 | 240.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 77263 |
| 去重后节点 | 22501 |
| TCP 可达 | 3000 |
| 真实可用 | 483 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22501 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 29.7 |
| probe | 58.0 |
| real_test | 115.9 |
| generate | 30.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45592 |
| trojan | 10956 |
| vmess | 10226 |
| shadowsocks | 9858 |
| hysteria2 | 235 |
| http | 161 |
| shadowsocksr | 157 |
| socks | 70 |
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
| 79.16 | shadowsocks | 246.7 | 606.9 | 22.07 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 156.146.38.170 |
| 77.53 | shadowsocks | 248.7 | 652.8 | 22.02 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 156.146.38.167 |
| 76.28 | shadowsocks | 241.4 | 617.6 | 22.19 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 156.146.38.169 |
| 76.16 | shadowsocks | 291.6 | 671.6 | 21.03 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 37.19.198.236 |
| 76.02 | shadowsocks | 299.7 | 698.9 | 20.84 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 37.19.198.243 |
| 75.92 | shadowsocks | 292.6 | 678.6 | 21.0 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 37.19.198.244 |
| 75.89 | shadowsocks | 244.5 | 597.5 | 22.12 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 156.146.38.168 |
| 75.18 | shadowsocks | 289.1 | 683.4 | 21.08 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 37.19.198.160 |
| 74.35 | shadowsocks | 281.6 | 584.0 | 21.26 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 173.244.56.9 |
| 73.79 | shadowsocks | 308.0 | 602.8 | 20.65 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 149.22.95.183 |
| 73.41 | shadowsocks | 297.9 | 539.5 | 20.88 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 108.181.118.10 |
| 72.91 | shadowsocks | 313.8 | 674.0 | 20.52 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 173.244.56.6 |
| 72.6 | shadowsocks | 292.5 | 572.2 | 21.01 | 0.0 | 10.0 | 12.25 | 18.84 | Au1rxx-base64 | 108.181.0.177 |
| 71.58 | trojan | 329.3 | 817.4 | 20.15 | 0.0 | 10.0 | 8.87 | 15.56 | mheidari-all | 64.94.95.118 |
| 70.59 | hysteria2 | 406.7 | 722.5 | 18.36 | 0.0 | 9.86 | 11.25 | 18.84 | Au1rxx-base64 | 62.210.124.146 |
| 70.27 | vless | 419.7 | 907.8 | 18.06 | 0.0 | 10.0 | 8.14 | 18.84 | Au1rxx-base64 | 15.204.97.214 |
| 69.69 | vless | 423.5 | 921.2 | 17.97 | 0.0 | 10.0 | 8.14 | 18.84 | Au1rxx-base64 | 15.204.97.219 |
| 69.46 | vless | 244.6 | 523.8 | 22.12 | 0.0 | 10.0 | 8.14 | 16.18 | Surfboard-tg-mixed | 64.118.153.6 |
| 68.6 | trojan | 402.5 | 848.2 | 18.46 | 0.0 | 10.0 | 8.87 | 18.84 | Au1rxx-base64 | 45.61.52.243 |
| 68.35 | shadowsocks | 362.3 | 409.5 | 19.39 | 0.0 | 9.62 | 12.25 | 18.84 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | 1.0 | 50 | 73 | prefer |
| Surfboard-tg-mixed | 0.856 | 0.778 | 284 | 5407 | prefer |
| mheidari-all | 0.787 | 0.709 | 165 | 15574 | prefer |
| Au1rxx-base64 | 0.77 | 0.774 | 62 | 113 | prefer |
| DeltaKronecker-all | 0.698 | 0.622 | 74 | 6644 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4745 | observe |
| Epodonios-all | 0.255 | None | 0 | 8169 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7672 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4121 | observe |
| barry-far-vless | 0.255 | None | 0 | 4921 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4710 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 62 |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 11 |
| geo | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 9 |
| geo | ClientOSError | - | 7 |
| speed | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
