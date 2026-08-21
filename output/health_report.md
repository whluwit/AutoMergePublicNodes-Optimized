# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-21 01:06:41 |
| 运行耗时 | 361.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 95474 |
| 去重后节点 | 25198 |
| TCP 可达 | 3000 |
| 真实可用 | 1155 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25198 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 40.1 |
| probe | 74.0 |
| real_test | 210.2 |
| generate | 29.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51357 |
| trojan | 19290 |
| shadowsocks | 11435 |
| vmess | 10392 |
| hysteria2 | 2454 |
| shadowsocksr | 201 |
| http | 164 |
| socks | 124 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 10 |

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
| 83.42 | hysteria2 | 282.7 | 709.6 | 21.23 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 81.7 | shadowsocks | 257.9 | 637.9 | 21.81 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.6 | shadowsocks | 262.1 | 654.9 | 21.71 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 80.88 | shadowsocks | 293.2 | 741.4 | 20.99 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 80.8 | shadowsocks | 279.6 | 647.0 | 21.31 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.57 | hysteria2 | 300.6 | 577.6 | 20.82 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 150.241.102.127 |
| 80.47 | shadowsocks | 300.1 | 793.9 | 20.83 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 80.45 | vless | 293.4 | 716.7 | 20.99 | 0.0 | 10.0 | 10.2 | 19.7 | Surfboard-tg-mixed | 209.50.241.126 |
| 80.33 | trojan | 267.1 | 619.2 | 21.59 | 0.0 | 10.0 | 14.84 | 18.18 | mheidari-all | 64.94.95.114 |
| 80.18 | shadowsocks | 259.5 | 631.7 | 21.77 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 80.18 | trojan | 351.8 | 902.5 | 19.64 | 0.0 | 10.0 | 14.84 | 19.7 | Surfboard-tg-mixed | 64.74.163.118 |
| 79.73 | vless | 287.6 | 693.0 | 21.12 | 0.0 | 10.0 | 10.2 | 19.7 | Surfboard-tg-mixed | 184.107.141.174 |
| 79.53 | shadowsocks | 259.3 | 636.4 | 21.78 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 79.49 | trojan | 286.0 | 683.1 | 21.16 | 0.0 | 10.0 | 14.84 | 18.18 | mheidari-all | 64.94.95.117 |
| 79.2 | shadowsocks | 279.4 | 712.9 | 21.31 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 78.75 | vless | 281.6 | 670.3 | 21.26 | 0.0 | 10.0 | 10.2 | 19.7 | Surfboard-tg-mixed | 169.40.42.212 |
| 78.28 | vless | 383.9 | 842.0 | 18.89 | 0.0 | 10.0 | 10.2 | 19.7 | Surfboard-tg-mixed | 169.40.42.75 |
| 78.03 | shadowsocks | 283.1 | 634.3 | 21.22 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 77.68 | trojan | 332.5 | 823.9 | 20.08 | 0.0 | 10.0 | 14.84 | 18.18 | mheidari-all | 64.94.95.118 |
| 77.65 | shadowsocks | 320.4 | 834.1 | 20.36 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 38.180.135.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.989 | 548 | 1663 | prefer |
| zhangkai | 0.997 | 1.0 | 111 | 144 | prefer |
| Surfboard-tg-mixed | 0.872 | 0.794 | 287 | 6424 | prefer |
| mheidari-all | 0.812 | 0.733 | 363 | 21987 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 3031 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| Epodonios-all | 0.255 | None | 0 | 7184 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3990 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7352 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5136 | observe |
| barry-far-vless | 0.255 | None | 0 | 5451 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4586 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1663 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 81 |
| geo | ClientOSError | - | 41 |
| speed | TimeoutError | - | 40 |
| cn-block | TimeoutError | - | 19 |
| speed | ClientOSError | - | 11 |
| cn-block | ClientOSError | - | 5 |
| 204 | TimeoutError | - | 4 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
