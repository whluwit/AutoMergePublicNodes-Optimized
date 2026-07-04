# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-04 19:07:01 |
| 运行耗时 | 187.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 79057 |
| 去重后节点 | 23716 |
| TCP 可达 | 3000 |
| 真实可用 | 165 |
| Verified 输出 | 165 |
| Global 输出 | 175 |
| All 输出 | 23716 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.3 |
| tcp | 30.8 |
| probe | 43.4 |
| real_test | 64.3 |
| generate | 43.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45614 |
| trojan | 12692 |
| vmess | 10551 |
| shadowsocks | 9547 |
| hysteria2 | 296 |
| shadowsocksr | 141 |
| http | 135 |
| socks | 71 |
| hysteria | 6 |
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
| 75.04 | shadowsocks | 226.9 | 626.2 | 22.53 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | 37.19.198.236 |
| 74.91 | shadowsocks | 232.3 | 639.5 | 22.4 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | 37.19.198.244 |
| 74.87 | shadowsocks | 234.2 | 652.6 | 22.36 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | 37.19.198.160 |
| 74.85 | shadowsocks | 234.9 | 646.0 | 22.34 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | 37.19.198.243 |
| 73.41 | shadowsocks | 297.0 | 819.6 | 20.9 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 71.37 | shadowsocks | 290.9 | 672.9 | 21.04 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | 156.146.38.168 |
| 71.21 | shadowsocks | 281.6 | 639.4 | 21.26 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | 156.146.38.169 |
| 70.66 | vless | 262.9 | 741.8 | 21.69 | 0.0 | 10.0 | 5.17 | 13.8 | Au1rxx-base64 | 47.253.226.114 |
| 70.49 | shadowsocks | 316.8 | 743.2 | 20.44 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | 156.146.38.167 |
| 69.59 | shadowsocks | 271.7 | 616.8 | 21.49 | 0.0 | 10.0 | 12.71 | 13.54 | DeltaKronecker-all | 185.196.61.82 |
| 69.4 | vless | 262.9 | 656.2 | 21.69 | 0.0 | 10.0 | 5.17 | 13.54 | DeltaKronecker-all | 104.25.161.29 |
| 69.37 | vless | 264.1 | 648.0 | 21.66 | 0.0 | 10.0 | 5.17 | 13.54 | DeltaKronecker-all | 198.41.209.87 |
| 68.36 | vless | 262.7 | 653.3 | 21.7 | 0.0 | 10.0 | 5.17 | 13.54 | DeltaKronecker-all | 162.159.252.15 |
| 68.31 | hysteria2 | 358.3 | 682.3 | 19.48 | 0.0 | 9.92 | 12.0 | 13.8 | Au1rxx-base64 | 62.210.124.146 |
| 68.11 | shadowsocks | 227.3 | 605.0 | 22.52 | 0.0 | 10.0 | 12.71 | 6.88 | mheidari-all | 198.98.53.130 |
| 67.37 | shadowsocks | 396.5 | 907.6 | 18.6 | 0.0 | 10.0 | 12.71 | 13.28 | Surfboard-tg-mixed | 130.51.22.8 |
| 67.36 | vmess | 392.2 | 1117.1 | 18.7 | 0.0 | 10.0 | 12.86 | 13.54 | DeltaKronecker-all | 67.220.95.3 |
| 67.25 | shadowsocks | 242.6 | 652.8 | 22.16 | 0.0 | 10.0 | 12.71 | 6.88 | mheidari-all | 108.181.57.93 |
| 67.11 | shadowsocks | 307.3 | 586.3 | 20.66 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | 108.181.118.10 |
| 66.9 | shadowsocks | 335.4 | 583.2 | 20.01 | 0.0 | 10.0 | 12.71 | 13.8 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.715 | 0.722 | 36 | 100 | prefer |
| Surfboard-tg-mixed | 0.691 | 0.614 | 70 | 6107 | observe |
| DeltaKronecker-all | 0.452 | 0.371 | 143 | 7309 | observe |
| mheidari-all | 0.337 | 0.308 | 13 | 16429 | observe |
| tg-ConfigV2rayNG | 0.319 | 1.0 | 2 | 200 | observe |
| nscl5-all | 0.303 | 1.0 | 1 | 1189 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4579 | observe |
| Epodonios-all | 0.255 | None | 0 | 6997 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3978 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7306 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4528 | observe |
| barry-far-vless | 0.255 | None | 0 | 5100 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5366 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 41 |
| 204 | TimeoutError | - | 24 |
| speed | ClientOSError | - | 20 |
| 204 | ProxyError | - | 16 |
| cn-block | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 11 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 251 | 165 | - |
| global | False | 266 | 175 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
