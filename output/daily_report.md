# AutoNodes 每日报告

生成时间：2026-09-25 21:10:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97260 |
| 去重后节点数 | 26455 |
| TCP 可达数 | 3000 |
| 真测通过数 | 361 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26455 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 78.8 |
| geo | 1.5 |
| probe | 217.8 |
| real_test | 169.4 |
| tcp | 43.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 35 | 19 | 16 | 54.3% |
| hysteria2 | 20 | 17 | 3 | 85.0% |
| shadowsocks | 148 | 130 | 18 | 87.8% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 22 | 5 | 17 | 22.7% |
| vless | 257 | 185 | 72 | 72.0% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 41 |
| cn-block:TimeoutError | 24 |
| cn-block:ClientOSError | 19 |
| 204:ProxyConnectionError | 17 |
| 204:ProxyError | 9 |
| geo:TimeoutError | 8 |
| speed:ClientOSError | 5 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6008 |
| ConnectionRefusedError | 951 |
| gaierror | 388 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.956 | prefer | 238 | 0.891 | 1701 |
| mheidari-all | 0.712 | prefer | 104 | 0.635 | 22345 |
| Surfboard-tg-mixed | 0.651 | observe | 110 | 0.573 | 7370 |
| ermaozi | 0.555 | observe | 33 | 0.545 | 304 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 5452 |
| Epodonios-all | 0.255 | observe | 0 | None | 7740 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9249 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5959 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.545 | 18 | 15 | 33 |
| Surfboard-tg-mixed | 0.573 | 63 | 47 | 110 |
| mheidari-all | 0.635 | 66 | 38 | 104 |
| Au1rxx-base64 | 0.891 | 212 | 26 | 238 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22345 | yes | 6.11 | 0 |
| SoliSpirit-all | 9249 | yes | 4.76 | 0 |
| Epodonios-all | 7740 | yes | 1.34 | 0 |
| Surfboard-tg-mixed | 7370 | yes | 3.63 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.95 | 0 |
| barry-far-vless | 6190 | yes | 3.74 | 0 |
| Surfboard-tg-vless | 5959 | yes | 4.16 | 0 |
| DeltaKronecker-all | 5452 | yes | 6.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 3.23 | 0 |
| mahdibland-V2RayAggregator | 4304 | yes | 3.27 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 68 |
| cn-block | 45 |
| speed | 9 |
| geo | 9 |
