# AutoNodes 每日报告

生成时间：2026-09-20 10:40:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 87004 |
| 去重后节点数 | 25137 |
| TCP 可达数 | 3000 |
| 真测通过数 | 450 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25137 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 81.9 |
| geo | 1.4 |
| probe | 232.3 |
| real_test | 217.4 |
| tcp | 40.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 54 | 43 | 11 | 79.6% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 180 | 163 | 17 | 90.6% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 21 | 7 | 14 | 33.3% |
| vless | 343 | 220 | 123 | 64.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 36 |
| geo:TimeoutError | 36 |
| 204:TimeoutError | 20 |
| 204:ProxyError | 18 |
| cn-block:ClientOSError | 18 |
| cn-block:TimeoutError | 16 |
| speed:TimeoutError | 11 |
| speed:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5162 |
| ConnectionRefusedError | 890 |
| gaierror | 384 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | prefer | 289 | 0.824 | 1589 |
| ermaozi | 0.792 | prefer | 52 | 0.788 | 365 |
| mheidari-all | 0.73 | prefer | 78 | 0.654 | 15979 |
| Surfboard-tg-mixed | 0.707 | prefer | 148 | 0.628 | 7138 |
| DeltaKronecker-all | 0.655 | observe | 38 | 0.579 | 6092 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3625 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4315 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 89 |
| Epodonios-all | 0.255 | observe | 0 | None | 7603 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-ScrapeCategorize-Vless | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.143 | 1 | 6 | 7 |
| DeltaKronecker-all | 0.579 | 22 | 16 | 38 |
| Surfboard-tg-mixed | 0.628 | 93 | 55 | 148 |
| mheidari-all | 0.654 | 51 | 27 | 78 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| ermaozi | 0.788 | 41 | 11 | 52 |
| Au1rxx-base64 | 0.824 | 238 | 51 | 289 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15979 | yes | 5.89 | 0 |
| SoliSpirit-all | 8786 | yes | 4.5 | 0 |
| Epodonios-all | 7603 | yes | 4.58 | 0 |
| Surfboard-tg-mixed | 7138 | yes | 4.31 | 0 |
| DeltaKronecker-all | 6092 | yes | 4.11 | 0 |
| barry-far-vless | 5912 | yes | 1.05 | 0 |
| Surfboard-tg-vless | 5693 | yes | 3.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 2.76 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 3.02 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.34 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 73 |
| 204 | 41 |
| cn-block | 37 |
| speed | 18 |
