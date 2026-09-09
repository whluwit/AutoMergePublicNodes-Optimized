# AutoNodes 每日报告

生成时间：2026-09-09 15:59:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 84834 |
| 去重后节点数 | 22009 |
| TCP 可达数 | 3000 |
| 真测通过数 | 484 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22009 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 80.0 |
| geo | 1.3 |
| probe | 257.2 |
| real_test | 265.3 |
| tcp | 36.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 31 | 21 | 10 | 67.7% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 170 | 159 | 11 | 93.5% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 22 | 18 | 4 | 81.8% |
| vless | 357 | 264 | 93 | 73.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 40 |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 16 |
| cn-block:ClientOSError | 16 |
| 204:TimeoutError | 14 |
| speed:ClientOSError | 6 |
| cn-block:ProxyError | 4 |
| geo:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4796 |
| ConnectionRefusedError | 898 |
| gaierror | 413 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | prefer | 284 | 0.919 | 1709 |
| Surfboard-tg-mixed | 0.857 | prefer | 155 | 0.781 | 7428 |
| ermaozi | 0.824 | prefer | 24 | 0.833 | 410 |
| DeltaKronecker-all | 0.689 | observe | 21 | 0.619 | 5187 |
| mheidari-all | 0.682 | observe | 111 | 0.604 | 16618 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 205 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4795 |
| Epodonios-all | 0.255 | observe | 0 | None | 7926 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9119 |

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
| downweight | ermaozi-get_subscribe | 0.085 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 6 | 6 |
| mheidari-all | 0.604 | 67 | 44 | 111 |
| DeltaKronecker-all | 0.619 | 13 | 8 | 21 |
| Surfboard-tg-mixed | 0.781 | 121 | 34 | 155 |
| ermaozi | 0.833 | 20 | 4 | 24 |
| Au1rxx-base64 | 0.919 | 261 | 23 | 284 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16618 | yes | 3.54 | 0 |
| SoliSpirit-all | 9119 | yes | 3.49 | 0 |
| Epodonios-all | 7926 | yes | 3.7 | 0 |
| Surfboard-tg-mixed | 7428 | yes | 2.78 | 0 |
| barry-far-vless | 6336 | yes | 2.42 | 0 |
| Surfboard-tg-vless | 6118 | yes | 2.97 | 0 |
| DeltaKronecker-all | 5187 | yes | 3.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 1.91 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 0.78 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.48 | 0 |

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
| geo | 43 |
| cn-block | 37 |
| 204 | 32 |
| speed | 8 |
