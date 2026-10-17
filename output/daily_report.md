# AutoNodes 每日报告

生成时间：2026-10-17 20:11:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99264 |
| 去重后节点数 | 27731 |
| TCP 可达数 | 3000 |
| 真测通过数 | 416 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27731 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 150.8 |
| geo | 1.5 |
| probe | 229.4 |
| real_test | 245.8 |
| tcp | 47.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 32 | 27 | 5 | 84.4% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 137 | 126 | 11 | 92.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 36 | 31 | 5 | 86.1% |
| vless | 294 | 214 | 80 | 72.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 24 |
| speed:TimeoutError | 19 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 15 |
| 204:ProxyError | 8 |
| geo:ClientOSError | 8 |
| geo:TimeoutError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6779 |
| ConnectionRefusedError | 1039 |
| gaierror | 254 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.896 | prefer | 456 | 0.818 | 1992 |
| ermaozi | 0.873 | prefer | 31 | 0.871 | 623 |
| mheidari-all | 0.58 | observe | 24 | 0.5 | 23876 |
| Surfboard-tg-mixed | 0.438 | observe | 3 | 1.0 | 7087 |
| ermaozi-get_subscribe | 0.275 | observe | 1 | 1.0 | 510 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1992 |
| Epodonios-all | 0.255 | observe | 0 | None | 7590 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10108 |

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
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.5 | 12 | 12 | 24 |
| Au1rxx-base64 | 0.818 | 373 | 83 | 456 |
| ermaozi | 0.871 | 27 | 4 | 31 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23876 | yes | 4.79 | 0 |
| SoliSpirit-all | 10108 | yes | 3.41 | 0 |
| Epodonios-all | 7590 | yes | 4.0 | 0 |
| Surfboard-tg-mixed | 7087 | yes | 5.28 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.23 | 0 |
| barry-far-vless | 5860 | yes | 2.17 | 0 |
| Surfboard-tg-vless | 5622 | yes | 3.24 | 0 |
| DeltaKronecker-all | 4999 | yes | 5.03 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 2.03 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 1.25 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 34 |
| speed | 34 |
| cn-block | 23 |
| geo | 13 |
