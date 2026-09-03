# AutoNodes 每日报告

生成时间：2026-09-03 15:45:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 81969 |
| 去重后节点数 | 22562 |
| TCP 可达数 | 3000 |
| 真测通过数 | 642 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22562 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 40.4 |
| geo | 1.5 |
| probe | 77.8 |
| real_test | 140.7 |
| tcp | 38.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 27 | 0 | 100.0% |
| hysteria2 | 23 | 21 | 2 | 91.3% |
| shadowsocks | 170 | 160 | 10 | 94.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 27 | 27 | 0 | 100.0% |
| vless | 492 | 402 | 90 | 81.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 24 |
| 204:TimeoutError | 21 |
| geo:ClientOSError | 19 |
| 204:ProxyError | 11 |
| speed:ClientOSError | 8 |
| geo:TimeoutError | 7 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5485 |
| ConnectionRefusedError | 916 |
| gaierror | 228 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 363 | 0.942 | 1770 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| mheidari-all | 0.932 | prefer | 106 | 0.858 | 15770 |
| DeltaKronecker-all | 0.823 | prefer | 72 | 0.75 | 6335 |
| Surfboard-tg-mixed | 0.802 | prefer | 174 | 0.724 | 7139 |
| tg-oneclickvpnkeys | 0.445 | observe | 5 | 1.0 | 145 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4671 |
| Epodonios-all | 0.255 | observe | 0 | None | 7586 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| Surfboard-tg-mixed | 0.724 | 126 | 48 | 174 |
| DeltaKronecker-all | 0.75 | 54 | 18 | 72 |
| mheidari-all | 0.858 | 91 | 15 | 106 |
| Au1rxx-base64 | 0.942 | 342 | 21 | 363 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15770 | yes | 3.43 | 0 |
| SoliSpirit-all | 7805 | yes | 4.53 | 0 |
| Epodonios-all | 7586 | yes | 2.42 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 3.08 | 0 |
| DeltaKronecker-all | 6335 | yes | 3.62 | 0 |
| barry-far-vless | 6219 | yes | 2.25 | 0 |
| Surfboard-tg-vless | 6006 | yes | 2.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 4671 | yes | 2.38 | 0 |
| mahdibland-V2RayAggregator | 4081 | yes | 0.16 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.88 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 34 |
| geo | 27 |
| cn-block | 27 |
| speed | 15 |
