# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 03:00:30 |
| 运行耗时 | 909.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85506 |
| 去重后节点 | 22889 |
| TCP 可达 | 3000 |
| 真实可用 | 531 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22889 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 38.9 |
| probe | 328.6 |
| real_test | 453.5 |
| generate | 80.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52913 |
| vmess | 11765 |
| shadowsocks | 10037 |
| trojan | 8361 |
| hysteria2 | 1575 |
| http | 637 |
| shadowsocksr | 128 |
| socks | 71 |
| hysteria | 9 |
| tuic | 8 |
| anytls | 2 |

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
| 83.58 | vless | 258.4 | 683.8 | 21.8 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.173 |
| 83.5 | vless | 261.9 | 633.0 | 21.72 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.16 |
| 83.07 | vless | 280.3 | 679.0 | 21.29 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 216.152.147.28 |
| 83.02 | vless | 282.6 | 757.0 | 21.24 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.225 |
| 82.74 | vless | 294.7 | 786.5 | 20.96 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.184 |
| 82.6 | vless | 300.6 | 825.2 | 20.82 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 137.184.218.169 |
| 82.37 | vless | 310.5 | 832.2 | 20.59 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 167.17.69.171 |
| 82.33 | vless | 312.2 | 835.9 | 20.55 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.232 |
| 82.24 | vless | 316.3 | 815.4 | 20.46 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 66.70.179.198 |
| 82.22 | vless | 317.2 | 856.6 | 20.44 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.223 |
| 81.84 | vless | 333.4 | 858.9 | 20.06 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.95 |
| 81.63 | vless | 342.6 | 953.9 | 19.85 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 185.95.231.156 |
| 81.44 | vless | 350.6 | 949.8 | 19.66 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.52 |
| 81.39 | vless | 241.2 | 684.3 | 22.19 | 0.0 | 10.0 | 12.2 | 20.0 | DeltaKronecker-all | 79.141.172.154 |
| 81.18 | vless | 361.7 | 940.0 | 19.4 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.235 |
| 81.13 | vless | 363.9 | 986.0 | 19.35 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.202 |
| 81.07 | vless | 290.2 | 670.6 | 21.06 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.179 |
| 80.72 | vless | 315.8 | 706.2 | 20.47 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.224 |
| 80.61 | vless | 310.1 | 721.8 | 20.6 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.231 |
| 80.26 | vless | 348.2 | 822.5 | 19.72 | 0.0 | 10.0 | 12.2 | 19.58 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.97 | 0.905 | 264 | 1690 | prefer |
| Surfboard-tg-mixed | 0.838 | 0.762 | 122 | 7518 | prefer |
| mheidari-all | 0.774 | 0.697 | 119 | 16648 | prefer |
| ermaozi-get_subscribe | 0.618 | 0.632 | 19 | 473 | observe |
| ermaozi | 0.49 | 0.471 | 34 | 442 | observe |
| DeltaKronecker-all | 0.431 | 0.35 | 243 | 6097 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 176 | observe |
| Epodonios-all | 0.255 | None | 0 | 7969 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8719 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6168 | observe |
| barry-far-vless | 0.255 | None | 0 | 6393 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 114 |
| geo | ClientOSError | - | 34 |
| speed | TimeoutError | - | 29 |
| 204 | ProxyError | - | 27 |
| speed | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
