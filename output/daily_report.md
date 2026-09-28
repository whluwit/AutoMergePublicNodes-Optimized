# AutoNodes 每日报告

生成时间：2026-09-28 12:54:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 95986 |
| 去重后节点数 | 26747 |
| TCP 可达数 | 3000 |
| 真测通过数 | 435 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26747 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 85.7 |
| geo | 1.5 |
| probe | 273.8 |
| real_test | 211.7 |
| tcp | 44.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 50 | 29 | 21 | 58.0% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 158 | 135 | 23 | 85.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 23 | 18 | 5 | 78.3% |
| vless | 290 | 229 | 61 | 79.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 25 |
| 204:ProxyError | 18 |
| speed:ClientOSError | 18 |
| 204:TimeoutError | 15 |
| geo:TimeoutError | 9 |
| 204:ProxyConnectionError | 7 |
| speed:TimeoutError | 6 |
| geo:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6076 |
| ConnectionRefusedError | 970 |
| gaierror | 416 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.924 | prefer | 285 | 0.863 | 1596 |
| mheidari-all | 0.866 | prefer | 54 | 0.796 | 22474 |
| Surfboard-tg-mixed | 0.811 | prefer | 143 | 0.734 | 7046 |
| ermaozi | 0.68 | observe | 52 | 0.673 | 344 |
| DeltaKronecker-all | 0.4 | observe | 4 | 0.75 | 5428 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 80 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5326 |
| Epodonios-all | 0.255 | observe | 0 | None | 7414 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.161 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| ermaozi | 0.673 | 35 | 17 | 52 |
| Surfboard-tg-mixed | 0.734 | 105 | 38 | 143 |
| DeltaKronecker-all | 0.75 | 3 | 1 | 4 |
| mheidari-all | 0.796 | 43 | 11 | 54 |
| Au1rxx-base64 | 0.863 | 246 | 39 | 285 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22474 | yes | 5.77 | 0 |
| SoliSpirit-all | 9417 | yes | 3.74 | 0 |
| Epodonios-all | 7414 | yes | 5.19 | 0 |
| Surfboard-tg-mixed | 7046 | yes | 4.27 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.0 | 0 |
| barry-far-vless | 5752 | yes | 1.01 | 0 |
| Surfboard-tg-vless | 5638 | yes | 3.13 | 0 |
| DeltaKronecker-all | 5428 | yes | 6.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 5326 | yes | 0.78 | 0 |
| mahdibland-V2RayAggregator | 4185 | yes | 3.25 | 0 |

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
| 204 | 43 |
| cn-block | 30 |
| speed | 24 |
| geo | 14 |
