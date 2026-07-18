# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-18 19:02:53 |
| 运行耗时 | 380.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 88176 |
| 去重后节点 | 23077 |
| TCP 可达 | 3000 |
| 真实可用 | 810 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23077 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.2 |
| tcp | 32.0 |
| probe | 72.2 |
| real_test | 229.3 |
| generate | 40.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51947 |
| trojan | 14331 |
| vmess | 10758 |
| shadowsocks | 10547 |
| hysteria2 | 323 |
| shadowsocksr | 127 |
| socks | 65 |
| http | 55 |
| hysteria | 14 |
| tuic | 7 |
| anytls | 2 |

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
| 78.58 | shadowsocks | 231.6 | 664.9 | 22.42 | 0.0 | 10.0 | 12.16 | 18.5 | mheidari-all | 108.181.57.93 |
| 77.28 | shadowsocks | 229.6 | 628.3 | 22.46 | 0.0 | 9.0 | 12.16 | 17.66 | Au1rxx-base64 | 37.19.198.236 |
| 77.28 | shadowsocks | 229.7 | 634.2 | 22.46 | 0.0 | 9.0 | 12.16 | 17.66 | Au1rxx-base64 | 37.19.198.243 |
| 77.06 | shadowsocks | 225.6 | 601.6 | 22.56 | 0.0 | 10.0 | 12.16 | 18.5 | mheidari-all | 198.98.53.130 |
| 76.61 | shadowsocks | 233.4 | 630.3 | 22.38 | 0.0 | 10.0 | 12.16 | 18.5 | mheidari-all | 147.90.234.133 |
| 76.17 | shadowsocks | 235.0 | 646.5 | 22.34 | 0.0 | 9.01 | 12.16 | 17.66 | Au1rxx-base64 | 37.19.198.244 |
| 75.45 | shadowsocks | 349.1 | 850.6 | 19.7 | 0.0 | 10.0 | 12.16 | 18.5 | mheidari-all | 185.196.61.82 |
| 73.93 | shadowsocks | 273.8 | 618.5 | 21.44 | 0.0 | 8.97 | 12.16 | 17.66 | Au1rxx-base64 | 156.146.38.169 |
| 73.3 | shadowsocks | 288.4 | 656.0 | 21.1 | 0.0 | 8.97 | 12.16 | 17.66 | Au1rxx-base64 | 156.146.38.168 |
| 72.43 | vless | 245.9 | 688.5 | 22.09 | 0.0 | 10.0 | 1.84 | 18.5 | mheidari-all | 47.89.186.170 |
| 72.41 | shadowsocks | 498.0 | 1118.0 | 16.25 | 0.0 | 10.0 | 12.16 | 18.5 | mheidari-all | 68.168.222.210 |
| 71.93 | shadowsocks | 281.8 | 643.1 | 21.26 | 0.0 | 8.97 | 12.16 | 17.66 | Au1rxx-base64 | 156.146.38.170 |
| 71.7 | shadowsocks | 470.3 | 1351.2 | 16.89 | 0.0 | 8.99 | 12.16 | 17.66 | Au1rxx-base64 | 37.19.198.160 |
| 71.31 | shadowsocks | 329.6 | 858.9 | 20.15 | 0.0 | 10.0 | 12.16 | 18.5 | mheidari-all | 50.114.177.235 |
| 71.04 | shadowsocks | 242.7 | 655.8 | 22.16 | 0.0 | 8.7 | 12.16 | 17.66 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 70.11 | trojan | 566.9 | 1471.8 | 14.66 | 0.0 | 10.0 | 13.6 | 18.5 | mheidari-all | 148.72.168.35 |
| 70.07 | shadowsocks | 312.2 | 566.7 | 20.55 | 0.0 | 8.96 | 12.16 | 17.66 | Au1rxx-base64 | 173.244.56.6 |
| 69.89 | shadowsocks | 315.2 | 613.6 | 20.48 | 0.0 | 8.96 | 12.16 | 17.66 | Au1rxx-base64 | 173.244.56.9 |
| 69.6 | trojan | 372.6 | 650.5 | 19.15 | 0.0 | 10.0 | 13.6 | 16.3 | Surfboard-tg-mixed | 188.114.98.0 |
| 69.27 | trojan | 455.9 | 763.3 | 17.22 | 0.0 | 10.0 | 13.6 | 18.5 | mheidari-all | 104.17.121.43 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.817 | 0.817 | 120 | 150 | prefer |
| Surfboard-tg-mixed | 0.797 | 0.72 | 164 | 5713 | prefer |
| mheidari-all | 0.713 | 0.633 | 867 | 19946 | prefer |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 4321 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 198 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4371 | observe |
| Epodonios-all | 0.255 | None | 0 | 6898 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7086 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4332 | observe |
| barry-far-vless | 0.255 | None | 0 | 4962 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5340 | observe |
| nscl5-all | 0.254 | None | 0 | 1976 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 212 |
| speed | ClientOSError | - | 84 |
| cn-block | TimeoutError | - | 53 |
| geo | ClientOSError | - | 46 |
| 204 | TimeoutError | - | 30 |
| speed | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
