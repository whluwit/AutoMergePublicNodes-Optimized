# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-01 19:51:21 |
| 运行耗时 | 226.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 77098 |
| 去重后节点 | 23239 |
| TCP 可达 | 3000 |
| 真实可用 | 330 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23239 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.3 |
| tcp | 30.9 |
| probe | 48.1 |
| real_test | 97.0 |
| generate | 44.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43503 |
| trojan | 13359 |
| vmess | 10471 |
| shadowsocks | 9167 |
| hysteria2 | 255 |
| shadowsocksr | 149 |
| http | 135 |
| socks | 52 |
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
| 76.09 | shadowsocks | 234.8 | 649.8 | 22.34 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 37.19.198.160 |
| 76.09 | shadowsocks | 234.9 | 648.6 | 22.34 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 37.19.198.236 |
| 75.99 | shadowsocks | 239.1 | 661.1 | 22.24 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 37.19.198.244 |
| 72.7 | shadowsocks | 276.7 | 631.5 | 21.37 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 156.146.38.168 |
| 72.57 | shadowsocks | 365.3 | 993.7 | 19.32 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 172.234.202.34 |
| 71.85 | shadowsocks | 290.4 | 665.5 | 21.06 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 156.146.38.167 |
| 71.11 | shadowsocks | 234.2 | 648.1 | 22.36 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 37.19.198.243 |
| 70.26 | shadowsocks | 313.6 | 737.0 | 20.52 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 156.146.38.169 |
| 70.16 | shadowsocks | 229.2 | 619.4 | 22.47 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 68.96 | shadowsocks | 317.2 | 588.1 | 20.43 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 173.244.56.6 |
| 68.53 | shadowsocks | 327.2 | 538.0 | 20.2 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 173.244.56.9 |
| 68.48 | shadowsocks | 318.2 | 594.0 | 20.41 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 149.22.95.183 |
| 68.2 | shadowsocks | 350.6 | 705.6 | 19.66 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 108.181.0.177 |
| 67.49 | shadowsocks | 351.0 | 637.7 | 19.65 | 0.0 | 10.0 | 12.03 | 15.72 | Au1rxx-base64 | 108.181.118.10 |
| 65.87 | http | 628.9 | 947.5 | 13.22 | 0.0 | 9.76 | 14.61 | 19.52 | snakem982 | 84.239.49.159 |
| 65.77 | http | 630.1 | 940.4 | 13.19 | 0.0 | 9.76 | 14.61 | 19.52 | snakem982 | 84.239.49.154 |
| 65.77 | http | 631.8 | 946.7 | 13.15 | 0.0 | 9.76 | 14.61 | 19.52 | snakem982 | 84.239.49.157 |
| 65.74 | http | 630.1 | 935.1 | 13.19 | 0.0 | 9.74 | 14.61 | 19.52 | snakem982 | 84.239.49.160 |
| 65.65 | http | 635.0 | 948.7 | 13.08 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 84.239.14.152 |
| 65.65 | http | 635.6 | 946.5 | 13.06 | 0.0 | 9.76 | 14.61 | 19.52 | snakem982 | 84.239.14.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.794 | 0.716 | 211 | 5849 | prefer |
| Au1rxx-base64 | 0.777 | 0.784 | 51 | 82 | prefer |
| mheidari-all | 0.665 | 0.59 | 39 | 16033 | observe |
| DeltaKronecker-all | 0.524 | 0.443 | 176 | 7631 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 169 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4308 | observe |
| Epodonios-all | 0.255 | None | 0 | 6737 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6642 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4351 | observe |
| barry-far-vless | 0.255 | None | 0 | 4858 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5331 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 89 |
| 204 | ProxyError | - | 23 |
| 204 | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 14 |
| geo | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 7 |
| geo | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 258 | 300 | - |
| global | False | 272 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
