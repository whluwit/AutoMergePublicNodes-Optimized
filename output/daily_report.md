# AutoNodes 每日报告

生成时间：2026-08-18 01:02:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 80342 |
| 去重后节点数 | 23001 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1289 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23001 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 25.2 |
| geo | 0.9 |
| probe | 72.6 |
| real_test | 237.5 |
| tcp | 35.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 36 | 35 | 1 | 97.2% |
| shadowsocks | 160 | 150 | 10 | 93.8% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 821 | 812 | 9 | 98.9% |
| tuic | 1 | 1 | 0 | 100.0% |
| vless | 336 | 155 | 181 | 46.1% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 85 |
| speed:TimeoutError | 46 |
| geo:ClientOSError | 25 |
| speed:ClientOSError | 13 |
| cn-block:TimeoutError | 10 |
| 204:TimeoutError | 9 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4489 |
| ConnectionRefusedError | 961 |
| gaierror | 390 |
| OSError | 27 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 438 | 0.966 | 1475 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.95 | prefer | 703 | 0.871 | 16056 |
| Surfboard-tg-mixed | 0.832 | prefer | 139 | 0.755 | 6145 |
| DeltaKronecker-all | 0.339 | observe | 79 | 0.253 | 6368 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 179 |
| Epodonios-all | 0.255 | observe | 0 | None | 6777 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3984 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6825 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.253 | 20 | 59 | 79 |
| Surfboard-tg-mixed | 0.755 | 105 | 34 | 139 |
| mheidari-all | 0.871 | 612 | 91 | 703 |
| Au1rxx-base64 | 0.966 | 423 | 15 | 438 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16056 | yes | 4.68 | 0 |
| SoliSpirit-all | 6825 | yes | 1.85 | 0 |
| Epodonios-all | 6777 | yes | 2.69 | 0 |
| DeltaKronecker-all | 6368 | yes | 4.59 | 0 |
| Surfboard-tg-mixed | 6145 | yes | 3.26 | 0 |
| barry-far-vless | 5165 | yes | 1.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 5085 | yes | 1.5 | 0 |
| Surfboard-tg-vless | 4833 | yes | 3.44 | 0 |
| mahdibland-V2RayAggregator | 4027 | yes | 2.5 | 0 |
| MatinGhanbari-all-sub | 3984 | yes | 1.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 110 |
| speed | 59 |
| 204 | 17 |
| cn-block | 16 |
