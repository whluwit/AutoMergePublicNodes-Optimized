# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-07 22:42:39 |
| 运行耗时 | 509.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98251 |
| 去重后节点 | 27407 |
| TCP 可达 | 3000 |
| 真实可用 | 430 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27407 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 46.6 |
| probe | 189.0 |
| real_test | 189.6 |
| generate | 74.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57931 |
| vmess | 15590 |
| shadowsocks | 11641 |
| trojan | 10677 |
| hysteria2 | 1524 |
| http | 561 |
| shadowsocksr | 171 |
| socks | 96 |
| anytls | 34 |
| hysteria | 17 |
| tuic | 9 |

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
| 81.77 | hysteria2 | 288.1 | 729.8 | 21.11 | 0.0 | 10.0 | 12.5 | 19.66 | Au1rxx-base64 | 129.213.91.185 |
| 80.41 | shadowsocks | 305.1 | 752.9 | 20.71 | 0.0 | 10.0 | 14.09 | 19.66 | Au1rxx-base64 | 37.19.198.160 |
| 80.41 | shadowsocks | 307.6 | 755.2 | 20.66 | 0.0 | 10.0 | 14.09 | 19.66 | Au1rxx-base64 | 37.19.198.243 |
| 79.94 | shadowsocks | 309.9 | 758.4 | 20.6 | 0.0 | 10.0 | 14.09 | 19.66 | Au1rxx-base64 | 37.19.198.236 |
| 79.1 | shadowsocks | 308.2 | 762.5 | 20.64 | 0.0 | 10.0 | 14.09 | 19.66 | Au1rxx-base64 | 37.19.198.244 |
| 78.06 | vless | 280.1 | 558.4 | 21.29 | 0.0 | 10.0 | 11.04 | 19.66 | Au1rxx-base64 | 47.251.108.158 |
| 77.92 | shadowsocks | 245.5 | 645.0 | 22.1 | 0.0 | 10.0 | 14.09 | 19.66 | Au1rxx-base64 | 156.146.38.167 |
| 77.53 | vless | 336.6 | 711.7 | 19.99 | 0.0 | 10.0 | 11.04 | 19.66 | Au1rxx-base64 | 169.40.42.235 |
| 77.5 | shadowsocks | 309.1 | 727.4 | 20.62 | 0.0 | 10.0 | 14.09 | 19.66 | Au1rxx-base64 | 140.82.63.79 |
| 77.49 | vless | 277.0 | 654.8 | 21.36 | 0.0 | 9.93 | 11.04 | 19.66 | Au1rxx-base64 | uspanel.unixzone.us |
| 77.12 | vless | 307.5 | 660.5 | 20.66 | 0.0 | 10.0 | 11.04 | 18.48 | mheidari-all | 216.227.161.95 |
| 77.01 | vless | 303.5 | 616.8 | 20.75 | 0.0 | 10.0 | 11.04 | 19.66 | Au1rxx-base64 | 107.173.237.146 |
| 76.85 | vless | 414.8 | 906.1 | 18.17 | 0.0 | 10.0 | 11.04 | 19.66 | Au1rxx-base64 | 169.40.42.224 |
| 76.71 | shadowsocks | 299.3 | 635.8 | 20.85 | 0.0 | 10.0 | 14.09 | 19.66 | Au1rxx-base64 | 149.22.95.183 |
| 76.67 | vless | 383.2 | 930.9 | 18.91 | 0.0 | 10.0 | 11.04 | 19.66 | Au1rxx-base64 | 137.184.218.169 |
| 76.06 | vless | 350.8 | 697.5 | 19.66 | 0.0 | 10.0 | 11.04 | 19.66 | Au1rxx-base64 | 169.40.42.225 |
| 75.98 | vless | 368.5 | 780.6 | 19.25 | 0.0 | 10.0 | 11.04 | 19.66 | Au1rxx-base64 | 169.40.42.52 |
| 75.78 | hysteria2 | 344.7 | 309.6 | 19.8 | 3.39 | 9.11 | 12.5 | 19.66 | Au1rxx-base64 | open.2ml.bid |
| 75.76 | vless | 335.8 | 678.5 | 20.0 | 0.0 | 10.0 | 11.04 | 19.66 | Au1rxx-base64 | 15.204.97.197 |
| 75.76 | hysteria2 | 339.1 | 849.8 | 19.93 | 0.0 | 10.0 | 12.5 | 19.66 | Au1rxx-base64 | 159.223.157.129 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.932 | 0.865 | 52 | 7069 | prefer |
| mheidari-all | 0.929 | 0.857 | 84 | 23169 | prefer |
| Au1rxx-base64 | 0.912 | 0.841 | 339 | 1824 | prefer |
| ermaozi | 0.636 | 0.615 | 39 | 664 | observe |
| ermaozi-get_subscribe | 0.278 | 1.0 | 1 | 565 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| DeltaKronecker-all | 0.259 | 0.333 | 3 | 5344 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7553 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9262 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5616 | observe |
| barry-far-vless | 0.255 | None | 0 | 5859 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4431 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 30 |
| 204 | ProxyError | - | 14 |
| speed | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 10 |
| speed | ClientOSError | - | 7 |
| geo | TimeoutError | - | 6 |
| geo | ClientOSError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
