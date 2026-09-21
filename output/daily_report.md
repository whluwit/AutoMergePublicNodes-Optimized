# AutoNodes 每日报告

生成时间：2026-09-21 11:58:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 84502 |
| 去重后节点数 | 23399 |
| TCP 可达数 | 3000 |
| 真测通过数 | 464 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23399 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 78.8 |
| geo | 1.4 |
| probe | 214.2 |
| real_test | 215.7 |
| tcp | 38.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 41 | 25 | 16 | 61.0% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 165 | 151 | 14 | 91.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 44 | 20 | 24 | 45.5% |
| vless | 371 | 249 | 122 | 67.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 32 |
| geo:TimeoutError | 31 |
| 204:TimeoutError | 27 |
| 204:ProxyError | 19 |
| cn-block:TimeoutError | 16 |
| cn-block:ClientOSError | 13 |
| speed:TimeoutError | 13 |
| speed:ClientOSError | 11 |
| 204:ProxyConnectionError | 9 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5406 |
| ConnectionRefusedError | 791 |
| gaierror | 293 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.944 | prefer | 42 | 0.881 | 16192 |
| Au1rxx-base64 | 0.919 | prefer | 277 | 0.856 | 1649 |
| Surfboard-tg-mixed | 0.685 | observe | 213 | 0.606 | 7246 |
| DeltaKronecker-all | 0.667 | observe | 61 | 0.59 | 6181 |
| ermaozi | 0.6 | observe | 39 | 0.59 | 355 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 108 |
| Epodonios-all | 0.255 | observe | 0 | None | 7697 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8880 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5845 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| 10ium-HighSpeed | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| ermaozi | 0.59 | 23 | 16 | 39 |
| DeltaKronecker-all | 0.59 | 36 | 25 | 61 |
| Surfboard-tg-mixed | 0.606 | 129 | 84 | 213 |
| Au1rxx-base64 | 0.856 | 237 | 40 | 277 |
| mheidari-all | 0.881 | 37 | 5 | 42 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16192 | yes | 5.07 | 0 |
| SoliSpirit-all | 8880 | yes | 4.57 | 0 |
| Epodonios-all | 7697 | yes | 4.61 | 0 |
| Surfboard-tg-mixed | 7246 | yes | 4.07 | 0 |
| DeltaKronecker-all | 6181 | yes | 5.89 | 0 |
| barry-far-vless | 6061 | yes | 3.55 | 0 |
| Surfboard-tg-vless | 5845 | yes | 3.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 2.92 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 0.35 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 3.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 63 |
| 204 | 58 |
| cn-block | 32 |
| speed | 26 |
