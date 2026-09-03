# AutoNodes 每日报告

生成时间：2026-09-03 10:39:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 82545 |
| 去重后节点数 | 22920 |
| TCP 可达数 | 3000 |
| 真测通过数 | 550 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22920 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 44.5 |
| geo | 1.6 |
| probe | 83.8 |
| real_test | 126.7 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 164 | 151 | 13 | 92.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 31 | 22 | 9 | 71.0% |
| vless | 423 | 335 | 88 | 79.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 28 |
| cn-block:TimeoutError | 28 |
| geo:ClientOSError | 17 |
| speed:TimeoutError | 9 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 3 |
| 204:ProxyConnectionError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4477 |
| ConnectionRefusedError | 904 |
| gaierror | 386 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | prefer | 328 | 0.909 | 1751 |
| mheidari-all | 0.965 | prefer | 24 | 0.917 | 16145 |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| DeltaKronecker-all | 0.823 | prefer | 99 | 0.747 | 6335 |
| Surfboard-tg-mixed | 0.787 | prefer | 189 | 0.709 | 7139 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 87 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4671 |
| Epodonios-all | 0.255 | observe | 0 | None | 7527 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8132 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.709 | 134 | 55 | 189 |
| DeltaKronecker-all | 0.747 | 74 | 25 | 99 |
| Au1rxx-base64 | 0.909 | 298 | 30 | 328 |
| mheidari-all | 0.917 | 22 | 2 | 24 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16145 | yes | 4.84 | 0 |
| SoliSpirit-all | 8132 | yes | 3.7 | 0 |
| Epodonios-all | 7527 | yes | 3.15 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 3.85 | 0 |
| DeltaKronecker-all | 6335 | yes | 5.26 | 0 |
| barry-far-vless | 6217 | yes | 2.65 | 0 |
| Surfboard-tg-vless | 6006 | yes | 3.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 4671 | yes | 2.93 | 0 |
| mahdibland-V2RayAggregator | 4081 | yes | 2.93 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.73 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 39 |
| cn-block | 36 |
| geo | 22 |
| speed | 17 |
