# AutoNodes 每日报告

生成时间：2026-09-17 16:15:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 5/101 |
| 原始节点数 | 84819 |
| 去重后节点数 | 23036 |
| TCP 可达数 | 3000 |
| 真测通过数 | 434 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23036 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 42.1 |
| geo | 1.5 |
| probe | 222.0 |
| real_test | 227.4 |
| tcp | 38.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 37 | 22 | 15 | 59.5% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 162 | 147 | 15 | 90.7% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 7 | 5 | 2 | 71.4% |
| vless | 352 | 242 | 110 | 68.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 34 |
| 204:ProxyError | 28 |
| 204:TimeoutError | 21 |
| geo:TimeoutError | 19 |
| cn-block:TimeoutError | 13 |
| speed:ClientOSError | 12 |
| cn-block:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5388 |
| ConnectionRefusedError | 823 |
| gaierror | 355 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.915 | prefer | 264 | 0.852 | 1626 |
| DeltaKronecker-all | 0.762 | prefer | 105 | 0.686 | 5931 |
| Surfboard-tg-mixed | 0.74 | prefer | 95 | 0.663 | 7430 |
| mheidari-all | 0.738 | prefer | 77 | 0.662 | 16008 |
| ermaozi | 0.724 | prefer | 29 | 0.724 | 357 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 115 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5093 |
| Epodonios-all | 0.255 | observe | 0 | None | 7888 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.079 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 7 | 7 |
| mheidari-all | 0.662 | 51 | 26 | 77 |
| Surfboard-tg-mixed | 0.663 | 63 | 32 | 95 |
| DeltaKronecker-all | 0.686 | 72 | 33 | 105 |
| ermaozi | 0.724 | 21 | 8 | 29 |
| Au1rxx-base64 | 0.852 | 225 | 39 | 264 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16008 | yes | 4.27 | 0 |
| SoliSpirit-all | 9477 | yes | 1.88 | 0 |
| Epodonios-all | 7888 | yes | 5.09 | 0 |
| Surfboard-tg-mixed | 7430 | yes | 3.55 | 0 |
| barry-far-vless | 6129 | yes | 0.45 | 0 |
| DeltaKronecker-all | 5931 | yes | 4.59 | 0 |
| Surfboard-tg-vless | 5904 | yes | 3.78 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 0.66 | 0 |
| mahdibland-V2RayAggregator | 4179 | yes | 2.74 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 54 |
| 204 | 51 |
| cn-block | 22 |
| speed | 19 |
