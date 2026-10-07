# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-07 12:42:31 |
| 运行耗时 | 639.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98651 |
| 去重后节点 | 27328 |
| TCP 可达 | 3000 |
| 真实可用 | 429 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27328 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 44.6 |
| probe | 294.6 |
| real_test | 200.0 |
| generate | 90.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57814 |
| vmess | 16051 |
| shadowsocks | 11590 |
| trojan | 10802 |
| hysteria2 | 1463 |
| http | 612 |
| shadowsocksr | 166 |
| socks | 92 |
| anytls | 34 |
| hysteria | 17 |
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
| 81.71 | hysteria2 | 244.2 | 228.7 | 22.12 | 6.43 | 7.32 | 12.86 | 20.0 | Au1rxx-base64 | open.2ml.bid |
| 81.61 | trojan | 254.3 | 590.3 | 21.89 | 0.0 | 9.32 | 13.5 | 20.0 | Au1rxx-base64 | guided-ferret.rooster465.autos |
| 81.59 | shadowsocks | 227.6 | 581.4 | 22.51 | 0.0 | 10.0 | 13.58 | 20.0 | Au1rxx-base64 | 5.78.51.123 |
| 81.57 | shadowsocks | 250.0 | 606.2 | 21.99 | 0.0 | 10.0 | 13.58 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 81.41 | shadowsocks | 235.4 | 595.5 | 22.33 | 0.0 | 10.0 | 13.58 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 81.34 | shadowsocks | 238.4 | 603.5 | 22.26 | 0.0 | 10.0 | 13.58 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 81.01 | trojan | 335.5 | 811.1 | 20.01 | 0.0 | 10.0 | 13.5 | 20.0 | Au1rxx-base64 | 34.220.15.24 |
| 80.83 | hysteria2 | 241.7 | 236.3 | 22.18 | 6.14 | 9.86 | 12.86 | 20.0 | Au1rxx-base64 | 158.101.148.79 |
| 80.08 | vless | 173.5 | 466.6 | 23.76 | 0.0 | 10.0 | 6.32 | 20.0 | Au1rxx-base64 | 47.251.108.158 |
| 78.6 | vless | 237.3 | 581.9 | 22.28 | 0.0 | 10.0 | 6.32 | 20.0 | Au1rxx-base64 | 15.204.97.216 |
| 78.41 | shadowsocks | 277.2 | 272.8 | 21.36 | 4.77 | 9.92 | 13.58 | 20.0 | Au1rxx-base64 | 149.22.87.240 |
| 78.19 | vless | 255.1 | 639.7 | 21.87 | 0.0 | 10.0 | 6.32 | 20.0 | Au1rxx-base64 | 15.204.97.197 |
| 77.69 | shadowsocks | 297.8 | 669.2 | 20.88 | 0.0 | 10.0 | 13.58 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 77.48 | hysteria2 | 347.8 | 759.5 | 19.73 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 129.213.91.185 |
| 77.39 | shadowsocks | 298.4 | 661.9 | 20.87 | 0.0 | 10.0 | 13.58 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 77.37 | shadowsocks | 303.2 | 674.7 | 20.76 | 0.0 | 10.0 | 13.58 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 76.03 | shadowsocks | 273.5 | 547.6 | 21.45 | 0.0 | 10.0 | 13.58 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 76.01 | shadowsocks | 283.8 | 606.0 | 21.21 | 0.0 | 10.0 | 13.58 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 75.84 | trojan | 387.3 | 296.5 | 18.81 | 3.88 | 9.92 | 13.5 | 20.0 | Au1rxx-base64 | 43.207.89.91 |
| 75.69 | trojan | 332.9 | 336.7 | 20.07 | 2.37 | 9.93 | 13.5 | 20.0 | Au1rxx-base64 | 54.65.177.190 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | 0.913 | 332 | 1830 | prefer |
| mheidari-all | 0.924 | 0.86 | 43 | 23381 | prefer |
| Surfboard-tg-mixed | 0.721 | 0.644 | 90 | 7069 | prefer |
| ermaozi | 0.644 | 0.622 | 45 | 664 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7480 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9550 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5616 | observe |
| barry-far-vless | 0.255 | None | 0 | 5861 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1830 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 24 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 19 |
| speed | ClientOSError | - | 11 |
| speed | TimeoutError | - | 8 |
| geo | ClientOSError | - | 6 |
| geo | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
