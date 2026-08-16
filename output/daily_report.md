# AutoNodes 每日报告

生成时间：2026-08-16 18:26:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 79830 |
| 去重后节点数 | 21997 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1071 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21997 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 37.8 |
| geo | 1.1 |
| probe | 62.2 |
| real_test | 192.5 |
| tcp | 33.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 24 | 21 | 3 | 87.5% |
| shadowsocks | 113 | 104 | 9 | 92.0% |
| trojan | 569 | 566 | 3 | 99.5% |
| vless | 327 | 251 | 76 | 76.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 17 |
| speed:TimeoutError | 15 |
| geo:TimeoutError | 11 |
| 204:ProxyError | 9 |
| geo:ClientOSError | 7 |
| 204:ClientOSError | 6 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4330 |
| ConnectionRefusedError | 819 |
| gaierror | 371 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 765 | 0.954 | 1997 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.933 | prefer | 114 | 0.86 | 5794 |
| mheidari-all | 0.856 | prefer | 145 | 0.779 | 17005 |
| 10ium-ScrapeCategorize-Vless | 0.287 | observe | 2 | 0.5 | 4990 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 174 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1997 |
| Epodonios-all | 0.255 | observe | 0 | None | 6468 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3985 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7449 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.143 | 1 | 6 | 7 |
| 10ium-ScrapeCategorize-Vless | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.779 | 113 | 32 | 145 |
| Surfboard-tg-mixed | 0.86 | 98 | 16 | 114 |
| Au1rxx-base64 | 0.954 | 730 | 35 | 765 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17005 | yes | 4.54 | 0 |
| SoliSpirit-all | 7449 | yes | 4.31 | 0 |
| Epodonios-all | 6468 | yes | 4.8 | 0 |
| Surfboard-tg-mixed | 5794 | yes | 3.37 | 0 |
| DeltaKronecker-all | 5092 | yes | 5.14 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 3.04 | 0 |
| barry-far-vless | 4856 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 4518 | yes | 3.56 | 0 |
| mahdibland-V2RayAggregator | 4025 | yes | 2.84 | 0 |
| MatinGhanbari-all-sub | 3985 | yes | 3.12 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 32 |
| cn-block | 23 |
| geo | 18 |
| speed | 18 |
