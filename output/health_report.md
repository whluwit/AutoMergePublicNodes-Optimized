# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-03 02:28:38 |
| 运行耗时 | 324.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 81019 |
| 去重后节点 | 22575 |
| TCP 可达 | 3000 |
| 真实可用 | 822 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22575 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 35.3 |
| probe | 62.3 |
| real_test | 189.0 |
| generate | 29.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49636 |
| vmess | 12503 |
| shadowsocks | 10266 |
| trojan | 7545 |
| hysteria2 | 731 |
| http | 176 |
| socks | 69 |
| shadowsocksr | 69 |
| hysteria | 12 |
| anytls | 7 |
| tuic | 5 |

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
| 81.56 | http | 350.6 | 967.8 | 19.66 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.207 |
| 81.47 | http | 354.5 | 943.7 | 19.57 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.198 |
| 81.47 | http | 354.7 | 983.3 | 19.57 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.197 |
| 81.43 | http | 356.3 | 962.0 | 19.53 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.217 |
| 81.33 | http | 360.6 | 970.0 | 19.43 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.208 |
| 81.32 | http | 360.9 | 977.5 | 19.42 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.218 |
| 81.31 | http | 361.4 | 975.0 | 19.41 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.215 |
| 81.29 | http | 362.5 | 986.7 | 19.39 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.204 |
| 81.28 | http | 362.7 | 982.6 | 19.38 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.202 |
| 81.28 | http | 362.8 | 977.7 | 19.38 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.206 |
| 81.28 | http | 362.9 | 979.0 | 19.38 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.216 |
| 81.27 | http | 363.4 | 988.1 | 19.37 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.213 |
| 81.25 | http | 364.1 | 987.6 | 19.35 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.195 |
| 81.25 | http | 364.3 | 981.1 | 19.35 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.211 |
| 81.23 | http | 365.1 | 979.7 | 19.33 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.212 |
| 81.22 | http | 365.6 | 932.8 | 19.32 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.214 |
| 81.19 | http | 366.8 | 995.6 | 19.29 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.200 |
| 81.14 | http | 351.1 | 965.8 | 19.65 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.205 |
| 80.88 | http | 379.9 | 987.6 | 18.98 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.209 |
| 80.87 | http | 380.4 | 1001.1 | 18.97 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 144 | 344 | prefer |
| Au1rxx-base64 | 0.952 | 0.888 | 599 | 1634 | prefer |
| Surfboard-tg-mixed | 0.587 | 0.526 | 19 | 5222 | observe |
| DeltaKronecker-all | 0.461 | 0.545 | 11 | 3437 | observe |
| mheidari-all | 0.399 | 0.318 | 399 | 18808 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 3833 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 56 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5486 | observe |
| Epodonios-all | 0.255 | None | 0 | 5849 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6721 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4172 | observe |
| barry-far-vless | 0.255 | None | 0 | 4560 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5208 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 135 |
| speed | ClientOSError | - | 78 |
| speed | TimeoutError | - | 71 |
| geo | ClientOSError | - | 46 |
| 204 | TimeoutError | - | 10 |
| cn-block | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
