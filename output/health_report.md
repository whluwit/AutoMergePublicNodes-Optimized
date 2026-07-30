# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-30 19:23:13 |
| 运行耗时 | 285.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78345 |
| 去重后节点 | 22956 |
| TCP 可达 | 3000 |
| 真实可用 | 580 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22956 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 32.9 |
| probe | 59.5 |
| real_test | 150.8 |
| generate | 34.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45540 |
| vmess | 11377 |
| shadowsocks | 10308 |
| trojan | 10204 |
| hysteria2 | 614 |
| http | 116 |
| shadowsocksr | 71 |
| socks | 55 |
| anytls | 26 |
| tuic | 20 |
| hysteria | 14 |

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
| 80.23 | http | 360.2 | 974.6 | 19.44 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.196 |
| 78.47 | http | 349.8 | 952.9 | 19.68 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.209 |
| 78.43 | http | 351.7 | 913.1 | 19.64 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.208 |
| 78.4 | http | 352.8 | 967.6 | 19.61 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.217 |
| 78.39 | http | 353.3 | 967.9 | 19.6 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.200 |
| 78.35 | http | 354.9 | 950.6 | 19.56 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.206 |
| 78.25 | http | 359.5 | 967.6 | 19.46 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.207 |
| 78.24 | http | 359.9 | 974.1 | 19.45 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.205 |
| 78.18 | http | 362.2 | 978.3 | 19.39 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.215 |
| 78.17 | http | 362.7 | 981.7 | 19.38 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.199 |
| 78.11 | http | 365.5 | 983.7 | 19.32 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.210 |
| 78.04 | http | 368.4 | 988.4 | 19.25 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.218 |
| 78.01 | http | 369.6 | 979.9 | 19.22 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.212 |
| 78.0 | http | 369.9 | 989.4 | 19.21 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.202 |
| 77.99 | http | 370.6 | 1012.5 | 19.2 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.198 |
| 77.99 | http | 370.6 | 1014.5 | 19.2 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.214 |
| 77.98 | http | 371.0 | 996.7 | 19.19 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.204 |
| 77.96 | http | 371.7 | 1000.5 | 19.17 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.213 |
| 77.85 | http | 376.4 | 1000.9 | 19.06 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.216 |
| 77.49 | shadowsocks | 219.1 | 528.2 | 22.71 | 0.0 | 10.0 | 12.02 | 16.76 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | 1.0 | 113 | 129 | prefer |
| Au1rxx-base64 | 0.866 | 0.811 | 270 | 1430 | prefer |
| Surfboard-tg-mixed | 0.677 | 0.598 | 117 | 5345 | observe |
| DeltaKronecker-all | 0.674 | 0.595 | 291 | 5759 | observe |
| mheidari-all | 0.373 | 0.6 | 5 | 16222 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5342 | observe |
| Epodonios-all | 0.255 | None | 0 | 6090 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6594 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4215 | observe |
| barry-far-vless | 0.255 | None | 0 | 4589 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5047 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 50 |
| cn-block | TimeoutError | - | 35 |
| 204 | TimeoutError | - | 31 |
| 204 | ProxyError | - | 25 |
| geo | ClientOSError | - | 19 |
| speed | TimeoutError | - | 17 |
| cn-block | ProxyError | - | 14 |
| speed | ClientOSError | - | 11 |
| speed | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42160: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
