# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-10 21:14:05 |
| 运行耗时 | 660.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98071 |
| 去重后节点 | 27313 |
| TCP 可达 | 3000 |
| 真实可用 | 421 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27313 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.6 |
| tcp | 47.1 |
| probe | 247.0 |
| real_test | 286.0 |
| generate | 72.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57857 |
| vmess | 15846 |
| shadowsocks | 11697 |
| trojan | 10301 |
| hysteria2 | 1559 |
| http | 520 |
| shadowsocksr | 164 |
| socks | 72 |
| anytls | 32 |
| hysteria | 16 |
| tuic | 7 |

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
| 80.51 | shadowsocks | 237.6 | 607.0 | 22.28 | 0.0 | 10.0 | 13.57 | 18.66 | Au1rxx-base64 | 156.146.38.167 |
| 80.4 | shadowsocks | 242.3 | 621.8 | 22.17 | 0.0 | 10.0 | 13.57 | 18.66 | Au1rxx-base64 | 156.146.38.170 |
| 79.95 | hysteria2 | 305.2 | 732.8 | 20.71 | 0.0 | 10.0 | 12.75 | 18.66 | Au1rxx-base64 | 129.213.91.185 |
| 79.42 | vless | 241.1 | 534.9 | 22.2 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 47.251.108.158 |
| 79.35 | hysteria2 | 334.3 | 725.6 | 20.04 | 0.0 | 10.0 | 12.75 | 18.66 | Au1rxx-base64 | 66.94.121.46 |
| 79.25 | shadowsocks | 243.3 | 555.5 | 22.14 | 0.0 | 10.0 | 13.57 | 18.66 | Au1rxx-base64 | 5.78.51.123 |
| 78.97 | vless | 272.1 | 597.4 | 21.48 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 15.204.97.216 |
| 78.88 | vless | 269.6 | 596.6 | 21.54 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 15.204.97.197 |
| 77.59 | shadowsocks | 275.5 | 720.6 | 21.4 | 0.0 | 10.0 | 13.57 | 18.66 | Au1rxx-base64 | 156.146.38.169 |
| 77.47 | shadowsocks | 282.5 | 740.0 | 21.24 | 0.0 | 10.0 | 13.57 | 18.66 | Au1rxx-base64 | 156.146.38.168 |
| 77.28 | vless | 302.9 | 687.4 | 20.77 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 172.245.253.16 |
| 76.86 | hysteria2 | 298.6 | 336.1 | 20.86 | 2.4 | 9.78 | 12.75 | 18.66 | Au1rxx-base64 | 158.101.148.79 |
| 76.56 | vless | 308.1 | 687.6 | 20.65 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 107.173.237.146 |
| 75.83 | vless | 316.9 | 643.8 | 20.44 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 137.175.82.40 |
| 74.88 | shadowsocks | 303.9 | 304.1 | 20.74 | 3.6 | 9.79 | 13.57 | 18.66 | Au1rxx-base64 | 149.22.87.204 |
| 74.86 | shadowsocks | 338.8 | 771.7 | 19.94 | 0.0 | 10.0 | 13.57 | 18.66 | Au1rxx-base64 | 37.19.198.243 |
| 74.61 | http | 248.1 | 556.9 | 22.04 | 0.0 | 10.0 | 9.08 | 17.72 | zhangkai | 138.199.35.198 |
| 74.52 | shadowsocks | 338.1 | 776.5 | 19.95 | 0.0 | 10.0 | 13.57 | 18.66 | Au1rxx-base64 | 37.19.198.160 |
| 74.28 | shadowsocks | 303.4 | 661.3 | 20.75 | 0.0 | 10.0 | 13.57 | 18.66 | Au1rxx-base64 | 173.244.56.6 |
| 74.28 | shadowsocks | 344.1 | 790.4 | 19.81 | 0.0 | 10.0 | 13.57 | 18.66 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | 0.9 | 351 | 1853 | prefer |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| mheidari-all | 0.817 | 0.742 | 93 | 23925 | prefer |
| Surfboard-tg-mixed | 0.568 | 0.875 | 8 | 7118 | observe |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 5009 | observe |
| ermaozi-get_subscribe | 0.296 | 0.25 | 20 | 580 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7597 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9339 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5677 | observe |
| barry-far-vless | 0.255 | None | 0 | 5914 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4347 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1853 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 12 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyError | - | 10 |
| geo | ClientOSError | - | 9 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
