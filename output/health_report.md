# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 21:13:33 |
| 运行耗时 | 569.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98160 |
| 去重后节点 | 26542 |
| TCP 可达 | 3000 |
| 真实可用 | 400 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26542 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 43.1 |
| probe | 245.8 |
| real_test | 197.1 |
| generate | 75.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60218 |
| vmess | 14913 |
| shadowsocks | 11303 |
| trojan | 9239 |
| hysteria2 | 1598 |
| http | 592 |
| shadowsocksr | 174 |
| socks | 76 |
| anytls | 22 |
| hysteria | 18 |
| tuic | 7 |

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
| 82.43 | hysteria2 | 279.1 | 743.0 | 21.32 | 0.0 | 9.01 | 13.42 | 19.78 | Au1rxx-base64 | 159.223.157.129 |
| 82.12 | vless | 245.5 | 686.0 | 22.09 | 0.0 | 8.95 | 11.3 | 19.78 | Au1rxx-base64 | 79.141.172.154 |
| 81.58 | vless | 271.5 | 698.4 | 21.49 | 0.0 | 9.01 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.225 |
| 80.85 | vless | 297.0 | 716.7 | 20.9 | 0.0 | 9.01 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.235 |
| 80.68 | vless | 308.6 | 682.5 | 20.63 | 0.0 | 8.97 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.89 |
| 80.58 | vless | 309.7 | 755.2 | 20.61 | 0.0 | 9.0 | 11.3 | 19.78 | Au1rxx-base64 | 66.70.179.198 |
| 79.76 | vless | 289.0 | 683.0 | 21.09 | 0.0 | 9.0 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.179 |
| 79.6 | vless | 369.4 | 876.2 | 19.23 | 0.0 | 10.0 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.35 |
| 79.49 | vless | 308.4 | 686.3 | 20.64 | 0.0 | 9.06 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.104 |
| 79.34 | vless | 367.8 | 976.9 | 19.26 | 0.0 | 9.0 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.95 |
| 79.07 | vless | 373.5 | 791.8 | 19.13 | 0.0 | 8.97 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.224 |
| 78.64 | vless | 398.3 | 945.9 | 18.56 | 0.0 | 9.0 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.133 |
| 78.6 | vless | 401.1 | 1088.1 | 18.49 | 0.0 | 9.03 | 11.3 | 19.78 | Au1rxx-base64 | 185.95.231.233 |
| 78.53 | vless | 406.1 | 1038.7 | 18.38 | 0.0 | 9.07 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.184 |
| 78.39 | vless | 313.0 | 692.7 | 20.53 | 0.0 | 8.92 | 11.3 | 19.78 | Au1rxx-base64 | 198.251.78.29 |
| 78.31 | vless | 314.3 | 702.4 | 20.5 | 0.0 | 8.95 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.90 |
| 78.18 | shadowsocks | 315.6 | 843.6 | 20.47 | 0.0 | 8.91 | 13.02 | 19.78 | Au1rxx-base64 | 198.98.53.130 |
| 78.11 | vless | 270.0 | 715.0 | 21.53 | 0.0 | 10.0 | 11.3 | 19.78 | Au1rxx-base64 | 162.35.96.39 |
| 78.02 | vless | 314.1 | 692.9 | 20.51 | 0.0 | 9.01 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.74 |
| 77.8 | vless | 322.1 | 846.3 | 20.32 | 0.0 | 9.06 | 11.3 | 19.78 | Au1rxx-base64 | 169.40.42.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | 0.921 | 265 | 1629 | prefer |
| Surfboard-tg-mixed | 0.801 | 0.729 | 59 | 7419 | prefer |
| mheidari-all | 0.702 | 0.624 | 170 | 22744 | prefer |
| ermaozi | 0.321 | 0.385 | 13 | 298 | observe |
| ermaozi-get_subscribe | 0.267 | 1.0 | 1 | 304 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5307 | observe |
| Epodonios-all | 0.255 | None | 0 | 7888 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9109 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5963 | observe |
| barry-far-vless | 0.255 | None | 0 | 6215 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1629 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 32 |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 18 |
| 204 | ProxyConnectionError | - | 7 |
| 204 | ClientOSError | - | 3 |
| speed | ClientOSError | - | 3 |
| speed | TimeoutError | - | 3 |
| geo | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
