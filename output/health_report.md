# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 15:46:27 |
| 运行耗时 | 546.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96601 |
| 去重后节点 | 26419 |
| TCP 可达 | 3000 |
| 真实可用 | 353 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26419 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 43.4 |
| probe | 223.6 |
| real_test | 183.7 |
| generate | 89.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58753 |
| vmess | 15181 |
| shadowsocks | 11319 |
| trojan | 8924 |
| hysteria2 | 1518 |
| http | 609 |
| shadowsocksr | 168 |
| socks | 78 |
| anytls | 25 |
| hysteria | 15 |
| tuic | 11 |

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
| 82.2 | vless | 177.2 | 478.7 | 23.67 | 0.0 | 10.0 | 10.61 | 17.92 | mheidari-all | 47.251.108.158 |
| 81.56 | vless | 177.2 | 482.4 | 23.68 | 0.0 | 8.79 | 10.61 | 18.48 | Au1rxx-base64 | 137.175.82.40 |
| 81.03 | vless | 199.8 | 526.0 | 23.15 | 0.0 | 8.79 | 10.61 | 18.48 | Au1rxx-base64 | 172.235.43.210 |
| 80.55 | vless | 221.6 | 546.5 | 22.65 | 0.0 | 8.81 | 10.61 | 18.48 | Au1rxx-base64 | 5.78.159.214 |
| 80.49 | vless | 226.4 | 548.3 | 22.54 | 0.0 | 8.86 | 10.61 | 18.48 | Au1rxx-base64 | 195.123.240.65 |
| 80.09 | vless | 268.7 | 721.7 | 21.56 | 0.0 | 10.0 | 10.61 | 17.92 | mheidari-all | 172.233.139.46 |
| 79.12 | trojan | 302.2 | 832.1 | 20.78 | 0.0 | 10.0 | 12.92 | 17.92 | mheidari-all | 34.94.125.227 |
| 79.04 | vless | 242.0 | 594.2 | 22.18 | 0.0 | 8.77 | 10.61 | 18.48 | Au1rxx-base64 | 38.244.20.25 |
| 78.18 | vless | 197.7 | 525.6 | 23.2 | 0.0 | 8.89 | 10.61 | 18.48 | Au1rxx-base64 | 23.95.222.127 |
| 77.05 | vless | 350.1 | 868.3 | 19.67 | 0.0 | 8.81 | 10.61 | 18.48 | Au1rxx-base64 | 51.81.203.63 |
| 76.7 | vless | 176.4 | 484.6 | 23.69 | 0.0 | 8.92 | 10.61 | 18.48 | Au1rxx-base64 | 173.249.207.28 |
| 75.97 | trojan | 438.6 | 1190.5 | 17.63 | 0.0 | 10.0 | 12.92 | 17.92 | mheidari-all | 100.42.228.109 |
| 75.77 | shadowsocks | 244.4 | 595.5 | 22.12 | 0.0 | 9.03 | 12.72 | 18.48 | Au1rxx-base64 | 149.22.95.183 |
| 75.68 | vless | 249.7 | 454.3 | 22.0 | 0.0 | 8.84 | 10.61 | 18.48 | Au1rxx-base64 | 172.64.42.85 |
| 75.24 | vless | 236.9 | 582.1 | 22.29 | 0.0 | 8.86 | 10.61 | 18.48 | Au1rxx-base64 | 15.204.97.209 |
| 74.6 | vless | 287.8 | 569.1 | 21.12 | 0.0 | 8.89 | 10.61 | 18.48 | Au1rxx-base64 | 104.18.46.234 |
| 74.42 | vless | 292.5 | 660.5 | 21.01 | 0.0 | 10.0 | 10.61 | 17.92 | mheidari-all | 216.227.161.95 |
| 74.31 | shadowsocks | 294.1 | 664.0 | 20.97 | 0.0 | 8.85 | 12.72 | 18.48 | Au1rxx-base64 | 156.146.38.168 |
| 73.91 | shadowsocks | 289.6 | 656.7 | 21.08 | 0.0 | 8.83 | 12.72 | 18.48 | Au1rxx-base64 | 156.146.38.170 |
| 73.76 | shadowsocks | 195.9 | 510.7 | 23.24 | 0.0 | 10.0 | 12.72 | 17.92 | mheidari-all | 192.3.247.109 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.905 | 0.842 | 278 | 1642 | prefer |
| Surfboard-tg-mixed | 0.863 | 0.842 | 19 | 7263 | prefer |
| mheidari-all | 0.69 | 0.612 | 152 | 22417 | observe |
| ermaozi | 0.439 | 0.471 | 17 | 296 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7742 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8947 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5823 | observe |
| barry-far-vless | 0.255 | None | 0 | 6056 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1642 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 31 |
| 204 | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 18 |
| speed | TimeoutError | - | 12 |
| geo | TimeoutError | - | 12 |
| 204 | ProxyError | - | 10 |
| speed | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
