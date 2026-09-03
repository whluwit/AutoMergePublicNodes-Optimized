# AutoNodes 每日报告

生成时间：2026-09-03 20:29:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 82530 |
| 去重后节点数 | 22584 |
| TCP 可达数 | 3000 |
| 真测通过数 | 566 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22584 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 37.2 |
| geo | 1.5 |
| probe | 90.9 |
| real_test | 106.6 |
| tcp | 37.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 22 | 21 | 1 | 95.5% |
| hysteria2 | 24 | 24 | 0 | 100.0% |
| shadowsocks | 161 | 147 | 14 | 91.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 59 | 54 | 5 | 91.5% |
| vless | 354 | 315 | 39 | 89.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 11 |
| 204:TimeoutError | 10 |
| 204:ProxyError | 9 |
| geo:ClientOSError | 9 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5010 |
| ConnectionRefusedError | 909 |
| gaierror | 368 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 365 | 0.94 | 1748 |
| DeltaKronecker-all | 0.927 | prefer | 57 | 0.86 | 6335 |
| zhangkai | 0.927 | prefer | 19 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.924 | prefer | 75 | 0.853 | 7177 |
| mheidari-all | 0.91 | prefer | 104 | 0.837 | 15893 |
| tg-oneclickvpnkeys | 0.325 | observe | 4 | 0.75 | 115 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4671 |
| Epodonios-all | 0.255 | observe | 0 | None | 7695 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| Pawdroid | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.75 | 3 | 1 | 4 |
| mheidari-all | 0.837 | 87 | 17 | 104 |
| Surfboard-tg-mixed | 0.853 | 64 | 11 | 75 |
| DeltaKronecker-all | 0.86 | 49 | 8 | 57 |
| Au1rxx-base64 | 0.94 | 343 | 22 | 365 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15893 | yes | 5.05 | 0 |
| SoliSpirit-all | 8160 | yes | 3.23 | 0 |
| Epodonios-all | 7695 | yes | 3.21 | 0 |
| Surfboard-tg-mixed | 7177 | yes | 4.31 | 0 |
| DeltaKronecker-all | 6335 | yes | 5.07 | 0 |
| barry-far-vless | 6219 | yes | 2.38 | 0 |
| Surfboard-tg-vless | 5920 | yes | 3.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 4671 | yes | 2.7 | 0 |
| mahdibland-V2RayAggregator | 4133 | yes | 1.45 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 24 |
| cn-block | 19 |
| geo | 11 |
| speed | 7 |
