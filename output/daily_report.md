# AutoNodes 每日报告

生成时间：2026-09-27 11:25:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 95694 |
| 去重后节点数 | 26581 |
| TCP 可达数 | 3000 |
| 真测通过数 | 438 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26581 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 81.1 |
| geo | 1.4 |
| probe | 276.1 |
| real_test | 193.4 |
| tcp | 43.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 72 | 46 | 26 | 63.9% |
| hysteria2 | 23 | 20 | 3 | 87.0% |
| shadowsocks | 175 | 150 | 25 | 85.7% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 43 | 34 | 9 | 79.1% |
| vless | 254 | 184 | 70 | 72.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 31 |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 21 |
| geo:TimeoutError | 20 |
| speed:TimeoutError | 12 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 7 |
| geo:ClientOSError | 5 |
| 204:ClientOSError | 5 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:33760: bind: address already in use | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6285 |
| ConnectionRefusedError | 941 |
| gaierror | 346 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.913 | prefer | 290 | 0.852 | 1589 |
| mheidari-all | 0.788 | prefer | 70 | 0.714 | 22397 |
| Surfboard-tg-mixed | 0.758 | prefer | 116 | 0.681 | 7025 |
| DeltaKronecker-all | 0.716 | prefer | 20 | 0.65 | 5466 |
| ermaozi | 0.697 | observe | 58 | 0.69 | 338 |
| ermaozi-get_subscribe | 0.401 | observe | 16 | 0.438 | 361 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7510 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.438 | 7 | 9 | 16 |
| DeltaKronecker-all | 0.65 | 13 | 7 | 20 |
| Surfboard-tg-mixed | 0.681 | 79 | 37 | 116 |
| ermaozi | 0.69 | 40 | 18 | 58 |
| mheidari-all | 0.714 | 50 | 20 | 70 |
| Au1rxx-base64 | 0.852 | 247 | 43 | 290 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22397 | yes | 3.36 | 0 |
| SoliSpirit-all | 8971 | yes | 3.84 | 0 |
| Epodonios-all | 7510 | yes | 2.75 | 0 |
| Surfboard-tg-mixed | 7025 | yes | 2.65 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.26 | 0 |
| barry-far-vless | 5862 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 5637 | yes | 2.18 | 0 |
| DeltaKronecker-all | 5466 | yes | 2.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.69 | 0 |
| mahdibland-V2RayAggregator | 4277 | yes | 1.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 60 |
| cn-block | 29 |
| geo | 25 |
| speed | 21 |
| sing-box exited 1 | 1 |
