# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-25 01:04:04 |
| 运行耗时 | 306.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 83622 |
| 去重后节点 | 23844 |
| TCP 可达 | 3000 |
| 真实可用 | 691 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23844 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.4 |
| tcp | 38.0 |
| probe | 58.1 |
| real_test | 164.7 |
| generate | 36.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52555 |
| shadowsocks | 11189 |
| vmess | 10446 |
| trojan | 7580 |
| hysteria2 | 1471 |
| http | 164 |
| shadowsocksr | 129 |
| socks | 68 |
| hysteria | 13 |
| tuic | 5 |
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
| 82.38 | hysteria2 | 286.7 | 707.4 | 21.14 | 0.0 | 10.0 | 14.44 | 17.9 | mheidari-all | 159.223.157.129 |
| 81.01 | vless | 286.9 | 662.7 | 21.14 | 0.0 | 10.0 | 11.09 | 18.78 | Au1rxx-base64 | 198.251.78.29 |
| 80.58 | shadowsocks | 234.6 | 603.3 | 22.35 | 0.0 | 10.0 | 13.45 | 18.78 | Au1rxx-base64 | 156.146.38.170 |
| 79.72 | shadowsocks | 250.0 | 602.8 | 21.99 | 0.0 | 10.0 | 13.45 | 18.78 | Au1rxx-base64 | 23.150.248.20 |
| 79.6 | shadowsocks | 266.1 | 654.6 | 21.62 | 0.0 | 10.0 | 13.45 | 18.78 | Au1rxx-base64 | 155.138.136.240 |
| 79.29 | shadowsocks | 290.2 | 731.5 | 21.06 | 0.0 | 10.0 | 13.45 | 18.78 | Au1rxx-base64 | 156.146.38.169 |
| 79.2 | shadowsocks | 244.7 | 629.6 | 22.11 | 0.0 | 10.0 | 13.45 | 18.78 | Au1rxx-base64 | 156.146.38.168 |
| 79.1 | shadowsocks | 298.5 | 707.1 | 20.87 | 0.0 | 10.0 | 13.45 | 18.78 | Au1rxx-base64 | 37.19.198.236 |
| 78.64 | vless | 317.4 | 741.3 | 20.43 | 0.0 | 10.0 | 11.09 | 18.78 | Au1rxx-base64 | 47.89.186.170 |
| 77.79 | http | 288.6 | 567.5 | 21.1 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.216 |
| 77.32 | shadowsocks | 317.7 | 775.7 | 20.42 | 0.0 | 10.0 | 13.45 | 18.78 | Au1rxx-base64 | 37.19.198.244 |
| 77.18 | vless | 328.0 | 747.0 | 20.19 | 0.0 | 10.0 | 11.09 | 18.78 | Au1rxx-base64 | 137.184.218.169 |
| 77.13 | vless | 374.0 | 706.8 | 19.12 | 0.0 | 10.0 | 11.09 | 18.78 | Au1rxx-base64 | 169.40.42.133 |
| 77.05 | shadowsocks | 257.2 | 638.3 | 21.82 | 0.0 | 10.0 | 13.45 | 18.78 | Au1rxx-base64 | 156.146.38.167 |
| 76.82 | http | 302.6 | 573.7 | 20.77 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.198 |
| 76.64 | shadowsocks | 293.6 | 699.3 | 20.98 | 0.0 | 10.0 | 13.45 | 18.78 | Au1rxx-base64 | 37.19.198.160 |
| 75.85 | shadowsocks | 294.9 | 722.2 | 20.95 | 0.0 | 10.0 | 13.45 | 17.9 | mheidari-all | 37.19.198.243 |
| 75.78 | vless | 390.0 | 933.5 | 18.75 | 0.0 | 10.0 | 11.09 | 18.78 | Au1rxx-base64 | 216.152.147.28 |
| 75.55 | vless | 325.6 | 629.4 | 20.24 | 0.0 | 10.0 | 11.09 | 18.78 | Au1rxx-base64 | 15.204.97.214 |
| 75.46 | vless | 338.0 | 756.0 | 19.95 | 0.0 | 10.0 | 11.09 | 18.78 | Au1rxx-base64 | 66.70.179.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | 0.896 | 450 | 1799 | prefer |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| Surfboard-tg-mixed | 0.864 | 0.787 | 197 | 6570 | prefer |
| mheidari-all | 0.316 | 0.235 | 455 | 19487 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4899 | observe |
| Epodonios-all | 0.255 | None | 0 | 7074 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7045 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5352 | observe |
| barry-far-vless | 0.255 | None | 0 | 5640 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4132 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1802 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 190 |
| geo | ClientOSError | - | 92 |
| speed | TimeoutError | - | 91 |
| speed | ClientOSError | - | 42 |
| cn-block | TimeoutError | - | 23 |
| 204 | ProxyError | - | 11 |
| 204 | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| 204 | ServerDisconnectedError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
