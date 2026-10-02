# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-02 04:00:59 |
| 运行耗时 | 947.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98613 |
| 去重后节点 | 27530 |
| TCP 可达 | 3000 |
| 真实可用 | 465 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27530 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.6 |
| tcp | 47.4 |
| probe | 314.6 |
| real_test | 493.8 |
| generate | 82.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60100 |
| vmess | 15717 |
| shadowsocks | 11591 |
| trojan | 8995 |
| hysteria2 | 1414 |
| http | 509 |
| shadowsocksr | 165 |
| socks | 61 |
| anytls | 35 |
| hysteria | 17 |
| tuic | 9 |

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
| 84.16 | hysteria2 | 243.4 | 543.9 | 22.14 | 0.0 | 10.0 | 14.4 | 18.62 | Au1rxx-base64 | 192.255.128.123 |
| 82.41 | hysteria2 | 269.4 | 549.5 | 21.54 | 0.0 | 10.0 | 14.4 | 18.62 | Au1rxx-base64 | 66.94.121.46 |
| 82.35 | vless | 232.8 | 513.9 | 22.39 | 0.0 | 10.0 | 12.33 | 19.6 | mheidari-all | 47.251.108.158 |
| 80.42 | vless | 269.7 | 589.2 | 21.53 | 0.0 | 10.0 | 12.33 | 18.62 | Au1rxx-base64 | 15.204.97.216 |
| 80.32 | shadowsocks | 237.0 | 610.5 | 22.29 | 0.0 | 10.0 | 13.41 | 18.62 | Au1rxx-base64 | 156.146.38.170 |
| 80.27 | shadowsocks | 239.0 | 612.9 | 22.24 | 0.0 | 10.0 | 13.41 | 18.62 | Au1rxx-base64 | 156.146.38.169 |
| 80.24 | shadowsocks | 240.7 | 620.5 | 22.21 | 0.0 | 10.0 | 13.41 | 18.62 | Au1rxx-base64 | 156.146.38.167 |
| 79.8 | hysteria2 | 322.5 | 724.4 | 20.31 | 0.0 | 10.0 | 14.4 | 18.62 | Au1rxx-base64 | 159.223.157.129 |
| 79.15 | vless | 275.4 | 588.7 | 21.4 | 0.0 | 10.0 | 12.33 | 18.62 | Au1rxx-base64 | 172.235.43.210 |
| 78.94 | vless | 301.1 | 718.1 | 20.81 | 0.0 | 10.0 | 12.33 | 18.62 | Au1rxx-base64 | 79.141.172.154 |
| 78.94 | vless | 314.6 | 682.9 | 20.49 | 0.0 | 10.0 | 12.33 | 18.62 | Au1rxx-base64 | 198.251.78.29 |
| 78.9 | vless | 272.4 | 577.7 | 21.47 | 0.0 | 10.0 | 12.33 | 18.62 | Au1rxx-base64 | 172.233.139.46 |
| 77.11 | vless | 290.4 | 708.9 | 21.06 | 0.0 | 10.0 | 12.33 | 19.6 | mheidari-all | 67.220.73.204 |
| 77.06 | vless | 298.6 | 578.1 | 20.87 | 0.0 | 10.0 | 12.33 | 18.62 | Au1rxx-base64 | 23.95.222.127 |
| 76.41 | vless | 336.5 | 704.8 | 19.99 | 0.0 | 10.0 | 12.33 | 18.62 | Au1rxx-base64 | 137.175.82.40 |
| 75.68 | shadowsocks | 300.3 | 622.0 | 20.83 | 0.0 | 10.0 | 13.41 | 19.6 | mheidari-all | 108.181.118.10 |
| 75.61 | shadowsocks | 275.5 | 521.2 | 21.4 | 0.0 | 10.0 | 13.41 | 19.6 | mheidari-all | 216.105.168.18 |
| 75.6 | shadowsocks | 304.8 | 732.1 | 20.72 | 0.0 | 10.0 | 13.41 | 16.7 | Surfboard-tg-mixed | 5.78.51.123 |
| 75.22 | shadowsocks | 306.4 | 803.3 | 20.69 | 0.0 | 10.0 | 13.41 | 18.62 | Au1rxx-base64 | 66.23.201.172 |
| 75.0 | vless | 255.9 | 617.4 | 21.85 | 0.0 | 7.2 | 12.33 | 18.62 | Au1rxx-base64 | us51.mech-pro.online |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | 0.917 | 278 | 1741 | prefer |
| Surfboard-tg-mixed | 0.921 | 0.852 | 61 | 7165 | prefer |
| ermaozi | 0.543 | 0.52 | 25 | 618 | observe |
| mheidari-all | 0.386 | 0.305 | 469 | 23308 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7654 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9195 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5778 | observe |
| barry-far-vless | 0.255 | None | 0 | 6015 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4310 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1741 | observe |
| ermaozi-get_subscribe | 0.226 | 0.5 | 2 | 475 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 178 |
| speed | TimeoutError | - | 99 |
| geo | ClientOSError | - | 29 |
| speed | ClientOSError | - | 23 |
| cn-block | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 10 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
