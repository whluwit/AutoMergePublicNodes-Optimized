# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-12 04:18:31 |
| 运行耗时 | 1144.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99269 |
| 去重后节点 | 27605 |
| TCP 可达 | 3000 |
| 真实可用 | 544 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27605 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 47.1 |
| probe | 355.0 |
| real_test | 648.6 |
| generate | 84.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58210 |
| vmess | 15773 |
| shadowsocks | 11902 |
| trojan | 10920 |
| hysteria2 | 1491 |
| http | 684 |
| shadowsocksr | 165 |
| socks | 69 |
| anytls | 31 |
| hysteria | 16 |
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
| 84.19 | vless | 271.3 | 694.5 | 21.5 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 84.09 | vless | 275.7 | 662.9 | 21.4 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.15 |
| 83.85 | vless | 285.8 | 738.0 | 21.16 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.212 |
| 83.41 | vless | 304.8 | 843.3 | 20.72 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 136.107.170.196 |
| 83.24 | vless | 288.5 | 626.8 | 21.1 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 172.245.253.16 |
| 83.24 | vless | 297.2 | 774.0 | 20.9 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.90 |
| 83.05 | hysteria2 | 274.3 | 772.7 | 21.43 | 0.0 | 10.0 | 13.12 | 20.0 | Au1rxx-base64 | 129.213.91.185 |
| 83.04 | vless | 277.8 | 672.9 | 21.35 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.89 |
| 82.74 | vless | 247.6 | 669.6 | 22.05 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 147.45.60.160 |
| 82.71 | vless | 335.3 | 886.3 | 20.02 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 159.89.87.21 |
| 82.6 | vless | 339.8 | 904.6 | 19.91 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.95 |
| 82.49 | vless | 284.0 | 654.0 | 21.2 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.235 |
| 82.37 | vless | 306.6 | 688.5 | 20.68 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.224 |
| 82.17 | vless | 358.6 | 957.8 | 19.48 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.229 |
| 81.79 | vless | 350.1 | 822.3 | 19.67 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.225 |
| 81.74 | vless | 377.2 | 1034.9 | 19.05 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 185.95.231.156 |
| 81.67 | vless | 261.5 | 667.8 | 21.72 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 169.40.42.52 |
| 81.6 | shadowsocks | 259.6 | 706.0 | 21.77 | 0.0 | 10.0 | 13.83 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 81.48 | shadowsocks | 264.8 | 723.8 | 21.65 | 0.0 | 10.0 | 13.83 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.46 | shadowsocks | 265.4 | 725.3 | 21.63 | 0.0 | 10.0 | 13.83 | 20.0 | Au1rxx-base64 | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.992 | 0.921 | 381 | 1815 | prefer |
| Surfboard-tg-mixed | 0.898 | 0.85 | 20 | 7200 | prefer |
| ermaozi | 0.682 | 0.66 | 50 | 708 | observe |
| mheidari-all | 0.388 | 0.307 | 450 | 23656 | observe |
| DeltaKronecker-all | 0.298 | 0.273 | 11 | 5372 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| Epodonios-all | 0.255 | None | 0 | 7699 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9443 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5717 | observe |
| barry-far-vless | 0.255 | None | 0 | 5961 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4284 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1815 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 182 |
| speed | TimeoutError | - | 82 |
| 204 | ProxyError | - | 27 |
| speed | ClientOSError | - | 25 |
| geo | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 18 |
| cn-block | ClientOSError | - | 5 |
| 204 | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
