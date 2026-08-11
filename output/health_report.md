# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-11 12:57:09 |
| 运行耗时 | 259.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 84076 |
| 去重后节点 | 24347 |
| TCP 可达 | 3000 |
| 真实可用 | 535 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24347 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.4 |
| tcp | 36.3 |
| probe | 48.2 |
| real_test | 129.2 |
| generate | 38.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48386 |
| vmess | 13354 |
| trojan | 10683 |
| shadowsocks | 9989 |
| hysteria2 | 1322 |
| http | 158 |
| shadowsocksr | 71 |
| socks | 66 |
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
| 82.48 | vless | 186.8 | 486.2 | 23.45 | 0.0 | 10.0 | 9.65 | 19.38 | Au1rxx-base64 | 179.255.148.66 |
| 82.43 | vless | 189.0 | 484.4 | 23.4 | 0.0 | 10.0 | 9.65 | 19.38 | Au1rxx-base64 | 179.253.240.24 |
| 82.15 | vless | 201.4 | 456.3 | 23.12 | 0.0 | 10.0 | 9.65 | 19.38 | Au1rxx-base64 | 70.39.198.183 |
| 82.09 | vless | 203.9 | 531.8 | 23.06 | 0.0 | 10.0 | 9.65 | 19.38 | Au1rxx-base64 | 167.17.68.205 |
| 80.82 | vless | 258.8 | 644.7 | 21.79 | 0.0 | 10.0 | 9.65 | 19.38 | Au1rxx-base64 | 70.39.197.13 |
| 80.44 | shadowsocks | 257.6 | 606.4 | 21.82 | 0.0 | 10.0 | 13.24 | 19.38 | Au1rxx-base64 | 173.244.56.6 |
| 80.41 | shadowsocks | 258.9 | 635.2 | 21.79 | 0.0 | 10.0 | 13.24 | 19.38 | Au1rxx-base64 | 156.146.38.168 |
| 80.4 | shadowsocks | 259.1 | 615.5 | 21.78 | 0.0 | 10.0 | 13.24 | 19.38 | Au1rxx-base64 | 173.244.56.9 |
| 80.31 | vless | 280.8 | 703.6 | 21.28 | 0.0 | 10.0 | 9.65 | 19.38 | Au1rxx-base64 | 186.241.106.97 |
| 80.2 | shadowsocks | 267.5 | 623.1 | 21.58 | 0.0 | 10.0 | 13.24 | 19.38 | Au1rxx-base64 | 156.146.38.169 |
| 80.04 | shadowsocks | 250.3 | 608.8 | 21.98 | 0.0 | 10.0 | 13.24 | 19.38 | Au1rxx-base64 | 156.146.38.170 |
| 79.69 | http | 408.8 | 1138.8 | 18.32 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.204 |
| 79.59 | http | 412.7 | 1149.9 | 18.22 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.213 |
| 79.51 | http | 416.2 | 1168.3 | 18.14 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.206 |
| 79.47 | http | 418.3 | 1166.4 | 18.1 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.210 |
| 79.44 | http | 419.6 | 1167.7 | 18.07 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.197 |
| 79.43 | http | 419.7 | 1171.3 | 18.06 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.209 |
| 79.42 | http | 420.3 | 1179.5 | 18.05 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.215 |
| 79.41 | http | 420.8 | 1179.1 | 18.04 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.195 |
| 79.4 | http | 420.9 | 1174.5 | 18.03 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.220 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.904 | 0.847 | 393 | 1449 | prefer |
| DeltaKronecker-all | 0.745 | 0.765 | 17 | 5522 | prefer |
| Surfboard-tg-mixed | 0.743 | 0.667 | 81 | 6149 | prefer |
| mheidari-all | 0.474 | 0.6 | 10 | 20194 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5419 | observe |
| Epodonios-all | 0.255 | None | 0 | 6769 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7316 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4944 | observe |
| barry-far-vless | 0.255 | None | 0 | 5245 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5209 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.239 | None | 0 | 1607 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 26 |
| 204 | ProxyError | - | 14 |
| geo | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 11 |
| speed | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 7 |
| geo | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
