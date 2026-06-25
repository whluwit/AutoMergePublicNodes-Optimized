# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-25 02:52:50 |
| 运行耗时 | 257.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 75407 |
| 去重后节点 | 22420 |
| TCP 可达 | 3000 |
| 真实可用 | 539 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22420 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 29.8 |
| probe | 55.6 |
| real_test | 136.2 |
| generate | 29.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44269 |
| trojan | 10722 |
| vmess | 9974 |
| shadowsocks | 9859 |
| hysteria2 | 225 |
| shadowsocksr | 155 |
| http | 129 |
| socks | 66 |
| hysteria | 6 |
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
| 75.83 | shadowsocks | 216.4 | 510.0 | 22.77 | 0.0 | 10.0 | 12.14 | 14.92 | Au1rxx-base64 | 173.244.56.9 |
| 75.64 | shadowsocks | 202.8 | 482.6 | 23.08 | 0.0 | 10.0 | 12.14 | 14.92 | Au1rxx-base64 | 108.181.0.177 |
| 75.14 | shadowsocks | 219.7 | 515.5 | 22.69 | 0.0 | 10.0 | 12.14 | 14.92 | Au1rxx-base64 | 149.22.95.183 |
| 75.11 | shadowsocks | 225.9 | 573.3 | 22.55 | 0.0 | 10.0 | 12.14 | 14.92 | Au1rxx-base64 | 108.181.118.10 |
| 75.06 | vless | 310.5 | 812.3 | 20.59 | 0.0 | 10.0 | 9.55 | 14.92 | Au1rxx-base64 | 15.204.97.214 |
| 74.96 | vless | 314.8 | 833.0 | 20.49 | 0.0 | 10.0 | 9.55 | 14.92 | Au1rxx-base64 | 15.204.97.219 |
| 74.87 | shadowsocks | 258.0 | 635.9 | 21.81 | 0.0 | 10.0 | 12.14 | 14.92 | Au1rxx-base64 | 173.244.56.6 |
| 74.11 | vless | 163.9 | 447.4 | 23.98 | 0.0 | 10.0 | 9.55 | 16.08 | Surfboard-tg-mixed | 92.223.71.246 |
| 73.13 | shadowsocks | 332.8 | 929.3 | 20.07 | 0.0 | 10.0 | 12.14 | 14.92 | Au1rxx-base64 | 216.105.168.18 |
| 71.97 | trojan | 314.6 | 838.7 | 20.5 | 0.0 | 10.0 | 9.05 | 14.92 | Au1rxx-base64 | 45.61.58.89 |
| 71.53 | trojan | 333.5 | 899.5 | 20.06 | 0.0 | 10.0 | 9.05 | 14.92 | Au1rxx-base64 | 45.61.52.243 |
| 71.15 | shadowsocks | 294.9 | 659.4 | 20.95 | 0.0 | 10.0 | 12.14 | 14.92 | Au1rxx-base64 | 156.146.38.167 |
| 70.89 | trojan | 298.5 | 588.1 | 20.87 | 0.0 | 10.0 | 9.05 | 14.92 | Au1rxx-base64 | 207.126.167.241 |
| 70.64 | trojan | 372.0 | 865.6 | 19.17 | 0.0 | 10.0 | 9.05 | 14.92 | Au1rxx-base64 | 198.52.244.10 |
| 69.12 | trojan | 364.0 | 823.6 | 19.35 | 0.0 | 10.0 | 9.05 | 14.92 | Au1rxx-base64 | 207.126.167.162 |
| 68.94 | shadowsocks | 262.5 | 734.7 | 21.7 | 0.0 | 10.0 | 12.14 | 12.2 | DeltaKronecker-all | 107.172.219.230 |
| 68.64 | shadowsocks | 298.3 | 344.6 | 20.87 | 2.08 | 9.9 | 12.14 | 14.92 | Au1rxx-base64 | 149.22.87.241 |
| 68.49 | shadowsocks | 300.2 | 350.9 | 20.83 | 1.84 | 9.9 | 12.14 | 14.92 | Au1rxx-base64 | 149.22.87.204 |
| 68.4 | shadowsocks | 300.2 | 352.8 | 20.83 | 1.77 | 9.9 | 12.14 | 14.92 | Au1rxx-base64 | 149.22.87.240 |
| 66.82 | shadowsocks | 289.9 | 639.0 | 21.07 | 0.0 | 10.0 | 12.14 | 14.92 | Au1rxx-base64 | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | 1.0 | 36 | 82 | prefer |
| Surfboard-tg-mixed | 0.852 | 0.774 | 292 | 5184 | prefer |
| mheidari-all | 0.706 | 0.627 | 271 | 15461 | prefer |
| Au1rxx-base64 | 0.697 | 0.697 | 76 | 119 | observe |
| nscl5-all | 0.357 | 1.0 | 2 | 1136 | observe |
| DeltaKronecker-all | 0.288 | 0.206 | 248 | 6644 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4745 | observe |
| Epodonios-all | 0.255 | None | 0 | 7785 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7180 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3909 | observe |
| barry-far-vless | 0.255 | None | 0 | 4704 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4710 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 151 |
| geo | TimeoutError | - | 141 |
| geo | ClientOSError | - | 35 |
| speed | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 9 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
