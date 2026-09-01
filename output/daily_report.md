# AutoNodes 每日报告

生成时间：2026-09-01 20:31:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 81525 |
| 去重后节点数 | 23511 |
| TCP 可达数 | 3000 |
| 真测通过数 | 641 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23511 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 37.8 |
| geo | 1.5 |
| probe | 78.3 |
| real_test | 134.0 |
| tcp | 39.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 162 | 146 | 16 | 90.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 35 | 32 | 3 | 91.4% |
| vless | 500 | 422 | 78 | 84.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 25 |
| 204:TimeoutError | 23 |
| 204:ProxyError | 11 |
| cn-block:ClientOSError | 8 |
| speed:ClientOSError | 8 |
| 204:ClientOSError | 8 |
| geo:ClientOSError | 6 |
| speed:TimeoutError | 4 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5631 |
| ConnectionRefusedError | 889 |
| gaierror | 181 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 1.0 | prefer | 32 | 0.969 | 7294 |
| Au1rxx-base64 | 0.978 | prefer | 408 | 0.912 | 1703 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| mheidari-all | 0.908 | prefer | 126 | 0.833 | 15436 |
| Surfboard-tg-mixed | 0.81 | prefer | 150 | 0.733 | 6974 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4708 |
| Epodonios-all | 0.255 | observe | 0 | None | 7385 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7585 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5805 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.733 | 110 | 40 | 150 |
| mheidari-all | 0.833 | 105 | 21 | 126 |
| Au1rxx-base64 | 0.912 | 372 | 36 | 408 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| DeltaKronecker-all | 0.969 | 31 | 1 | 32 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15436 | yes | 3.14 | 0 |
| SoliSpirit-all | 7585 | yes | 2.88 | 0 |
| Epodonios-all | 7385 | yes | 3.36 | 0 |
| DeltaKronecker-all | 7294 | yes | 3.85 | 0 |
| Surfboard-tg-mixed | 6974 | yes | 2.8 | 0 |
| barry-far-vless | 5987 | yes | 3.94 | 0 |
| Surfboard-tg-vless | 5805 | yes | 5.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 4708 | yes | 4.11 | 0 |
| mahdibland-V2RayAggregator | 4159 | yes | 0.84 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 43 |
| cn-block | 35 |
| speed | 13 |
| geo | 9 |
