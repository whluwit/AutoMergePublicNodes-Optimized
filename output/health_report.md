# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-01 13:13:10 |
| 运行耗时 | 296.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79417 |
| 去重后节点 | 23458 |
| TCP 可达 | 3000 |
| 真实可用 | 614 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23458 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.4 |
| tcp | 34.9 |
| probe | 62.7 |
| real_test | 154.7 |
| generate | 36.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47809 |
| vmess | 12506 |
| shadowsocks | 10134 |
| trojan | 7994 |
| hysteria2 | 614 |
| http | 173 |
| shadowsocksr | 73 |
| socks | 66 |
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
| 78.89 | vless | 178.4 | 452.2 | 23.65 | 0.0 | 10.0 | 8.26 | 16.98 | Au1rxx-base64 | 70.39.178.231 |
| 78.76 | vless | 184.0 | 466.2 | 23.52 | 0.0 | 10.0 | 8.26 | 16.98 | Au1rxx-base64 | 70.39.198.183 |
| 78.7 | vless | 186.4 | 480.6 | 23.46 | 0.0 | 10.0 | 8.26 | 16.98 | Au1rxx-base64 | 192.204.50.220 |
| 78.42 | http | 487.0 | 1339.7 | 16.51 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.208 |
| 78.37 | http | 488.8 | 1353.3 | 16.46 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.198 |
| 78.35 | http | 489.8 | 1357.0 | 16.44 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.209 |
| 78.34 | http | 490.1 | 1352.9 | 16.43 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.202 |
| 78.34 | http | 490.3 | 1355.4 | 16.43 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.218 |
| 78.33 | http | 490.5 | 1359.4 | 16.42 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.206 |
| 78.31 | http | 491.5 | 1355.3 | 16.4 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.207 |
| 78.29 | http | 492.5 | 1362.7 | 16.38 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.214 |
| 78.28 | http | 492.6 | 1355.8 | 16.37 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.197 |
| 78.27 | http | 493.4 | 1364.0 | 16.36 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.204 |
| 78.25 | http | 493.9 | 1355.9 | 16.34 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.220 |
| 78.24 | http | 494.7 | 1365.9 | 16.33 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.217 |
| 78.22 | http | 495.6 | 1364.0 | 16.31 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.199 |
| 78.21 | http | 496.0 | 1375.2 | 16.3 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.196 |
| 78.19 | http | 496.7 | 1365.0 | 16.28 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.213 |
| 78.16 | http | 498.0 | 1375.5 | 16.25 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.212 |
| 78.15 | http | 498.2 | 1367.4 | 16.24 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.205 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 158 | 228 | prefer |
| Au1rxx-base64 | 0.833 | 0.766 | 483 | 1689 | prefer |
| Surfboard-tg-mixed | 0.638 | 0.56 | 84 | 5348 | observe |
| DeltaKronecker-all | 0.52 | 0.439 | 82 | 5502 | observe |
| mheidari-all | 0.391 | 1.0 | 2 | 16803 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5391 | observe |
| Epodonios-all | 0.255 | None | 0 | 5964 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7133 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4142 | observe |
| barry-far-vless | 0.255 | None | 0 | 4602 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5039 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1689 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 71 |
| speed | TimeoutError | - | 36 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 17 |
| speed | ClientOSError | - | 14 |
| 204 | ProxyError | - | 11 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
