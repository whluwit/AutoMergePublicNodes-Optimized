# AutoNodes 每日报告

生成时间：2026-10-10 21:14:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98071 |
| 去重后节点数 | 27313 |
| TCP 可达数 | 3000 |
| 真测通过数 | 421 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27313 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 72.6 |
| geo | 1.6 |
| probe | 247.0 |
| real_test | 286.0 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 2 | 5 | 28.6% |
| http | 34 | 24 | 10 | 70.6% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 111 | 104 | 7 | 93.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 92 | 91 | 1 | 98.9% |
| vless | 240 | 187 | 53 | 77.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 12 |
| speed:ClientOSError | 11 |
| 204:ProxyError | 10 |
| geo:ClientOSError | 9 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6675 |
| ConnectionRefusedError | 1026 |
| gaierror | 360 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | prefer | 351 | 0.9 | 1853 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| mheidari-all | 0.817 | prefer | 93 | 0.742 | 23925 |
| Surfboard-tg-mixed | 0.568 | observe | 8 | 0.875 | 7118 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 5009 |
| ermaozi-get_subscribe | 0.296 | observe | 20 | 0.25 | 580 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7597 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9339 |

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
| ermaozi-get_subscribe | 0.25 | 5 | 15 | 20 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| mheidari-all | 0.742 | 69 | 24 | 93 |
| Surfboard-tg-mixed | 0.875 | 7 | 1 | 8 |
| Au1rxx-base64 | 0.9 | 316 | 35 | 351 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23925 | yes | 4.42 | 0 |
| SoliSpirit-all | 9339 | yes | 4.57 | 0 |
| Epodonios-all | 7597 | yes | 2.9 | 0 |
| Surfboard-tg-mixed | 7118 | yes | 5.26 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.45 | 0 |
| barry-far-vless | 5914 | yes | 0.73 | 0 |
| Surfboard-tg-vless | 5677 | yes | 4.57 | 0 |
| DeltaKronecker-all | 5009 | yes | 5.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 4999 | yes | 0.92 | 0 |
| mahdibland-V2RayAggregator | 4347 | yes | 2.72 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 27 |
| cn-block | 24 |
| speed | 18 |
| geo | 9 |
