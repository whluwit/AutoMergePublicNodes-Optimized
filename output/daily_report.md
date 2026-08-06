# AutoNodes 每日报告

生成时间：2026-08-06 08:31:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 89018 |
| 去重后节点数 | 24407 |
| TCP 可达数 | 3000 |
| 真测通过数 | 459 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24407 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 33.4 |
| geo | 1.0 |
| probe | 51.7 |
| real_test | 99.7 |
| tcp | 36.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 17 | 3 | 85.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 159 | 148 | 11 | 93.1% |
| socks | 19 | 13 | 6 | 68.4% |
| trojan | 164 | 156 | 8 | 95.1% |
| vless | 185 | 101 | 84 | 54.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 36 |
| geo:ClientOSError | 17 |
| 204:ProxyError | 13 |
| speed:TimeoutError | 13 |
| 204:TimeoutError | 13 |
| cn-block:TimeoutError | 6 |
| speed:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4799 |
| ConnectionRefusedError | 821 |
| gaierror | 335 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 358 | 0.955 | 1409 |
| zhangkai | 0.819 | prefer | 20 | 0.85 | 25 |
| Surfboard-tg-mixed | 0.693 | observe | 135 | 0.615 | 5904 |
| mheidari-all | 0.423 | observe | 33 | 0.333 | 20781 |
| DeltaKronecker-all | 0.32 | observe | 23 | 0.217 | 5897 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 5214 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5219 |
| Epodonios-all | 0.255 | observe | 0 | None | 6505 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7196 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.217 | 5 | 18 | 23 |
| mheidari-all | 0.333 | 11 | 22 | 33 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.615 | 83 | 52 | 135 |
| zhangkai | 0.85 | 17 | 3 | 20 |
| Au1rxx-base64 | 0.955 | 342 | 16 | 358 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20781 | yes | 4.23 | 0 |
| SoliSpirit-all | 7196 | yes | 3.0 | 0 |
| Epodonios-all | 6505 | yes | 4.57 | 0 |
| Surfboard-tg-mixed | 5904 | yes | 2.5 | 0 |
| DeltaKronecker-all | 5897 | yes | 4.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 5219 | yes | 1.39 | 0 |
| xiaoji235-airport-v2ray-all | 5214 | yes | 0.92 | 0 |
| mahdibland-V2RayAggregator | 5212 | yes | 0.71 | 0 |
| barry-far-vless | 5049 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 4739 | yes | 2.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 54 |
| 204 | 29 |
| speed | 19 |
| cn-block | 11 |
