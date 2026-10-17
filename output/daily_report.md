# AutoNodes 每日报告

生成时间：2026-10-17 02:58:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99804 |
| 去重后节点数 | 27729 |
| TCP 可达数 | 3000 |
| 真测通过数 | 557 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27729 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 77.7 |
| geo | 1.5 |
| probe | 337.8 |
| real_test | 435.2 |
| tcp | 48.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 51 | 21 | 30 | 41.2% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 163 | 153 | 10 | 93.9% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 48 | 41 | 7 | 85.4% |
| vless | 541 | 317 | 224 | 58.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 113 |
| speed:ClientOSError | 49 |
| geo:ClientOSError | 26 |
| 204:ProxyError | 23 |
| speed:TimeoutError | 17 |
| 204:TimeoutError | 13 |
| 204:ProxyConnectionError | 10 |
| cn-block:ClientOSError | 8 |
| cn-block:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6902 |
| ConnectionRefusedError | 1054 |
| gaierror | 240 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 528 | 0.886 | 1993 |
| ermaozi | 0.473 | observe | 52 | 0.442 | 702 |
| Surfboard-tg-mixed | 0.446 | observe | 8 | 0.625 | 7128 |
| ermaozi-get_subscribe | 0.335 | observe | 2 | 1.0 | 601 |
| mheidari-all | 0.333 | observe | 223 | 0.251 | 24092 |
| DeltaKronecker-all | 0.286 | observe | 13 | 0.231 | 4946 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1993 |
| Epodonios-all | 0.255 | observe | 0 | None | 7692 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.231 | 3 | 10 | 13 |
| mheidari-all | 0.251 | 56 | 167 | 223 |
| ermaozi | 0.442 | 23 | 29 | 52 |
| Surfboard-tg-mixed | 0.625 | 5 | 3 | 8 |
| Au1rxx-base64 | 0.886 | 468 | 60 | 528 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24092 | yes | 5.02 | 0 |
| SoliSpirit-all | 10040 | yes | 5.27 | 0 |
| Epodonios-all | 7692 | yes | 4.37 | 0 |
| Surfboard-tg-mixed | 7128 | yes | 5.22 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.93 | 0 |
| barry-far-vless | 5904 | yes | 4.85 | 0 |
| Surfboard-tg-vless | 5602 | yes | 3.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 2.14 | 0 |
| DeltaKronecker-all | 4946 | yes | 5.66 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 2.03 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 139 |
| speed | 66 |
| 204 | 50 |
| cn-block | 17 |
