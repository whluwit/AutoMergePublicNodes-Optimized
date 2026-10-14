# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 11:12:27 |
| 运行耗时 | 589.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98253 |
| 去重后节点 | 27177 |
| TCP 可达 | 3000 |
| 真实可用 | 335 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27177 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| geo | 1.5 |
| tcp | 47.6 |
| probe | 230.0 |
| real_test | 225.2 |
| generate | 76.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58047 |
| vmess | 16099 |
| shadowsocks | 11810 |
| trojan | 10208 |
| hysteria2 | 1304 |
| http | 483 |
| shadowsocksr | 167 |
| socks | 86 |
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
| 82.52 | shadowsocks | 254.8 | 634.1 | 21.88 | 0.0 | 10.0 | 14.64 | 20.0 | Surfboard-tg-mixed | 156.146.38.167 |
| 82.14 | shadowsocks | 239.1 | 636.3 | 22.24 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 156.146.38.169 |
| 82.05 | hysteria2 | 290.5 | 720.8 | 21.05 | 0.0 | 10.0 | 13.24 | 19.26 | Au1rxx-base64 | 129.213.91.185 |
| 81.97 | shadowsocks | 246.5 | 616.9 | 22.07 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 156.146.38.168 |
| 81.87 | shadowsocks | 251.0 | 626.5 | 21.97 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 156.146.38.170 |
| 79.83 | shadowsocks | 302.2 | 752.3 | 20.78 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 37.19.198.243 |
| 79.74 | shadowsocks | 295.5 | 725.6 | 20.94 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 37.19.198.160 |
| 79.53 | shadowsocks | 300.7 | 744.9 | 20.82 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 37.19.198.244 |
| 79.15 | shadowsocks | 303.1 | 743.8 | 20.76 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 37.19.198.236 |
| 76.77 | shadowsocks | 375.7 | 895.6 | 19.08 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 140.82.63.79 |
| 76.48 | shadowsocks | 391.4 | 993.3 | 18.72 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 15.204.233.41 |
| 76.47 | shadowsocks | 302.3 | 628.7 | 20.78 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 149.22.95.183 |
| 75.89 | shadowsocks | 381.4 | 985.0 | 18.95 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 15.204.247.206 |
| 74.64 | trojan | 496.5 | 1281.5 | 16.28 | 0.0 | 10.0 | 14.09 | 19.26 | Au1rxx-base64 | 69.164.240.85 |
| 74.48 | shadowsocks | 302.8 | 583.4 | 20.77 | 0.0 | 10.0 | 14.64 | 19.26 | Au1rxx-base64 | 173.244.56.6 |
| 73.96 | vless | 292.2 | 583.4 | 21.01 | 0.0 | 10.0 | 7.65 | 19.26 | Au1rxx-base64 | 45.32.69.110 |
| 73.79 | hysteria2 | 570.7 | 652.8 | 14.57 | 0.0 | 10.0 | 13.24 | 19.26 | Au1rxx-base64 | 66.94.121.46 |
| 73.72 | vless | 294.8 | 602.8 | 20.95 | 0.0 | 10.0 | 7.65 | 19.26 | Au1rxx-base64 | 144.202.126.147 |
| 72.82 | vless | 386.2 | 932.2 | 18.84 | 0.0 | 10.0 | 7.65 | 19.26 | Au1rxx-base64 | 159.89.87.21 |
| 72.73 | vless | 322.6 | 602.0 | 20.31 | 0.0 | 10.0 | 7.65 | 19.26 | Au1rxx-base64 | 154.29.145.196 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.916 | 0.847 | 255 | 1786 | prefer |
| zhangkai | 0.894 | 1.0 | 18 | 144 | prefer |
| mheidari-all | 0.892 | 0.826 | 46 | 23983 | prefer |
| Surfboard-tg-mixed | 0.67 | 0.592 | 76 | 7056 | observe |
| ermaozi-get_subscribe | 0.42 | 0.391 | 46 | 598 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7542 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10026 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5579 | observe |
| barry-far-vless | 0.255 | None | 0 | 5831 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1786 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 32 |
| 204 | ProxyError | - | 28 |
| cn-block | TimeoutError | - | 20 |
| geo | ClientOSError | - | 9 |
| speed | ClientOSError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| speed | TimeoutError | - | 4 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
