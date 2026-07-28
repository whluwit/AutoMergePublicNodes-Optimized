# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-28 02:10:50 |
| 运行耗时 | 354.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86135 |
| 去重后节点 | 23123 |
| TCP 可达 | 3000 |
| 真实可用 | 964 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23123 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 32.4 |
| probe | 70.0 |
| real_test | 223.8 |
| generate | 21.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48771 |
| trojan | 16216 |
| vmess | 10342 |
| shadowsocks | 9989 |
| hysteria2 | 547 |
| shadowsocksr | 108 |
| socks | 68 |
| http | 63 |
| hysteria | 15 |
| anytls | 10 |
| tuic | 6 |

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
| 80.96 | shadowsocks | 230.2 | 586.1 | 22.45 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 156.146.38.167 |
| 80.89 | shadowsocks | 233.0 | 596.4 | 22.38 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 156.146.38.168 |
| 80.83 | shadowsocks | 235.7 | 598.6 | 22.32 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 156.146.38.170 |
| 80.83 | shadowsocks | 236.0 | 605.0 | 22.32 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 156.146.38.169 |
| 78.82 | trojan | 380.3 | 801.8 | 18.98 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 64.94.95.117 |
| 78.77 | trojan | 377.1 | 786.7 | 19.05 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 64.94.95.114 |
| 78.68 | hysteria2 | 313.8 | 701.3 | 20.51 | 0.0 | 10.0 | 11.79 | 19.92 | Au1rxx-base64 | 159.223.157.129 |
| 78.48 | trojan | 379.6 | 797.0 | 18.99 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 64.94.95.115 |
| 77.67 | trojan | 377.1 | 787.3 | 19.05 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 64.94.95.118 |
| 77.34 | shadowsocks | 255.6 | 559.7 | 21.86 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 173.244.56.6 |
| 77.08 | shadowsocks | 249.1 | 539.9 | 22.01 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 173.244.56.9 |
| 76.7 | trojan | 476.5 | 1263.6 | 16.75 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 163.245.196.68 |
| 75.56 | shadowsocks | 238.1 | 525.1 | 22.27 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 216.105.168.18 |
| 75.36 | shadowsocks | 299.7 | 664.8 | 20.84 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 198.98.53.130 |
| 75.31 | shadowsocks | 302.6 | 638.8 | 20.77 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 108.181.0.177 |
| 75.24 | shadowsocks | 313.6 | 669.0 | 20.52 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 108.181.118.10 |
| 74.9 | trojan | 362.2 | 776.8 | 19.39 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 153.75.250.171 |
| 74.75 | shadowsocks | 321.7 | 703.2 | 20.33 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 37.19.198.236 |
| 74.68 | shadowsocks | 324.3 | 709.6 | 20.27 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 37.19.198.160 |
| 74.43 | shadowsocks | 338.5 | 737.9 | 19.94 | 0.0 | 10.0 | 12.59 | 19.92 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.958 | 522 | 1410 | prefer |
| zhangkai | 0.987 | 1.0 | 59 | 74 | prefer |
| DeltaKronecker-all | 0.68 | 0.601 | 158 | 5643 | observe |
| mheidari-all | 0.52 | 0.439 | 685 | 19690 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3959 | observe |
| Surfboard-tg-mixed | 0.337 | 0.308 | 13 | 5636 | observe |
| MatinGhanbari-all-sub | 0.335 | 1.0 | 1 | 3966 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4831 | observe |
| Epodonios-all | 0.255 | None | 0 | 6677 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6491 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5025 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4997 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 174 |
| speed | ClientOSError | - | 145 |
| geo | ClientOSError | - | 61 |
| speed | TimeoutError | - | 46 |
| cn-block | TimeoutError | - | 24 |
| 204 | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
