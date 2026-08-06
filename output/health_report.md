# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-06 23:57:28 |
| 运行耗时 | 193.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 88841 |
| 去重后节点 | 24642 |
| TCP 可达 | 3000 |
| 真实可用 | 430 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24642 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.1 |
| tcp | 36.6 |
| probe | 49.7 |
| real_test | 80.3 |
| generate | 20.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51681 |
| vmess | 13341 |
| trojan | 11821 |
| shadowsocks | 10225 |
| hysteria2 | 1480 |
| socks | 129 |
| shadowsocksr | 74 |
| anytls | 30 |
| http | 25 |
| hysteria | 21 |
| tuic | 14 |

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
| 82.6 | trojan | 275.1 | 726.3 | 21.41 | 0.0 | 10.0 | 14.63 | 19.56 | Au1rxx-base64 | 153.75.250.171 |
| 81.13 | hysteria2 | 247.6 | 670.7 | 22.05 | 0.0 | 10.0 | 10.62 | 19.56 | Au1rxx-base64 | 159.223.157.129 |
| 80.77 | shadowsocks | 238.8 | 641.5 | 22.25 | 0.0 | 10.0 | 12.96 | 19.56 | Au1rxx-base64 | 37.19.198.236 |
| 80.57 | shadowsocks | 247.5 | 667.2 | 22.05 | 0.0 | 10.0 | 12.96 | 19.56 | Au1rxx-base64 | 37.19.198.160 |
| 80.33 | shadowsocks | 257.8 | 684.1 | 21.81 | 0.0 | 10.0 | 12.96 | 19.56 | Au1rxx-base64 | 37.19.198.244 |
| 80.12 | hysteria2 | 295.3 | 814.5 | 20.94 | 0.0 | 10.0 | 10.62 | 19.56 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 80.0 | hysteria2 | 300.5 | 828.3 | 20.82 | 0.0 | 10.0 | 10.62 | 19.56 | Au1rxx-base64 | 138.124.68.188 |
| 79.52 | shadowsocks | 271.2 | 701.6 | 21.5 | 0.0 | 10.0 | 12.96 | 19.56 | Au1rxx-base64 | 68.168.222.210 |
| 78.03 | trojan | 307.3 | 656.8 | 20.66 | 0.0 | 10.0 | 14.63 | 19.56 | Au1rxx-base64 | 163.245.196.68 |
| 77.69 | shadowsocks | 230.4 | 603.3 | 22.44 | 0.0 | 10.0 | 12.96 | 19.56 | Au1rxx-base64 | 198.98.53.130 |
| 77.33 | shadowsocks | 280.9 | 650.3 | 21.28 | 0.0 | 10.0 | 12.96 | 19.56 | Au1rxx-base64 | 156.146.38.167 |
| 77.03 | shadowsocks | 275.8 | 640.7 | 21.39 | 0.0 | 10.0 | 12.96 | 19.56 | Au1rxx-base64 | 156.146.38.170 |
| 76.49 | shadowsocks | 332.6 | 803.1 | 20.08 | 0.0 | 10.0 | 12.96 | 19.56 | Au1rxx-base64 | 156.146.38.169 |
| 75.89 | shadowsocks | 360.8 | 873.6 | 19.43 | 0.0 | 10.0 | 12.96 | 19.56 | Au1rxx-base64 | 185.196.61.82 |
| 74.65 | trojan | 366.8 | 856.9 | 19.29 | 0.0 | 10.0 | 14.63 | 19.56 | Au1rxx-base64 | 64.94.95.115 |
| 74.61 | trojan | 324.9 | 616.3 | 20.26 | 0.0 | 10.0 | 14.63 | 19.56 | Au1rxx-base64 | 64.94.95.117 |
| 74.4 | trojan | 355.2 | 828.3 | 19.55 | 0.0 | 10.0 | 14.63 | 19.56 | Au1rxx-base64 | 64.94.95.118 |
| 73.94 | http | 359.7 | 638.5 | 19.45 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 73.89 | trojan | 363.4 | 848.7 | 19.37 | 0.0 | 10.0 | 14.63 | 19.56 | Au1rxx-base64 | 64.94.95.114 |
| 73.87 | http | 353.3 | 641.8 | 19.6 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | 0.946 | 336 | 1338 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| mheidari-all | 0.649 | 0.57 | 135 | 20787 | observe |
| DeltaKronecker-all | 0.507 | 0.75 | 8 | 5897 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 5184 | observe |
| Surfboard-tg-mixed | 0.397 | 0.417 | 12 | 5904 | observe |
| nscl5-all | 0.32 | 1.0 | 1 | 1621 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5219 | observe |
| Epodonios-all | 0.255 | None | 0 | 6481 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7217 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4729 | observe |
| barry-far-vless | 0.255 | None | 0 | 5041 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5225 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 25 |
| geo | ClientOSError | - | 21 |
| speed | ClientOSError | - | 15 |
| speed | TimeoutError | - | 10 |
| 204 | TimeoutError | - | 7 |
| cn-block | TimeoutError | - | 3 |
| 204 | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
