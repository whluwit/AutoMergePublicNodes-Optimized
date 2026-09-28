# AutoNodes 每日报告

生成时间：2026-09-28 23:02:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97528 |
| 去重后节点数 | 27014 |
| TCP 可达数 | 3000 |
| 真测通过数 | 432 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27014 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 74.9 |
| geo | 1.5 |
| probe | 242.9 |
| real_test | 155.5 |
| tcp | 44.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 35 | 17 | 18 | 48.6% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 150 | 139 | 11 | 92.7% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 11 | 9 | 2 | 81.8% |
| vless | 300 | 240 | 60 | 80.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 32 |
| 204:ProxyError | 17 |
| cn-block:TimeoutError | 14 |
| 204:TimeoutError | 9 |
| speed:TimeoutError | 5 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 4 |
| cn-block:ClientOSError | 4 |
| geo:TimeoutError | 3 |
| geo:ClientOSError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5586 |
| ConnectionRefusedError | 1005 |
| gaierror | 444 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.922 | prefer | 351 | 0.858 | 1674 |
| mheidari-all | 0.901 | prefer | 115 | 0.826 | 22856 |
| Surfboard-tg-mixed | 0.734 | prefer | 14 | 0.857 | 7142 |
| ermaozi | 0.514 | observe | 30 | 0.5 | 344 |
| DeltaKronecker-all | 0.465 | observe | 7 | 0.714 | 5428 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 121 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5326 |
| Epodonios-all | 0.255 | observe | 0 | None | 7535 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9706 |

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
| downweight | ermaozi-get_subscribe | 0.219 | 6 | 0.333 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.333 | 2 | 4 | 6 |
| ermaozi | 0.5 | 15 | 15 | 30 |
| DeltaKronecker-all | 0.714 | 5 | 2 | 7 |
| mheidari-all | 0.826 | 95 | 20 | 115 |
| Surfboard-tg-mixed | 0.857 | 12 | 2 | 14 |
| Au1rxx-base64 | 0.858 | 301 | 50 | 351 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22856 | yes | 6.38 | 0 |
| SoliSpirit-all | 9706 | yes | 3.97 | 0 |
| Epodonios-all | 7535 | yes | 3.6 | 0 |
| Surfboard-tg-mixed | 7142 | yes | 4.68 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.87 | 0 |
| barry-far-vless | 6027 | yes | 3.25 | 0 |
| Surfboard-tg-vless | 5799 | yes | 4.14 | 0 |
| DeltaKronecker-all | 5428 | yes | 6.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 5326 | yes | 2.79 | 0 |
| mahdibland-V2RayAggregator | 4237 | yes | 0.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 37 |
| 204 | 31 |
| cn-block | 22 |
| geo | 4 |
