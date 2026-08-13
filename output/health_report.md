# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-13 01:32:45 |
| 运行耗时 | 291.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79693 |
| 去重后节点 | 22323 |
| TCP 可达 | 3000 |
| 真实可用 | 671 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22323 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.3 |
| tcp | 32.9 |
| probe | 56.3 |
| real_test | 162.5 |
| generate | 32.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45220 |
| vmess | 13412 |
| trojan | 9842 |
| shadowsocks | 9671 |
| hysteria2 | 1221 |
| http | 160 |
| shadowsocksr | 75 |
| socks | 71 |
| tuic | 11 |
| hysteria | 7 |
| anytls | 3 |

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
| 85.2 | http | 191.5 | 485.3 | 23.34 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 85.09 | http | 196.4 | 504.0 | 23.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 85.06 | http | 197.7 | 519.3 | 23.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 85.05 | http | 198.4 | 510.3 | 23.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 85.03 | http | 198.9 | 506.7 | 23.17 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 85.03 | http | 199.1 | 516.0 | 23.17 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 85.02 | http | 199.4 | 517.7 | 23.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 85.01 | http | 200.0 | 521.7 | 23.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 84.94 | http | 203.0 | 519.3 | 23.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 84.93 | http | 203.4 | 531.7 | 23.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 84.9 | http | 204.7 | 529.2 | 23.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 84.85 | http | 206.7 | 536.1 | 22.99 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 84.83 | http | 207.5 | 534.1 | 22.97 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 84.06 | http | 196.7 | 505.4 | 23.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 83.14 | vless | 198.3 | 516.2 | 23.19 | 0.0 | 10.0 | 11.43 | 18.68 | Au1rxx-base64 | 167.17.68.205 |
| 82.68 | vless | 225.1 | 588.4 | 22.57 | 0.0 | 10.0 | 11.43 | 18.68 | Au1rxx-base64 | 70.39.197.13 |
| 81.73 | vless | 264.8 | 704.7 | 21.65 | 0.0 | 10.0 | 11.43 | 18.68 | Au1rxx-base64 | 70.39.178.231 |
| 81.07 | shadowsocks | 182.4 | 470.5 | 23.55 | 0.0 | 10.0 | 13.34 | 18.68 | Au1rxx-base64 | 108.181.0.177 |
| 80.19 | vless | 318.7 | 796.5 | 20.4 | 0.0 | 10.0 | 11.43 | 18.68 | Au1rxx-base64 | 172.247.109.66 |
| 79.9 | shadowsocks | 254.9 | 617.1 | 21.88 | 0.0 | 10.0 | 13.34 | 18.68 | Au1rxx-base64 | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 0.992 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.954 | 0.896 | 404 | 1489 | prefer |
| Surfboard-tg-mixed | 0.686 | 0.608 | 158 | 5952 | observe |
| mheidari-all | 0.465 | 0.384 | 177 | 16809 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5328 | observe |
| Epodonios-all | 0.255 | None | 0 | 6571 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7449 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4781 | observe |
| barry-far-vless | 0.255 | None | 0 | 5114 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5209 | observe |
| DeltaKronecker-all | 0.253 | 0.167 | 108 | 4975 | observe |
| nscl5-all | 0.241 | None | 0 | 1654 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1489 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 123 |
| speed | TimeoutError | - | 65 |
| cn-block | TimeoutError | - | 35 |
| geo | ClientOSError | - | 34 |
| speed | ClientOSError | - | 26 |
| 204 | TimeoutError | - | 10 |
| 204 | ProxyError | - | 9 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
