# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-28 13:57:47 |
| 运行耗时 | 253.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 86375 |
| 去重后节点 | 23470 |
| TCP 可达 | 3000 |
| 真实可用 | 501 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23470 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 32.3 |
| probe | 53.6 |
| real_test | 120.5 |
| generate | 39.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48795 |
| trojan | 16073 |
| vmess | 10401 |
| shadowsocks | 10288 |
| hysteria2 | 560 |
| shadowsocksr | 95 |
| http | 73 |
| socks | 63 |
| hysteria | 12 |
| anytls | 10 |
| tuic | 5 |

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
| 83.69 | hysteria2 | 233.0 | 641.9 | 22.39 | 0.0 | 10.0 | 12.86 | 19.54 | Au1rxx-base64 | 159.223.157.129 |
| 81.18 | shadowsocks | 222.2 | 598.7 | 22.63 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 198.98.53.130 |
| 80.94 | shadowsocks | 232.6 | 642.1 | 22.39 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 37.19.198.244 |
| 80.91 | shadowsocks | 234.0 | 640.6 | 22.36 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 37.19.198.243 |
| 80.84 | shadowsocks | 237.0 | 658.6 | 22.29 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 37.19.198.236 |
| 80.73 | shadowsocks | 241.7 | 667.5 | 22.18 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 37.19.198.160 |
| 77.81 | shadowsocks | 285.0 | 690.1 | 21.18 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 185.196.61.82 |
| 77.4 | shadowsocks | 281.4 | 648.3 | 21.26 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 156.146.38.168 |
| 77.22 | shadowsocks | 280.0 | 627.0 | 21.3 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 156.146.38.170 |
| 77.07 | trojan | 463.3 | 1318.2 | 17.05 | 0.0 | 10.0 | 13.48 | 19.54 | Au1rxx-base64 | 153.75.250.171 |
| 76.59 | shadowsocks | 278.9 | 638.9 | 21.32 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 156.146.38.167 |
| 76.58 | trojan | 317.8 | 661.2 | 20.42 | 0.0 | 10.0 | 13.48 | 19.54 | Au1rxx-base64 | 163.245.196.68 |
| 75.46 | trojan | 303.2 | 647.2 | 20.76 | 0.0 | 10.0 | 13.48 | 19.54 | Au1rxx-base64 | 64.94.95.118 |
| 75.11 | hysteria2 | 358.9 | 688.7 | 19.47 | 0.0 | 10.0 | 12.86 | 19.54 | Au1rxx-base64 | 62.210.124.146 |
| 74.94 | shadowsocks | 317.7 | 696.4 | 20.42 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 108.181.57.93 |
| 74.58 | shadowsocks | 298.9 | 588.4 | 20.86 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 173.244.56.9 |
| 74.1 | hysteria2 | 428.1 | 884.1 | 17.87 | 0.0 | 10.0 | 12.86 | 19.54 | Au1rxx-base64 | 5.255.102.165 |
| 73.88 | shadowsocks | 304.2 | 604.1 | 20.74 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 173.244.56.6 |
| 73.68 | shadowsocks | 303.2 | 582.8 | 20.76 | 0.0 | 10.0 | 13.01 | 19.54 | Au1rxx-base64 | 108.181.0.177 |
| 73.62 | vless | 332.8 | 830.6 | 20.07 | 0.0 | 10.0 | 6.12 | 17.48 | mheidari-all | 158.69.112.254 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 69 | 81 | prefer |
| DeltaKronecker-all | 0.953 | 0.879 | 124 | 5965 | prefer |
| Au1rxx-base64 | 0.877 | 0.825 | 211 | 1391 | prefer |
| Surfboard-tg-mixed | 0.694 | 0.619 | 42 | 5771 | observe |
| mheidari-all | 0.625 | 0.545 | 209 | 18775 | observe |
| tg-LonUp_M | 0.407 | 1.0 | 4 | 179 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4972 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 3959 | observe |
| tg-Farah_VPN | 0.263 | 1.0 | 1 | 200 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Pawdroid | 0.256 | 1.0 | 1 | 17 | observe |
| Epodonios-all | 0.255 | None | 0 | 6785 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6699 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4628 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 38 |
| 204 | ProxyError | - | 33 |
| geo | TimeoutError | - | 29 |
| geo | ClientOSError | - | 19 |
| speed | TimeoutError | - | 13 |
| speed | ClientOSError | - | 12 |
| cn-block | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
