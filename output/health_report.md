# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-28 19:20:06 |
| 运行耗时 | 237.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 80684 |
| 去重后节点 | 23093 |
| TCP 可达 | 3000 |
| 真实可用 | 408 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23093 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 33.0 |
| probe | 53.8 |
| real_test | 111.3 |
| generate | 33.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46587 |
| trojan | 12798 |
| shadowsocks | 10333 |
| vmess | 10312 |
| hysteria2 | 514 |
| shadowsocksr | 74 |
| socks | 52 |
| hysteria | 8 |
| tuic | 3 |
| http | 3 |

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
| 80.25 | hysteria2 | 237.9 | 644.5 | 22.27 | 0.0 | 10.0 | 11.54 | 17.54 | Au1rxx-base64 | 159.223.157.129 |
| 77.67 | trojan | 342.1 | 932.9 | 19.86 | 0.0 | 10.0 | 13.27 | 17.54 | Au1rxx-base64 | 153.75.250.171 |
| 77.65 | shadowsocks | 231.0 | 608.1 | 22.43 | 0.0 | 10.0 | 11.68 | 17.54 | Au1rxx-base64 | 198.98.53.130 |
| 77.39 | shadowsocks | 242.1 | 652.3 | 22.17 | 0.0 | 10.0 | 11.68 | 17.54 | Au1rxx-base64 | 37.19.198.160 |
| 77.3 | trojan | 357.7 | 870.2 | 19.5 | 0.0 | 10.0 | 13.27 | 19.06 | DeltaKronecker-all | 64.74.163.118 |
| 77.25 | shadowsocks | 248.2 | 663.7 | 22.03 | 0.0 | 10.0 | 11.68 | 17.54 | Au1rxx-base64 | 37.19.198.244 |
| 76.21 | vless | 269.0 | 727.7 | 21.55 | 0.0 | 10.0 | 8.12 | 17.54 | Au1rxx-base64 | 47.253.226.114 |
| 75.89 | shadowsocks | 307.0 | 826.7 | 20.67 | 0.0 | 10.0 | 11.68 | 17.54 | Au1rxx-base64 | 37.19.198.236 |
| 75.75 | trojan | 295.6 | 645.0 | 20.94 | 0.0 | 10.0 | 13.27 | 17.54 | Au1rxx-base64 | 64.94.95.115 |
| 75.59 | trojan | 368.0 | 759.5 | 19.26 | 0.0 | 10.0 | 13.27 | 19.06 | DeltaKronecker-all | 45.142.120.27 |
| 75.2 | trojan | 296.5 | 641.8 | 20.91 | 0.0 | 10.0 | 13.27 | 17.54 | Au1rxx-base64 | 64.94.95.117 |
| 74.4 | vless | 260.9 | 662.2 | 21.74 | 0.0 | 10.0 | 8.12 | 17.54 | Au1rxx-base64 | 167.99.48.117 |
| 74.03 | vless | 256.0 | 659.9 | 21.85 | 0.0 | 10.0 | 8.12 | 19.06 | DeltaKronecker-all | 78.153.155.112 |
| 73.96 | trojan | 310.2 | 668.5 | 20.6 | 0.0 | 10.0 | 13.27 | 17.54 | Au1rxx-base64 | 163.245.196.68 |
| 73.51 | trojan | 386.6 | 916.4 | 18.83 | 0.0 | 10.0 | 13.27 | 17.54 | Au1rxx-base64 | 64.94.95.114 |
| 73.14 | shadowsocks | 287.5 | 661.1 | 21.12 | 0.0 | 10.0 | 11.68 | 17.54 | Au1rxx-base64 | 156.146.38.167 |
| 72.99 | trojan | 377.6 | 896.2 | 19.04 | 0.0 | 10.0 | 13.27 | 17.54 | Au1rxx-base64 | 64.94.95.118 |
| 72.83 | vless | 286.4 | 541.0 | 21.15 | 0.0 | 10.0 | 8.12 | 19.06 | DeltaKronecker-all | 172.67.209.126 |
| 72.24 | vless | 267.7 | 657.5 | 21.58 | 0.0 | 10.0 | 8.12 | 17.54 | Au1rxx-base64 | pro-us.emrata.top |
| 72.21 | vless | 294.3 | 543.9 | 20.97 | 0.0 | 10.0 | 8.12 | 19.06 | DeltaKronecker-all | 104.25.161.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | 0.881 | 285 | 1352 | prefer |
| Surfboard-tg-mixed | 0.547 | 0.778 | 9 | 5820 | observe |
| DeltaKronecker-all | 0.504 | 0.424 | 335 | 5965 | observe |
| mheidari-all | 0.489 | 0.833 | 6 | 17171 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4972 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| Epodonios-all | 0.255 | None | 0 | 6834 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6507 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4597 | observe |
| barry-far-vless | 0.255 | None | 0 | 5117 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5059 | observe |
| nscl5-all | 0.255 | None | 0 | 3331 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 63 |
| 204 | TimeoutError | - | 36 |
| geo | TimeoutError | - | 34 |
| geo | ClientOSError | - | 19 |
| cn-block | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 17 |
| speed | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 4 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
