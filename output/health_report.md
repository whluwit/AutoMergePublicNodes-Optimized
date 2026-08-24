# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-24 01:03:54 |
| 运行耗时 | 284.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 78342 |
| 去重后节点 | 21491 |
| TCP 可达 | 3000 |
| 真实可用 | 740 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21491 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.5 |
| tcp | 34.1 |
| probe | 58.9 |
| real_test | 153.0 |
| generate | 31.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48610 |
| shadowsocks | 10382 |
| vmess | 9921 |
| trojan | 7845 |
| hysteria2 | 1183 |
| http | 165 |
| shadowsocksr | 128 |
| socks | 99 |
| hysteria | 7 |
| tuic | 2 |

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
| 84.84 | http | 205.1 | 496.6 | 23.03 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |
| 84.81 | http | 206.2 | 498.7 | 23.0 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 83.12 | vless | 239.9 | 566.4 | 22.22 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 38.244.20.113 |
| 83.03 | trojan | 199.5 | 506.9 | 23.16 | 0.0 | 10.0 | 12.93 | 19.94 | Au1rxx-base64 | 14.1.28.76 |
| 82.32 | vless | 231.6 | 601.3 | 22.42 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 38.244.21.64 |
| 81.43 | vless | 226.7 | 595.2 | 22.53 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 38.244.21.147 |
| 81.23 | vless | 192.2 | 482.4 | 23.33 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 192.220.55.133 |
| 81.09 | vless | 198.2 | 495.9 | 23.19 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 192.220.54.83 |
| 81.09 | shadowsocks | 250.3 | 609.7 | 21.98 | 0.0 | 10.0 | 13.61 | 19.94 | Au1rxx-base64 | 156.146.38.168 |
| 81.07 | vless | 272.0 | 606.3 | 21.48 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 15.204.97.209 |
| 80.66 | shadowsocks | 266.3 | 728.3 | 21.61 | 0.0 | 10.0 | 13.61 | 19.94 | mheidari-all | 108.181.0.177 |
| 80.52 | shadowsocks | 272.4 | 735.3 | 21.47 | 0.0 | 10.0 | 13.61 | 19.94 | Au1rxx-base64 | 108.181.118.10 |
| 79.79 | trojan | 209.9 | 542.3 | 22.92 | 0.0 | 10.0 | 12.93 | 19.94 | Au1rxx-base64 | us01.duotg.top |
| 79.51 | shadowsocks | 294.6 | 748.7 | 20.96 | 0.0 | 10.0 | 13.61 | 19.94 | Au1rxx-base64 | 173.244.56.9 |
| 79.37 | vless | 185.9 | 490.2 | 23.47 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 154.17.224.207 |
| 79.34 | shadowsocks | 249.5 | 550.4 | 22.0 | 0.0 | 10.0 | 13.61 | 19.94 | Au1rxx-base64 | 94.72.127.55 |
| 79.3 | vless | 229.0 | 537.1 | 22.48 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 23.172.40.60 |
| 79.11 | vless | 362.1 | 883.8 | 19.4 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 15.204.97.197 |
| 79.02 | vless | 361.4 | 881.9 | 19.41 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 15.204.97.216 |
| 78.88 | vless | 267.2 | 598.3 | 21.59 | 0.0 | 10.0 | 10.96 | 19.94 | Au1rxx-base64 | 15.204.97.214 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.935 | 429 | 1689 | prefer |
| zhangkai | 0.997 | 1.0 | 113 | 144 | prefer |
| Surfboard-tg-mixed | 0.864 | 0.787 | 183 | 6428 | prefer |
| DeltaKronecker-all | 0.498 | 0.416 | 77 | 5415 | observe |
| mheidari-all | 0.435 | 0.353 | 136 | 14677 | observe |
| nscl5-all | 0.26 | 0.4 | 5 | 1008 | observe |
| Epodonios-all | 0.255 | None | 0 | 6993 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7082 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5343 | observe |
| barry-far-vless | 0.255 | None | 0 | 5618 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4085 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1690 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 75 |
| speed | TimeoutError | - | 38 |
| geo | ClientOSError | - | 27 |
| speed | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyError | - | 9 |
| 204 | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
