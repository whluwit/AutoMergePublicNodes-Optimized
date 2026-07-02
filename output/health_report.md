# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-02 13:52:59 |
| 运行耗时 | 225.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 77153 |
| 去重后节点 | 23310 |
| TCP 可达 | 3000 |
| 真实可用 | 387 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23310 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 30.8 |
| probe | 54.7 |
| real_test | 104.6 |
| generate | 29.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44162 |
| trojan | 12752 |
| vmess | 10460 |
| shadowsocks | 9102 |
| hysteria2 | 231 |
| socks | 159 |
| shadowsocksr | 145 |
| http | 135 |
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
| 77.52 | shadowsocks | 214.1 | 473.7 | 22.82 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 173.244.56.9 |
| 77.49 | shadowsocks | 193.9 | 497.0 | 23.29 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 108.181.118.10 |
| 76.71 | shadowsocks | 249.0 | 606.0 | 22.01 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 156.146.38.169 |
| 76.54 | shadowsocks | 256.4 | 630.8 | 21.84 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 156.146.38.167 |
| 76.36 | shadowsocks | 264.5 | 657.6 | 21.66 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 173.244.56.6 |
| 75.9 | socks | 200.4 | 495.1 | 23.14 | 0.0 | 10.0 | 13.54 | 16.72 | Surfboard-tg-mixed | 104.152.50.252 |
| 75.54 | shadowsocks | 293.2 | 739.4 | 20.99 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 156.146.38.168 |
| 75.34 | shadowsocks | 286.8 | 756.8 | 21.14 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 108.181.0.177 |
| 75.15 | vless | 208.0 | 547.6 | 22.96 | 0.0 | 10.0 | 8.47 | 16.72 | Surfboard-tg-mixed | 112.121.184.10 |
| 75.15 | shadowsocks | 224.0 | 530.1 | 22.59 | 0.0 | 10.0 | 13.78 | 13.88 | DeltaKronecker-all | 107.172.219.230 |
| 73.07 | shadowsocks | 262.4 | 549.8 | 21.7 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 149.22.95.183 |
| 73.06 | vless | 212.1 | 511.5 | 22.87 | 0.0 | 10.0 | 8.47 | 16.72 | Surfboard-tg-mixed | 64.23.143.23 |
| 72.63 | shadowsocks | 284.1 | 291.2 | 21.2 | 4.08 | 9.91 | 13.78 | 14.92 | Au1rxx-base64 | 149.22.87.204 |
| 72.63 | shadowsocks | 295.6 | 748.1 | 20.93 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 156.146.38.170 |
| 71.39 | vless | 348.5 | 845.0 | 19.71 | 0.0 | 10.0 | 8.47 | 14.92 | Au1rxx-base64 | 15.204.97.214 |
| 69.77 | trojan | 237.7 | 514.3 | 22.28 | 0.0 | 10.0 | 9.85 | 13.88 | DeltaKronecker-all | 104.17.148.22 |
| 69.0 | shadowsocks | 344.1 | 346.2 | 19.81 | 2.02 | 9.91 | 13.78 | 14.92 | Au1rxx-base64 | 149.22.87.240 |
| 68.94 | shadowsocks | 310.0 | 370.2 | 20.6 | 1.12 | 9.91 | 13.78 | 14.92 | Au1rxx-base64 | 149.22.87.241 |
| 68.93 | shadowsocks | 349.4 | 726.0 | 19.69 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 37.19.198.236 |
| 68.91 | shadowsocks | 385.2 | 902.8 | 18.86 | 0.0 | 10.0 | 13.78 | 14.92 | Au1rxx-base64 | 172.234.202.34 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.813 | 0.825 | 40 | 78 | prefer |
| Surfboard-tg-mixed | 0.794 | 0.716 | 264 | 5750 | prefer |
| mheidari-all | 0.685 | 0.607 | 84 | 16231 | observe |
| DeltaKronecker-all | 0.631 | 0.551 | 136 | 7467 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| nscl5-all | 0.301 | 1.0 | 1 | 1162 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4254 | observe |
| Epodonios-all | 0.255 | None | 0 | 6611 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7019 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4338 | observe |
| barry-far-vless | 0.255 | None | 0 | 4895 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5365 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 64 |
| 204 | ProxyError | - | 33 |
| 204 | ClientOSError | - | 14 |
| 204 | TimeoutError | - | 10 |
| geo | TimeoutError | - | 10 |
| cn-block | TimeoutError | - | 10 |
| geo | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 9 |
| speed | ProxyError | - | 8 |
| geo | ProxyError | - | 7 |
| cn-block | ProxyError | - | 6 |
| speed | TimeoutError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
