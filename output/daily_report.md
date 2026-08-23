# AutoNodes 每日报告

生成时间：2026-08-23 18:26:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77721 |
| 去重后节点数 | 21470 |
| TCP 可达数 | 3000 |
| 真测通过数 | 708 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21470 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 13.6 |
| generate | 40.2 |
| geo | 1.4 |
| probe | 59.8 |
| real_test | 158.4 |
| tcp | 34.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 171 | 156 | 15 | 91.2% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 27 | 24 | 3 | 88.9% |
| vless | 536 | 392 | 144 | 73.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 39 |
| cn-block:TimeoutError | 37 |
| 204:TimeoutError | 21 |
| geo:ClientOSError | 17 |
| 204:ProxyError | 14 |
| speed:TimeoutError | 14 |
| cn-block:ClientOSError | 8 |
| speed:ClientOSError | 8 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4772 |
| ConnectionRefusedError | 833 |
| gaierror | 338 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | prefer | 399 | 0.93 | 1729 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| mheidari-all | 0.997 | prefer | 34 | 0.941 | 14516 |
| Surfboard-tg-mixed | 0.737 | prefer | 138 | 0.659 | 6307 |
| DeltaKronecker-all | 0.609 | observe | 189 | 0.529 | 5415 |
| nscl5-all | 0.298 | observe | 1 | 1.0 | 1082 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 177 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4989 |
| Epodonios-all | 0.255 | observe | 0 | None | 6874 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3990 |

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
| DeltaKronecker-all | 0.529 | 100 | 89 | 189 |
| Surfboard-tg-mixed | 0.659 | 91 | 47 | 138 |
| Au1rxx-base64 | 0.93 | 371 | 28 | 399 |
| mheidari-all | 0.941 | 32 | 2 | 34 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14516 | yes | 4.54 | 0 |
| SoliSpirit-all | 6995 | yes | 2.36 | 0 |
| Epodonios-all | 6874 | yes | 5.34 | 0 |
| Surfboard-tg-mixed | 6307 | yes | 3.42 | 0 |
| barry-far-vless | 5492 | yes | 1.38 | 0 |
| DeltaKronecker-all | 5415 | yes | 4.67 | 0 |
| Surfboard-tg-vless | 5215 | yes | 3.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4989 | yes | 1.64 | 0 |
| mahdibland-V2RayAggregator | 4085 | yes | 1.92 | 0 |
| MatinGhanbari-all-sub | 3990 | yes | 1.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 58 |
| cn-block | 48 |
| 204 | 38 |
| speed | 23 |
