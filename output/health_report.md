# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-23 12:34:32 |
| 运行耗时 | 301.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 77785 |
| 去重后节点 | 21407 |
| TCP 可达 | 3000 |
| 真实可用 | 699 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21407 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 34.3 |
| probe | 61.9 |
| real_test | 156.1 |
| generate | 40.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47781 |
| vmess | 10331 |
| shadowsocks | 10282 |
| trojan | 7829 |
| hysteria2 | 1163 |
| http | 164 |
| shadowsocksr | 128 |
| socks | 98 |
| hysteria | 7 |
| tuic | 2 |

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
| 85.07 | http | 195.2 | 507.9 | 23.26 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |
| 85.04 | http | 196.5 | 505.0 | 23.23 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 83.75 | trojan | 217.5 | 486.3 | 22.74 | 0.0 | 10.0 | 13.59 | 19.92 | Au1rxx-base64 | 35.91.251.124 |
| 83.6 | trojan | 223.9 | 508.9 | 22.59 | 0.0 | 10.0 | 13.59 | 19.92 | Au1rxx-base64 | obliging-louse.rooster465.autos |
| 83.44 | trojan | 230.9 | 526.1 | 22.43 | 0.0 | 10.0 | 13.59 | 19.92 | Au1rxx-base64 | 35.92.245.6 |
| 83.27 | trojan | 238.2 | 546.6 | 22.26 | 0.0 | 10.0 | 13.59 | 19.92 | Au1rxx-base64 | neutral-quail.rooster465.autos |
| 82.71 | vless | 223.8 | 560.5 | 22.6 | 0.0 | 10.0 | 10.19 | 19.92 | Au1rxx-base64 | 15.204.97.216 |
| 82.68 | vless | 224.8 | 564.7 | 22.57 | 0.0 | 10.0 | 10.19 | 19.92 | Au1rxx-base64 | 15.204.97.197 |
| 82.62 | vless | 227.5 | 568.2 | 22.51 | 0.0 | 10.0 | 10.19 | 19.92 | Au1rxx-base64 | 15.204.97.209 |
| 82.54 | shadowsocks | 225.8 | 556.4 | 22.55 | 0.0 | 10.0 | 14.32 | 19.92 | Au1rxx-base64 | 154.12.240.141 |
| 82.3 | vless | 241.2 | 587.1 | 22.19 | 0.0 | 10.0 | 10.19 | 19.92 | Au1rxx-base64 | 38.244.20.113 |
| 82.11 | shadowsocks | 244.3 | 589.0 | 22.12 | 0.0 | 10.0 | 14.32 | 19.92 | Au1rxx-base64 | 94.72.127.58 |
| 81.74 | trojan | 304.5 | 752.5 | 20.73 | 0.0 | 10.0 | 13.59 | 19.92 | Au1rxx-base64 | 44.251.158.80 |
| 81.04 | trojan | 241.4 | 476.6 | 22.19 | 0.0 | 7.84 | 13.59 | 19.92 | Au1rxx-base64 | sincere-gelding.rooster465.autos |
| 80.36 | shadowsocks | 222.9 | 539.1 | 22.62 | 0.0 | 10.0 | 14.32 | 19.92 | Au1rxx-base64 | 129.146.221.27 |
| 80.03 | shadowsocks | 334.5 | 890.6 | 20.04 | 0.0 | 10.0 | 14.32 | 19.92 | Au1rxx-base64 | 94.72.127.55 |
| 79.98 | shadowsocks | 234.9 | 590.1 | 22.34 | 0.0 | 10.0 | 14.32 | 17.82 | Surfboard-tg-mixed | 108.181.0.177 |
| 79.5 | shadowsocks | 238.3 | 531.6 | 22.26 | 0.0 | 10.0 | 14.32 | 19.92 | Au1rxx-base64 | 173.244.56.9 |
| 79.49 | shadowsocks | 217.3 | 506.8 | 22.75 | 0.0 | 10.0 | 14.32 | 19.92 | Au1rxx-base64 | 129.146.217.99 |
| 79.45 | shadowsocks | 218.8 | 520.1 | 22.71 | 0.0 | 10.0 | 14.32 | 19.92 | Au1rxx-base64 | 132.226.28.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| Au1rxx-base64 | 0.985 | 0.917 | 432 | 1745 | prefer |
| Surfboard-tg-mixed | 0.906 | 0.831 | 142 | 6381 | prefer |
| DeltaKronecker-all | 0.794 | 0.722 | 54 | 5415 | prefer |
| mheidari-all | 0.78 | 0.708 | 48 | 14522 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4989 | observe |
| Epodonios-all | 0.255 | None | 0 | 6941 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3990 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6992 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5191 | observe |
| barry-far-vless | 0.255 | None | 0 | 5469 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4094 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1746 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 22 |
| geo | TimeoutError | - | 20 |
| speed | TimeoutError | - | 11 |
| speed | ClientOSError | - | 8 |
| 204 | ProxyError | - | 8 |
| 204 | TimeoutError | - | 8 |
| geo | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
