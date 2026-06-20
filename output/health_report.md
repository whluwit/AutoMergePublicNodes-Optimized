# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.9.1 |
| 更新时间 | 2026-06-20 01:58:36 |
| 运行耗时 | 419.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 73168 |
| 去重后节点 | 22175 |
| TCP 可达 | 975 |
| 真实可用 | 703 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22175 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.3 |
| tcp | 62.7 |
| probe | 104.1 |
| real_test | 212.6 |
| generate | 34.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 41794 |
| shadowsocks | 10725 |
| trojan | 10146 |
| vmess | 9865 |
| hysteria2 | 238 |
| shadowsocksr | 166 |
| http | 107 |
| socks | 100 |
| anytls | 19 |
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
| 78.8 | vless | 193.5 | 500.1 | 23.3 | 0.0 | 10.0 | 12.02 | 17.98 | Surfboard-tg-mixed | 67.230.170.34 |
| 73.56 | vless | 224.5 | 505.1 | 22.58 | 0.0 | 10.0 | 12.02 | 16.34 | mheidari-all | 104.24.9.6 |
| 73.0 | vless | 343.2 | 832.5 | 19.83 | 0.0 | 10.0 | 12.02 | 14.34 | Au1rxx-base64 | 15.204.97.214 |
| 72.53 | shadowsocks | 241.3 | 621.1 | 22.19 | 0.0 | 10.0 | 12.5 | 14.34 | Au1rxx-base64 | 173.244.56.6 |
| 72.22 | shadowsocks | 254.7 | 628.7 | 21.88 | 0.0 | 10.0 | 12.5 | 14.34 | Au1rxx-base64 | 156.146.38.170 |
| 72.19 | shadowsocks | 256.1 | 622.7 | 21.85 | 0.0 | 10.0 | 12.5 | 14.34 | Au1rxx-base64 | 156.146.38.168 |
| 72.14 | vless | 280.6 | 438.7 | 21.28 | 0.0 | 10.0 | 12.02 | 16.34 | mheidari-all | 162.159.43.131 |
| 72.1 | shadowsocks | 259.9 | 641.2 | 21.76 | 0.0 | 10.0 | 12.5 | 14.34 | Au1rxx-base64 | 156.146.38.167 |
| 72.05 | shadowsocks | 253.6 | 621.6 | 21.91 | 0.0 | 10.0 | 12.5 | 14.34 | Au1rxx-base64 | 156.146.38.169 |
| 70.44 | vless | 310.9 | 836.1 | 20.58 | 0.0 | 10.0 | 12.02 | 16.34 | mheidari-all | 98.159.111.111 |
| 70.28 | vless | 351.1 | 394.3 | 19.65 | 0.21 | 9.92 | 12.02 | 17.98 | Surfboard-tg-mixed | 31.76.91.18 |
| 70.2 | vless | 352.4 | 398.5 | 19.62 | 0.06 | 9.92 | 12.02 | 17.98 | Surfboard-tg-mixed | 31.76.91.24 |
| 70.16 | shadowsocks | 214.4 | 488.1 | 22.82 | 0.0 | 10.0 | 12.5 | 14.34 | Au1rxx-base64 | 173.244.56.9 |
| 70.12 | vless | 353.3 | 401.2 | 19.6 | 0.0 | 9.92 | 12.02 | 17.98 | Surfboard-tg-mixed | 31.76.91.26 |
| 70.02 | vless | 352.7 | 397.8 | 19.61 | 0.08 | 9.92 | 12.02 | 17.98 | Surfboard-tg-mixed | 31.76.91.28 |
| 69.62 | shadowsocks | 345.4 | 939.1 | 19.78 | 0.0 | 10.0 | 12.5 | 14.34 | Au1rxx-base64 | 167.160.90.51 |
| 69.53 | vless | 364.7 | 884.6 | 19.34 | 0.0 | 10.0 | 12.02 | 14.34 | Au1rxx-base64 | 15.204.97.219 |
| 69.23 | shadowsocks | 272.0 | 602.7 | 21.48 | 0.0 | 10.0 | 12.5 | 14.34 | Au1rxx-base64 | 149.22.95.183 |
| 69.18 | vless | 458.2 | 961.5 | 17.17 | 0.0 | 10.0 | 12.02 | 17.98 | Surfboard-tg-mixed | 193.233.202.1 |
| 68.73 | trojan | 356.5 | 973.9 | 19.53 | 0.0 | 10.0 | 6.22 | 17.98 | Surfboard-tg-mixed | 45.61.52.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | 1.0 | 25 | 73 | prefer |
| Surfboard-tg-mixed | 0.924 | 0.846 | 441 | 5022 | prefer |
| mheidari-all | 0.824 | 0.745 | 330 | 14629 | prefer |
| Au1rxx-base64 | 0.671 | 0.675 | 40 | 100 | observe |
| DeltaKronecker-all | 0.317 | 0.233 | 129 | 6989 | observe |
| nscl5-all | 0.309 | 1.0 | 1 | 1360 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7454 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3982 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6670 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3739 | observe |
| barry-far-vless | 0.255 | None | 0 | 4406 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4527 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 94 |
| speed | ClientOSError | - | 82 |
| cn-block | TimeoutError | - | 32 |
| speed | TimeoutError | - | 24 |
| geo | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 7 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
