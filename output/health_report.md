# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-23 09:35:48 |
| 运行耗时 | 250.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 76189 |
| 去重后节点 | 21935 |
| TCP 可达 | 3000 |
| 真实可用 | 371 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21935 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.4 |
| tcp | 29.3 |
| probe | 65.8 |
| real_test | 115.6 |
| generate | 34.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45913 |
| trojan | 10151 |
| vmess | 9735 |
| shadowsocks | 9733 |
| hysteria2 | 245 |
| http | 171 |
| shadowsocksr | 168 |
| socks | 63 |
| hysteria | 7 |
| tuic | 2 |
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
| 77.11 | shadowsocks | 235.3 | 602.4 | 22.33 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 156.146.38.168 |
| 77.04 | shadowsocks | 238.3 | 614.1 | 22.26 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 156.146.38.170 |
| 76.98 | shadowsocks | 240.9 | 620.6 | 22.2 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 156.146.38.169 |
| 75.0 | shadowsocks | 240.3 | 616.1 | 22.22 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 156.146.38.167 |
| 73.1 | shadowsocks | 266.8 | 567.7 | 21.6 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 173.244.56.9 |
| 72.49 | shadowsocks | 301.8 | 676.9 | 20.79 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 173.244.56.6 |
| 71.7 | shadowsocks | 290.3 | 629.9 | 21.06 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 108.181.0.177 |
| 71.07 | shadowsocks | 329.7 | 732.1 | 20.15 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 37.19.198.236 |
| 70.9 | shadowsocks | 323.5 | 705.4 | 20.29 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 37.19.198.244 |
| 70.55 | shadowsocks | 333.1 | 734.0 | 20.07 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 37.19.198.160 |
| 70.22 | shadowsocks | 349.7 | 773.0 | 19.68 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 108.181.118.10 |
| 69.69 | shadowsocks | 332.1 | 726.2 | 20.09 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 37.19.198.243 |
| 69.6 | shadowsocks | 319.8 | 662.2 | 20.37 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 149.22.95.183 |
| 67.84 | shadowsocks | 334.1 | 380.0 | 20.04 | 0.75 | 9.77 | 13.86 | 14.92 | Au1rxx-base64 | 149.22.87.240 |
| 67.76 | shadowsocks | 335.0 | 379.8 | 20.02 | 0.76 | 9.76 | 13.86 | 14.92 | Au1rxx-base64 | 149.22.87.204 |
| 67.41 | shadowsocks | 336.3 | 385.0 | 19.99 | 0.56 | 9.73 | 13.86 | 14.92 | Au1rxx-base64 | 149.22.87.241 |
| 66.95 | vless | 353.7 | 852.7 | 19.59 | 0.0 | 10.0 | 3.75 | 14.92 | Au1rxx-base64 | 15.204.97.219 |
| 66.89 | vmess | 226.8 | 535.1 | 22.53 | 0.0 | 10.0 | 12.5 | 6.36 | Barabama-yudou | 82.198.246.233 |
| 66.42 | vless | 350.1 | 852.1 | 19.67 | 0.0 | 10.0 | 3.75 | 14.92 | Au1rxx-base64 | 15.204.97.214 |
| 65.95 | shadowsocks | 340.8 | 738.7 | 19.89 | 0.0 | 10.0 | 13.86 | 14.92 | Au1rxx-base64 | 147.90.234.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.987 | 1.0 | 58 | 95 | prefer |
| Au1rxx-base64 | 0.761 | 0.763 | 76 | 126 | prefer |
| Surfboard-tg-mixed | 0.727 | 0.649 | 205 | 5285 | prefer |
| DeltaKronecker-all | 0.664 | 0.587 | 75 | 6437 | observe |
| mheidari-all | 0.58 | 0.5 | 152 | 15546 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4576 | observe |
| Epodonios-all | 0.255 | None | 0 | 7878 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7202 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4084 | observe |
| barry-far-vless | 0.255 | None | 0 | 4896 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4477 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 71 |
| 204 | TimeoutError | - | 33 |
| 204 | ProxyError | - | 18 |
| geo | TimeoutError | - | 16 |
| cn-block | TimeoutError | - | 16 |
| geo | ClientOSError | - | 11 |
| speed | TimeoutError | - | 10 |
| speed | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
