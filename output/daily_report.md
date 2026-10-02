# AutoNodes 每日报告

生成时间：2026-10-02 11:56:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97759 |
| 去重后节点数 | 26962 |
| TCP 可达数 | 3000 |
| 真测通过数 | 335 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26962 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 81.6 |
| geo | 1.0 |
| probe | 285.2 |
| real_test | 160.1 |
| tcp | 46.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 6 | 18 | 25.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 144 | 125 | 19 | 86.8% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 23 | 20 | 3 | 87.0% |
| vless | 228 | 165 | 63 | 72.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 19 |
| 204:ProxyConnectionError | 18 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 9 |
| geo:TimeoutError | 8 |
| geo:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| speed:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6029 |
| ConnectionRefusedError | 1140 |
| gaierror | 446 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.894 | prefer | 258 | 0.829 | 1676 |
| mheidari-all | 0.88 | prefer | 53 | 0.811 | 23059 |
| Surfboard-tg-mixed | 0.784 | prefer | 96 | 0.708 | 7176 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 4981 |
| ermaozi | 0.294 | observe | 24 | 0.25 | 618 |
| ermaozi-get_subscribe | 0.274 | observe | 1 | 1.0 | 475 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5276 |
| Epodonios-all | 0.255 | observe | 0 | None | 7676 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.25 | 6 | 18 | 24 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.708 | 68 | 28 | 96 |
| mheidari-all | 0.811 | 43 | 10 | 53 |
| Au1rxx-base64 | 0.829 | 214 | 44 | 258 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23059 | yes | 6.38 | 0 |
| SoliSpirit-all | 9233 | yes | 4.27 | 0 |
| Epodonios-all | 7676 | yes | 1.04 | 0 |
| Surfboard-tg-mixed | 7176 | yes | 4.43 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.33 | 0 |
| barry-far-vless | 6070 | yes | 1.37 | 0 |
| Surfboard-tg-vless | 5828 | yes | 3.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5276 | yes | 0.78 | 0 |
| DeltaKronecker-all | 4981 | yes | 6.65 | 0 |
| mahdibland-V2RayAggregator | 4310 | yes | 3.52 | 0 |

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
| 204 | 51 |
| cn-block | 28 |
| geo | 13 |
| speed | 12 |
