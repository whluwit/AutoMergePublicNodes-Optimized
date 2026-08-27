# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-27 06:58:18 |
| 运行耗时 | 242.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 88858 |
| 去重后节点 | 24427 |
| TCP 可达 | 3000 |
| 真实可用 | 510 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24427 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.5 |
| tcp | 39.7 |
| probe | 49.5 |
| real_test | 108.7 |
| generate | 36.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55361 |
| shadowsocks | 11878 |
| vmess | 11511 |
| trojan | 7624 |
| hysteria2 | 2063 |
| http | 164 |
| shadowsocksr | 137 |
| socks | 79 |
| anytls | 20 |
| hysteria | 16 |
| tuic | 5 |

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
| 82.89 | vless | 222.9 | 595.2 | 22.62 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 195.211.99.45 |
| 82.77 | hysteria2 | 273.6 | 685.5 | 21.44 | 0.0 | 10.0 | 13.39 | 19.04 | Au1rxx-base64 | 159.223.157.129 |
| 82.59 | vless | 235.8 | 640.9 | 22.32 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 195.211.99.49 |
| 82.21 | vless | 252.0 | 626.9 | 21.94 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 198.251.78.29 |
| 81.83 | vless | 268.7 | 689.5 | 21.56 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 216.152.147.28 |
| 81.48 | shadowsocks | 239.2 | 601.0 | 22.24 | 0.0 | 10.0 | 14.2 | 19.04 | Au1rxx-base64 | 198.98.53.130 |
| 81.22 | vless | 294.8 | 739.8 | 20.95 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 47.89.186.170 |
| 80.91 | shadowsocks | 263.7 | 655.9 | 21.67 | 0.0 | 10.0 | 14.2 | 19.04 | Au1rxx-base64 | 156.146.38.169 |
| 80.86 | shadowsocks | 261.6 | 638.8 | 21.72 | 0.0 | 10.0 | 14.2 | 19.04 | Au1rxx-base64 | 156.146.38.168 |
| 80.55 | vless | 289.8 | 698.7 | 21.07 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 137.184.218.169 |
| 79.95 | vless | 335.5 | 833.9 | 20.01 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 169.40.42.229 |
| 79.83 | vless | 330.3 | 703.4 | 20.13 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 169.40.42.232 |
| 79.78 | vless | 330.4 | 824.9 | 20.13 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 167.17.69.171 |
| 79.53 | vless | 351.8 | 885.6 | 19.63 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 169.40.42.179 |
| 79.32 | vless | 377.0 | 956.7 | 19.05 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 185.95.231.156 |
| 79.29 | vless | 378.4 | 973.9 | 19.02 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 79.127.243.217 |
| 79.09 | vless | 311.2 | 739.2 | 20.57 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 66.70.179.198 |
| 78.5 | vless | 369.2 | 815.7 | 19.23 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 169.40.42.75 |
| 78.35 | vless | 309.9 | 760.1 | 20.6 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 169.40.42.95 |
| 77.76 | vless | 302.7 | 735.8 | 20.77 | 0.0 | 10.0 | 11.23 | 19.04 | Au1rxx-base64 | 169.40.42.184 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | 0.93 | 329 | 1668 | prefer |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.862 | 0.786 | 154 | 6600 | prefer |
| mheidari-all | 0.523 | 0.442 | 104 | 19260 | observe |
| DeltaKronecker-all | 0.462 | 0.375 | 32 | 6107 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4825 | observe |
| Epodonios-all | 0.255 | None | 0 | 7097 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7131 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5353 | observe |
| barry-far-vless | 0.255 | None | 0 | 5696 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4011 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1668 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 43 |
| geo | ClientOSError | - | 21 |
| speed | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 15 |
| speed | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
