# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-17 02:15:33 |
| 运行耗时 | 233.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 79323 |
| 去重后节点 | 24537 |
| TCP 可达 | 3000 |
| 真实可用 | 538 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24537 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.1 |
| tcp | 32.8 |
| probe | 53.4 |
| real_test | 121.7 |
| generate | 19.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45707 |
| trojan | 12568 |
| vmess | 10856 |
| shadowsocks | 9651 |
| hysteria2 | 270 |
| shadowsocksr | 131 |
| http | 97 |
| socks | 31 |
| hysteria | 8 |
| tuic | 4 |

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
| 79.21 | shadowsocks | 256.1 | 622.2 | 21.85 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 156.146.38.170 |
| 79.14 | shadowsocks | 257.3 | 622.1 | 21.82 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 156.146.38.168 |
| 79.13 | shadowsocks | 259.7 | 623.6 | 21.77 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 156.146.38.169 |
| 79.1 | shadowsocks | 260.8 | 628.7 | 21.74 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 156.146.38.167 |
| 78.15 | shadowsocks | 280.4 | 680.7 | 21.29 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 108.181.57.93 |
| 77.81 | shadowsocks | 269.1 | 675.2 | 21.55 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 37.19.198.244 |
| 77.81 | shadowsocks | 273.3 | 669.8 | 21.45 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 37.19.198.160 |
| 77.38 | shadowsocks | 313.4 | 850.3 | 20.52 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 50.114.177.235 |
| 76.82 | shadowsocks | 337.7 | 882.7 | 19.96 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 185.196.61.82 |
| 76.73 | shadowsocks | 276.7 | 678.5 | 21.37 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 37.19.198.243 |
| 73.4 | shadowsocks | 298.4 | 564.8 | 20.87 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 173.244.56.6 |
| 73.38 | shadowsocks | 295.4 | 560.9 | 20.94 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 173.244.56.9 |
| 73.25 | shadowsocks | 286.6 | 524.0 | 21.14 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 108.181.0.177 |
| 73.1 | shadowsocks | 294.5 | 567.6 | 20.96 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 108.181.118.10 |
| 71.6 | shadowsocks | 544.5 | 1474.1 | 15.17 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 68.168.222.210 |
| 70.74 | shadowsocks | 353.8 | 874.4 | 19.59 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 184.75.221.134 |
| 70.23 | shadowsocks | 363.0 | 349.5 | 19.37 | 1.89 | 9.53 | 13.06 | 18.3 | Au1rxx-base64 | 149.22.87.204 |
| 69.52 | shadowsocks | 326.3 | 617.0 | 20.22 | 0.0 | 10.0 | 13.06 | 18.3 | Au1rxx-base64 | 149.22.95.183 |
| 69.19 | vless | 316.6 | 723.0 | 20.45 | 0.0 | 10.0 | 1.44 | 18.3 | Au1rxx-base64 | 47.89.186.170 |
| 68.34 | trojan | 301.1 | 583.9 | 20.81 | 0.0 | 10.0 | 13.34 | 15.98 | DeltaKronecker-all | 165.22.168.182 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | 0.956 | 136 | 5452 | prefer |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.827 | 0.827 | 110 | 149 | prefer |
| DeltaKronecker-all | 0.625 | 0.545 | 497 | 8462 | observe |
| mheidari-all | 0.426 | 0.333 | 24 | 16574 | observe |
| nscl5-all | 0.328 | 1.0 | 1 | 1821 | observe |
| xiaoji235-airport-v2ray-all | 0.322 | 1.0 | 1 | 1680 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4470 | observe |
| Epodonios-all | 0.255 | None | 0 | 6574 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6815 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4223 | observe |
| barry-far-vless | 0.255 | None | 0 | 4857 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5260 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 110 |
| geo | TimeoutError | - | 92 |
| geo | ClientOSError | - | 30 |
| speed | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | status | 403 | 1 |
| 204 | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
