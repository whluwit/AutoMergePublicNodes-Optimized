# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 18:24:39 |
| 运行耗时 | 577.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94362 |
| 去重后节点 | 26032 |
| TCP 可达 | 3000 |
| 真实可用 | 341 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26032 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.6 |
| tcp | 44.3 |
| probe | 232.5 |
| real_test | 206.3 |
| generate | 83.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55405 |
| vmess | 16839 |
| shadowsocks | 11521 |
| trojan | 8425 |
| hysteria2 | 1479 |
| http | 390 |
| shadowsocksr | 170 |
| socks | 64 |
| anytls | 46 |
| hysteria | 17 |
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
| 80.12 | vless | 209.7 | 519.5 | 22.92 | 0.0 | 9.59 | 10.21 | 17.4 | Au1rxx-base64 | 154.29.145.196 |
| 79.91 | vless | 216.8 | 524.7 | 22.76 | 0.0 | 9.54 | 10.21 | 17.4 | Au1rxx-base64 | 154.9.241.170 |
| 78.92 | shadowsocks | 243.1 | 576.0 | 22.15 | 0.0 | 10.0 | 13.37 | 17.4 | Au1rxx-base64 | 173.244.56.6 |
| 76.51 | vless | 253.8 | 626.0 | 21.9 | 0.0 | 10.0 | 10.21 | 17.4 | Au1rxx-base64 | 47.251.108.158 |
| 76.16 | hysteria2 | 214.0 | 567.5 | 22.82 | 0.0 | 9.53 | 11.84 | 17.4 | Au1rxx-base64 | 179.255.104.98 |
| 75.81 | shadowsocks | 260.4 | 630.3 | 21.75 | 0.0 | 9.52 | 13.37 | 17.4 | Au1rxx-base64 | 156.146.38.168 |
| 75.79 | vless | 347.1 | 700.5 | 19.74 | 0.0 | 9.54 | 10.21 | 17.4 | Au1rxx-base64 | 95.111.212.241 |
| 75.29 | hysteria2 | 278.6 | 601.6 | 21.33 | 0.0 | 10.0 | 11.84 | 17.4 | Au1rxx-base64 | 66.94.121.46 |
| 75.27 | vless | 199.7 | 506.8 | 23.15 | 0.0 | 9.51 | 10.21 | 17.4 | Au1rxx-base64 | 104.225.239.122 |
| 74.98 | shadowsocks | 280.5 | 285.4 | 21.29 | 4.3 | 9.84 | 13.37 | 17.4 | Au1rxx-base64 | 149.22.87.204 |
| 74.22 | shadowsocks | 259.7 | 628.4 | 21.77 | 0.0 | 10.0 | 13.37 | 17.4 | Au1rxx-base64 | 156.146.38.167 |
| 73.93 | vless | 293.8 | 613.9 | 20.98 | 0.0 | 9.07 | 10.21 | 17.4 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 73.58 | vless | 338.1 | 739.2 | 19.95 | 0.0 | 9.49 | 10.21 | 17.4 | Au1rxx-base64 | 44.248.233.99 |
| 73.17 | vless | 249.1 | 643.2 | 22.01 | 0.0 | 9.53 | 10.21 | 17.4 | Au1rxx-base64 | 144.202.126.147 |
| 73.17 | shadowsocks | 265.6 | 641.2 | 21.63 | 0.0 | 9.48 | 13.37 | 17.4 | Au1rxx-base64 | 156.146.38.169 |
| 72.41 | shadowsocks | 299.2 | 342.5 | 20.85 | 2.16 | 9.85 | 13.37 | 17.4 | Au1rxx-base64 | 149.22.87.241 |
| 71.66 | vless | 284.0 | 625.5 | 21.2 | 0.0 | 10.0 | 10.21 | 17.4 | Au1rxx-base64 | 15.204.97.209 |
| 71.32 | vless | 479.1 | 1207.2 | 16.69 | 0.0 | 9.53 | 10.21 | 17.4 | Au1rxx-base64 | 51.81.203.63 |
| 71.27 | shadowsocks | 287.8 | 618.7 | 21.12 | 0.0 | 9.48 | 13.37 | 17.4 | Au1rxx-base64 | 149.22.95.183 |
| 70.49 | vless | 342.1 | 356.1 | 19.86 | 1.65 | 9.51 | 10.21 | 17.4 | Au1rxx-base64 | 154.31.114.248 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.897 | 0.835 | 357 | 1598 | prefer |
| zhangkai | 0.654 | 1.0 | 11 | 27 | observe |
| mheidari-all | 0.612 | 0.625 | 16 | 23148 | observe |
| Surfboard-tg-mixed | 0.515 | 0.432 | 44 | 6948 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 172 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| Epodonios-all | 0.255 | None | 0 | 7406 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9916 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5438 | observe |
| barry-far-vless | 0.255 | None | 0 | 5654 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 18 |
| geo | ClientOSError | - | 14 |
| speed | ClientOSError | - | 13 |
| 204 | ProxyError | - | 10 |
| speed | TimeoutError | - | 7 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
