# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-15 19:07:35 |
| 运行耗时 | 202.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 76350 |
| 去重后节点 | 23029 |
| TCP 可达 | 3000 |
| 真实可用 | 321 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23029 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.3 |
| tcp | 32.2 |
| probe | 50.2 |
| real_test | 88.4 |
| generate | 26.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44079 |
| trojan | 11444 |
| vmess | 10873 |
| shadowsocks | 9370 |
| hysteria2 | 310 |
| shadowsocksr | 126 |
| http | 98 |
| socks | 29 |
| hysteria | 10 |
| tuic | 6 |
| anytls | 5 |

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
| 77.56 | shadowsocks | 230.7 | 635.4 | 22.44 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 37.19.198.244 |
| 77.42 | shadowsocks | 236.7 | 646.1 | 22.3 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 37.19.198.243 |
| 77.29 | shadowsocks | 242.3 | 651.7 | 22.17 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 74.03 | shadowsocks | 283.5 | 643.6 | 21.22 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 156.146.38.167 |
| 74.01 | shadowsocks | 278.6 | 638.5 | 21.33 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 156.146.38.169 |
| 73.86 | shadowsocks | 223.8 | 601.4 | 22.6 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 198.98.53.130 |
| 73.41 | hysteria2 | 291.4 | 554.5 | 21.03 | 0.0 | 10.0 | 12.5 | 16.46 | Au1rxx-base64 | 38.148.249.252 |
| 72.87 | shadowsocks | 248.2 | 658.0 | 22.03 | 0.0 | 10.0 | 12.66 | 12.68 | Surfboard-tg-mixed | 108.181.57.93 |
| 72.54 | shadowsocks | 331.4 | 790.9 | 20.11 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 156.146.38.170 |
| 72.48 | shadowsocks | 287.4 | 652.8 | 21.13 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 156.146.38.168 |
| 71.29 | hysteria2 | 362.0 | 683.0 | 19.4 | 0.0 | 10.0 | 12.5 | 16.46 | Au1rxx-base64 | 62.210.124.146 |
| 70.47 | shadowsocks | 367.2 | 938.4 | 19.28 | 0.0 | 10.0 | 12.66 | 13.68 | DeltaKronecker-all | 185.196.61.82 |
| 70.37 | vless | 234.5 | 657.1 | 22.35 | 0.0 | 10.0 | 1.56 | 16.46 | Au1rxx-base64 | 47.253.226.114 |
| 70.12 | shadowsocks | 316.1 | 580.6 | 20.46 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 173.244.56.6 |
| 69.92 | shadowsocks | 322.1 | 579.0 | 20.32 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 173.244.56.9 |
| 69.86 | vmess | 371.2 | 1074.7 | 19.18 | 0.0 | 10.0 | 12.5 | 12.68 | Surfboard-tg-mixed | 67.220.95.3 |
| 69.55 | shadowsocks | 339.2 | 876.7 | 19.93 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 50.114.177.235 |
| 69.23 | shadowsocks | 339.7 | 651.7 | 19.92 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 149.22.95.183 |
| 68.88 | shadowsocks | 324.8 | 560.1 | 20.26 | 0.0 | 10.0 | 12.66 | 16.46 | Au1rxx-base64 | 108.181.118.10 |
| 68.85 | vmess | 458.3 | 1075.8 | 17.17 | 0.0 | 10.0 | 12.5 | 13.68 | DeltaKronecker-all | 67.220.85.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.966 | 0.891 | 138 | 16638 | prefer |
| Au1rxx-base64 | 0.722 | 0.722 | 97 | 132 | prefer |
| Surfboard-tg-mixed | 0.703 | 0.627 | 67 | 5510 | prefer |
| DeltaKronecker-all | 0.495 | 0.413 | 121 | 6421 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 3759 | observe |
| Epodonios-all | 0.255 | None | 0 | 6514 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6916 | observe |
| barry-far-vless | 0.255 | None | 0 | 4862 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5183 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.245 | None | 0 | 1741 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 66 |
| 204 | TimeoutError | - | 16 |
| speed | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 6 |
| geo | ClientOSError | - | 5 |
| 204 | ProxyError | - | 5 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 258 | 300 | - |
| global | False | 266 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
