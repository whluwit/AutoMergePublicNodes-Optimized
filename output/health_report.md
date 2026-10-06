# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-06 12:47:42 |
| 运行耗时 | 549.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97830 |
| 去重后节点 | 26948 |
| TCP 可达 | 3000 |
| 真实可用 | 479 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26948 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 45.5 |
| probe | 224.3 |
| real_test | 183.4 |
| generate | 86.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57293 |
| vmess | 16138 |
| shadowsocks | 11733 |
| trojan | 10194 |
| hysteria2 | 1426 |
| http | 715 |
| shadowsocksr | 171 |
| socks | 97 |
| anytls | 36 |
| hysteria | 17 |
| tuic | 10 |

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
| 81.56 | hysteria2 | 321.8 | 851.1 | 20.33 | 0.0 | 10.0 | 12.75 | 19.58 | Au1rxx-base64 | 159.223.157.129 |
| 81.28 | shadowsocks | 259.9 | 701.8 | 21.76 | 0.0 | 10.0 | 13.94 | 19.58 | Au1rxx-base64 | 37.19.198.160 |
| 81.19 | shadowsocks | 263.8 | 713.2 | 21.67 | 0.0 | 10.0 | 13.94 | 19.58 | Au1rxx-base64 | 37.19.198.236 |
| 81.09 | shadowsocks | 268.0 | 729.5 | 21.57 | 0.0 | 10.0 | 13.94 | 19.58 | Au1rxx-base64 | 37.19.198.243 |
| 79.66 | hysteria2 | 386.5 | 1110.3 | 18.83 | 0.0 | 10.0 | 12.75 | 19.58 | Au1rxx-base64 | 129.213.91.185 |
| 79.37 | shadowsocks | 276.8 | 643.1 | 21.37 | 0.0 | 10.0 | 13.94 | 19.58 | Au1rxx-base64 | 156.146.38.170 |
| 79.18 | shadowsocks | 282.1 | 651.6 | 21.25 | 0.0 | 10.0 | 13.94 | 19.58 | Au1rxx-base64 | 156.146.38.168 |
| 79.08 | shadowsocks | 333.3 | 607.7 | 20.06 | 0.0 | 10.0 | 13.94 | 19.58 | Au1rxx-base64 | 140.82.63.79 |
| 78.24 | vless | 284.4 | 734.8 | 21.19 | 0.0 | 10.0 | 7.47 | 19.58 | Au1rxx-base64 | 169.40.42.229 |
| 78.17 | vless | 287.7 | 690.6 | 21.12 | 0.0 | 10.0 | 7.47 | 19.58 | Au1rxx-base64 | 169.40.42.202 |
| 77.99 | vless | 295.6 | 734.7 | 20.94 | 0.0 | 10.0 | 7.47 | 19.58 | Au1rxx-base64 | 66.70.179.198 |
| 77.79 | vless | 303.9 | 708.5 | 20.74 | 0.0 | 10.0 | 7.47 | 19.58 | Au1rxx-base64 | 169.40.42.90 |
| 77.0 | vless | 303.0 | 672.7 | 20.76 | 0.0 | 10.0 | 7.47 | 19.58 | Au1rxx-base64 | 169.40.42.133 |
| 76.82 | vless | 298.4 | 717.9 | 20.87 | 0.0 | 10.0 | 7.47 | 19.58 | Au1rxx-base64 | 169.40.42.179 |
| 76.54 | shadowsocks | 325.5 | 827.1 | 20.24 | 0.0 | 10.0 | 13.94 | 16.86 | Surfboard-tg-mixed | 66.23.204.210 |
| 76.33 | vless | 367.2 | 928.7 | 19.28 | 0.0 | 10.0 | 7.47 | 19.58 | Au1rxx-base64 | 169.40.42.15 |
| 76.2 | shadowsocks | 263.3 | 711.8 | 21.68 | 0.0 | 10.0 | 13.94 | 19.58 | Au1rxx-base64 | 37.19.198.244 |
| 76.18 | vless | 297.4 | 725.3 | 20.89 | 0.0 | 10.0 | 7.47 | 19.58 | Au1rxx-base64 | 2.24.124.64 |
| 75.82 | shadowsocks | 344.6 | 969.5 | 19.8 | 0.0 | 10.0 | 13.94 | 19.58 | Au1rxx-base64 | 15.204.247.206 |
| 75.65 | vless | 310.8 | 753.0 | 20.58 | 0.0 | 10.0 | 7.47 | 19.58 | Au1rxx-base64 | 169.40.42.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.995 | 0.933 | 45 | 23204 | prefer |
| Au1rxx-base64 | 0.991 | 0.922 | 320 | 1805 | prefer |
| Surfboard-tg-mixed | 0.804 | 0.727 | 132 | 7050 | prefer |
| DeltaKronecker-all | 0.538 | 0.455 | 22 | 4889 | observe |
| ermaozi | 0.453 | 0.423 | 78 | 708 | observe |
| ermaozi-get_subscribe | 0.335 | 1.0 | 2 | 597 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Epodonios-all | 0.255 | None | 0 | 7553 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9571 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5573 | observe |
| barry-far-vless | 0.255 | None | 0 | 5839 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4373 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 42 |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 17 |
| geo | TimeoutError | - | 10 |
| speed | ClientOSError | - | 10 |
| geo | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
