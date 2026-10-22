# AutoNodes 每日报告

生成时间：2026-10-22 03:12:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96930 |
| 去重后节点数 | 27025 |
| TCP 可达数 | 3000 |
| 真测通过数 | 360 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27025 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 72.2 |
| geo | 1.5 |
| probe | 274.6 |
| real_test | 262.6 |
| tcp | 45.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 26 | 23 | 53.1% |
| hysteria2 | 10 | 10 | 0 | 100.0% |
| shadowsocks | 167 | 158 | 9 | 94.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 87 | 81 | 6 | 93.1% |
| vless | 242 | 82 | 160 | 33.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 99 |
| 204:ProxyError | 32 |
| geo:ClientOSError | 26 |
| speed:ClientOSError | 21 |
| cn-block:TimeoutError | 6 |
| 204:TimeoutError | 5 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6586 |
| ConnectionRefusedError | 1041 |
| gaierror | 253 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 128 | 0.977 | 1587 |
| Surfboard-tg-mixed | 0.976 | prefer | 75 | 0.907 | 7097 |
| mheidari-all | 0.551 | observe | 278 | 0.471 | 24252 |
| zhangkai | 0.533 | observe | 16 | 0.625 | 31 |
| ermaozi-get_subscribe | 0.507 | observe | 33 | 0.485 | 523 |
| DeltaKronecker-all | 0.447 | observe | 28 | 0.357 | 4067 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| Epodonios-all | 0.255 | observe | 0 | None | 7591 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10124 |

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
| DeltaKronecker-all | 0.357 | 10 | 18 | 28 |
| mheidari-all | 0.471 | 131 | 147 | 278 |
| ermaozi-get_subscribe | 0.485 | 16 | 17 | 33 |
| zhangkai | 0.625 | 10 | 6 | 16 |
| Surfboard-tg-mixed | 0.907 | 68 | 7 | 75 |
| Au1rxx-base64 | 0.977 | 125 | 3 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24252 | yes | 4.73 | 0 |
| SoliSpirit-all | 10124 | yes | 3.44 | 0 |
| Epodonios-all | 7591 | yes | 3.64 | 0 |
| Surfboard-tg-mixed | 7097 | yes | 3.06 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5773 | yes | 1.06 | 0 |
| Surfboard-tg-vless | 5559 | yes | 2.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 0.91 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 2.35 | 0 |
| DeltaKronecker-all | 4067 | yes | 3.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 125 |
| 204 | 40 |
| speed | 27 |
| cn-block | 7 |
