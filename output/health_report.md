# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 10:51:06 |
| 运行耗时 | 534.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97157 |
| 去重后节点 | 26411 |
| TCP 可达 | 3000 |
| 真实可用 | 365 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26411 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.4 |
| tcp | 43.4 |
| probe | 229.5 |
| real_test | 164.5 |
| generate | 88.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59112 |
| vmess | 15221 |
| shadowsocks | 11246 |
| trojan | 8995 |
| hysteria2 | 1578 |
| http | 672 |
| shadowsocksr | 176 |
| socks | 98 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 12 |

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
| 79.95 | shadowsocks | 254.8 | 715.1 | 21.88 | 0.0 | 9.25 | 14.1 | 18.72 | Au1rxx-base64 | 37.19.198.244 |
| 79.16 | shadowsocks | 271.1 | 773.7 | 21.5 | 0.0 | 9.34 | 14.1 | 18.72 | Au1rxx-base64 | 15.204.247.206 |
| 78.89 | shadowsocks | 295.5 | 797.5 | 20.94 | 0.0 | 9.13 | 14.1 | 18.72 | Au1rxx-base64 | 142.4.216.225 |
| 78.26 | shadowsocks | 310.2 | 859.7 | 20.6 | 0.0 | 9.34 | 14.1 | 18.72 | Au1rxx-base64 | 38.180.135.156 |
| 77.69 | shadowsocks | 255.0 | 704.8 | 21.87 | 0.0 | 10.0 | 14.1 | 18.72 | Au1rxx-base64 | 37.19.198.236 |
| 77.22 | hysteria2 | 309.2 | 648.2 | 20.62 | 0.0 | 9.33 | 13.64 | 18.72 | Au1rxx-base64 | 66.94.121.46 |
| 77.12 | shadowsocks | 251.4 | 701.7 | 21.96 | 0.0 | 9.34 | 14.1 | 18.72 | Au1rxx-base64 | 37.19.198.243 |
| 75.91 | vless | 236.9 | 678.9 | 22.29 | 0.0 | 9.16 | 5.74 | 18.72 | Au1rxx-base64 | 79.141.172.154 |
| 75.36 | vless | 259.3 | 640.4 | 21.78 | 0.0 | 9.12 | 5.74 | 18.72 | Au1rxx-base64 | 195.211.98.43 |
| 75.06 | vless | 273.4 | 665.6 | 21.45 | 0.0 | 9.15 | 5.74 | 18.72 | Au1rxx-base64 | 169.40.42.231 |
| 74.86 | shadowsocks | 443.7 | 1161.6 | 17.51 | 0.0 | 9.33 | 14.1 | 18.72 | Au1rxx-base64 | 15.235.75.71 |
| 74.79 | vless | 288.7 | 656.0 | 21.1 | 0.0 | 9.23 | 5.74 | 18.72 | Au1rxx-base64 | 169.40.42.75 |
| 74.57 | vless | 294.4 | 731.1 | 20.96 | 0.0 | 9.15 | 5.74 | 18.72 | Au1rxx-base64 | 169.40.42.163 |
| 74.42 | vless | 302.3 | 692.3 | 20.78 | 0.0 | 9.18 | 5.74 | 18.72 | Au1rxx-base64 | 169.40.42.90 |
| 73.93 | vless | 327.5 | 844.6 | 20.2 | 0.0 | 9.27 | 5.74 | 18.72 | Au1rxx-base64 | 66.70.179.198 |
| 73.88 | vless | 329.9 | 896.0 | 20.14 | 0.0 | 9.28 | 5.74 | 18.72 | Au1rxx-base64 | 169.40.42.74 |
| 73.55 | vless | 340.0 | 948.9 | 19.91 | 0.0 | 9.18 | 5.74 | 18.72 | Au1rxx-base64 | 185.95.231.156 |
| 73.54 | vless | 282.4 | 697.6 | 21.24 | 0.0 | 9.14 | 5.74 | 18.72 | Au1rxx-base64 | 169.40.42.168 |
| 73.51 | vless | 343.7 | 956.7 | 19.82 | 0.0 | 9.23 | 5.74 | 18.72 | Au1rxx-base64 | 185.95.231.233 |
| 73.4 | vless | 352.3 | 917.1 | 19.62 | 0.0 | 9.32 | 5.74 | 18.72 | Au1rxx-base64 | 169.40.42.184 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.924 | 0.861 | 230 | 1660 | prefer |
| mheidari-all | 0.896 | 0.824 | 74 | 22392 | prefer |
| Surfboard-tg-mixed | 0.709 | 0.631 | 130 | 7247 | prefer |
| DeltaKronecker-all | 0.646 | 0.769 | 13 | 5512 | observe |
| ermaozi | 0.373 | 0.351 | 37 | 352 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| Epodonios-all | 0.255 | None | 0 | 7713 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9376 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5840 | observe |
| barry-far-vless | 0.255 | None | 0 | 6058 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1660 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 26 |
| 204 | TimeoutError | - | 26 |
| cn-block | TimeoutError | - | 21 |
| cn-block | ClientOSError | - | 12 |
| speed | TimeoutError | - | 12 |
| geo | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| geo | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
