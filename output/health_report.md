# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-15 06:36:16 |
| 运行耗时 | 422.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78114 |
| 去重后节点 | 22180 |
| TCP 可达 | 3000 |
| 真实可用 | 1205 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22180 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.0 |
| tcp | 33.4 |
| probe | 80.3 |
| real_test | 259.4 |
| generate | 42.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43989 |
| trojan | 11964 |
| vmess | 10764 |
| shadowsocks | 10090 |
| hysteria2 | 952 |
| http | 187 |
| socks | 77 |
| shadowsocksr | 76 |
| tuic | 8 |
| hysteria | 7 |

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
| 84.43 | hysteria2 | 241.1 | 646.9 | 22.2 | 0.0 | 10.0 | 13.33 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 84.11 | hysteria2 | 259.1 | 706.6 | 21.78 | 0.0 | 10.0 | 13.33 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.93 | http | 246.4 | 638.6 | 22.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 83.78 | http | 252.9 | 650.2 | 21.92 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 83.77 | http | 253.5 | 662.2 | 21.91 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 83.67 | http | 257.6 | 672.3 | 21.81 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 83.66 | http | 258.1 | 672.7 | 21.8 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 83.66 | http | 258.3 | 673.5 | 21.8 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 83.64 | http | 259.3 | 665.4 | 21.78 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.63 | http | 259.7 | 663.5 | 21.77 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 83.48 | http | 265.8 | 696.6 | 21.62 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.46 | http | 266.7 | 694.4 | 21.6 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 83.4 | http | 269.5 | 693.8 | 21.54 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.29 | http | 274.2 | 722.2 | 21.43 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 83.2 | http | 278.2 | 726.3 | 21.34 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 83.14 | http | 280.9 | 731.2 | 21.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 83.04 | http | 285.2 | 755.8 | 21.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 82.08 | vless | 258.4 | 684.7 | 21.8 | 0.0 | 10.0 | 10.28 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 81.91 | http | 333.9 | 902.9 | 20.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 81.77 | http | 339.7 | 911.5 | 19.91 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.953 | 814 | 1975 | prefer |
| zhangkai | 0.991 | 0.992 | 126 | 159 | prefer |
| Surfboard-tg-mixed | 0.965 | 0.917 | 24 | 5665 | prefer |
| DeltaKronecker-all | 0.487 | 0.407 | 671 | 5773 | observe |
| nscl5-all | 0.438 | 1.0 | 3 | 2081 | observe |
| mheidari-all | 0.314 | 0.333 | 9 | 15492 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 162 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5113 | observe |
| Epodonios-all | 0.255 | None | 0 | 6322 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7671 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4367 | observe |
| barry-far-vless | 0.255 | None | 0 | 4707 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 195 |
| geo | ClientOSError | - | 80 |
| speed | TimeoutError | - | 51 |
| speed | ClientOSError | - | 41 |
| cn-block | TimeoutError | - | 23 |
| 204 | TimeoutError | - | 22 |
| 204 | ProxyError | - | 20 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 4 |
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
