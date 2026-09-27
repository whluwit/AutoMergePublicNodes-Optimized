# AutoNodes 每日报告

生成时间：2026-09-27 20:54:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 95925 |
| 去重后节点数 | 26706 |
| TCP 可达数 | 3000 |
| 真测通过数 | 368 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26706 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 81.4 |
| geo | 1.5 |
| probe | 236.1 |
| real_test | 181.2 |
| tcp | 44.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 36 | 23 | 13 | 63.9% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 151 | 138 | 13 | 91.4% |
| socks | 4 | 1 | 3 | 25.0% |
| vless | 255 | 184 | 71 | 72.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 19 |
| speed:TimeoutError | 17 |
| 204:TimeoutError | 14 |
| geo:TimeoutError | 14 |
| speed:ClientOSError | 13 |
| 204:ProxyError | 11 |
| cn-block:ClientOSError | 6 |
| 204:ProxyConnectionError | 5 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5997 |
| ConnectionRefusedError | 956 |
| gaierror | 372 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.955 | prefer | 94 | 0.883 | 22680 |
| Au1rxx-base64 | 0.869 | prefer | 242 | 0.806 | 1652 |
| Surfboard-tg-mixed | 0.783 | prefer | 89 | 0.708 | 7039 |
| ermaozi | 0.633 | observe | 35 | 0.629 | 289 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 5466 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| ermaozi-get_subscribe | 0.267 | observe | 1 | 1.0 | 299 |
| tg-oneclickvpnkeys | 0.256 | observe | 1 | 1.0 | 13 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7540 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| ermaozi | 0.629 | 22 | 13 | 35 |
| Surfboard-tg-mixed | 0.708 | 63 | 26 | 89 |
| Au1rxx-base64 | 0.806 | 195 | 47 | 242 |
| mheidari-all | 0.883 | 83 | 11 | 94 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22680 | yes | 6.38 | 0 |
| SoliSpirit-all | 9014 | yes | 2.37 | 0 |
| Epodonios-all | 7540 | yes | 5.76 | 0 |
| Surfboard-tg-mixed | 7039 | yes | 4.89 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.56 | 0 |
| barry-far-vless | 5845 | yes | 1.76 | 0 |
| Surfboard-tg-vless | 5608 | yes | 3.45 | 0 |
| DeltaKronecker-all | 5466 | yes | 2.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 0.79 | 0 |
| mahdibland-V2RayAggregator | 4185 | yes | 3.03 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 31 |
| speed | 30 |
| cn-block | 27 |
| geo | 14 |
