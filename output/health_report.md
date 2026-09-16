# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 16:09:09 |
| 运行耗时 | 584.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89631 |
| 去重后节点 | 24406 |
| TCP 可达 | 3000 |
| 真实可用 | 406 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24406 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 41.3 |
| probe | 230.4 |
| real_test | 220.9 |
| generate | 83.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53320 |
| vmess | 14341 |
| shadowsocks | 10578 |
| trojan | 9136 |
| hysteria2 | 1495 |
| http | 561 |
| shadowsocksr | 127 |
| socks | 60 |
| hysteria | 8 |
| tuic | 3 |
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
| 81.51 | vless | 230.4 | 612.0 | 22.45 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 195.123.235.177 |
| 80.75 | vless | 263.0 | 649.6 | 21.69 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.232 |
| 80.64 | vless | 267.6 | 711.2 | 21.58 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.184 |
| 80.6 | vless | 269.4 | 688.5 | 21.54 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.182 |
| 80.49 | vless | 274.4 | 721.9 | 21.43 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.173 |
| 80.37 | shadowsocks | 217.4 | 577.2 | 22.75 | 0.0 | 10.0 | 13.34 | 18.28 | Au1rxx-base64 | 198.98.53.130 |
| 80.1 | hysteria2 | 247.7 | 648.8 | 22.04 | 0.0 | 10.0 | 13.64 | 15.52 | mheidari-all | 159.223.157.129 |
| 79.81 | vless | 303.5 | 694.9 | 20.75 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.52 |
| 79.66 | vless | 310.2 | 859.5 | 20.6 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 137.184.218.169 |
| 79.03 | vless | 259.9 | 633.5 | 21.76 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.225 |
| 78.9 | vless | 342.9 | 885.4 | 19.84 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 216.152.147.28 |
| 78.77 | vless | 348.4 | 903.9 | 19.71 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.224 |
| 78.35 | vless | 366.5 | 943.8 | 19.29 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.168 |
| 78.28 | vless | 294.2 | 672.6 | 20.97 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.35 |
| 77.15 | shadowsocks | 237.2 | 657.7 | 22.29 | 0.0 | 10.0 | 13.34 | 15.52 | mheidari-all | 37.19.198.236 |
| 76.77 | vless | 364.3 | 943.0 | 19.35 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.75 |
| 76.72 | vless | 366.8 | 1001.7 | 19.29 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.202 |
| 76.67 | vless | 367.9 | 631.9 | 19.26 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.212 |
| 76.64 | shadowsocks | 280.2 | 645.5 | 21.29 | 0.0 | 10.0 | 13.34 | 18.28 | Au1rxx-base64 | 156.146.38.170 |
| 76.56 | vless | 333.2 | 747.4 | 20.06 | 0.0 | 10.0 | 10.78 | 18.28 | Au1rxx-base64 | 169.40.42.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.985 | 0.918 | 61 | 17973 | prefer |
| Au1rxx-base64 | 0.918 | 0.853 | 259 | 1698 | prefer |
| Surfboard-tg-mixed | 0.901 | 0.833 | 54 | 7470 | prefer |
| ermaozi | 0.764 | 0.773 | 22 | 353 | prefer |
| DeltaKronecker-all | 0.73 | 0.653 | 101 | 6081 | prefer |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4206 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5115 | observe |
| Epodonios-all | 0.255 | None | 0 | 7938 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9150 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5979 | observe |
| barry-far-vless | 0.255 | None | 0 | 6195 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1698 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 16 |
| geo | TimeoutError | - | 16 |
| 204 | ProxyError | - | 12 |
| geo | ClientOSError | - | 12 |
| speed | ClientOSError | - | 12 |
| speed | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
