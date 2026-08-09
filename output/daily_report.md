# AutoNodes 每日报告

生成时间：2026-08-09 12:44:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 85466 |
| 去重后节点数 | 23881 |
| TCP 可达数 | 3000 |
| 真测通过数 | 463 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23881 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 12.3 |
| generate | 45.7 |
| geo | 1.4 |
| probe | 55.1 |
| real_test | 107.2 |
| tcp | 36.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 150 | 134 | 16 | 89.3% |
| socks | 10 | 4 | 6 | 40.0% |
| trojan | 154 | 134 | 20 | 87.0% |
| vless | 210 | 148 | 62 | 70.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 20 |
| speed:TimeoutError | 14 |
| 204:ProxyError | 11 |
| geo:ClientOSError | 10 |
| speed:ClientOSError | 8 |
| geo:TimeoutError | 5 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5020 |
| ConnectionRefusedError | 823 |
| gaierror | 258 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | prefer | 409 | 0.914 | 1704 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.622 | observe | 94 | 0.543 | 6537 |
| mheidari-all | 0.587 | observe | 19 | 0.526 | 20170 |
| DeltaKronecker-all | 0.388 | observe | 24 | 0.292 | 4998 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 77 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5505 |
| Epodonios-all | 0.255 | observe | 0 | None | 7128 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7369 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.292 | 7 | 17 | 24 |
| mheidari-all | 0.526 | 10 | 9 | 19 |
| Surfboard-tg-mixed | 0.543 | 51 | 43 | 94 |
| Au1rxx-base64 | 0.914 | 374 | 35 | 409 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20170 | yes | 4.57 | 0 |
| SoliSpirit-all | 7369 | yes | 4.67 | 0 |
| Epodonios-all | 7128 | yes | 4.03 | 0 |
| Surfboard-tg-mixed | 6537 | yes | 3.72 | 0 |
| barry-far-vless | 5659 | yes | 0.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 5505 | yes | 2.92 | 0 |
| Surfboard-tg-vless | 5349 | yes | 3.0 | 0 |
| mahdibland-V2RayAggregator | 5130 | yes | 4.67 | 0 |
| DeltaKronecker-all | 4998 | yes | 5.47 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| cn-block | 26 |
| speed | 23 |
| geo | 15 |
