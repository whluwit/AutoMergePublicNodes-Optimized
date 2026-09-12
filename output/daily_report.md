# AutoNodes 每日报告

生成时间：2026-09-12 03:07:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83355 |
| 去重后节点数 | 23379 |
| TCP 可达数 | 3000 |
| 真测通过数 | 593 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23379 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 80.6 |
| geo | 1.4 |
| probe | 389.0 |
| real_test | 544.1 |
| tcp | 40.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 31 | 22 | 9 | 71.0% |
| hysteria2 | 27 | 23 | 4 | 85.2% |
| shadowsocks | 181 | 173 | 8 | 95.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 52 | 19 | 33 | 36.5% |
| vless | 801 | 355 | 446 | 44.3% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 239 |
| geo:ClientOSError | 92 |
| speed:ClientOSError | 51 |
| speed:TimeoutError | 47 |
| 204:ProxyError | 23 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 12 |
| 204:ProxyConnectionError | 8 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 6 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5206 |
| ConnectionRefusedError | 899 |
| gaierror | 540 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | prefer | 326 | 0.868 | 1681 |
| Surfboard-tg-mixed | 0.833 | prefer | 79 | 0.759 | 7263 |
| ermaozi | 0.732 | prefer | 26 | 0.731 | 434 |
| mheidari-all | 0.585 | observe | 105 | 0.505 | 15597 |
| DeltaKronecker-all | 0.396 | observe | 549 | 0.315 | 6070 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 194 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.259 | observe | 3 | 0.333 | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7719 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.238 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.315 | 173 | 376 | 549 |
| 10ium-ScrapeCategorize-Vless | 0.333 | 1 | 2 | 3 |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| mheidari-all | 0.505 | 53 | 52 | 105 |
| ermaozi | 0.731 | 19 | 7 | 26 |
| Surfboard-tg-mixed | 0.759 | 60 | 19 | 79 |
| Au1rxx-base64 | 0.868 | 283 | 43 | 326 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15597 | yes | 5.78 | 0 |
| SoliSpirit-all | 8501 | yes | 4.15 | 0 |
| Epodonios-all | 7719 | yes | 3.47 | 0 |
| Surfboard-tg-mixed | 7263 | yes | 4.62 | 0 |
| barry-far-vless | 6106 | yes | 3.27 | 0 |
| DeltaKronecker-all | 6070 | yes | 5.12 | 0 |
| Surfboard-tg-vless | 5889 | yes | 4.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 3.03 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 0.21 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.56 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 331 |
| speed | 99 |
| 204 | 49 |
| cn-block | 24 |
