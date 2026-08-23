# AutoNodes 每日报告

生成时间：2026-08-23 12:34:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 77785 |
| 去重后节点数 | 21407 |
| TCP 可达数 | 3000 |
| 真测通过数 | 699 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21407 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 40.6 |
| geo | 1.4 |
| probe | 61.9 |
| real_test | 156.1 |
| tcp | 34.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 210 | 197 | 13 | 93.8% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 27 | 23 | 4 | 85.2% |
| vless | 415 | 345 | 70 | 83.1% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 22 |
| geo:TimeoutError | 20 |
| speed:TimeoutError | 11 |
| speed:ClientOSError | 8 |
| 204:ProxyError | 8 |
| 204:TimeoutError | 8 |
| geo:ClientOSError | 6 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4524 |
| ConnectionRefusedError | 864 |
| gaierror | 421 |
| OSError | 22 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| Au1rxx-base64 | 0.985 | prefer | 432 | 0.917 | 1745 |
| Surfboard-tg-mixed | 0.906 | prefer | 142 | 0.831 | 6381 |
| DeltaKronecker-all | 0.794 | prefer | 54 | 0.722 | 5415 |
| mheidari-all | 0.78 | prefer | 48 | 0.708 | 14522 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4989 |
| Epodonios-all | 0.255 | observe | 0 | None | 6941 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3990 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6992 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5191 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.708 | 34 | 14 | 48 |
| DeltaKronecker-all | 0.722 | 39 | 15 | 54 |
| Surfboard-tg-mixed | 0.831 | 118 | 24 | 142 |
| Au1rxx-base64 | 0.917 | 396 | 36 | 432 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14522 | yes | 1.9 | 0 |
| SoliSpirit-all | 6992 | yes | 4.89 | 0 |
| Epodonios-all | 6941 | yes | 4.85 | 0 |
| Surfboard-tg-mixed | 6381 | yes | 4.09 | 0 |
| barry-far-vless | 5469 | yes | 2.73 | 0 |
| DeltaKronecker-all | 5415 | yes | 4.97 | 0 |
| Surfboard-tg-vless | 5191 | yes | 3.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 4989 | yes | 2.95 | 0 |
| mahdibland-V2RayAggregator | 4094 | yes | 1.97 | 0 |
| MatinGhanbari-all-sub | 3990 | yes | 3.05 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 28 |
| geo | 26 |
| speed | 19 |
| 204 | 18 |
