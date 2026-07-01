# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-01 14:29:28 |
| 运行耗时 | 215.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 77019 |
| 去重后节点 | 23292 |
| TCP 可达 | 3000 |
| 真实可用 | 258 |
| Verified 输出 | 258 |
| Global 输出 | 272 |
| All 输出 | 23292 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.5 |
| tcp | 31.3 |
| probe | 47.8 |
| real_test | 94.0 |
| generate | 36.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43979 |
| trojan | 12898 |
| vmess | 10250 |
| shadowsocks | 9281 |
| hysteria2 | 253 |
| shadowsocksr | 158 |
| http | 135 |
| socks | 58 |
| hysteria | 6 |
| tuic | 1 |

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
| 76.57 | shadowsocks | 237.9 | 618.3 | 22.27 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 156.146.38.168 |
| 76.4 | shadowsocks | 245.4 | 606.1 | 22.1 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 156.146.38.167 |
| 75.65 | shadowsocks | 237.3 | 573.4 | 22.28 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 156.146.38.170 |
| 74.31 | shadowsocks | 320.6 | 831.3 | 20.36 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 156.146.38.169 |
| 72.96 | shadowsocks | 299.9 | 716.9 | 20.84 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 37.19.198.160 |
| 72.29 | shadowsocks | 333.8 | 803.3 | 20.05 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 37.19.198.236 |
| 71.11 | shadowsocks | 298.6 | 686.5 | 20.87 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 37.19.198.244 |
| 70.97 | trojan | 262.9 | 634.7 | 21.69 | 0.0 | 10.0 | 8.82 | 13.46 | DeltaKronecker-all | 64.94.95.114 |
| 70.02 | shadowsocks | 298.0 | 579.4 | 20.88 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 149.22.95.183 |
| 69.9 | trojan | 259.9 | 623.1 | 21.76 | 0.0 | 10.0 | 8.82 | 13.46 | DeltaKronecker-all | 64.94.95.115 |
| 69.42 | shadowsocks | 418.6 | 964.6 | 18.09 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 108.181.57.93 |
| 68.08 | shadowsocks | 386.6 | 837.2 | 18.83 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 108.181.0.177 |
| 68.07 | shadowsocks | 357.2 | 763.5 | 19.51 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 108.181.118.10 |
| 66.72 | hysteria2 | 409.4 | 720.1 | 18.3 | 0.0 | 9.8 | 10.0 | 16.6 | Au1rxx-base64 | 62.210.124.146 |
| 66.11 | shadowsocks | 616.2 | 1729.0 | 13.51 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 172.234.202.34 |
| 65.92 | vless | 420.7 | 909.9 | 18.04 | 0.0 | 10.0 | 7.14 | 16.6 | Au1rxx-base64 | 15.204.97.214 |
| 65.78 | shadowsocks | 411.0 | 770.4 | 18.26 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 173.244.56.6 |
| 65.43 | shadowsocks | 364.1 | 412.6 | 19.35 | 0.0 | 9.61 | 11.7 | 16.6 | Au1rxx-base64 | 149.22.87.240 |
| 65.31 | shadowsocks | 366.9 | 414.8 | 19.29 | 0.0 | 9.59 | 11.7 | 16.6 | Au1rxx-base64 | 149.22.87.241 |
| 65.1 | shadowsocks | 335.1 | 640.1 | 20.02 | 0.0 | 10.0 | 11.7 | 16.6 | Au1rxx-base64 | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.786 | 0.795 | 44 | 87 | prefer |
| Surfboard-tg-mixed | 0.65 | 0.57 | 149 | 5922 | observe |
| DeltaKronecker-all | 0.411 | 0.33 | 300 | 7631 | observe |
| mheidari-all | 0.272 | 0.286 | 7 | 15660 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4308 | observe |
| Epodonios-all | 0.255 | None | 0 | 6803 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6937 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4402 | observe |
| barry-far-vless | 0.255 | None | 0 | 4908 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5331 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 200 |
| 204 | TimeoutError | - | 18 |
| geo | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 12 |
| geo | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 11 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| speed | TimeoutError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 258 | - |
| global | False | 300 | 272 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
