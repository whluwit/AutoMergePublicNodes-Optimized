# AutoNodes 每日报告

生成时间：2026-08-30 11:10:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79189 |
| 去重后节点数 | 21796 |
| TCP 可达数 | 3000 |
| 真测通过数 | 574 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21796 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 46.8 |
| geo | 1.4 |
| probe | 56.4 |
| real_test | 110.7 |
| tcp | 34.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 153 | 140 | 13 | 91.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 34 | 33 | 1 | 97.1% |
| vless | 427 | 355 | 72 | 83.1% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 19 |
| geo:ClientOSError | 18 |
| 204:ProxyError | 10 |
| cn-block:TimeoutError | 10 |
| speed:ClientOSError | 9 |
| geo:TimeoutError | 6 |
| speed:TimeoutError | 5 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4438 |
| ConnectionRefusedError | 888 |
| gaierror | 414 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 350 | 0.931 | 1804 |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.863 | prefer | 155 | 0.787 | 6846 |
| DeltaKronecker-all | 0.853 | prefer | 117 | 0.778 | 5576 |
| mheidari-all | 0.633 | observe | 14 | 0.714 | 15081 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4762 |
| Epodonios-all | 0.255 | observe | 0 | None | 7251 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3991 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7562 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.714 | 10 | 4 | 14 |
| DeltaKronecker-all | 0.778 | 91 | 26 | 117 |
| Surfboard-tg-mixed | 0.787 | 122 | 33 | 155 |
| Au1rxx-base64 | 0.931 | 326 | 24 | 350 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15081 | yes | 4.86 | 0 |
| SoliSpirit-all | 7562 | yes | 4.47 | 0 |
| Epodonios-all | 7251 | yes | 4.43 | 0 |
| Surfboard-tg-mixed | 6846 | yes | 4.19 | 0 |
| barry-far-vless | 5908 | yes | 2.61 | 0 |
| Surfboard-tg-vless | 5683 | yes | 3.43 | 0 |
| DeltaKronecker-all | 5576 | yes | 5.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4762 | yes | 2.82 | 0 |
| MatinGhanbari-all-sub | 3991 | yes | 2.94 | 0 |
| mahdibland-V2RayAggregator | 3949 | yes | 2.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 32 |
| geo | 25 |
| cn-block | 17 |
| speed | 15 |
