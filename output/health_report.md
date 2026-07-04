# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-04 13:17:51 |
| 运行耗时 | 196.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 78476 |
| 去重后节点 | 23648 |
| TCP 可达 | 3000 |
| 真实可用 | 251 |
| Verified 输出 | 251 |
| Global 输出 | 266 |
| All 输出 | 23648 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.3 |
| tcp | 31.0 |
| probe | 44.8 |
| real_test | 70.8 |
| generate | 43.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45328 |
| trojan | 12531 |
| vmess | 10519 |
| shadowsocks | 9424 |
| hysteria2 | 301 |
| shadowsocksr | 154 |
| http | 135 |
| socks | 74 |
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
| 78.7 | shadowsocks | 257.9 | 628.3 | 21.81 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 156.146.38.169 |
| 78.61 | shadowsocks | 261.9 | 642.5 | 21.72 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 37.19.198.160 |
| 78.49 | shadowsocks | 266.9 | 666.7 | 21.6 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 37.19.198.243 |
| 77.78 | shadowsocks | 254.3 | 635.8 | 21.89 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 156.146.38.168 |
| 77.71 | shadowsocks | 300.5 | 770.5 | 20.82 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 37.19.198.236 |
| 77.01 | shadowsocks | 317.6 | 821.3 | 20.43 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 37.19.198.244 |
| 76.79 | shadowsocks | 340.3 | 879.8 | 19.9 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 156.146.38.167 |
| 72.69 | shadowsocks | 297.3 | 531.5 | 20.9 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 149.22.95.183 |
| 71.86 | shadowsocks | 377.3 | 811.0 | 19.05 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 108.181.0.177 |
| 71.03 | shadowsocks | 379.2 | 766.8 | 19.0 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 108.181.118.10 |
| 70.86 | shadowsocks | 333.3 | 623.8 | 20.06 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 173.244.56.9 |
| 69.46 | shadowsocks | 380.2 | 737.0 | 18.98 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 173.244.56.6 |
| 69.17 | shadowsocks | 330.8 | 851.9 | 20.12 | 0.0 | 10.0 | 13.33 | 13.22 | DeltaKronecker-all | 185.196.61.82 |
| 69.02 | shadowsocks | 373.1 | 357.8 | 19.14 | 1.58 | 9.45 | 13.33 | 17.56 | Au1rxx-base64 | 149.22.87.241 |
| 68.89 | shadowsocks | 374.8 | 360.4 | 19.1 | 1.48 | 9.45 | 13.33 | 17.56 | Au1rxx-base64 | 149.22.87.204 |
| 67.72 | vless | 418.0 | 918.5 | 18.1 | 0.0 | 10.0 | 6.69 | 17.56 | Au1rxx-base64 | 15.204.97.214 |
| 67.16 | vless | 278.7 | 697.8 | 21.33 | 0.0 | 10.0 | 6.69 | 14.14 | Surfboard-tg-mixed | 44.223.17.190 |
| 65.48 | trojan | 311.3 | 765.3 | 20.57 | 0.0 | 10.0 | 9.76 | 13.22 | DeltaKronecker-all | 45.32.198.247 |
| 65.42 | trojan | 302.9 | 746.6 | 20.77 | 0.0 | 10.0 | 9.76 | 13.22 | DeltaKronecker-all | 45.32.195.168 |
| 65.33 | shadowsocks | 305.5 | 590.9 | 20.71 | 0.0 | 10.0 | 13.33 | 17.56 | Au1rxx-base64 | 216.105.168.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.69 | 0.7 | 30 | 68 | observe |
| DeltaKronecker-all | 0.677 | 0.599 | 157 | 7309 | observe |
| Surfboard-tg-mixed | 0.664 | 0.585 | 159 | 6003 | observe |
| nscl5-all | 0.359 | 1.0 | 2 | 1189 | observe |
| mheidari-all | 0.344 | 0.333 | 12 | 16374 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4579 | observe |
| Epodonios-all | 0.255 | None | 0 | 6895 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3967 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7174 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4552 | observe |
| barry-far-vless | 0.255 | None | 0 | 5028 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5333 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.226 | None | 0 | 1263 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 56 |
| 204 | ProxyError | - | 16 |
| 204 | TimeoutError | - | 15 |
| geo | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| 204 | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 6 |
| geo | ProxyError | - | 6 |
| speed | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| geo | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | status | 403 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 251 | - |
| global | False | 300 | 266 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
