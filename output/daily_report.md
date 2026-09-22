# AutoNodes 每日报告

生成时间：2026-09-22 16:19:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87920 |
| 去重后节点数 | 25306 |
| TCP 可达数 | 3000 |
| 真测通过数 | 483 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25306 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 82.2 |
| geo | 1.5 |
| probe | 248.4 |
| real_test | 231.1 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 31 | 22 | 9 | 71.0% |
| hysteria2 | 23 | 20 | 3 | 87.0% |
| shadowsocks | 169 | 153 | 16 | 90.5% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 22 | 19 | 3 | 86.4% |
| vless | 453 | 265 | 188 | 58.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 68 |
| geo:ClientOSError | 34 |
| 204:TimeoutError | 27 |
| geo:TimeoutError | 26 |
| 204:ProxyError | 20 |
| cn-block:ClientOSError | 16 |
| cn-block:TimeoutError | 14 |
| 204:ClientOSError | 10 |
| speed:TimeoutError | 5 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6225 |
| ConnectionRefusedError | 939 |
| gaierror | 278 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.986 | prefer | 30 | 0.933 | 16289 |
| Au1rxx-base64 | 0.919 | prefer | 298 | 0.856 | 1636 |
| ermaozi | 0.737 | prefer | 27 | 0.741 | 325 |
| Surfboard-tg-mixed | 0.6 | observe | 177 | 0.52 | 7076 |
| DeltaKronecker-all | 0.586 | observe | 152 | 0.507 | 6324 |
| xiaoji235-airport-v2ray-all | 0.543 | observe | 13 | 0.615 | 4242 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 132 |
| Epodonios-all | 0.255 | observe | 0 | None | 7611 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.507 | 77 | 75 | 152 |
| Surfboard-tg-mixed | 0.52 | 92 | 85 | 177 |
| xiaoji235-airport-v2ray-all | 0.615 | 8 | 5 | 13 |
| ermaozi | 0.741 | 20 | 7 | 27 |
| Au1rxx-base64 | 0.856 | 255 | 43 | 298 |
| mheidari-all | 0.933 | 28 | 2 | 30 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16289 | yes | 4.45 | 0 |
| SoliSpirit-all | 8744 | yes | 2.6 | 0 |
| Epodonios-all | 7611 | yes | 4.71 | 0 |
| Surfboard-tg-mixed | 7076 | yes | 3.71 | 0 |
| DeltaKronecker-all | 6324 | yes | 4.85 | 0 |
| barry-far-vless | 6010 | yes | 1.19 | 0 |
| Surfboard-tg-vless | 5712 | yes | 3.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 0.47 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 2.88 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 3.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 74 |
| geo | 60 |
| 204 | 57 |
| cn-block | 32 |
