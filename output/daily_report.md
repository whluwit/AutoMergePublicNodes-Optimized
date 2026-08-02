# AutoNodes 每日报告

生成时间：2026-08-02 02:27:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 78082 |
| 去重后节点数 | 23287 |
| TCP 可达数 | 3000 |
| 真测通过数 | 988 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23287 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 28.0 |
| geo | 1.4 |
| probe | 76.2 |
| real_test | 270.7 |
| tcp | 34.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 146 | 146 | 0 | 100.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 160 | 151 | 9 | 94.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 50 | 36 | 14 | 72.0% |
| vless | 1328 | 632 | 696 | 47.6% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 293 |
| speed:ClientOSError | 160 |
| speed:TimeoutError | 78 |
| geo:ClientOSError | 77 |
| cn-block:TimeoutError | 67 |
| 204:ProxyError | 20 |
| cn-block:ProxyError | 9 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 6 |
| 204:TimeoutError | 5 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4737 |
| ConnectionRefusedError | 794 |
| gaierror | 281 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 147 | 1.0 | 194 |
| Au1rxx-base64 | 0.937 | prefer | 526 | 0.875 | 1599 |
| Surfboard-tg-mixed | 0.625 | observe | 20 | 0.55 | 5166 |
| DeltaKronecker-all | 0.45 | observe | 987 | 0.37 | 5502 |
| xiaoji235-airport-v2ray-all | 0.343 | observe | 3 | 0.667 | 1861 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5391 |
| Epodonios-all | 0.255 | observe | 0 | None | 5783 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6590 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.128 | observe | 1 | 0.0 | 0 | 13 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.21 | 21 | 0.095 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.095 | 2 | 19 | 21 |
| DeltaKronecker-all | 0.37 | 365 | 622 | 987 |
| Surfboard-tg-mixed | 0.55 | 11 | 9 | 20 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.875 | 460 | 66 | 526 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16656 | yes | 4.75 | 0 |
| SoliSpirit-all | 6590 | yes | 4.41 | 0 |
| Epodonios-all | 5783 | yes | 5.25 | 0 |
| DeltaKronecker-all | 5502 | yes | 5.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 5391 | yes | 2.74 | 0 |
| Surfboard-tg-mixed | 5166 | yes | 4.3 | 0 |
| mahdibland-V2RayAggregator | 5071 | yes | 2.88 | 0 |
| barry-far-vless | 4431 | yes | 1.82 | 0 |
| Surfboard-tg-vless | 4054 | yes | 3.8 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 2.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 371 |
| speed | 239 |
| cn-block | 82 |
| 204 | 31 |
