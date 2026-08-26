# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-26 19:45:09 |
| 运行耗时 | 217.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 89591 |
| 去重后节点 | 24383 |
| TCP 可达 | 3000 |
| 真实可用 | 439 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24383 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 38.6 |
| probe | 47.9 |
| real_test | 93.3 |
| generate | 29.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56350 |
| shadowsocks | 11855 |
| vmess | 11483 |
| trojan | 7322 |
| hysteria2 | 2159 |
| http | 172 |
| shadowsocksr | 133 |
| socks | 79 |
| anytls | 20 |
| hysteria | 13 |
| tuic | 5 |

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
| 83.26 | vless | 247.6 | 645.4 | 22.05 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.182 |
| 83.01 | hysteria2 | 270.1 | 723.4 | 21.53 | 0.0 | 10.0 | 13.06 | 19.52 | Au1rxx-base64 | 159.223.157.129 |
| 82.49 | vless | 280.5 | 685.5 | 21.28 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.133 |
| 82.45 | vless | 282.2 | 691.8 | 21.24 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.89 |
| 82.3 | vless | 288.9 | 670.2 | 21.09 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.184 |
| 82.14 | vless | 296.0 | 740.4 | 20.93 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.235 |
| 82.13 | vless | 296.2 | 833.5 | 20.92 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 47.89.186.170 |
| 81.93 | shadowsocks | 240.2 | 666.9 | 22.22 | 0.0 | 10.0 | 13.71 | 20.0 | mheidari-all | 37.19.198.243 |
| 81.87 | vless | 307.6 | 833.9 | 20.66 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.229 |
| 81.85 | vless | 293.5 | 724.2 | 20.98 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 66.70.179.198 |
| 81.82 | vless | 262.2 | 632.8 | 21.71 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 195.211.99.45 |
| 81.67 | vless | 250.7 | 654.6 | 21.97 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.15 |
| 81.66 | vless | 316.6 | 713.1 | 20.45 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.225 |
| 81.6 | vless | 319.1 | 813.2 | 20.39 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.202 |
| 81.53 | vless | 322.2 | 901.4 | 20.32 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 137.184.218.169 |
| 81.28 | shadowsocks | 247.3 | 687.3 | 22.05 | 0.0 | 10.0 | 13.71 | 19.52 | Au1rxx-base64 | 37.19.198.160 |
| 81.16 | vless | 338.3 | 844.0 | 19.95 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.104 |
| 80.97 | shadowsocks | 260.8 | 725.1 | 21.74 | 0.0 | 10.0 | 13.71 | 19.52 | Au1rxx-base64 | 37.19.198.244 |
| 80.91 | vless | 348.8 | 824.5 | 19.7 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 169.40.42.232 |
| 80.83 | vless | 296.0 | 655.9 | 20.93 | 0.0 | 10.0 | 11.69 | 19.52 | Au1rxx-base64 | 198.251.78.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.952 | 0.875 | 360 | 1979 | prefer |
| zhangkai | 0.922 | 0.955 | 22 | 144 | prefer |
| Surfboard-tg-mixed | 0.714 | 0.917 | 12 | 6645 | prefer |
| mheidari-all | 0.68 | 0.602 | 133 | 19290 | observe |
| DeltaKronecker-all | 0.643 | 0.9 | 10 | 6107 | observe |
| tg-oneclickvpnkeys | 0.32 | 1.0 | 2 | 218 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4825 | observe |
| Epodonios-all | 0.255 | None | 0 | 7011 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7313 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5444 | observe |
| barry-far-vless | 0.255 | None | 0 | 5698 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4011 | observe |
| Au1rxx-clash | 0.254 | None | 0 | 1979 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 37 |
| cn-block | TimeoutError | - | 14 |
| speed | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 11 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyError | - | 9 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
