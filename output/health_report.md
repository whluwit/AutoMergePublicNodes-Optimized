# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 03:06:46 |
| 运行耗时 | 912.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99770 |
| 去重后节点 | 27948 |
| TCP 可达 | 3000 |
| 真实可用 | 555 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27948 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| geo | 1.5 |
| tcp | 47.6 |
| probe | 289.3 |
| real_test | 479.3 |
| generate | 86.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58970 |
| vmess | 16462 |
| shadowsocks | 11813 |
| trojan | 10316 |
| hysteria2 | 1231 |
| http | 713 |
| shadowsocksr | 158 |
| socks | 59 |
| anytls | 25 |
| hysteria | 17 |
| tuic | 6 |

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
| 80.33 | hysteria2 | 237.0 | 676.1 | 22.29 | 0.0 | 10.0 | 11.54 | 18.0 | Au1rxx-base64 | 129.213.91.185 |
| 78.85 | shadowsocks | 251.0 | 687.8 | 21.97 | 0.0 | 10.0 | 13.88 | 18.0 | Au1rxx-base64 | 198.98.53.130 |
| 78.76 | vless | 259.1 | 617.4 | 21.78 | 0.0 | 8.66 | 10.32 | 18.0 | Au1rxx-base64 | 195.211.98.43 |
| 78.71 | vless | 259.5 | 681.7 | 21.77 | 0.0 | 8.62 | 10.32 | 18.0 | Au1rxx-base64 | 167.17.69.171 |
| 78.19 | shadowsocks | 254.8 | 706.7 | 21.88 | 0.0 | 8.43 | 13.88 | 18.0 | Au1rxx-base64 | 37.19.198.244 |
| 78.18 | shadowsocks | 255.2 | 706.5 | 21.87 | 0.0 | 8.43 | 13.88 | 18.0 | Au1rxx-base64 | 37.19.198.236 |
| 78.18 | shadowsocks | 257.7 | 703.5 | 21.81 | 0.0 | 8.49 | 13.88 | 18.0 | Au1rxx-base64 | 37.19.198.243 |
| 78.18 | vless | 288.4 | 784.8 | 21.1 | 0.0 | 8.76 | 10.32 | 18.0 | Au1rxx-base64 | 195.123.235.183 |
| 78.14 | vless | 290.8 | 768.9 | 21.05 | 0.0 | 8.77 | 10.32 | 18.0 | Au1rxx-base64 | 169.40.42.163 |
| 78.03 | shadowsocks | 261.9 | 729.9 | 21.72 | 0.0 | 8.43 | 13.88 | 18.0 | Au1rxx-base64 | 37.19.198.160 |
| 78.02 | vless | 283.0 | 697.1 | 21.23 | 0.0 | 8.47 | 10.32 | 18.0 | Au1rxx-base64 | 169.40.42.184 |
| 77.87 | vless | 291.9 | 773.4 | 21.02 | 0.0 | 8.53 | 10.32 | 18.0 | Au1rxx-base64 | 169.40.42.74 |
| 77.65 | vless | 303.3 | 763.1 | 20.76 | 0.0 | 8.57 | 10.32 | 18.0 | Au1rxx-base64 | 169.40.42.212 |
| 77.63 | shadowsocks | 325.2 | 940.0 | 20.25 | 0.0 | 10.0 | 13.88 | 18.0 | Au1rxx-base64 | 15.204.233.41 |
| 77.42 | vless | 229.2 | 596.0 | 22.47 | 0.0 | 8.63 | 10.32 | 18.0 | Au1rxx-base64 | 195.123.235.177 |
| 77.33 | vless | 312.6 | 726.1 | 20.54 | 0.0 | 8.47 | 10.32 | 18.0 | Au1rxx-base64 | 169.40.42.133 |
| 77.28 | vless | 317.5 | 881.9 | 20.43 | 0.0 | 8.53 | 10.32 | 18.0 | Au1rxx-base64 | 159.89.87.21 |
| 76.97 | vless | 336.8 | 938.6 | 19.98 | 0.0 | 8.67 | 10.32 | 18.0 | Au1rxx-base64 | 185.95.231.156 |
| 76.93 | vless | 334.2 | 855.5 | 20.04 | 0.0 | 8.57 | 10.32 | 18.0 | Au1rxx-base64 | 169.40.42.104 |
| 76.78 | vless | 343.3 | 804.2 | 19.83 | 0.0 | 8.63 | 10.32 | 18.0 | Au1rxx-base64 | 169.40.42.35 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.803 | 0.724 | 652 | 1992 | prefer |
| ermaozi | 0.653 | 0.632 | 38 | 693 | observe |
| Surfboard-tg-mixed | 0.446 | 0.8 | 5 | 7135 | observe |
| DeltaKronecker-all | 0.398 | 0.3 | 20 | 5147 | observe |
| mheidari-all | 0.354 | 0.271 | 177 | 23985 | observe |
| ermaozi-get_subscribe | 0.278 | 1.0 | 1 | 574 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1992 | observe |
| Epodonios-all | 0.255 | None | 0 | 7647 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9899 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5628 | observe |
| barry-far-vless | 0.255 | None | 0 | 5878 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4235 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 94 |
| speed | TimeoutError | - | 74 |
| speed | ClientOSError | - | 67 |
| geo | ClientOSError | - | 40 |
| 204 | ProxyError | - | 16 |
| 204 | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| geo | ProxyError | - | 4 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
