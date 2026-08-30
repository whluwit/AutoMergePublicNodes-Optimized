# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-30 11:10:37 |
| 运行耗时 | 255.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 79189 |
| 去重后节点 | 21796 |
| TCP 可达 | 3000 |
| 真实可用 | 574 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21796 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 34.4 |
| probe | 56.4 |
| real_test | 110.7 |
| generate | 46.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49367 |
| vmess | 10540 |
| shadowsocks | 10278 |
| trojan | 7159 |
| hysteria2 | 1477 |
| http | 166 |
| shadowsocksr | 134 |
| socks | 53 |
| hysteria | 7 |
| tuic | 7 |
| anytls | 1 |

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
| 84.49 | hysteria2 | 229.8 | 633.3 | 22.46 | 0.0 | 10.0 | 13.33 | 19.8 | Au1rxx-base64 | 159.223.157.129 |
| 82.8 | shadowsocks | 225.2 | 623.1 | 22.56 | 0.0 | 10.0 | 14.44 | 19.8 | Au1rxx-base64 | 37.19.198.243 |
| 82.7 | shadowsocks | 229.8 | 634.1 | 22.46 | 0.0 | 10.0 | 14.44 | 19.8 | Au1rxx-base64 | 37.19.198.160 |
| 82.7 | shadowsocks | 229.8 | 630.3 | 22.46 | 0.0 | 10.0 | 14.44 | 19.8 | Au1rxx-base64 | 37.19.198.244 |
| 82.52 | vless | 237.7 | 637.3 | 22.28 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 82.25 | vless | 249.1 | 665.7 | 22.01 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 38.77.133.141 |
| 81.95 | vless | 262.0 | 635.7 | 21.71 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 195.211.99.45 |
| 81.46 | vless | 283.2 | 740.2 | 21.22 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.173 |
| 81.43 | vless | 284.8 | 687.7 | 21.19 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.16 |
| 81.34 | vless | 288.3 | 768.4 | 21.1 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.182 |
| 81.13 | vless | 297.4 | 726.4 | 20.89 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.35 |
| 81.05 | vless | 258.0 | 657.7 | 21.81 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 172.105.104.54 |
| 80.98 | vless | 303.8 | 842.2 | 20.74 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 79.127.243.217 |
| 80.97 | vless | 304.6 | 750.8 | 20.73 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.225 |
| 80.79 | vless | 312.2 | 830.2 | 20.55 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.95 |
| 80.77 | vless | 313.1 | 842.8 | 20.53 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.74 |
| 80.74 | vless | 271.2 | 718.5 | 21.5 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.235 |
| 80.44 | vless | 327.2 | 823.0 | 20.2 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 66.70.179.198 |
| 80.25 | vless | 335.6 | 906.8 | 20.01 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.75 |
| 80.23 | vless | 336.5 | 858.6 | 19.99 | 0.0 | 10.0 | 10.44 | 19.8 | Au1rxx-base64 | 169.40.42.232 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.931 | 350 | 1804 | prefer |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.863 | 0.787 | 155 | 6846 | prefer |
| DeltaKronecker-all | 0.853 | 0.778 | 117 | 5576 | prefer |
| mheidari-all | 0.633 | 0.714 | 14 | 15081 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4762 | observe |
| Epodonios-all | 0.255 | None | 0 | 7251 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3991 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7562 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5683 | observe |
| barry-far-vless | 0.255 | None | 0 | 5908 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3949 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 19 |
| geo | ClientOSError | - | 18 |
| 204 | ProxyError | - | 10 |
| cn-block | TimeoutError | - | 10 |
| speed | ClientOSError | - | 9 |
| geo | TimeoutError | - | 6 |
| speed | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
