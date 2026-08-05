# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-05 19:27:11 |
| 运行耗时 | 236.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 87797 |
| 去重后节点 | 24099 |
| TCP 可达 | 3000 |
| 真实可用 | 480 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24099 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 36.1 |
| probe | 47.8 |
| real_test | 103.5 |
| generate | 41.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52007 |
| vmess | 13141 |
| trojan | 10738 |
| shadowsocks | 10326 |
| hysteria2 | 1361 |
| socks | 74 |
| shadowsocksr | 72 |
| http | 24 |
| anytls | 21 |
| hysteria | 19 |
| tuic | 14 |

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
| 82.52 | hysteria2 | 297.5 | 600.0 | 20.89 | 0.0 | 8.66 | 14.29 | 19.78 | Au1rxx-base64 | 159.223.157.129 |
| 82.34 | hysteria2 | 309.7 | 614.6 | 20.61 | 0.0 | 8.66 | 14.29 | 19.78 | Au1rxx-base64 | 138.124.68.188 |
| 81.9 | vless | 257.2 | 649.6 | 21.82 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 167.17.69.171 |
| 80.41 | trojan | 329.8 | 886.7 | 20.14 | 0.0 | 8.87 | 14.62 | 19.78 | Au1rxx-base64 | 153.75.250.171 |
| 80.05 | hysteria2 | 303.8 | 830.4 | 20.75 | 0.0 | 6.23 | 14.29 | 19.78 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 80.0 | shadowsocks | 243.7 | 632.2 | 22.14 | 0.0 | 8.73 | 13.35 | 19.78 | Au1rxx-base64 | 37.19.198.244 |
| 79.94 | vless | 288.5 | 678.9 | 21.1 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 169.40.42.179 |
| 79.88 | shadowsocks | 248.2 | 633.5 | 22.03 | 0.0 | 8.72 | 13.35 | 19.78 | Au1rxx-base64 | 37.19.198.160 |
| 79.85 | shadowsocks | 250.1 | 656.5 | 21.99 | 0.0 | 8.73 | 13.35 | 19.78 | Au1rxx-base64 | 37.19.198.236 |
| 79.69 | vless | 296.6 | 698.3 | 20.91 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 216.152.147.28 |
| 79.3 | vless | 369.8 | 988.4 | 19.22 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 169.40.42.95 |
| 78.93 | vless | 256.0 | 663.3 | 21.85 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 159.89.87.21 |
| 78.29 | vless | 365.8 | 1012.8 | 19.31 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 45.138.100.226 |
| 78.22 | vless | 380.3 | 958.1 | 18.98 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 158.69.112.254 |
| 78.19 | vless | 381.8 | 908.3 | 18.94 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 169.40.42.212 |
| 78.17 | vless | 370.9 | 922.2 | 19.19 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 169.40.42.75 |
| 78.16 | vless | 289.5 | 641.6 | 21.08 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 104.17.21.111 |
| 78.09 | vless | 363.4 | 972.8 | 19.37 | 0.0 | 8.64 | 10.3 | 19.78 | Au1rxx-base64 | 78.111.89.171 |
| 77.29 | trojan | 304.1 | 657.2 | 20.74 | 0.0 | 8.87 | 14.62 | 19.78 | Au1rxx-base64 | 163.245.196.68 |
| 77.13 | vless | 296.4 | 715.6 | 20.92 | 0.0 | 10.0 | 10.3 | 19.78 | Au1rxx-base64 | 128.254.207.163 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.996 | 0.936 | 405 | 1563 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.639 | 0.56 | 100 | 5930 | observe |
| mheidari-all | 0.483 | 0.4 | 60 | 20396 | observe |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 5316 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5260 | observe |
| Epodonios-all | 0.255 | None | 0 | 6540 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7160 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4758 | observe |
| barry-far-vless | 0.255 | None | 0 | 5072 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5206 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 4655 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.239 | None | 0 | 1594 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 34 |
| geo | ClientOSError | - | 20 |
| 204 | ProxyError | - | 17 |
| 204 | TimeoutError | - | 14 |
| speed | TimeoutError | - | 9 |
| cn-block | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 2 |
| speed | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
