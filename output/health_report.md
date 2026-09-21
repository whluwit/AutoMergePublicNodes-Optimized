# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 21:46:30 |
| 运行耗时 | 581.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 88638 |
| 去重后节点 | 25157 |
| TCP 可达 | 3000 |
| 真实可用 | 537 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25157 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 42.1 |
| probe | 219.3 |
| real_test | 230.9 |
| generate | 80.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53477 |
| vmess | 13990 |
| shadowsocks | 10212 |
| trojan | 8828 |
| hysteria2 | 1263 |
| http | 627 |
| shadowsocksr | 132 |
| socks | 77 |
| hysteria | 14 |
| anytls | 12 |
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
| 79.26 | vless | 228.5 | 601.2 | 22.49 | 0.0 | 10.0 | 9.63 | 19.14 | Au1rxx-base64 | 195.123.235.177 |
| 79.09 | vless | 265.8 | 652.0 | 21.62 | 0.0 | 9.01 | 9.63 | 19.14 | Au1rxx-base64 | 195.211.98.43 |
| 79.01 | hysteria2 | 245.1 | 681.8 | 22.1 | 0.0 | 10.0 | 12.63 | 15.38 | mheidari-all | 159.223.157.129 |
| 78.91 | shadowsocks | 310.4 | 822.7 | 20.59 | 0.0 | 8.91 | 14.27 | 19.14 | Au1rxx-base64 | 142.4.216.225 |
| 78.85 | vless | 287.8 | 708.9 | 21.12 | 0.0 | 8.96 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.75 |
| 78.61 | vless | 298.0 | 742.1 | 20.88 | 0.0 | 8.96 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.225 |
| 78.59 | vless | 301.5 | 748.9 | 20.8 | 0.0 | 9.02 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.15 |
| 78.49 | vless | 304.4 | 764.9 | 20.73 | 0.0 | 8.99 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.35 |
| 78.42 | vless | 306.6 | 767.4 | 20.68 | 0.0 | 8.97 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.89 |
| 78.38 | vless | 308.0 | 700.7 | 20.65 | 0.0 | 8.96 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.74 |
| 78.37 | vless | 311.0 | 886.4 | 20.58 | 0.0 | 9.02 | 9.63 | 19.14 | Au1rxx-base64 | 34.85.179.6 |
| 78.36 | vless | 310.8 | 852.4 | 20.58 | 0.0 | 9.01 | 9.63 | 19.14 | Au1rxx-base64 | 137.184.218.169 |
| 78.22 | vless | 315.0 | 713.4 | 20.49 | 0.0 | 8.96 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.229 |
| 77.96 | vless | 326.2 | 886.2 | 20.23 | 0.0 | 8.96 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.163 |
| 77.64 | vless | 345.6 | 893.6 | 19.78 | 0.0 | 9.09 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.231 |
| 77.44 | shadowsocks | 258.6 | 717.6 | 21.79 | 0.0 | 10.0 | 14.27 | 15.38 | mheidari-all | 37.19.198.244 |
| 77.44 | shadowsocks | 258.8 | 706.5 | 21.79 | 0.0 | 10.0 | 14.27 | 15.38 | mheidari-all | 37.19.198.236 |
| 77.4 | shadowsocks | 260.3 | 724.4 | 21.75 | 0.0 | 10.0 | 14.27 | 15.38 | mheidari-all | 37.19.198.160 |
| 77.37 | vless | 354.1 | 978.4 | 19.58 | 0.0 | 9.02 | 9.63 | 19.14 | Au1rxx-base64 | 185.95.231.156 |
| 77.37 | vless | 356.3 | 916.2 | 19.53 | 0.0 | 9.07 | 9.63 | 19.14 | Au1rxx-base64 | 169.40.42.235 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.962 | 0.895 | 276 | 1752 | prefer |
| ermaozi | 0.69 | 0.686 | 35 | 350 | observe |
| Surfboard-tg-mixed | 0.664 | 0.585 | 164 | 7273 | observe |
| mheidari-all | 0.591 | 0.511 | 323 | 20197 | observe |
| DeltaKronecker-all | 0.373 | 0.6 | 5 | 6181 | observe |
| ermaozi-get_subscribe | 0.27 | 1.0 | 1 | 377 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7717 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8749 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5859 | observe |
| barry-far-vless | 0.255 | None | 0 | 6075 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 68 |
| geo | ClientOSError | - | 54 |
| geo | TimeoutError | - | 50 |
| speed | ClientOSError | - | 29 |
| 204 | TimeoutError | - | 21 |
| 204 | ProxyError | - | 15 |
| speed | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
