# AutoNodes 每日报告

生成时间：2026-09-29 12:10:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97025 |
| 去重后节点数 | 26954 |
| TCP 可达数 | 3000 |
| 真测通过数 | 473 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26954 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 87.2 |
| geo | 1.5 |
| probe | 268.4 |
| real_test | 189.0 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 55 | 37 | 18 | 67.3% |
| hysteria2 | 24 | 22 | 2 | 91.7% |
| shadowsocks | 178 | 159 | 19 | 89.3% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 31 | 21 | 10 | 67.7% |
| vless | 327 | 232 | 95 | 70.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 31 |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 27 |
| geo:TimeoutError | 15 |
| 204:ProxyError | 13 |
| 204:ProxyConnectionError | 12 |
| speed:TimeoutError | 6 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6125 |
| ConnectionRefusedError | 1008 |
| gaierror | 416 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.903 | prefer | 340 | 0.841 | 1599 |
| mheidari-all | 0.839 | prefer | 56 | 0.768 | 22883 |
| Surfboard-tg-mixed | 0.729 | prefer | 152 | 0.651 | 7053 |
| ermaozi | 0.681 | observe | 55 | 0.673 | 354 |
| DeltaKronecker-all | 0.543 | observe | 13 | 0.615 | 5528 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5314 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9541 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5690 |
| barry-far-vless | 0.255 | observe | 0 | None | 5869 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Epodonios-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.615 | 8 | 5 | 13 |
| Surfboard-tg-mixed | 0.651 | 99 | 53 | 152 |
| ermaozi | 0.673 | 37 | 18 | 55 |
| mheidari-all | 0.768 | 43 | 13 | 56 |
| Au1rxx-base64 | 0.841 | 286 | 54 | 340 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22883 | yes | 6.48 | 0 |
| SoliSpirit-all | 9541 | yes | 2.11 | 0 |
| Epodonios-all | 7502 | yes | 3.47 | 0 |
| Surfboard-tg-mixed | 7053 | yes | 4.49 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.85 | 0 |
| barry-far-vless | 5869 | yes | 1.26 | 0 |
| Surfboard-tg-vless | 5690 | yes | 3.96 | 0 |
| DeltaKronecker-all | 5528 | yes | 4.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 5314 | yes | 0.74 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 3.05 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 55 |
| speed | 37 |
| cn-block | 34 |
| geo | 19 |
