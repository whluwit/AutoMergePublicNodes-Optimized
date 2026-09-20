# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 15:28:08 |
| 运行耗时 | 569.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84315 |
| 去重后节点 | 23455 |
| TCP 可达 | 3000 |
| 真实可用 | 499 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23455 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 38.9 |
| probe | 234.4 |
| real_test | 204.1 |
| generate | 84.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50856 |
| vmess | 13608 |
| shadowsocks | 9833 |
| trojan | 8191 |
| hysteria2 | 1044 |
| http | 576 |
| shadowsocksr | 122 |
| socks | 70 |
| hysteria | 11 |
| tuic | 3 |
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
| 79.2 | shadowsocks | 250.5 | 622.5 | 21.98 | 0.0 | 10.0 | 13.52 | 17.7 | Au1rxx-base64 | 156.146.38.168 |
| 78.66 | shadowsocks | 273.9 | 693.9 | 21.44 | 0.0 | 10.0 | 13.52 | 17.7 | Au1rxx-base64 | 37.19.198.243 |
| 78.61 | shadowsocks | 275.8 | 701.4 | 21.39 | 0.0 | 10.0 | 13.52 | 17.7 | Au1rxx-base64 | 156.146.38.169 |
| 78.56 | vless | 281.9 | 704.1 | 21.25 | 0.0 | 10.0 | 9.61 | 17.7 | Au1rxx-base64 | 79.141.172.154 |
| 78.46 | shadowsocks | 282.6 | 719.5 | 21.24 | 0.0 | 10.0 | 13.52 | 17.7 | Au1rxx-base64 | 156.146.38.170 |
| 78.44 | shadowsocks | 283.2 | 721.6 | 21.22 | 0.0 | 10.0 | 13.52 | 17.7 | Au1rxx-base64 | 37.19.198.236 |
| 78.18 | shadowsocks | 251.5 | 628.0 | 21.96 | 0.0 | 10.0 | 13.52 | 17.7 | Au1rxx-base64 | 156.146.38.167 |
| 78.08 | hysteria2 | 261.6 | 676.5 | 21.72 | 0.0 | 10.0 | 12.86 | 14.6 | mheidari-all | 159.223.157.129 |
| 77.25 | vless | 338.8 | 907.9 | 19.94 | 0.0 | 10.0 | 9.61 | 17.7 | Au1rxx-base64 | 216.152.147.28 |
| 76.13 | shadowsocks | 361.3 | 997.5 | 19.41 | 0.0 | 10.0 | 13.52 | 17.7 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 75.91 | vless | 355.2 | 846.3 | 19.55 | 0.0 | 10.0 | 9.61 | 17.7 | Au1rxx-base64 | 66.70.179.198 |
| 75.77 | hysteria2 | 322.5 | 639.2 | 20.31 | 0.0 | 10.0 | 12.86 | 17.7 | Au1rxx-base64 | 66.94.121.46 |
| 75.57 | vless | 389.9 | 999.8 | 18.75 | 0.0 | 10.0 | 9.61 | 17.7 | Au1rxx-base64 | 169.40.42.202 |
| 75.52 | vless | 342.5 | 728.9 | 19.85 | 0.0 | 10.0 | 9.61 | 17.7 | Au1rxx-base64 | 169.40.42.15 |
| 75.37 | vless | 361.3 | 867.4 | 19.41 | 0.0 | 10.0 | 9.61 | 17.7 | Au1rxx-base64 | 169.40.42.231 |
| 75.24 | vless | 402.6 | 906.8 | 18.46 | 0.0 | 10.0 | 9.61 | 17.7 | Au1rxx-base64 | 169.40.42.224 |
| 75.19 | shadowsocks | 353.0 | 876.9 | 19.61 | 0.0 | 10.0 | 13.52 | 17.7 | Au1rxx-base64 | 38.180.135.156 |
| 75.08 | shadowsocks | 300.7 | 657.3 | 20.82 | 0.0 | 10.0 | 13.52 | 17.7 | Au1rxx-base64 | 23.150.248.20 |
| 74.96 | vless | 352.7 | 765.1 | 19.61 | 0.0 | 10.0 | 9.61 | 17.7 | Au1rxx-base64 | 169.40.42.133 |
| 74.34 | vless | 443.8 | 1094.2 | 17.5 | 0.0 | 10.0 | 9.61 | 17.7 | Au1rxx-base64 | 169.40.42.75 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | 0.926 | 283 | 1621 | prefer |
| ermaozi | 0.839 | 0.857 | 21 | 314 | prefer |
| Surfboard-tg-mixed | 0.725 | 0.646 | 195 | 7133 | prefer |
| mheidari-all | 0.665 | 0.587 | 92 | 16459 | observe |
| DeltaKronecker-all | 0.611 | 0.532 | 62 | 6092 | observe |
| roosterkid-openproxylist-v2ray | 0.317 | 1.0 | 2 | 150 | observe |
| tg-oneclickvpnkeys | 0.315 | 1.0 | 2 | 103 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.259 | 0.333 | 3 | 5238 | observe |
| Epodonios-all | 0.255 | None | 0 | 7577 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9286 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5703 | observe |
| barry-far-vless | 0.255 | None | 0 | 5960 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 47 |
| geo | TimeoutError | - | 24 |
| cn-block | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 18 |
| 204 | TimeoutError | - | 15 |
| speed | ClientOSError | - | 11 |
| speed | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
