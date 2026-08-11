# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-11 01:22:46 |
| 运行耗时 | 299.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85331 |
| 去重后节点 | 24694 |
| TCP 可达 | 3000 |
| 真实可用 | 574 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24694 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 37.0 |
| probe | 64.1 |
| real_test | 163.7 |
| generate | 28.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50306 |
| vmess | 13230 |
| trojan | 10516 |
| shadowsocks | 9707 |
| hysteria2 | 1304 |
| shadowsocksr | 75 |
| socks | 74 |
| http | 72 |
| anytls | 26 |
| hysteria | 13 |
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
| 82.27 | hysteria2 | 285.8 | 713.6 | 21.16 | 0.0 | 10.0 | 13.33 | 18.78 | Au1rxx-base64 | 138.124.68.188 |
| 81.99 | hysteria2 | 275.8 | 672.8 | 21.39 | 0.0 | 10.0 | 13.33 | 18.78 | Au1rxx-base64 | 159.223.157.129 |
| 81.33 | trojan | 283.7 | 714.5 | 21.21 | 0.0 | 10.0 | 14.34 | 18.78 | Au1rxx-base64 | 64.94.95.115 |
| 80.58 | hysteria2 | 280.5 | 695.8 | 21.29 | 0.0 | 8.18 | 13.33 | 18.78 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 80.16 | trojan | 319.7 | 793.1 | 20.38 | 0.0 | 10.0 | 14.34 | 18.78 | Au1rxx-base64 | 64.94.95.117 |
| 79.69 | trojan | 354.5 | 895.3 | 19.57 | 0.0 | 10.0 | 14.34 | 18.78 | Au1rxx-base64 | 64.94.95.114 |
| 79.01 | shadowsocks | 262.4 | 648.5 | 21.7 | 0.0 | 10.0 | 12.53 | 18.78 | Au1rxx-base64 | 156.146.38.169 |
| 78.46 | shadowsocks | 286.2 | 775.5 | 21.15 | 0.0 | 10.0 | 12.53 | 18.78 | Au1rxx-base64 | 156.146.38.170 |
| 77.53 | shadowsocks | 255.9 | 634.5 | 21.85 | 0.0 | 10.0 | 12.53 | 18.78 | Au1rxx-base64 | 156.146.38.168 |
| 76.53 | shadowsocks | 294.3 | 717.8 | 20.96 | 0.0 | 10.0 | 12.53 | 18.78 | Au1rxx-base64 | 37.19.198.160 |
| 76.5 | shadowsocks | 281.9 | 673.6 | 21.25 | 0.0 | 10.0 | 12.53 | 18.78 | Au1rxx-base64 | 37.19.198.243 |
| 76.15 | trojan | 305.9 | 566.2 | 20.7 | 0.0 | 10.0 | 14.34 | 18.78 | Au1rxx-base64 | 44.244.3.114 |
| 75.78 | trojan | 320.7 | 602.9 | 20.36 | 0.0 | 10.0 | 14.34 | 18.78 | Au1rxx-base64 | 44.242.235.129 |
| 75.12 | trojan | 346.7 | 688.5 | 19.75 | 0.0 | 10.0 | 14.34 | 18.78 | Au1rxx-base64 | 44.246.163.102 |
| 74.88 | trojan | 358.2 | 711.9 | 19.49 | 0.0 | 10.0 | 14.34 | 18.78 | Au1rxx-base64 | 35.86.90.51 |
| 74.83 | vless | 313.2 | 668.6 | 20.53 | 0.0 | 10.0 | 8.95 | 18.78 | Au1rxx-base64 | 179.253.240.24 |
| 74.44 | vless | 321.0 | 541.2 | 20.35 | 0.0 | 10.0 | 8.95 | 18.78 | Au1rxx-base64 | 186.241.106.97 |
| 74.24 | shadowsocks | 300.1 | 651.9 | 20.83 | 0.0 | 10.0 | 12.53 | 18.78 | Au1rxx-base64 | 198.98.53.130 |
| 73.87 | vless | 324.4 | 708.5 | 20.27 | 0.0 | 10.0 | 8.95 | 18.78 | Au1rxx-base64 | 179.255.148.66 |
| 73.61 | shadowsocks | 369.7 | 923.3 | 19.22 | 0.0 | 10.0 | 12.53 | 18.78 | Au1rxx-base64 | 68.168.222.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | 0.98 | 50 | 67 | prefer |
| Surfboard-tg-mixed | 0.955 | 0.947 | 19 | 6306 | prefer |
| Au1rxx-base64 | 0.949 | 0.893 | 392 | 1464 | prefer |
| DeltaKronecker-all | 0.314 | 0.233 | 631 | 5881 | observe |
| mheidari-all | 0.307 | 0.214 | 42 | 20211 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 6946 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7525 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5176 | observe |
| barry-far-vless | 0.255 | None | 0 | 5506 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5191 | observe |
| nscl5-all | 0.239 | None | 0 | 1607 | observe |
| Au1rxx-clash | 0.234 | None | 0 | 1464 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 202 |
| speed | ClientOSError | - | 108 |
| 204 | ProxyError | - | 85 |
| geo | ClientOSError | - | 74 |
| speed | TimeoutError | - | 40 |
| cn-block | TimeoutError | - | 23 |
| cn-block | ProxyError | - | 13 |
| 204 | TimeoutError | - | 12 |
| geo | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
