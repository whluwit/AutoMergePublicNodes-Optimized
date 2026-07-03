# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-03 13:56:36 |
| 运行耗时 | 200.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 77176 |
| 去重后节点 | 22933 |
| TCP 可达 | 3000 |
| 真实可用 | 263 |
| Verified 输出 | 263 |
| Global 输出 | 269 |
| All 输出 | 22933 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.5 |
| tcp | 31.1 |
| probe | 46.2 |
| real_test | 85.0 |
| generate | 32.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44773 |
| trojan | 12221 |
| vmess | 10399 |
| shadowsocks | 9177 |
| hysteria2 | 237 |
| shadowsocksr | 153 |
| http | 135 |
| socks | 74 |
| hysteria | 6 |
| tuic | 1 |

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
| 77.84 | shadowsocks | 236.1 | 599.9 | 22.31 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 156.146.38.170 |
| 77.81 | shadowsocks | 237.5 | 607.9 | 22.28 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 156.146.38.167 |
| 77.75 | shadowsocks | 240.1 | 613.6 | 22.22 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 156.146.38.168 |
| 77.29 | shadowsocks | 259.9 | 662.8 | 21.76 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 156.146.38.169 |
| 76.05 | trojan | 249.9 | 609.5 | 21.99 | 0.0 | 10.0 | 11.72 | 15.34 | DeltaKronecker-all | 64.94.95.114 |
| 76.01 | trojan | 251.6 | 615.0 | 21.95 | 0.0 | 10.0 | 11.72 | 15.34 | DeltaKronecker-all | 64.94.95.117 |
| 73.65 | trojan | 353.6 | 922.6 | 19.59 | 0.0 | 10.0 | 11.72 | 15.34 | DeltaKronecker-all | 64.94.95.115 |
| 73.57 | shadowsocks | 282.1 | 533.8 | 21.25 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 173.244.56.9 |
| 72.9 | shadowsocks | 269.6 | 531.5 | 21.54 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 108.181.118.10 |
| 72.83 | shadowsocks | 281.4 | 577.8 | 21.26 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 108.181.0.177 |
| 72.47 | shadowsocks | 322.3 | 693.0 | 20.32 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 37.19.198.236 |
| 72.4 | shadowsocks | 314.8 | 700.2 | 20.49 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 37.19.198.243 |
| 72.29 | shadowsocks | 320.3 | 724.5 | 20.36 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 37.19.198.160 |
| 71.58 | shadowsocks | 327.7 | 701.4 | 20.19 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 173.244.56.6 |
| 71.33 | vless | 243.9 | 527.7 | 22.13 | 0.0 | 10.0 | 7.15 | 15.34 | DeltaKronecker-all | 112.121.184.10 |
| 71.31 | vless | 357.5 | 869.1 | 19.5 | 0.0 | 10.0 | 7.15 | 16.5 | Au1rxx-base64 | 15.204.97.214 |
| 70.81 | vless | 214.3 | 488.3 | 22.82 | 0.0 | 10.0 | 7.15 | 15.34 | DeltaKronecker-all | 92.223.71.246 |
| 70.66 | shadowsocks | 383.6 | 860.6 | 18.9 | 0.0 | 10.0 | 13.03 | 16.5 | Au1rxx-base64 | 172.245.235.84 |
| 69.56 | shadowsocks | 265.2 | 544.9 | 21.64 | 0.0 | 10.0 | 13.03 | 15.34 | DeltaKronecker-all | 107.172.219.230 |
| 69.25 | shadowsocks | 324.6 | 362.4 | 20.26 | 1.41 | 9.79 | 13.03 | 16.5 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.804 | 0.729 | 96 | 5871 | prefer |
| Au1rxx-base64 | 0.67 | 0.676 | 37 | 79 | observe |
| DeltaKronecker-all | 0.542 | 0.462 | 277 | 6997 | observe |
| nscl5-all | 0.356 | 1.0 | 2 | 1114 | observe |
| tg-ConfigV2rayNG | 0.263 | 1.0 | 1 | 200 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4368 | observe |
| Epodonios-all | 0.255 | None | 0 | 6926 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7163 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4477 | observe |
| barry-far-vless | 0.255 | None | 0 | 5041 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5372 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 95 |
| geo | TimeoutError | - | 48 |
| 204 | ClientOSError | - | 11 |
| 204 | TimeoutError | - | 10 |
| geo | ClientOSError | - | 10 |
| cn-block | TimeoutError | - | 6 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| speed | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 263 | - |
| global | False | 300 | 269 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
