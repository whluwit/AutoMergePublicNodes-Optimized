# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-29 12:15:15 |
| 运行耗时 | 287.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 77950 |
| 去重后节点 | 21150 |
| TCP 可达 | 3000 |
| 真实可用 | 599 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21150 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.4 |
| tcp | 34.6 |
| probe | 59.5 |
| real_test | 135.6 |
| generate | 50.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48309 |
| vmess | 11090 |
| shadowsocks | 10635 |
| trojan | 6055 |
| hysteria2 | 1487 |
| http | 175 |
| shadowsocksr | 133 |
| socks | 56 |
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
| 81.72 | vless | 279.4 | 763.4 | 21.31 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 15.204.97.195 |
| 81.57 | shadowsocks | 207.5 | 560.8 | 22.97 | 0.0 | 10.0 | 13.8 | 18.8 | Au1rxx-base64 | 149.22.95.183 |
| 81.53 | vless | 287.5 | 792.2 | 21.12 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 15.204.97.216 |
| 81.5 | vless | 233.0 | 536.7 | 22.39 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 64.23.229.123 |
| 81.1 | vless | 306.3 | 846.1 | 20.69 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 15.204.97.197 |
| 79.81 | vless | 250.2 | 529.0 | 21.99 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 192.220.9.89 |
| 79.78 | vless | 233.6 | 536.9 | 22.37 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 74.207.245.124 |
| 79.77 | vless | 233.9 | 544.2 | 22.36 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 45.33.107.237 |
| 79.66 | vless | 230.1 | 526.4 | 22.45 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 45.33.62.166 |
| 79.49 | vless | 289.3 | 796.9 | 21.08 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 15.204.97.206 |
| 79.46 | vless | 277.5 | 761.5 | 21.35 | 0.0 | 10.0 | 11.61 | 16.5 | DeltaKronecker-all | 15.204.97.209 |
| 79.23 | vless | 240.8 | 556.5 | 22.2 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 192.155.87.188 |
| 79.23 | http | 254.6 | 535.3 | 21.89 | 0.0 | 10.0 | 14.48 | 19.34 | zhangkai | 138.199.35.198 |
| 79.07 | vless | 228.6 | 527.7 | 22.49 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 173.230.155.55 |
| 79.07 | http | 267.2 | 573.0 | 21.59 | 0.0 | 10.0 | 14.48 | 19.34 | zhangkai | 138.199.35.216 |
| 78.74 | vless | 229.5 | 526.0 | 22.47 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 45.33.62.226 |
| 77.82 | shadowsocks | 259.5 | 543.5 | 21.77 | 0.0 | 10.0 | 13.8 | 18.8 | Au1rxx-base64 | 108.181.118.10 |
| 77.63 | vless | 239.9 | 559.7 | 22.22 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 50.116.13.24 |
| 77.61 | trojan | 300.8 | 658.9 | 20.81 | 0.0 | 10.0 | 13.12 | 18.8 | Au1rxx-base64 | 14.1.28.76 |
| 77.58 | vless | 231.6 | 520.3 | 22.42 | 0.0 | 10.0 | 11.61 | 18.8 | Au1rxx-base64 | 192.81.131.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 1.0 | 22 | 14706 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.951 | 0.881 | 403 | 1806 | prefer |
| Surfboard-tg-mixed | 0.795 | 0.719 | 121 | 6733 | prefer |
| DeltaKronecker-all | 0.783 | 0.706 | 153 | 4926 | prefer |
| tg-oneclickvpnkeys | 0.364 | 1.0 | 3 | 141 | observe |
| Au1rxx-clash | 0.328 | 1.0 | 1 | 1817 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4635 | observe |
| Epodonios-all | 0.255 | None | 0 | 7153 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7260 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5530 | observe |
| barry-far-vless | 0.255 | None | 0 | 5723 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4012 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 32 |
| geo | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 21 |
| geo | ClientOSError | - | 15 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 8 |
| speed | TimeoutError | - | 6 |
| speed | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
