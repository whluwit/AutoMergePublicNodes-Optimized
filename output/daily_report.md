# AutoNodes 每日报告

生成时间：2026-08-24 01:04:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78342 |
| 去重后节点数 | 21491 |
| TCP 可达数 | 3000 |
| 真测通过数 | 740 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21491 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 31.7 |
| geo | 1.5 |
| probe | 58.9 |
| real_test | 153.0 |
| tcp | 34.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 206 | 196 | 10 | 95.1% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 47 | 34 | 13 | 72.3% |
| vless | 553 | 371 | 182 | 67.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 75 |
| speed:TimeoutError | 38 |
| geo:ClientOSError | 27 |
| speed:ClientOSError | 21 |
| cn-block:TimeoutError | 18 |
| 204:ProxyError | 9 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4520 |
| ConnectionRefusedError | 860 |
| gaierror | 439 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 429 | 0.935 | 1689 |
| zhangkai | 0.997 | prefer | 113 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.864 | prefer | 183 | 0.787 | 6428 |
| DeltaKronecker-all | 0.498 | observe | 77 | 0.416 | 5415 |
| mheidari-all | 0.435 | observe | 136 | 0.353 | 14677 |
| nscl5-all | 0.26 | observe | 5 | 0.4 | 1008 |
| Epodonios-all | 0.255 | observe | 0 | None | 6993 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3986 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7082 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5343 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.353 | 48 | 88 | 136 |
| nscl5-all | 0.4 | 2 | 3 | 5 |
| DeltaKronecker-all | 0.416 | 32 | 45 | 77 |
| Surfboard-tg-mixed | 0.787 | 144 | 39 | 183 |
| Au1rxx-base64 | 0.935 | 401 | 28 | 429 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14677 | yes | 3.08 | 0 |
| SoliSpirit-all | 7082 | yes | 3.17 | 0 |
| Epodonios-all | 6993 | yes | 3.28 | 0 |
| Surfboard-tg-mixed | 6428 | yes | 2.84 | 0 |
| barry-far-vless | 5618 | yes | 2.09 | 0 |
| DeltaKronecker-all | 5415 | yes | 3.52 | 0 |
| Surfboard-tg-vless | 5343 | yes | 2.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4989 | yes | 2.18 | 0 |
| mahdibland-V2RayAggregator | 4085 | yes | 1.15 | 0 |
| MatinGhanbari-all-sub | 3986 | yes | 2.23 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 102 |
| speed | 59 |
| cn-block | 26 |
| 204 | 20 |
