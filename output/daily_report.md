# AutoNodes 每日报告

生成时间：2026-08-29 05:25:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 76982 |
| 去重后节点数 | 20854 |
| TCP 可达数 | 3000 |
| 真测通过数 | 706 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 20854 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 36.7 |
| geo | 1.5 |
| probe | 57.8 |
| real_test | 143.1 |
| tcp | 35.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 27 | 27 | 0 | 100.0% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 185 | 171 | 14 | 92.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 22 | 20 | 2 | 90.9% |
| vless | 600 | 465 | 135 | 77.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 33 |
| cn-block:TimeoutError | 31 |
| 204:TimeoutError | 23 |
| geo:ClientOSError | 20 |
| geo:TimeoutError | 15 |
| cn-block:ClientOSError | 12 |
| 204:ProxyError | 7 |
| speed:ClientOSError | 6 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4992 |
| ConnectionRefusedError | 852 |
| gaierror | 273 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Au1rxx-base64 | 0.94 | prefer | 395 | 0.868 | 1828 |
| Surfboard-tg-mixed | 0.881 | prefer | 199 | 0.804 | 6733 |
| DeltaKronecker-all | 0.825 | prefer | 135 | 0.748 | 4065 |
| mheidari-all | 0.81 | prefer | 98 | 0.735 | 14598 |
| tg-oneclickvpnkeys | 0.405 | observe | 4 | 1.0 | 127 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| Epodonios-all | 0.255 | observe | 0 | None | 7084 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.735 | 72 | 26 | 98 |
| DeltaKronecker-all | 0.748 | 101 | 34 | 135 |
| Surfboard-tg-mixed | 0.804 | 160 | 39 | 199 |
| Au1rxx-base64 | 0.868 | 343 | 52 | 395 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14598 | yes | 4.74 | 0 |
| SoliSpirit-all | 7191 | yes | 3.1 | 0 |
| Epodonios-all | 7084 | yes | 3.05 | 0 |
| Surfboard-tg-mixed | 6733 | yes | 4.34 | 0 |
| barry-far-vless | 5694 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 5530 | yes | 3.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 4725 | yes | 1.84 | 0 |
| mahdibland-V2RayAggregator | 4093 | yes | 3.11 | 0 |
| DeltaKronecker-all | 4065 | yes | 5.19 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 47 |
| speed | 40 |
| geo | 35 |
| 204 | 33 |
