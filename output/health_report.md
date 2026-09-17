# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 16:15:11 |
| 运行耗时 | 538.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84819 |
| 去重后节点 | 23036 |
| TCP 可达 | 3000 |
| 真实可用 | 434 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23036 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.5 |
| tcp | 38.4 |
| probe | 222.0 |
| real_test | 227.4 |
| generate | 42.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51094 |
| vmess | 13386 |
| shadowsocks | 10096 |
| trojan | 8111 |
| hysteria2 | 1375 |
| http | 545 |
| shadowsocksr | 126 |
| socks | 74 |
| hysteria | 8 |
| tuic | 2 |
| anytls | 2 |

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
| 79.77 | hysteria2 | 250.8 | 666.9 | 21.97 | 0.0 | 10.0 | 12.14 | 16.76 | mheidari-all | 159.223.157.129 |
| 79.08 | vless | 254.1 | 659.7 | 21.9 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 137.184.218.169 |
| 78.29 | vless | 288.1 | 689.7 | 21.11 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.232 |
| 78.12 | shadowsocks | 246.4 | 654.3 | 22.07 | 0.0 | 10.0 | 13.29 | 16.76 | mheidari-all | 37.19.198.160 |
| 78.07 | shadowsocks | 248.8 | 664.4 | 22.02 | 0.0 | 10.0 | 13.29 | 16.76 | mheidari-all | 37.19.198.236 |
| 78.04 | shadowsocks | 250.2 | 659.6 | 21.99 | 0.0 | 10.0 | 13.29 | 16.76 | mheidari-all | 37.19.198.243 |
| 77.84 | vless | 307.7 | 651.2 | 20.66 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 167.17.69.171 |
| 77.42 | vless | 303.1 | 731.3 | 20.76 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.229 |
| 77.04 | vless | 341.9 | 780.5 | 19.86 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.225 |
| 76.99 | vless | 344.4 | 841.3 | 19.81 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.95 |
| 76.78 | shadowsocks | 319.8 | 864.1 | 20.37 | 0.0 | 10.0 | 13.29 | 17.62 | Au1rxx-base64 | 38.180.135.156 |
| 76.64 | vless | 359.3 | 983.5 | 19.46 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 185.95.231.156 |
| 76.45 | vless | 367.4 | 970.0 | 19.27 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.223 |
| 76.16 | vless | 379.9 | 1017.3 | 18.98 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.184 |
| 76.12 | vless | 381.8 | 1016.5 | 18.94 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.224 |
| 76.1 | vless | 361.1 | 822.0 | 19.42 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.15 |
| 76.1 | vless | 382.7 | 956.6 | 18.92 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.163 |
| 76.0 | vless | 324.7 | 631.0 | 20.26 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.202 |
| 75.59 | shadowsocks | 371.5 | 1052.3 | 19.18 | 0.0 | 10.0 | 13.29 | 17.62 | Au1rxx-base64 | 15.204.247.206 |
| 75.57 | vless | 371.3 | 934.6 | 19.18 | 0.0 | 10.0 | 9.56 | 17.62 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.915 | 0.852 | 264 | 1626 | prefer |
| DeltaKronecker-all | 0.762 | 0.686 | 105 | 5931 | prefer |
| Surfboard-tg-mixed | 0.74 | 0.663 | 95 | 7430 | prefer |
| mheidari-all | 0.738 | 0.662 | 77 | 16008 | prefer |
| ermaozi | 0.724 | 0.724 | 29 | 357 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 115 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5093 | observe |
| Epodonios-all | 0.255 | None | 0 | 7888 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9477 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5904 | observe |
| barry-far-vless | 0.255 | None | 0 | 6129 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4179 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 34 |
| 204 | ProxyError | - | 28 |
| 204 | TimeoutError | - | 21 |
| geo | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 13 |
| speed | ClientOSError | - | 12 |
| cn-block | ClientOSError | - | 8 |
| speed | TimeoutError | - | 7 |
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
