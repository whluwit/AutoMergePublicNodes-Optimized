# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-28 08:46:46 |
| 运行耗时 | 263.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 81032 |
| 去重后节点 | 23362 |
| TCP 可达 | 3000 |
| 真实可用 | 505 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23362 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 39.1 |
| probe | 54.4 |
| real_test | 124.4 |
| generate | 37.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48939 |
| shadowsocks | 11265 |
| vmess | 11198 |
| trojan | 7358 |
| hysteria2 | 1867 |
| http | 170 |
| shadowsocksr | 135 |
| socks | 73 |
| hysteria | 13 |
| anytls | 10 |
| tuic | 4 |

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
| 83.88 | vless | 215.9 | 594.9 | 22.78 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 195.211.99.49 |
| 83.87 | vless | 216.3 | 600.0 | 22.77 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 195.211.99.45 |
| 83.75 | vless | 221.6 | 611.0 | 22.65 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 195.211.98.214 |
| 83.66 | hysteria2 | 258.8 | 652.6 | 21.79 | 0.0 | 10.0 | 13.27 | 19.7 | Au1rxx-base64 | 159.223.157.129 |
| 82.72 | vless | 266.0 | 691.8 | 21.62 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 216.152.147.28 |
| 82.14 | vless | 277.3 | 679.3 | 21.36 | 0.0 | 9.77 | 11.4 | 19.7 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 82.01 | vless | 282.7 | 677.0 | 21.23 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 167.17.69.171 |
| 81.96 | vless | 298.8 | 749.1 | 20.86 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 47.89.186.170 |
| 81.85 | vless | 292.3 | 688.3 | 21.01 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 204.48.20.223 |
| 81.63 | vless | 271.9 | 634.7 | 21.48 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 216.227.161.95 |
| 81.55 | vless | 316.6 | 723.2 | 20.45 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 169.40.42.74 |
| 80.72 | shadowsocks | 265.7 | 661.0 | 21.63 | 0.0 | 10.0 | 13.39 | 19.7 | Au1rxx-base64 | 156.146.38.169 |
| 80.57 | vless | 358.9 | 921.2 | 19.47 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 79.127.243.217 |
| 80.19 | vless | 375.2 | 908.2 | 19.09 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 169.40.42.182 |
| 79.91 | shadowsocks | 257.3 | 659.1 | 21.82 | 0.0 | 10.0 | 13.39 | 19.7 | Au1rxx-base64 | 37.19.198.236 |
| 79.81 | vless | 349.4 | 854.4 | 19.69 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 66.70.179.198 |
| 79.72 | vless | 395.5 | 954.3 | 18.62 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 169.40.42.229 |
| 79.58 | vless | 386.5 | 989.1 | 18.83 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 169.40.42.235 |
| 79.47 | vless | 359.1 | 935.5 | 19.47 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 45.138.100.226 |
| 79.13 | vless | 297.7 | 713.1 | 20.89 | 0.0 | 10.0 | 11.4 | 19.7 | Au1rxx-base64 | 184.107.106.68 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Au1rxx-base64 | 0.952 | 0.882 | 304 | 1822 | prefer |
| Surfboard-tg-mixed | 0.826 | 0.75 | 136 | 6427 | prefer |
| mheidari-all | 0.771 | 0.698 | 53 | 14456 | prefer |
| DeltaKronecker-all | 0.57 | 0.49 | 149 | 4318 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 87 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4783 | observe |
| Epodonios-all | 0.255 | None | 0 | 6791 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3990 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6921 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5241 | observe |
| barry-far-vless | 0.255 | None | 0 | 5416 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4061 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1822 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 39 |
| 204 | TimeoutError | - | 26 |
| cn-block | TimeoutError | - | 22 |
| geo | TimeoutError | - | 22 |
| speed | ClientOSError | - | 20 |
| speed | TimeoutError | - | 17 |
| 204 | ProxyError | - | 15 |
| cn-block | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
