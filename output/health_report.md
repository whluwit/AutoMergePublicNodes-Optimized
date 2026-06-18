# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.9.1 |
| 更新时间 | 2026-06-18 04:21:59 |
| 运行耗时 | 272.4s |
| 订阅源总数 | 44 |
| 健康订阅源 | 44 |
| 原始节点 | 67675 |
| 去重后节点 | 22191 |
| TCP 可达 | 799 |
| 真实可用 | 618 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22191 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.2 |
| geo | 1.3 |
| tcp | 60.4 |
| probe | 99.2 |
| real_test | 70.8 |
| generate | 37.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 36790 |
| shadowsocks | 10235 |
| vmess | 10116 |
| trojan | 10057 |
| hysteria2 | 179 |
| shadowsocksr | 160 |
| http | 95 |
| socks | 35 |
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
| 77.88 | trojan | 256.1 | 650.7 | 21.85 | 0.0 | 10.0 | 14.17 | 18.86 | Surfboard-tg-mixed | 207.126.167.150 |
| 77.09 | shadowsocks | 227.4 | 620.7 | 22.51 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 37.19.198.160 |
| 76.98 | shadowsocks | 232.5 | 633.2 | 22.4 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 37.19.198.243 |
| 76.84 | shadowsocks | 238.3 | 643.9 | 22.26 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 37.19.198.244 |
| 75.91 | shadowsocks | 278.5 | 770.7 | 21.33 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 37.19.198.236 |
| 75.55 | shadowsocks | 225.1 | 603.6 | 22.57 | 0.0 | 10.0 | 13.52 | 14.96 | mheidari-all | 198.98.53.130 |
| 74.77 | trojan | 334.8 | 885.8 | 20.03 | 0.0 | 10.0 | 14.17 | 18.86 | Surfboard-tg-mixed | 45.61.52.243 |
| 73.84 | shadowsocks | 281.3 | 645.7 | 21.27 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 156.146.38.167 |
| 72.71 | trojan | 336.8 | 545.5 | 19.98 | 0.0 | 10.0 | 14.17 | 18.86 | Surfboard-tg-mixed | 151.101.110.219 |
| 72.47 | shadowsocks | 318.3 | 767.4 | 20.41 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 156.146.38.170 |
| 72.34 | shadowsocks | 318.8 | 765.1 | 20.4 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 149.28.255.6 |
| 72.21 | shadowsocks | 278.3 | 644.0 | 21.34 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 156.146.38.169 |
| 72.05 | shadowsocks | 353.2 | 833.0 | 19.6 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 107.172.250.161 |
| 70.05 | trojan | 382.8 | 899.2 | 18.92 | 0.0 | 10.0 | 14.17 | 14.96 | mheidari-all | 207.126.167.241 |
| 70.01 | shadowsocks | 316.6 | 756.5 | 20.45 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 156.146.38.168 |
| 69.28 | shadowsocks | 330.3 | 595.9 | 20.13 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 108.181.0.177 |
| 69.25 | shadowsocks | 318.1 | 634.1 | 20.41 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 173.244.56.9 |
| 69.09 | shadowsocks | 231.3 | 630.1 | 22.42 | 0.0 | 9.95 | 13.52 | 16.56 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 69.02 | shadowsocks | 338.7 | 676.5 | 19.94 | 0.0 | 10.0 | 13.52 | 16.56 | Au1rxx-base64 | 108.181.118.10 |
| 68.73 | vless | 302.9 | 843.6 | 20.77 | 0.0 | 10.0 | 7.6 | 18.86 | Surfboard-tg-mixed | 137.184.218.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | 1.0 | 25 | 73 | prefer |
| Surfboard-tg-mixed | 0.941 | 0.863 | 350 | 4586 | prefer |
| mheidari-all | 0.837 | 0.759 | 216 | 13927 | prefer |
| Au1rxx-base64 | 0.817 | 0.819 | 83 | 126 | prefer |
| DeltaKronecker-all | 0.58 | 0.5 | 112 | 7763 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| xiaoji235-airport-v2ray-all | 0.289 | 1.0 | 1 | 847 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4274 | observe |
| Epodonios-all | 0.255 | None | 0 | 6401 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3977 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 5959 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3590 | observe |
| barry-far-vless | 0.255 | None | 0 | 4240 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4541 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| general | unknown | - | 130 |
| speed | ClientOSError | - | 23 |
| geo | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 6 |
| geo | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| 204 | TimeoutError | - | 2 |
| 204 | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
