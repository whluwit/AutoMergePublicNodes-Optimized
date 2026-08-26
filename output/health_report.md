# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-26 01:05:35 |
| 运行耗时 | 303.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 79265 |
| 去重后节点 | 22523 |
| TCP 可达 | 3000 |
| 真实可用 | 723 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22523 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.6 |
| tcp | 36.6 |
| probe | 61.8 |
| real_test | 175.3 |
| generate | 22.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49742 |
| shadowsocks | 10775 |
| vmess | 10473 |
| trojan | 6516 |
| hysteria2 | 1384 |
| http | 167 |
| shadowsocksr | 131 |
| socks | 67 |
| hysteria | 7 |
| tuic | 3 |

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
| 81.21 | hysteria2 | 296.8 | 692.0 | 20.91 | 0.0 | 10.0 | 13.8 | 18.06 | Au1rxx-base64 | 159.223.157.129 |
| 80.72 | shadowsocks | 226.1 | 593.6 | 22.54 | 0.0 | 10.0 | 14.12 | 18.06 | Au1rxx-base64 | 156.146.38.170 |
| 79.94 | shadowsocks | 215.2 | 569.1 | 22.8 | 0.0 | 10.0 | 14.12 | 17.02 | mheidari-all | 156.146.38.168 |
| 79.67 | shadowsocks | 226.8 | 604.4 | 22.53 | 0.0 | 10.0 | 14.12 | 17.02 | mheidari-all | 156.146.38.169 |
| 78.68 | shadowsocks | 243.7 | 597.0 | 22.14 | 0.0 | 10.0 | 14.12 | 16.92 | DeltaKronecker-all | 23.150.248.20 |
| 78.29 | vless | 374.6 | 669.3 | 19.11 | 0.0 | 10.0 | 11.12 | 18.06 | Au1rxx-base64 | 38.180.242.205 |
| 77.85 | trojan | 315.3 | 846.6 | 20.48 | 0.0 | 10.0 | 12.31 | 18.06 | Au1rxx-base64 | 64.94.95.117 |
| 77.84 | trojan | 315.9 | 821.6 | 20.47 | 0.0 | 10.0 | 12.31 | 18.06 | Au1rxx-base64 | 64.94.95.115 |
| 77.62 | shadowsocks | 230.5 | 615.2 | 22.44 | 0.0 | 10.0 | 14.12 | 18.06 | Au1rxx-base64 | 156.146.38.167 |
| 77.58 | shadowsocks | 252.2 | 540.3 | 21.94 | 0.0 | 10.0 | 14.12 | 17.02 | mheidari-all | 173.244.56.6 |
| 77.54 | trojan | 328.5 | 846.2 | 20.17 | 0.0 | 10.0 | 12.31 | 18.06 | Au1rxx-base64 | 64.94.95.114 |
| 76.63 | trojan | 322.9 | 816.2 | 20.3 | 0.0 | 10.0 | 12.31 | 17.02 | mheidari-all | 64.94.95.118 |
| 76.56 | vless | 307.4 | 657.6 | 20.66 | 0.0 | 10.0 | 11.12 | 18.06 | Au1rxx-base64 | 195.211.99.49 |
| 76.32 | trojan | 261.4 | 536.6 | 21.73 | 0.0 | 10.0 | 12.31 | 18.06 | Au1rxx-base64 | 14.1.28.76 |
| 75.94 | trojan | 276.7 | 604.8 | 21.37 | 0.0 | 10.0 | 12.31 | 18.06 | Au1rxx-base64 | us01.duotg.top |
| 75.92 | shadowsocks | 317.9 | 741.6 | 20.42 | 0.0 | 10.0 | 14.12 | 18.06 | Au1rxx-base64 | 37.19.198.160 |
| 75.9 | http | 475.9 | 1224.4 | 16.76 | 0.0 | 10.0 | 14.38 | 19.28 | zhangkai | 138.199.35.198 |
| 75.52 | shadowsocks | 315.9 | 721.3 | 20.47 | 0.0 | 10.0 | 14.12 | 18.06 | Au1rxx-base64 | 37.19.198.244 |
| 75.24 | vless | 347.5 | 768.9 | 19.73 | 0.0 | 10.0 | 11.12 | 18.06 | Au1rxx-base64 | 47.89.186.170 |
| 75.02 | http | 485.1 | 1241.7 | 16.55 | 0.0 | 10.0 | 14.38 | 19.28 | zhangkai | 138.199.35.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.999 | 0.923 | 478 | 1943 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.963 | 0.891 | 92 | 6512 | prefer |
| mheidari-all | 0.551 | 0.471 | 138 | 14587 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 191 | observe |
| DeltaKronecker-all | 0.301 | 0.22 | 491 | 6340 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7017 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7056 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5328 | observe |
| barry-far-vless | 0.255 | None | 0 | 5602 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4119 | observe |
| Au1rxx-clash | 0.253 | None | 0 | 1945 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 282 |
| speed | ClientOSError | - | 72 |
| geo | ClientOSError | - | 62 |
| speed | TimeoutError | - | 62 |
| cn-block | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 7 |
| cn-block | TimeoutError | - | 7 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
