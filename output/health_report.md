# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 15:27:43 |
| 运行耗时 | 675.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98081 |
| 去重后节点 | 27683 |
| TCP 可达 | 3000 |
| 真实可用 | 381 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27683 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 48.5 |
| probe | 277.3 |
| real_test | 249.1 |
| generate | 90.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57735 |
| vmess | 16742 |
| shadowsocks | 11752 |
| trojan | 9647 |
| hysteria2 | 1310 |
| http | 613 |
| shadowsocksr | 167 |
| socks | 69 |
| anytls | 22 |
| hysteria | 17 |
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
| 82.2 | hysteria2 | 242.5 | 680.5 | 22.16 | 0.0 | 10.0 | 13.5 | 18.04 | Au1rxx-base64 | 129.213.91.185 |
| 80.66 | vless | 252.1 | 670.0 | 21.94 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.184 |
| 80.65 | vless | 252.6 | 676.9 | 21.93 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 147.45.60.160 |
| 80.5 | vless | 259.0 | 665.9 | 21.78 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.163 |
| 80.34 | vless | 266.1 | 645.0 | 21.62 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.173 |
| 79.86 | vless | 286.9 | 635.8 | 21.14 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.90 |
| 79.57 | vless | 299.2 | 741.5 | 20.85 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.179 |
| 79.49 | vless | 302.7 | 741.6 | 20.77 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.35 |
| 79.33 | vless | 309.8 | 706.9 | 20.61 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.232 |
| 79.24 | vless | 313.7 | 715.0 | 20.52 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.225 |
| 79.16 | vless | 317.1 | 878.9 | 20.44 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 159.89.87.21 |
| 78.66 | vless | 338.6 | 791.9 | 19.94 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.224 |
| 78.63 | vless | 340.1 | 926.0 | 19.91 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 185.95.231.156 |
| 78.37 | vless | 351.0 | 827.1 | 19.65 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.15 |
| 78.31 | vless | 353.7 | 957.4 | 19.59 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.133 |
| 78.23 | vless | 357.1 | 992.0 | 19.51 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 195.123.235.183 |
| 78.2 | vless | 293.4 | 663.9 | 20.99 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.89 |
| 77.98 | vless | 265.7 | 629.8 | 21.63 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.212 |
| 77.77 | vless | 299.6 | 662.9 | 20.84 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.235 |
| 77.12 | vless | 279.5 | 690.4 | 21.31 | 0.0 | 10.0 | 10.68 | 18.04 | Au1rxx-base64 | 169.40.42.229 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.879 | 0.812 | 356 | 1730 | prefer |
| mheidari-all | 0.822 | 0.759 | 29 | 23775 | prefer |
| ermaozi | 0.72 | 0.706 | 34 | 639 | prefer |
| Surfboard-tg-mixed | 0.634 | 0.556 | 81 | 7095 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| Epodonios-all | 0.255 | None | 0 | 7485 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10058 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5602 | observe |
| barry-far-vless | 0.255 | None | 0 | 5815 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1730 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 33 |
| 204 | TimeoutError | - | 26 |
| 204 | ProxyError | - | 13 |
| speed | ClientOSError | - | 12 |
| 204 | ProxyConnectionError | - | 11 |
| geo | ClientOSError | - | 10 |
| speed | TimeoutError | - | 7 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
