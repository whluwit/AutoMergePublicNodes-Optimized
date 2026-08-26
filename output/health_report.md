# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-26 06:43:59 |
| 运行耗时 | 276.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 77676 |
| 去重后节点 | 22059 |
| TCP 可达 | 3000 |
| 真实可用 | 600 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22059 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.4 |
| tcp | 35.1 |
| probe | 58.2 |
| real_test | 136.2 |
| generate | 39.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48723 |
| shadowsocks | 10320 |
| vmess | 10275 |
| trojan | 6605 |
| hysteria2 | 1369 |
| http | 172 |
| shadowsocksr | 133 |
| socks | 69 |
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
| 81.42 | http | 247.8 | 560.3 | 22.04 | 0.0 | 10.0 | 14.44 | 19.32 | zhangkai | 138.199.35.216 |
| 81.35 | shadowsocks | 245.8 | 607.4 | 22.09 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 156.146.38.169 |
| 81.34 | shadowsocks | 246.2 | 611.8 | 22.08 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 156.146.38.168 |
| 81.32 | shadowsocks | 247.0 | 615.0 | 22.06 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 156.146.38.170 |
| 80.22 | http | 270.5 | 630.4 | 21.52 | 0.0 | 10.0 | 14.44 | 19.32 | zhangkai | 138.199.35.198 |
| 79.58 | shadowsocks | 252.0 | 587.2 | 21.95 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 94.72.127.55 |
| 79.4 | shadowsocks | 243.5 | 608.6 | 22.14 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 156.146.38.167 |
| 78.94 | shadowsocks | 285.4 | 676.5 | 21.17 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 154.53.60.212 |
| 76.93 | vless | 268.7 | 601.1 | 21.56 | 0.0 | 10.0 | 7.02 | 19.98 | Au1rxx-base64 | 15.204.97.216 |
| 76.27 | shadowsocks | 319.2 | 683.7 | 20.39 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 173.244.56.6 |
| 75.76 | vless | 277.9 | 612.2 | 21.34 | 0.0 | 10.0 | 7.02 | 19.98 | Au1rxx-base64 | 15.204.97.209 |
| 75.73 | shadowsocks | 305.5 | 304.0 | 20.7 | 3.6 | 9.79 | 14.0 | 19.26 | Surfboard-tg-mixed | 149.22.87.241 |
| 75.7 | trojan | 273.3 | 581.5 | 21.45 | 0.0 | 10.0 | 10.99 | 19.98 | Au1rxx-base64 | 107.150.105.84 |
| 75.58 | shadowsocks | 305.1 | 307.8 | 20.72 | 3.46 | 9.77 | 14.0 | 19.26 | Surfboard-tg-mixed | 149.22.87.204 |
| 75.44 | trojan | 299.2 | 625.3 | 20.85 | 0.0 | 10.0 | 10.99 | 19.98 | Au1rxx-base64 | 35.91.251.124 |
| 75.33 | vless | 346.0 | 833.3 | 19.77 | 0.0 | 10.0 | 7.02 | 19.98 | Au1rxx-base64 | 15.204.97.197 |
| 75.22 | shadowsocks | 336.4 | 749.2 | 19.99 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 37.19.198.243 |
| 75.06 | vless | 353.6 | 860.6 | 19.59 | 0.0 | 10.0 | 7.02 | 19.98 | Au1rxx-base64 | 15.204.97.195 |
| 75.02 | shadowsocks | 329.6 | 650.5 | 20.15 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 149.22.95.183 |
| 74.98 | shadowsocks | 340.6 | 745.5 | 19.89 | 0.0 | 10.0 | 14.0 | 19.26 | Surfboard-tg-mixed | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.926 | 0.957 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.925 | 0.847 | 393 | 1986 | prefer |
| Surfboard-tg-mixed | 0.829 | 0.751 | 185 | 6366 | prefer |
| DeltaKronecker-all | 0.626 | 0.547 | 106 | 6107 | observe |
| mheidari-all | 0.538 | 0.457 | 81 | 14091 | observe |
| nscl5-all | 0.475 | 1.0 | 5 | 887 | observe |
| 10ium-ScrapeCategorize-Vless | 0.391 | 1.0 | 2 | 4825 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 191 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1990 | observe |
| Epodonios-all | 0.255 | None | 0 | 6845 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6976 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5211 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 54 |
| speed | TimeoutError | - | 53 |
| cn-block | TimeoutError | - | 24 |
| geo | ClientOSError | - | 20 |
| speed | ClientOSError | - | 19 |
| 204 | TimeoutError | - | 15 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
