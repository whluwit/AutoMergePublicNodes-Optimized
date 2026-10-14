# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 16:34:24 |
| 运行耗时 | 662.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98095 |
| 去重后节点 | 27247 |
| TCP 可达 | 3000 |
| 真实可用 | 337 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27247 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.7 |
| geo | 1.4 |
| tcp | 47.1 |
| probe | 283.7 |
| real_test | 239.9 |
| generate | 80.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58111 |
| vmess | 16256 |
| shadowsocks | 11795 |
| trojan | 9935 |
| hysteria2 | 1288 |
| http | 410 |
| shadowsocksr | 166 |
| socks | 85 |
| anytls | 25 |
| hysteria | 18 |
| tuic | 6 |

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
| 81.19 | vless | 216.4 | 502.7 | 22.77 | 0.0 | 10.0 | 10.26 | 18.32 | Au1rxx-base64 | 47.251.108.158 |
| 81.15 | vless | 225.0 | 569.7 | 22.57 | 0.0 | 10.0 | 10.26 | 18.32 | Au1rxx-base64 | 154.29.145.196 |
| 81.07 | vless | 228.4 | 537.9 | 22.49 | 0.0 | 10.0 | 10.26 | 18.32 | Au1rxx-base64 | 154.12.38.159 |
| 81.0 | shadowsocks | 218.4 | 538.7 | 22.72 | 0.0 | 10.0 | 13.96 | 18.32 | Au1rxx-base64 | 173.244.56.6 |
| 80.96 | shadowsocks | 220.4 | 535.6 | 22.68 | 0.0 | 10.0 | 13.96 | 18.32 | Au1rxx-base64 | 173.244.56.9 |
| 80.7 | vless | 244.4 | 642.4 | 22.12 | 0.0 | 10.0 | 10.26 | 18.32 | Au1rxx-base64 | 45.32.69.110 |
| 79.55 | shadowsocks | 264.4 | 628.1 | 21.66 | 0.0 | 10.0 | 13.96 | 18.32 | Au1rxx-base64 | 156.146.38.169 |
| 79.51 | shadowsocks | 264.5 | 640.7 | 21.65 | 0.0 | 10.0 | 13.96 | 18.32 | Au1rxx-base64 | 156.146.38.167 |
| 79.37 | shadowsocks | 257.0 | 621.4 | 21.83 | 0.0 | 10.0 | 13.96 | 17.84 | mheidari-all | 156.146.38.170 |
| 78.25 | vless | 271.6 | 677.4 | 21.49 | 0.0 | 10.0 | 10.26 | 18.32 | Au1rxx-base64 | 154.40.55.185 |
| 76.2 | shadowsocks | 285.2 | 292.0 | 21.18 | 4.05 | 9.91 | 13.96 | 18.32 | Au1rxx-base64 | 149.22.87.240 |
| 76.15 | shadowsocks | 284.3 | 290.0 | 21.2 | 4.12 | 9.88 | 13.96 | 18.32 | Au1rxx-base64 | 149.22.87.241 |
| 76.01 | hysteria2 | 328.8 | 749.7 | 20.17 | 0.0 | 10.0 | 12.0 | 18.32 | Au1rxx-base64 | 129.213.91.185 |
| 75.95 | http | 202.3 | 509.0 | 23.09 | 0.0 | 10.0 | 7.98 | 17.88 | zhangkai | 138.199.35.216 |
| 75.88 | http | 205.6 | 521.8 | 23.02 | 0.0 | 10.0 | 7.98 | 17.88 | zhangkai | 138.199.35.198 |
| 75.65 | vless | 292.0 | 602.6 | 21.02 | 0.0 | 10.0 | 10.26 | 18.32 | Au1rxx-base64 | 44.248.233.99 |
| 75.39 | shadowsocks | 319.9 | 722.5 | 20.37 | 0.0 | 10.0 | 13.96 | 18.32 | Au1rxx-base64 | 149.22.95.183 |
| 75.31 | vless | 327.6 | 606.1 | 20.19 | 0.0 | 10.0 | 10.26 | 18.32 | Au1rxx-base64 | 95.111.212.241 |
| 74.4 | vless | 414.2 | 991.8 | 18.19 | 0.0 | 10.0 | 10.26 | 18.32 | Au1rxx-base64 | 51.81.203.63 |
| 73.96 | vless | 294.9 | 608.6 | 20.95 | 0.0 | 9.51 | 10.26 | 18.32 | Au1rxx-base64 | tk1.high-speed-test-56424.me |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.862 | 0.793 | 294 | 1780 | prefer |
| mheidari-all | 0.799 | 0.724 | 87 | 23968 | prefer |
| Surfboard-tg-mixed | 0.747 | 0.682 | 22 | 7056 | prefer |
| DeltaKronecker-all | 0.373 | 0.6 | 5 | 4803 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7543 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9997 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5579 | observe |
| barry-far-vless | 0.255 | None | 0 | 5831 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1780 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 29 |
| cn-block | TimeoutError | - | 26 |
| 204 | ProxyError | - | 15 |
| speed | ClientOSError | - | 10 |
| geo | TimeoutError | - | 8 |
| speed | TimeoutError | - | 5 |
| geo | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
