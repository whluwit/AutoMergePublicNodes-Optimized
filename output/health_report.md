# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-03 19:16:06 |
| 运行耗时 | 181.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 78197 |
| 去重后节点 | 23106 |
| TCP 可达 | 3000 |
| 真实可用 | 209 |
| Verified 输出 | 209 |
| Global 输出 | 217 |
| All 输出 | 23106 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.3 |
| tcp | 30.3 |
| probe | 43.7 |
| real_test | 71.5 |
| generate | 30.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45713 |
| trojan | 12325 |
| vmess | 10428 |
| shadowsocks | 9090 |
| hysteria2 | 278 |
| shadowsocksr | 150 |
| http | 135 |
| socks | 71 |
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
| 73.39 | shadowsocks | 247.6 | 607.6 | 22.05 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 156.146.38.170 |
| 73.21 | shadowsocks | 255.3 | 621.5 | 21.87 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 156.146.38.167 |
| 73.16 | shadowsocks | 257.3 | 630.8 | 21.82 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 156.146.38.168 |
| 73.1 | shadowsocks | 260.0 | 640.9 | 21.76 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 156.146.38.169 |
| 73.07 | shadowsocks | 261.2 | 654.8 | 21.73 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 37.19.198.236 |
| 72.95 | shadowsocks | 266.5 | 669.3 | 21.61 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 37.19.198.160 |
| 72.83 | shadowsocks | 271.6 | 673.9 | 21.49 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 37.19.198.243 |
| 69.51 | vless | 299.4 | 754.9 | 20.85 | 0.0 | 10.0 | 2.58 | 16.08 | Surfboard-tg-mixed | 47.253.226.114 |
| 68.85 | shadowsocks | 314.1 | 805.9 | 20.51 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 37.19.198.244 |
| 68.35 | shadowsocks | 272.6 | 570.2 | 21.47 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 173.244.56.9 |
| 68.15 | trojan | 386.8 | 551.4 | 18.82 | 0.0 | 10.0 | 12.67 | 16.08 | Surfboard-tg-mixed | 104.19.230.21 |
| 66.87 | shadowsocks | 314.3 | 631.7 | 20.5 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 108.181.0.177 |
| 66.61 | vmess | 432.3 | 1168.4 | 17.77 | 0.0 | 10.0 | 12.5 | 10.84 | DeltaKronecker-all | 67.220.95.3 |
| 66.52 | trojan | 497.8 | 795.7 | 16.26 | 0.0 | 10.0 | 12.67 | 16.08 | Surfboard-tg-mixed | 212.183.88.136 |
| 66.51 | shadowsocks | 302.6 | 538.4 | 20.77 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 108.181.118.10 |
| 66.35 | shadowsocks | 324.2 | 687.9 | 20.27 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | 173.244.56.6 |
| 65.97 | trojan | 519.6 | 839.9 | 15.75 | 0.0 | 10.0 | 12.67 | 16.08 | Surfboard-tg-mixed | 45.130.125.75 |
| 65.6 | trojan | 380.5 | 559.3 | 18.97 | 0.0 | 10.0 | 12.67 | 16.08 | Surfboard-tg-mixed | 69.84.182.44 |
| 65.2 | trojan | 502.2 | 612.7 | 16.15 | 0.0 | 10.0 | 12.67 | 16.08 | Surfboard-tg-mixed | 91.193.58.201 |
| 65.09 | shadowsocks | 266.3 | 654.7 | 21.61 | 0.0 | 10.0 | 11.94 | 13.4 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.837 | 0.864 | 22 | 84 | prefer |
| DeltaKronecker-all | 0.618 | 0.538 | 104 | 6997 | observe |
| Surfboard-tg-mixed | 0.606 | 0.527 | 169 | 6201 | observe |
| nscl5-all | 0.403 | 1.0 | 3 | 1114 | observe |
| mheidari-all | 0.326 | 0.267 | 15 | 16169 | observe |
| tg-ConfigV2rayNG | 0.319 | 1.0 | 2 | 200 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4368 | observe |
| Epodonios-all | 0.255 | None | 0 | 7138 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6834 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4705 | observe |
| barry-far-vless | 0.255 | None | 0 | 5303 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5333 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 45 |
| geo | TimeoutError | - | 19 |
| 204 | ProxyError | - | 16 |
| 204 | ClientOSError | - | 11 |
| geo | ProxyError | - | 10 |
| 204 | TimeoutError | - | 9 |
| cn-block | TimeoutError | - | 9 |
| geo | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 7 |
| speed | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| speed | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 263 | 209 | - |
| global | False | 269 | 217 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
