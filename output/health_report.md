# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-04 14:02:55 |
| 运行耗时 | 224.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86791 |
| 去重后节点 | 24317 |
| TCP 可达 | 3000 |
| 真实可用 | 464 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24317 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.6 |
| tcp | 36.7 |
| probe | 51.1 |
| real_test | 100.7 |
| generate | 28.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53088 |
| vmess | 12986 |
| shadowsocks | 10083 |
| trojan | 9366 |
| hysteria2 | 1010 |
| socks | 79 |
| shadowsocksr | 77 |
| http | 63 |
| hysteria | 19 |
| tuic | 10 |
| anytls | 10 |

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
| 83.3 | http | 261.0 | 672.2 | 21.74 | 0.0 | 10.0 | 14.78 | 19.78 | zhangkai | 156.146.59.33 |
| 81.45 | hysteria2 | 241.3 | 645.9 | 22.19 | 0.0 | 10.0 | 13.64 | 16.72 | Au1rxx-base64 | 159.223.157.129 |
| 77.51 | shadowsocks | 240.9 | 649.4 | 22.2 | 0.0 | 10.0 | 12.59 | 16.72 | Au1rxx-base64 | 37.19.198.243 |
| 77.42 | shadowsocks | 245.0 | 633.7 | 22.11 | 0.0 | 10.0 | 12.59 | 16.72 | Au1rxx-base64 | 37.19.198.244 |
| 77.04 | vless | 251.7 | 688.6 | 21.95 | 0.0 | 10.0 | 8.37 | 16.72 | Au1rxx-base64 | 47.253.226.114 |
| 76.75 | vless | 264.2 | 650.4 | 21.66 | 0.0 | 10.0 | 8.37 | 16.72 | Au1rxx-base64 | 167.17.69.171 |
| 75.78 | shadowsocks | 294.1 | 724.9 | 20.97 | 0.0 | 10.0 | 12.59 | 16.72 | Au1rxx-base64 | 68.168.222.210 |
| 74.5 | shadowsocks | 278.4 | 645.5 | 21.33 | 0.0 | 10.0 | 12.59 | 16.72 | Au1rxx-base64 | 156.146.38.170 |
| 74.26 | shadowsocks | 251.9 | 678.2 | 21.95 | 0.0 | 10.0 | 12.59 | 16.72 | Au1rxx-base64 | 37.19.198.236 |
| 73.95 | shadowsocks | 272.9 | 628.8 | 21.46 | 0.0 | 10.0 | 12.59 | 16.72 | Au1rxx-base64 | 156.146.38.168 |
| 73.9 | vless | 351.3 | 871.9 | 19.65 | 0.0 | 10.0 | 8.37 | 16.72 | Au1rxx-base64 | 158.69.112.254 |
| 72.76 | shadowsocks | 273.8 | 634.8 | 21.44 | 0.0 | 10.0 | 12.59 | 16.72 | Au1rxx-base64 | 156.146.38.169 |
| 72.66 | hysteria2 | 364.5 | 700.4 | 19.34 | 0.0 | 10.0 | 13.64 | 16.72 | Au1rxx-base64 | 62.210.124.146 |
| 72.43 | shadowsocks | 317.0 | 718.0 | 20.44 | 0.0 | 10.0 | 12.59 | 16.72 | Au1rxx-base64 | 108.181.57.93 |
| 72.4 | shadowsocks | 340.7 | 831.3 | 19.89 | 0.0 | 10.0 | 12.59 | 16.72 | Au1rxx-base64 | 156.146.38.167 |
| 72.39 | vless | 258.4 | 676.1 | 21.8 | 0.0 | 10.0 | 8.37 | 16.72 | Au1rxx-base64 | 162.159.36.5 |
| 72.07 | hysteria2 | 417.3 | 856.1 | 18.12 | 0.0 | 10.0 | 13.64 | 16.72 | Au1rxx-base64 | 5.255.102.165 |
| 71.98 | vless | 421.8 | 1031.1 | 18.01 | 0.0 | 10.0 | 8.37 | 16.72 | Au1rxx-base64 | 169.40.42.15 |
| 71.67 | vless | 289.1 | 771.3 | 21.08 | 0.0 | 10.0 | 8.37 | 16.72 | Au1rxx-base64 | 104.17.101.139 |
| 70.94 | vless | 321.0 | 873.9 | 20.35 | 0.0 | 10.0 | 8.37 | 16.72 | Au1rxx-base64 | 104.21.76.231 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.984 | 1.0 | 52 | 72 | prefer |
| Au1rxx-base64 | 0.902 | 0.836 | 444 | 1686 | prefer |
| Surfboard-tg-mixed | 0.72 | 0.8 | 15 | 5397 | prefer |
| DeltaKronecker-all | 0.45 | 0.5 | 12 | 5788 | observe |
| mheidari-all | 0.39 | 0.304 | 69 | 20302 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 58 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5251 | observe |
| Epodonios-all | 0.255 | None | 0 | 5995 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7362 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4315 | observe |
| barry-far-vless | 0.255 | None | 0 | 4658 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5110 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 21 |
| speed | TimeoutError | - | 20 |
| geo | ClientOSError | - | 17 |
| cn-block | TimeoutError | - | 13 |
| speed | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 10 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
