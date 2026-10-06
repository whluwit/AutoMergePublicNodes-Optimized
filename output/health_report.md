# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-06 22:20:54 |
| 运行耗时 | 505.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97973 |
| 去重后节点 | 27040 |
| TCP 可达 | 3000 |
| 真实可用 | 437 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27040 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.3 |
| tcp | 45.0 |
| probe | 230.1 |
| real_test | 143.3 |
| generate | 78.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57851 |
| vmess | 15909 |
| shadowsocks | 11604 |
| trojan | 10151 |
| hysteria2 | 1423 |
| http | 706 |
| shadowsocksr | 172 |
| socks | 96 |
| anytls | 36 |
| hysteria | 17 |
| tuic | 8 |

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
| 84.87 | hysteria2 | 261.1 | 682.7 | 21.73 | 0.0 | 10.0 | 14.42 | 19.82 | Au1rxx-base64 | 159.223.157.129 |
| 84.78 | hysteria2 | 247.7 | 689.8 | 22.04 | 0.0 | 10.0 | 14.42 | 19.82 | Au1rxx-base64 | 129.213.91.185 |
| 82.58 | vless | 285.5 | 719.9 | 21.17 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | 2.24.124.64 |
| 81.92 | vless | 289.3 | 699.1 | 21.08 | 0.0 | 10.0 | 11.59 | 19.9 | mheidari-all | 167.17.69.171 |
| 81.77 | vless | 320.5 | 889.3 | 20.36 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | 159.89.87.21 |
| 81.71 | shadowsocks | 253.5 | 708.3 | 21.91 | 0.0 | 10.0 | 13.98 | 19.82 | Au1rxx-base64 | 37.19.198.236 |
| 81.69 | shadowsocks | 254.5 | 702.7 | 21.89 | 0.0 | 10.0 | 13.98 | 19.82 | Au1rxx-base64 | 37.19.198.243 |
| 81.69 | vless | 323.9 | 868.3 | 20.28 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | 137.184.218.169 |
| 81.63 | shadowsocks | 257.0 | 711.2 | 21.83 | 0.0 | 10.0 | 13.98 | 19.82 | Au1rxx-base64 | 37.19.198.160 |
| 81.4 | shadowsocks | 245.1 | 672.1 | 22.1 | 0.0 | 10.0 | 13.98 | 19.82 | Au1rxx-base64 | 140.82.63.79 |
| 81.3 | vless | 340.8 | 924.4 | 19.89 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | 169.40.42.182 |
| 81.2 | vless | 267.0 | 629.9 | 21.6 | 0.0 | 10.0 | 11.59 | 19.9 | mheidari-all | 216.227.161.95 |
| 80.72 | vless | 365.9 | 994.9 | 19.31 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | 169.40.42.179 |
| 80.64 | vless | 369.3 | 1036.8 | 19.23 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 80.01 | vless | 371.3 | 955.4 | 19.18 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | 169.40.42.173 |
| 79.86 | vless | 403.1 | 970.2 | 18.45 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | 169.40.42.74 |
| 79.84 | vless | 404.0 | 1081.9 | 18.43 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | 185.95.231.156 |
| 79.69 | vless | 410.2 | 1077.6 | 18.28 | 0.0 | 10.0 | 11.59 | 19.82 | Au1rxx-base64 | 169.40.42.224 |
| 79.68 | shadowsocks | 319.5 | 743.1 | 20.38 | 0.0 | 10.0 | 13.98 | 19.82 | Au1rxx-base64 | 15.204.246.132 |
| 79.5 | vless | 407.6 | 1046.2 | 18.34 | 0.0 | 10.0 | 11.59 | 19.9 | mheidari-all | 209.200.246.148 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.934 | 319 | 1841 | prefer |
| Surfboard-tg-mixed | 0.945 | 0.88 | 50 | 7117 | prefer |
| mheidari-all | 0.88 | 0.806 | 93 | 23303 | prefer |
| ermaozi | 0.396 | 0.362 | 47 | 708 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Epodonios-all | 0.255 | None | 0 | 7604 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9213 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5711 | observe |
| barry-far-vless | 0.255 | None | 0 | 5954 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4373 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1841 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| DeltaKronecker-all | 0.24 | 0.25 | 4 | 4889 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 17 |
| 204 | ProxyConnectionError | - | 15 |
| cn-block | TimeoutError | - | 12 |
| speed | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 8 |
| geo | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
