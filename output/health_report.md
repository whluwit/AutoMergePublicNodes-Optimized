# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-20 08:56:24 |
| 运行耗时 | 379.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 85554 |
| 去重后节点 | 23995 |
| TCP 可达 | 3000 |
| 真实可用 | 534 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23995 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.5 |
| geo | 0.5 |
| tcp | 32.7 |
| probe | 65.6 |
| real_test | 223.4 |
| generate | 43.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50778 |
| trojan | 13070 |
| vmess | 10969 |
| shadowsocks | 10157 |
| hysteria2 | 395 |
| shadowsocksr | 73 |
| http | 52 |
| socks | 36 |
| hysteria | 16 |
| tuic | 7 |
| anytls | 1 |

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
| 82.25 | shadowsocks | 229.5 | 637.5 | 22.47 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 37.19.198.243 |
| 82.19 | shadowsocks | 231.8 | 641.6 | 22.41 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 37.19.198.160 |
| 82.17 | shadowsocks | 232.8 | 645.5 | 22.39 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 37.19.198.236 |
| 81.28 | shadowsocks | 249.5 | 658.5 | 22.0 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 108.181.57.93 |
| 79.82 | shadowsocks | 312.8 | 869.5 | 20.54 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 68.168.222.210 |
| 78.96 | shadowsocks | 371.5 | 1045.0 | 19.18 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 147.90.234.133 |
| 78.75 | shadowsocks | 284.7 | 652.8 | 21.19 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 156.146.38.167 |
| 78.63 | shadowsocks | 282.7 | 643.3 | 21.23 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 156.146.38.170 |
| 78.38 | shadowsocks | 361.2 | 909.0 | 19.42 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 185.196.61.82 |
| 77.5 | shadowsocks | 216.6 | 586.6 | 22.76 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 198.98.53.130 |
| 76.98 | trojan | 500.8 | 1311.8 | 16.18 | 0.0 | 10.0 | 14.28 | 19.76 | Au1rxx-base64 | 148.72.168.35 |
| 76.58 | shadowsocks | 387.8 | 1090.5 | 18.8 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 76.3 | shadowsocks | 311.2 | 730.1 | 20.57 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 156.146.38.169 |
| 75.94 | shadowsocks | 396.7 | 991.2 | 18.6 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 156.146.38.168 |
| 75.85 | trojan | 400.6 | 959.0 | 18.51 | 0.0 | 10.0 | 14.28 | 19.76 | Au1rxx-base64 | 64.94.95.118 |
| 74.98 | trojan | 413.6 | 988.0 | 18.2 | 0.0 | 10.0 | 14.28 | 19.76 | Au1rxx-base64 | 64.94.95.117 |
| 74.88 | trojan | 416.4 | 1003.8 | 18.14 | 0.0 | 10.0 | 14.28 | 19.76 | Au1rxx-base64 | 64.94.95.114 |
| 74.53 | shadowsocks | 317.1 | 569.5 | 20.44 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 173.244.56.9 |
| 74.42 | hysteria2 | 376.8 | 753.2 | 19.06 | 0.0 | 10.0 | 12.0 | 19.76 | Au1rxx-base64 | 62.210.124.146 |
| 74.31 | shadowsocks | 310.8 | 571.0 | 20.58 | 0.0 | 10.0 | 14.02 | 19.76 | Au1rxx-base64 | 108.181.118.10 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.949 | 0.911 | 235 | 1057 | prefer |
| Surfboard-tg-mixed | 0.683 | 0.607 | 56 | 5183 | observe |
| mheidari-all | 0.657 | 0.578 | 109 | 20095 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5035 | observe |
| DeltaKronecker-all | 0.27 | 0.189 | 979 | 5962 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4714 | observe |
| Epodonios-all | 0.255 | None | 0 | 6441 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6852 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4032 | observe |
| barry-far-vless | 0.255 | None | 0 | 4852 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5193 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| Au1rxx-clash | 0.217 | None | 0 | 1057 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 424 |
| speed | ClientOSError | - | 364 |
| cn-block | TimeoutError | - | 32 |
| speed | TimeoutError | - | 23 |
| geo | ClientOSError | - | 18 |
| cn-block | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 6 |
| 204 | ProxyError | - | 6 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
