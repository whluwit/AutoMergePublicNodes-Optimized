# AutoNodes 每日报告

生成时间：2026-09-10 15:55:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 91308 |
| 去重后节点数 | 24428 |
| TCP 可达数 | 3000 |
| 真测通过数 | 403 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24428 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 75.7 |
| geo | 1.4 |
| probe | 317.1 |
| real_test | 269.8 |
| tcp | 42.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 30 | 21 | 9 | 70.0% |
| hysteria2 | 19 | 15 | 4 | 78.9% |
| shadowsocks | 151 | 139 | 12 | 92.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 26 | 14 | 12 | 53.8% |
| vless | 348 | 212 | 136 | 60.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 49 |
| geo:ClientOSError | 48 |
| cn-block:TimeoutError | 18 |
| geo:TimeoutError | 13 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 9 |
| speed:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 4 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6106 |
| ConnectionRefusedError | 959 |
| gaierror | 342 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.873 | prefer | 270 | 0.807 | 1693 |
| ermaozi | 0.824 | prefer | 24 | 0.833 | 405 |
| Surfboard-tg-mixed | 0.805 | prefer | 147 | 0.728 | 7191 |
| mheidari-all | 0.533 | observe | 126 | 0.452 | 19266 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 196 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7902 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9189 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5790 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.09 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| ermaozi-get_subscribe | 0.0 | 0 | 5 | 5 |
| mheidari-all | 0.452 | 57 | 69 | 126 |
| Surfboard-tg-mixed | 0.728 | 107 | 40 | 147 |
| Au1rxx-base64 | 0.807 | 218 | 52 | 270 |
| ermaozi | 0.833 | 20 | 4 | 24 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19266 | yes | 3.18 | 0 |
| SoliSpirit-all | 9189 | yes | 1.9 | 0 |
| Epodonios-all | 7902 | yes | 3.36 | 0 |
| Surfboard-tg-mixed | 7191 | yes | 3.58 | 0 |
| barry-far-vless | 6248 | yes | 1.31 | 0 |
| DeltaKronecker-all | 5853 | yes | 3.63 | 0 |
| Surfboard-tg-vless | 5790 | yes | 2.65 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 1.18 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 0.98 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.38 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 65 |
| geo | 62 |
| cn-block | 31 |
| speed | 16 |
