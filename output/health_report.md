# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-19 06:42:28 |
| 运行耗时 | 431.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82903 |
| 去重后节点 | 22462 |
| TCP 可达 | 3000 |
| 真实可用 | 1393 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22462 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 0.8 |
| tcp | 34.7 |
| probe | 83.1 |
| real_test | 277.1 |
| generate | 31.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44347 |
| trojan | 18527 |
| shadowsocks | 10105 |
| vmess | 8392 |
| hysteria2 | 1119 |
| http | 178 |
| socks | 117 |
| shadowsocksr | 94 |
| tuic | 10 |
| hysteria | 7 |
| anytls | 7 |

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
| 83.58 | shadowsocks | 203.1 | 498.0 | 23.08 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 82.74 | trojan | 208.3 | 509.6 | 22.96 | 0.0 | 10.0 | 14.78 | 20.0 | Au1rxx-base64 | 147.182.198.83 |
| 82.44 | shadowsocks | 213.0 | 495.8 | 22.85 | 0.0 | 9.09 | 14.5 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 82.4 | shadowsocks | 254.0 | 622.6 | 21.9 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 82.23 | shadowsocks | 261.0 | 645.8 | 21.73 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 81.36 | vless | 184.5 | 466.0 | 23.51 | 0.0 | 10.0 | 7.85 | 20.0 | Au1rxx-base64 | 70.39.197.13 |
| 81.09 | http | 369.2 | 1025.0 | 19.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 81.04 | http | 371.4 | 1034.3 | 19.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 81.02 | http | 372.2 | 1032.5 | 19.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 80.99 | http | 373.6 | 1032.3 | 19.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 80.99 | http | 373.7 | 1027.7 | 19.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 80.98 | http | 374.1 | 1008.0 | 19.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 80.95 | http | 375.5 | 1036.3 | 19.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 80.94 | http | 375.7 | 1024.8 | 19.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 80.93 | http | 376.3 | 1033.0 | 19.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 80.93 | http | 376.3 | 1025.8 | 19.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 80.92 | http | 376.8 | 1035.5 | 19.06 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 80.86 | http | 379.2 | 1048.8 | 19.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 80.82 | http | 380.8 | 1058.3 | 18.96 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 80.48 | trojan | 210.1 | 504.2 | 22.92 | 0.0 | 10.0 | 14.78 | 17.78 | Surfboard-tg-mixed | 173.255.247.228 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.987 | 792 | 1924 | prefer |
| mheidari-all | 1.0 | 0.931 | 259 | 16809 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.859 | 0.781 | 292 | 6315 | prefer |
| DeltaKronecker-all | 0.535 | 0.45 | 20 | 6390 | observe |
| nscl5-all | 0.352 | 0.5 | 6 | 3330 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 175 | observe |
| Epodonios-all | 0.255 | None | 0 | 7030 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3985 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7119 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4850 | observe |
| barry-far-vless | 0.255 | None | 0 | 5174 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3995 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 31 |
| speed | TimeoutError | - | 16 |
| geo | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 8 |
| speed | ClientOSError | - | 8 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
