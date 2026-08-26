# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-26 12:45:16 |
| 运行耗时 | 248.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 78614 |
| 去重后节点 | 22194 |
| TCP 可达 | 3000 |
| 真实可用 | 520 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22194 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.5 |
| tcp | 34.9 |
| probe | 52.6 |
| real_test | 113.0 |
| generate | 39.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49633 |
| shadowsocks | 10460 |
| vmess | 10237 |
| trojan | 6422 |
| hysteria2 | 1483 |
| http | 172 |
| shadowsocksr | 134 |
| socks | 63 |
| hysteria | 7 |
| tuic | 3 |

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
| 83.27 | http | 192.3 | 497.4 | 23.33 | 0.0 | 10.0 | 14.42 | 18.52 | zhangkai | 138.199.35.216 |
| 82.45 | http | 227.7 | 592.4 | 22.51 | 0.0 | 10.0 | 14.42 | 18.52 | zhangkai | 138.199.35.198 |
| 81.9 | vless | 190.7 | 491.7 | 23.36 | 0.0 | 10.0 | 10.04 | 18.5 | Au1rxx-base64 | 69.63.193.78 |
| 81.05 | vless | 227.5 | 570.0 | 22.51 | 0.0 | 10.0 | 10.04 | 18.5 | Au1rxx-base64 | 15.204.97.216 |
| 80.92 | vless | 233.0 | 556.0 | 22.38 | 0.0 | 10.0 | 10.04 | 18.5 | Au1rxx-base64 | 15.204.97.195 |
| 80.2 | trojan | 230.7 | 524.4 | 22.44 | 0.0 | 10.0 | 11.76 | 18.5 | Au1rxx-base64 | 35.91.251.124 |
| 79.65 | vless | 201.5 | 517.5 | 23.11 | 0.0 | 10.0 | 10.04 | 18.5 | Au1rxx-base64 | 166.88.186.151 |
| 79.28 | vless | 217.8 | 575.1 | 22.74 | 0.0 | 10.0 | 10.04 | 18.5 | Au1rxx-base64 | 108.186.202.51 |
| 79.25 | vless | 305.3 | 794.4 | 20.71 | 0.0 | 10.0 | 10.04 | 18.5 | Au1rxx-base64 | 15.204.97.214 |
| 79.17 | vless | 308.8 | 815.2 | 20.63 | 0.0 | 10.0 | 10.04 | 18.5 | Au1rxx-base64 | 15.204.97.197 |
| 79.11 | vless | 311.2 | 813.9 | 20.57 | 0.0 | 10.0 | 10.04 | 18.5 | Au1rxx-base64 | 15.204.97.209 |
| 79.07 | vless | 183.4 | 497.2 | 23.53 | 0.0 | 10.0 | 10.04 | 18.5 | Au1rxx-base64 | 31.58.50.200 |
| 78.42 | trojan | 285.8 | 767.0 | 21.16 | 0.0 | 10.0 | 11.76 | 18.5 | Au1rxx-base64 | 14.1.28.76 |
| 78.19 | trojan | 209.6 | 547.1 | 22.93 | 0.0 | 10.0 | 11.76 | 18.5 | Au1rxx-base64 | us01.duotg.top |
| 77.06 | trojan | 252.7 | 589.5 | 21.93 | 0.0 | 7.37 | 11.76 | 18.5 | Au1rxx-base64 | sincere-gelding.rooster465.autos |
| 75.47 | http | 341.0 | 622.1 | 19.88 | 0.0 | 10.0 | 14.42 | 18.52 | zhangkai | 38.28.193.188 |
| 75.02 | shadowsocks | 271.3 | 275.0 | 21.5 | 4.69 | 9.95 | 13.54 | 16.58 | Surfboard-tg-mixed | 149.22.87.240 |
| 74.98 | trojan | 218.4 | 529.3 | 22.72 | 0.0 | 10.0 | 11.76 | 18.5 | Au1rxx-base64 | 107.150.105.84 |
| 74.81 | shadowsocks | 274.0 | 281.3 | 21.44 | 4.45 | 9.94 | 13.54 | 16.58 | Surfboard-tg-mixed | 149.22.87.204 |
| 74.75 | vless | 299.1 | 267.3 | 20.85 | 4.98 | 9.58 | 10.04 | 16.58 | Surfboard-tg-mixed | 31.76.91.72 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 1.0 | 29 | 14222 | prefer |
| Au1rxx-base64 | 0.976 | 0.899 | 327 | 1988 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| DeltaKronecker-all | 0.92 | 0.854 | 48 | 6107 | prefer |
| Surfboard-tg-mixed | 0.761 | 0.683 | 183 | 6518 | prefer |
| nscl5-all | 0.475 | 1.0 | 5 | 887 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 206 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4825 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1992 | observe |
| Epodonios-all | 0.255 | None | 0 | 7010 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7145 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5376 | observe |
| barry-far-vless | 0.255 | None | 0 | 5628 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 32 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 9 |
| speed | ClientOSError | - | 8 |
| geo | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:37154: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
