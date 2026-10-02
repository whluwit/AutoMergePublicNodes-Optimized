# AutoNodes 每日报告

生成时间：2026-10-02 04:01:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 98613 |
| 去重后节点数 | 27530 |
| TCP 可达数 | 3000 |
| 真测通过数 | 465 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27530 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 82.9 |
| geo | 1.6 |
| probe | 314.6 |
| real_test | 493.8 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 3 | 1 | 75.0% |
| http | 24 | 13 | 11 | 54.2% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 175 | 170 | 5 | 97.1% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 34 | 26 | 8 | 76.5% |
| vless | 586 | 234 | 352 | 39.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 178 |
| speed:TimeoutError | 99 |
| geo:ClientOSError | 29 |
| speed:ClientOSError | 23 |
| cn-block:TimeoutError | 12 |
| 204:TimeoutError | 11 |
| 204:ProxyConnectionError | 10 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6756 |
| ConnectionRefusedError | 1045 |
| gaierror | 411 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | prefer | 278 | 0.917 | 1741 |
| Surfboard-tg-mixed | 0.921 | prefer | 61 | 0.852 | 7165 |
| ermaozi | 0.543 | observe | 25 | 0.52 | 618 |
| mheidari-all | 0.386 | observe | 469 | 0.305 | 23308 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7654 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9195 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5778 |
| barry-far-vless | 0.255 | observe | 0 | None | 6015 |

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
| downweight | DeltaKronecker-all | 0.148 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 6 | 6 |
| mheidari-all | 0.305 | 143 | 326 | 469 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.52 | 13 | 12 | 25 |
| Surfboard-tg-mixed | 0.852 | 52 | 9 | 61 |
| Au1rxx-base64 | 0.917 | 255 | 23 | 278 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23308 | yes | 6.94 | 0 |
| SoliSpirit-all | 9195 | yes | 4.12 | 0 |
| Epodonios-all | 7654 | yes | 3.23 | 0 |
| Surfboard-tg-mixed | 7165 | yes | 3.79 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.25 | 0 |
| barry-far-vless | 6015 | yes | 3.67 | 0 |
| Surfboard-tg-vless | 5778 | yes | 4.57 | 0 |
| DeltaKronecker-all | 5603 | yes | 5.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 2.44 | 0 |
| mahdibland-V2RayAggregator | 4310 | yes | 3.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 209 |
| speed | 122 |
| 204 | 30 |
| cn-block | 19 |
