# AutoNodes 每日报告

生成时间：2026-07-18 13:11:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 81258 |
| 去重后节点数 | 22073 |
| TCP 可达数 | 3000 |
| 真测通过数 | 846 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22073 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 31.6 |
| geo | 1.1 |
| probe | 77.1 |
| real_test | 241.4 |
| tcp | 32.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 162 | 132 | 30 | 81.5% |
| socks | 13 | 9 | 4 | 69.2% |
| trojan | 629 | 571 | 58 | 90.8% |
| vless | 772 | 94 | 678 | 12.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 388 |
| geo:TimeoutError | 228 |
| geo:ClientOSError | 47 |
| cn-block:TimeoutError | 26 |
| 204:ProxyError | 19 |
| 204:TimeoutError | 18 |
| 204:ClientOSError | 11 |
| speed:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| cn-block:ProxyError | 7 |
| geo:ProxyError | 6 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4318 |
| ConnectionRefusedError | 688 |
| OSError | 216 |
| gaierror | 215 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.925 | prefer | 418 | 0.847 | 19072 |
| Au1rxx-base64 | 0.883 | prefer | 136 | 0.882 | 150 |
| Surfboard-tg-mixed | 0.815 | prefer | 149 | 0.738 | 5677 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 4321 |
| DeltaKronecker-all | 0.335 | observe | 870 | 0.254 | 4096 |
| nscl5-all | 0.287 | observe | 2 | 0.5 | 1976 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4371 |
| Epodonios-all | 0.255 | observe | 0 | None | 6767 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.254 | 221 | 649 | 870 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.738 | 110 | 39 | 149 |
| mheidari-all | 0.847 | 354 | 64 | 418 |
| Au1rxx-base64 | 0.882 | 120 | 16 | 136 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19072 | yes | 3.64 | 0 |
| SoliSpirit-all | 7257 | yes | 3.07 | 0 |
| Epodonios-all | 6767 | yes | 2.62 | 0 |
| Surfboard-tg-mixed | 5677 | yes | 2.43 | 0 |
| mahdibland-V2RayAggregator | 5334 | yes | 1.56 | 0 |
| barry-far-vless | 4927 | yes | 1.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 4371 | yes | 1.75 | 0 |
| xiaoji235-airport-v2ray-all | 4321 | yes | 0.8 | 0 |
| Surfboard-tg-vless | 4291 | yes | 2.03 | 0 |
| DeltaKronecker-all | 4096 | yes | 3.36 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 400 |
| geo | 281 |
| 204 | 48 |
| cn-block | 41 |
