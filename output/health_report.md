# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-02 08:53:22 |
| 运行耗时 | 231.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 76077 |
| 去重后节点 | 23089 |
| TCP 可达 | 3000 |
| 真实可用 | 433 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23089 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.5 |
| tcp | 30.3 |
| probe | 48.2 |
| real_test | 100.0 |
| generate | 46.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43043 |
| trojan | 12578 |
| vmess | 10436 |
| shadowsocks | 9334 |
| hysteria2 | 224 |
| socks | 165 |
| shadowsocksr | 155 |
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
| 76.72 | shadowsocks | 197.3 | 488.7 | 23.21 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 108.181.118.10 |
| 76.3 | shadowsocks | 215.4 | 543.2 | 22.79 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 108.181.0.177 |
| 75.52 | shadowsocks | 270.9 | 641.5 | 21.51 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 173.244.56.6 |
| 75.43 | shadowsocks | 232.6 | 487.9 | 22.39 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 173.244.56.9 |
| 72.87 | shadowsocks | 271.6 | 277.9 | 21.49 | 4.58 | 9.93 | 12.71 | 15.3 | Au1rxx-base64 | 149.22.87.240 |
| 72.35 | shadowsocks | 220.1 | 523.2 | 22.68 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 149.22.95.183 |
| 72.04 | shadowsocks | 294.2 | 659.4 | 20.97 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 156.146.38.169 |
| 71.94 | shadowsocks | 291.0 | 651.7 | 21.04 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 156.146.38.168 |
| 71.93 | shadowsocks | 290.5 | 661.1 | 21.05 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 156.146.38.167 |
| 71.28 | vless | 310.4 | 815.6 | 20.59 | 0.0 | 10.0 | 5.39 | 15.3 | Au1rxx-base64 | 15.204.97.214 |
| 71.17 | socks | 289.6 | 790.1 | 21.07 | 0.0 | 10.0 | 13.08 | 16.52 | Surfboard-tg-mixed | 104.152.50.252 |
| 69.26 | shadowsocks | 299.3 | 355.3 | 20.85 | 1.68 | 9.93 | 12.71 | 15.3 | Au1rxx-base64 | 149.22.87.241 |
| 68.88 | shadowsocks | 301.9 | 364.6 | 20.79 | 1.33 | 9.93 | 12.71 | 15.3 | Au1rxx-base64 | 149.22.87.204 |
| 68.35 | trojan | 305.3 | 647.7 | 20.71 | 0.0 | 10.0 | 12.97 | 11.22 | mheidari-all | 64.94.95.118 |
| 67.79 | shadowsocks | 369.4 | 734.1 | 19.23 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 37.19.198.236 |
| 67.28 | vless | 288.3 | 421.2 | 21.11 | 0.0 | 10.0 | 5.39 | 16.52 | Surfboard-tg-mixed | 173.245.59.35 |
| 67.16 | shadowsocks | 363.2 | 738.1 | 19.37 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 37.19.198.160 |
| 67.06 | vmess | 246.2 | 656.0 | 22.08 | 0.0 | 10.0 | 13.12 | 6.36 | Barabama-yudou | 82.198.246.233 |
| 67.06 | shadowsocks | 379.2 | 764.6 | 19.0 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 37.19.198.244 |
| 66.78 | shadowsocks | 292.6 | 659.1 | 21.01 | 0.0 | 10.0 | 12.71 | 15.3 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.836 | 0.758 | 219 | 5705 | prefer |
| Au1rxx-base64 | 0.746 | 0.75 | 60 | 106 | prefer |
| mheidari-all | 0.724 | 0.647 | 85 | 15877 | prefer |
| DeltaKronecker-all | 0.694 | 0.615 | 205 | 7467 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 179 | observe |
| nscl5-all | 0.301 | 1.0 | 1 | 1162 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| ermaozi | 0.256 | 1.0 | 1 | 20 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4254 | observe |
| Epodonios-all | 0.255 | None | 0 | 6497 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6693 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4232 | observe |
| barry-far-vless | 0.255 | None | 0 | 4756 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 77 |
| geo | TimeoutError | - | 30 |
| 204 | ProxyError | - | 23 |
| 204 | ClientOSError | - | 11 |
| geo | ClientOSError | - | 10 |
| cn-block | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| geo | ProxyError | - | 5 |
| speed | TimeoutError | - | 4 |
| 204 | TimeoutError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
