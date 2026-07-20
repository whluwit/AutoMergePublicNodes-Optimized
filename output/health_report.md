# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-20 14:00:42 |
| 运行耗时 | 271.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 85548 |
| 去重后节点 | 24075 |
| TCP 可达 | 3000 |
| 真实可用 | 392 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24075 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.1 |
| tcp | 33.6 |
| probe | 58.0 |
| real_test | 137.0 |
| generate | 36.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50887 |
| trojan | 12952 |
| vmess | 10980 |
| shadowsocks | 10162 |
| hysteria2 | 384 |
| shadowsocksr | 71 |
| http | 52 |
| socks | 36 |
| hysteria | 16 |
| tuic | 7 |
| anytls | 1 |

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
| 80.22 | trojan | 267.2 | 619.8 | 21.59 | 0.0 | 10.0 | 13.05 | 18.98 | Au1rxx-base64 | 64.94.95.114 |
| 80.15 | shadowsocks | 248.6 | 606.4 | 22.02 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 156.146.38.168 |
| 79.97 | trojan | 265.6 | 614.1 | 21.63 | 0.0 | 10.0 | 13.05 | 18.98 | Au1rxx-base64 | 64.94.95.118 |
| 79.91 | shadowsocks | 259.0 | 631.8 | 21.78 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 156.146.38.170 |
| 79.77 | shadowsocks | 264.9 | 651.0 | 21.64 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 156.146.38.169 |
| 79.77 | shadowsocks | 265.0 | 652.6 | 21.64 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 37.19.198.236 |
| 79.6 | shadowsocks | 272.5 | 673.3 | 21.47 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 37.19.198.160 |
| 78.79 | shadowsocks | 286.0 | 672.1 | 21.16 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 108.181.57.93 |
| 77.87 | shadowsocks | 325.8 | 849.7 | 20.24 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 185.196.61.82 |
| 77.21 | trojan | 349.3 | 869.2 | 19.69 | 0.0 | 10.0 | 13.05 | 18.98 | Au1rxx-base64 | 64.94.95.117 |
| 76.76 | trojan | 267.9 | 614.0 | 21.58 | 0.0 | 10.0 | 13.05 | 18.98 | Au1rxx-base64 | 64.94.95.115 |
| 74.7 | shadowsocks | 295.9 | 592.5 | 20.93 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 173.244.56.9 |
| 74.69 | shadowsocks | 268.7 | 666.2 | 21.56 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 37.19.198.244 |
| 73.51 | shadowsocks | 306.0 | 588.8 | 20.69 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 108.181.0.177 |
| 72.97 | shadowsocks | 317.5 | 630.6 | 20.43 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 108.181.118.10 |
| 71.99 | hysteria2 | 447.1 | 886.1 | 17.43 | 0.0 | 9.89 | 12.5 | 18.98 | Au1rxx-base64 | 5.255.102.165 |
| 71.52 | trojan | 371.2 | 673.4 | 19.19 | 0.0 | 10.0 | 13.05 | 18.98 | Au1rxx-base64 | 54.184.22.123 |
| 71.12 | hysteria2 | 461.6 | 840.1 | 17.09 | 0.0 | 9.9 | 12.5 | 18.98 | Au1rxx-base64 | 62.210.124.146 |
| 70.9 | shadowsocks | 363.6 | 351.1 | 19.36 | 1.84 | 9.48 | 13.15 | 18.98 | Au1rxx-base64 | 149.22.87.204 |
| 70.82 | shadowsocks | 280.9 | 684.6 | 21.28 | 0.0 | 10.0 | 13.15 | 18.98 | Au1rxx-base64 | 147.90.234.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.923 | 0.944 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.899 | 0.864 | 242 | 969 | prefer |
| Surfboard-tg-mixed | 0.531 | 0.451 | 173 | 5287 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5035 | observe |
| mheidari-all | 0.293 | 0.211 | 299 | 19893 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4714 | observe |
| Epodonios-all | 0.255 | None | 0 | 6550 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6890 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4082 | observe |
| barry-far-vless | 0.255 | None | 0 | 4908 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5193 | observe |
| nscl5-all | 0.255 | None | 0 | 2118 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 282 |
| speed | ClientOSError | - | 77 |
| cn-block | TimeoutError | - | 31 |
| geo | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 12 |
| speed | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 5 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
