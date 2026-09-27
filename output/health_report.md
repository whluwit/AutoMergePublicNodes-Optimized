# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 16:24:57 |
| 运行耗时 | 521.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 96138 |
| 去重后节点 | 26664 |
| TCP 可达 | 3000 |
| 真实可用 | 373 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26664 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.6 |
| tcp | 43.1 |
| probe | 212.4 |
| real_test | 166.7 |
| generate | 90.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58724 |
| vmess | 14606 |
| shadowsocks | 11321 |
| trojan | 9176 |
| hysteria2 | 1450 |
| http | 574 |
| shadowsocksr | 170 |
| socks | 69 |
| anytls | 25 |
| hysteria | 15 |
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
| 80.02 | vless | 258.1 | 681.0 | 21.8 | 0.0 | 9.12 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.173 |
| 79.87 | vless | 264.9 | 644.2 | 21.65 | 0.0 | 9.12 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.229 |
| 79.48 | vless | 281.4 | 747.2 | 21.26 | 0.0 | 9.12 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.95 |
| 79.2 | vless | 294.1 | 748.3 | 20.97 | 0.0 | 9.13 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.235 |
| 78.66 | vless | 318.9 | 740.3 | 20.4 | 0.0 | 9.16 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.179 |
| 78.4 | vless | 332.7 | 852.1 | 20.08 | 0.0 | 9.22 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.133 |
| 78.39 | vless | 329.3 | 847.4 | 20.16 | 0.0 | 9.13 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.168 |
| 78.13 | shadowsocks | 255.3 | 710.5 | 21.87 | 0.0 | 9.2 | 12.8 | 18.26 | Au1rxx-base64 | 37.19.198.244 |
| 78.11 | vless | 343.0 | 933.6 | 19.84 | 0.0 | 9.17 | 10.84 | 18.26 | Au1rxx-base64 | 38.77.133.202 |
| 77.77 | vless | 357.6 | 989.2 | 19.5 | 0.0 | 9.17 | 10.84 | 18.26 | Au1rxx-base64 | 185.95.231.156 |
| 77.63 | vless | 265.4 | 645.7 | 21.63 | 0.0 | 9.13 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.90 |
| 77.36 | vless | 303.4 | 756.5 | 20.75 | 0.0 | 9.18 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.16 |
| 77.35 | vless | 374.1 | 916.2 | 19.12 | 0.0 | 9.13 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.35 |
| 77.28 | vless | 381.0 | 1060.8 | 18.96 | 0.0 | 9.22 | 10.84 | 18.26 | Au1rxx-base64 | 185.95.231.233 |
| 77.08 | vless | 389.9 | 1061.8 | 18.75 | 0.0 | 9.23 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.52 |
| 77.03 | vless | 288.2 | 645.5 | 21.11 | 0.0 | 9.09 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.231 |
| 76.99 | vless | 262.2 | 741.8 | 21.71 | 0.0 | 9.18 | 10.84 | 18.26 | Au1rxx-base64 | 47.90.153.88 |
| 76.89 | vless | 281.7 | 708.9 | 21.26 | 0.0 | 9.13 | 10.84 | 18.26 | Au1rxx-base64 | 169.40.42.163 |
| 76.84 | vless | 300.1 | 680.0 | 20.83 | 0.0 | 9.08 | 10.84 | 18.26 | Au1rxx-base64 | 198.251.78.29 |
| 76.45 | shadowsocks | 254.3 | 714.7 | 21.89 | 0.0 | 10.0 | 12.8 | 15.76 | mheidari-all | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.89 | 0.828 | 309 | 1601 | prefer |
| Surfboard-tg-mixed | 0.884 | 0.818 | 44 | 7109 | prefer |
| mheidari-all | 0.858 | 0.786 | 70 | 22413 | prefer |
| ermaozi | 0.66 | 0.657 | 35 | 289 | observe |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 5466 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7600 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9194 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5703 | observe |
| barry-far-vless | 0.255 | None | 0 | 5938 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4277 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1601 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 20 |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 20 |
| speed | TimeoutError | - | 12 |
| geo | TimeoutError | - | 11 |
| speed | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
