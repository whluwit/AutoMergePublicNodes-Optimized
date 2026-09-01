# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-01 03:18:57 |
| 运行耗时 | 291.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 79254 |
| 去重后节点 | 22371 |
| TCP 可达 | 3000 |
| 真实可用 | 737 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22371 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.2 |
| tcp | 35.1 |
| probe | 85.2 |
| real_test | 137.7 |
| generate | 26.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49694 |
| vmess | 11143 |
| shadowsocks | 10101 |
| trojan | 6246 |
| hysteria2 | 1722 |
| http | 139 |
| shadowsocksr | 119 |
| socks | 76 |
| hysteria | 7 |
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
| 83.98 | vless | 244.4 | 655.7 | 22.12 | 0.0 | 10.0 | 12.64 | 19.22 | Au1rxx-base64 | 204.48.20.223 |
| 83.73 | vless | 248.2 | 635.2 | 22.03 | 0.0 | 10.0 | 12.64 | 19.06 | Surfboard-tg-mixed | 172.105.104.54 |
| 83.47 | vless | 252.8 | 659.5 | 21.93 | 0.0 | 10.0 | 12.64 | 18.9 | mheidari-all | 169.40.42.74 |
| 83.21 | vless | 258.9 | 627.4 | 21.79 | 0.0 | 10.0 | 12.64 | 19.22 | Au1rxx-base64 | 195.211.99.45 |
| 82.81 | vless | 294.9 | 814.7 | 20.95 | 0.0 | 10.0 | 12.64 | 19.22 | Au1rxx-base64 | 79.127.243.217 |
| 82.43 | vless | 311.6 | 863.8 | 20.57 | 0.0 | 10.0 | 12.64 | 19.22 | Au1rxx-base64 | 137.184.218.169 |
| 82.23 | vless | 306.1 | 772.8 | 20.69 | 0.0 | 10.0 | 12.64 | 18.9 | mheidari-all | 66.70.179.198 |
| 81.84 | vless | 282.2 | 630.6 | 21.25 | 0.0 | 10.0 | 12.64 | 18.9 | mheidari-all | 169.40.42.35 |
| 81.75 | vless | 340.7 | 928.0 | 19.89 | 0.0 | 10.0 | 12.64 | 19.22 | Au1rxx-base64 | 169.40.42.223 |
| 81.71 | vless | 335.4 | 903.7 | 20.01 | 0.0 | 10.0 | 12.64 | 19.06 | Surfboard-tg-mixed | 169.40.42.16 |
| 81.61 | vless | 325.8 | 818.2 | 20.24 | 0.0 | 10.0 | 12.64 | 19.06 | Surfboard-tg-mixed | 158.69.112.254 |
| 81.45 | shadowsocks | 228.9 | 632.8 | 22.48 | 0.0 | 10.0 | 14.07 | 18.9 | mheidari-all | 37.19.198.243 |
| 81.32 | shadowsocks | 234.4 | 646.0 | 22.35 | 0.0 | 10.0 | 14.07 | 18.9 | mheidari-all | 37.19.198.244 |
| 81.14 | shadowsocks | 234.6 | 593.8 | 22.35 | 0.0 | 10.0 | 14.07 | 19.22 | Au1rxx-base64 | 84.32.131.61 |
| 81.04 | vless | 357.5 | 926.7 | 19.5 | 0.0 | 10.0 | 12.64 | 18.9 | mheidari-all | 169.40.42.163 |
| 81.0 | vless | 366.2 | 938.2 | 19.3 | 0.0 | 10.0 | 12.64 | 19.06 | Surfboard-tg-mixed | 169.40.42.133 |
| 80.99 | vless | 359.9 | 924.8 | 19.45 | 0.0 | 10.0 | 12.64 | 18.9 | mheidari-all | 169.40.42.15 |
| 80.7 | vless | 379.2 | 976.6 | 19.0 | 0.0 | 10.0 | 12.64 | 19.06 | Surfboard-tg-mixed | 169.40.42.173 |
| 80.62 | vless | 264.1 | 638.9 | 21.66 | 0.0 | 10.0 | 12.64 | 19.06 | Surfboard-tg-mixed | 169.40.42.184 |
| 80.61 | vless | 315.8 | 847.6 | 20.47 | 0.0 | 10.0 | 12.64 | 19.06 | Surfboard-tg-mixed | 169.40.42.212 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | 0.944 | 286 | 1183 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.841 | 0.763 | 266 | 6997 | prefer |
| mheidari-all | 0.837 | 0.759 | 274 | 15162 | prefer |
| DeltaKronecker-all | 0.427 | 0.344 | 96 | 5904 | observe |
| Epodonios-all | 0.255 | None | 0 | 7436 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7826 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5908 | observe |
| barry-far-vless | 0.255 | None | 0 | 6067 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4025 | observe |
| Au1rxx-clash | 0.222 | None | 0 | 1183 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |
| ninja-vless | 0.199 | 0.0 | 1 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 57 |
| geo | ClientOSError | - | 42 |
| speed | TimeoutError | - | 42 |
| speed | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 6 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
