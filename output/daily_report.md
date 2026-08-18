# AutoNodes 每日报告

生成时间：2026-08-18 06:41:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 91014 |
| 去重后节点数 | 23825 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1327 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23825 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 35.2 |
| geo | 1.1 |
| probe | 72.6 |
| real_test | 257.4 |
| tcp | 35.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 24 | 22 | 2 | 91.7% |
| shadowsocks | 168 | 153 | 15 | 91.1% |
| socks | 8 | 5 | 3 | 62.5% |
| trojan | 906 | 882 | 24 | 97.4% |
| tuic | 1 | 1 | 0 | 100.0% |
| vless | 444 | 135 | 309 | 30.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 108 |
| speed:TimeoutError | 101 |
| geo:ClientOSError | 53 |
| speed:ClientOSError | 26 |
| 204:ProxyError | 22 |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 13 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4196 |
| ConnectionRefusedError | 894 |
| gaierror | 440 |
| OSError | 223 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.998 | prefer | 168 | 0.923 | 6109 |
| Au1rxx-base64 | 0.879 | prefer | 837 | 0.823 | 1408 |
| mheidari-all | 0.742 | prefer | 524 | 0.662 | 21284 |
| nscl5-all | 0.438 | observe | 3 | 1.0 | 2992 |
| DeltaKronecker-all | 0.37 | observe | 16 | 0.312 | 5725 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6329 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5068 |
| Epodonios-all | 0.255 | observe | 0 | None | 6729 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3986 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.312 | 5 | 11 | 16 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.662 | 347 | 177 | 524 |
| Au1rxx-base64 | 0.823 | 689 | 148 | 837 |
| Surfboard-tg-mixed | 0.923 | 155 | 13 | 168 |
| nscl5-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21284 | yes | 4.22 | 0 |
| SoliSpirit-all | 6856 | yes | 2.19 | 0 |
| Epodonios-all | 6729 | yes | 0.24 | 0 |
| xiaoji235-airport-v2ray-all | 6329 | yes | 1.04 | 0 |
| Surfboard-tg-mixed | 6109 | yes | 2.75 | 0 |
| DeltaKronecker-all | 5725 | yes | 4.61 | 0 |
| barry-far-vless | 5077 | yes | 1.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 5068 | yes | 1.44 | 0 |
| Surfboard-tg-vless | 4779 | yes | 2.93 | 0 |
| mahdibland-V2RayAggregator | 4045 | yes | 2.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 162 |
| speed | 127 |
| 204 | 39 |
| cn-block | 25 |
