# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-10 07:26:08 |
| 运行耗时 | 242.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 87538 |
| 去重后节点 | 24644 |
| TCP 可达 | 3000 |
| 真实可用 | 465 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24644 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 36.0 |
| probe | 56.8 |
| real_test | 108.6 |
| generate | 32.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52542 |
| vmess | 13128 |
| trojan | 10507 |
| shadowsocks | 9729 |
| hysteria2 | 1401 |
| shadowsocksr | 75 |
| socks | 68 |
| http | 40 |
| anytls | 26 |
| hysteria | 14 |
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
| 82.34 | shadowsocks | 191.2 | 469.5 | 23.35 | 0.0 | 10.0 | 14.43 | 19.06 | Au1rxx-base64 | 108.181.0.177 |
| 81.58 | shadowsocks | 245.7 | 634.5 | 22.09 | 0.0 | 10.0 | 14.43 | 19.06 | Au1rxx-base64 | 173.244.56.6 |
| 81.49 | shadowsocks | 249.5 | 653.0 | 22.0 | 0.0 | 10.0 | 14.43 | 19.06 | Au1rxx-base64 | 173.244.56.9 |
| 81.46 | shadowsocks | 250.9 | 618.3 | 21.97 | 0.0 | 10.0 | 14.43 | 19.06 | Au1rxx-base64 | 156.146.38.170 |
| 81.3 | shadowsocks | 257.8 | 632.6 | 21.81 | 0.0 | 10.0 | 14.43 | 19.06 | Au1rxx-base64 | 156.146.38.169 |
| 81.26 | shadowsocks | 259.5 | 635.2 | 21.77 | 0.0 | 10.0 | 14.43 | 19.06 | Au1rxx-base64 | 156.146.38.167 |
| 81.18 | shadowsocks | 241.6 | 606.9 | 22.19 | 0.0 | 10.0 | 14.43 | 19.06 | Au1rxx-base64 | 108.181.118.10 |
| 81.02 | shadowsocks | 262.3 | 648.8 | 21.71 | 0.0 | 10.0 | 14.43 | 19.06 | Au1rxx-base64 | 156.146.38.168 |
| 79.09 | vless | 192.6 | 481.4 | 23.32 | 0.0 | 10.0 | 6.71 | 19.06 | Au1rxx-base64 | 179.253.240.24 |
| 78.98 | vless | 197.4 | 506.1 | 23.21 | 0.0 | 10.0 | 6.71 | 19.06 | Au1rxx-base64 | 167.17.68.205 |
| 78.94 | vless | 199.2 | 452.9 | 23.17 | 0.0 | 10.0 | 6.71 | 19.06 | Au1rxx-base64 | 70.39.197.13 |
| 78.81 | http | 406.5 | 1145.1 | 18.37 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 78.73 | http | 410.0 | 1152.6 | 18.29 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 78.59 | trojan | 268.0 | 553.2 | 21.57 | 0.0 | 10.0 | 13.63 | 19.06 | Au1rxx-base64 | 44.246.163.102 |
| 78.55 | http | 417.8 | 1175.0 | 18.11 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 78.48 | vless | 219.1 | 571.1 | 22.71 | 0.0 | 10.0 | 6.71 | 19.06 | Au1rxx-base64 | 186.241.106.97 |
| 78.36 | vless | 191.6 | 491.7 | 23.34 | 0.0 | 9.25 | 6.71 | 19.06 | Au1rxx-base64 | 179.255.148.66 |
| 78.28 | trojan | 281.6 | 593.6 | 21.26 | 0.0 | 10.0 | 13.63 | 19.06 | Au1rxx-base64 | 44.244.3.114 |
| 78.12 | http | 436.3 | 1228.6 | 17.68 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 78.0 | hysteria2 | 335.2 | 749.5 | 20.02 | 0.0 | 10.0 | 13.04 | 19.06 | Au1rxx-base64 | 138.124.68.188 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Au1rxx-base64 | 0.879 | 0.811 | 450 | 1742 | prefer |
| Surfboard-tg-mixed | 0.666 | 0.588 | 85 | 6713 | observe |
| DeltaKronecker-all | 0.448 | 0.361 | 36 | 5881 | observe |
| mheidari-all | 0.421 | 0.333 | 39 | 20373 | observe |
| Au1rxx-clash | 0.389 | 0.75 | 4 | 1723 | observe |
| nscl5-all | 0.313 | 1.0 | 1 | 1442 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7338 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7807 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5446 | observe |
| barry-far-vless | 0.255 | None | 0 | 5853 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5191 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 46 |
| geo | TimeoutError | - | 34 |
| 204 | TimeoutError | - | 19 |
| speed | ClientOSError | - | 18 |
| 204 | ProxyError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| geo | ClientOSError | - | 13 |
| 204 | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
