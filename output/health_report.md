# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-04 20:15:36 |
| 运行耗时 | 280.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 84222 |
| 去重后节点 | 23527 |
| TCP 可达 | 3000 |
| 真实可用 | 587 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23527 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 38.1 |
| probe | 71.4 |
| real_test | 127.3 |
| generate | 37.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53319 |
| vmess | 11512 |
| shadowsocks | 9667 |
| trojan | 7950 |
| hysteria2 | 1359 |
| http | 192 |
| shadowsocksr | 130 |
| socks | 67 |
| tuic | 15 |
| hysteria | 10 |
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
| 83.56 | vless | 248.2 | 657.9 | 22.03 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.89 |
| 83.41 | vless | 254.7 | 692.4 | 21.88 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 204.48.20.223 |
| 83.22 | vless | 263.0 | 688.1 | 21.69 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.184 |
| 82.61 | vless | 289.3 | 762.2 | 21.08 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.16 |
| 82.55 | vless | 291.8 | 737.8 | 21.02 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 66.70.179.198 |
| 82.43 | vless | 297.2 | 782.7 | 20.9 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.235 |
| 82.37 | vless | 299.7 | 803.6 | 20.84 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.104 |
| 82.3 | vless | 302.9 | 812.5 | 20.77 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.225 |
| 82.28 | vless | 273.4 | 665.2 | 21.45 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.173 |
| 82.01 | vless | 315.4 | 791.7 | 20.48 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.75 |
| 81.77 | vless | 282.3 | 704.2 | 21.24 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 2.24.124.64 |
| 81.63 | vless | 331.7 | 886.7 | 20.1 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.133 |
| 81.55 | vless | 263.5 | 642.5 | 21.68 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.52 |
| 81.28 | vless | 280.4 | 607.7 | 21.29 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.232 |
| 81.19 | vless | 350.9 | 894.2 | 19.66 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.202 |
| 81.05 | vless | 356.7 | 985.3 | 19.52 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 185.95.231.156 |
| 80.72 | vless | 279.6 | 730.1 | 21.31 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.95 |
| 80.5 | vless | 301.5 | 843.0 | 20.8 | 0.0 | 9.27 | 12.23 | 19.3 | Au1rxx-base64 | using.neobo-tooth.ru |
| 80.37 | vless | 386.0 | 948.2 | 18.84 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 169.40.42.168 |
| 80.24 | vless | 344.1 | 968.0 | 19.81 | 0.0 | 10.0 | 12.23 | 19.3 | Au1rxx-base64 | 45.138.100.226 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| Au1rxx-base64 | 0.952 | 0.884 | 346 | 1756 | prefer |
| mheidari-all | 0.899 | 0.825 | 114 | 16096 | prefer |
| Surfboard-tg-mixed | 0.807 | 0.729 | 170 | 7342 | prefer |
| DeltaKronecker-all | 0.747 | 0.673 | 49 | 7089 | prefer |
| tg-oneclickvpnkeys | 0.554 | 1.0 | 8 | 118 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| Epodonios-all | 0.255 | None | 0 | 7798 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8118 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6159 | observe |
| barry-far-vless | 0.255 | None | 0 | 6376 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4095 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1756 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 27 |
| geo | ClientOSError | - | 22 |
| 204 | TimeoutError | - | 18 |
| cn-block | ClientOSError | - | 14 |
| 204 | ProxyError | - | 12 |
| speed | TimeoutError | - | 10 |
| speed | ClientOSError | - | 9 |
| geo | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
