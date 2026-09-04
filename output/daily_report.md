# AutoNodes 每日报告

生成时间：2026-09-04 02:41:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82381 |
| 去重后节点数 | 22756 |
| TCP 可达数 | 3000 |
| 真测通过数 | 719 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22756 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 33.3 |
| geo | 1.6 |
| probe | 74.1 |
| real_test | 161.0 |
| tcp | 37.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 26 | 26 | 0 | 100.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 181 | 175 | 6 | 96.7% |
| trojan | 69 | 48 | 21 | 69.6% |
| vless | 650 | 446 | 204 | 68.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 98 |
| geo:ClientOSError | 43 |
| speed:ClientOSError | 28 |
| speed:TimeoutError | 17 |
| cn-block:TimeoutError | 14 |
| 204:TimeoutError | 10 |
| cn-block:ClientOSError | 9 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5356 |
| ConnectionRefusedError | 917 |
| gaierror | 318 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 382 | 0.955 | 1739 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.842 | prefer | 229 | 0.764 | 7237 |
| mheidari-all | 0.788 | prefer | 46 | 0.717 | 15793 |
| DeltaKronecker-all | 0.532 | observe | 261 | 0.452 | 6335 |
| tg-oneclickvpnkeys | 0.403 | observe | 4 | 1.0 | 71 |
| Epodonios-all | 0.255 | observe | 0 | None | 7701 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7945 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6022 |

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
| ninja-vless | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.25 | 1 | 3 | 4 |
| DeltaKronecker-all | 0.452 | 118 | 143 | 261 |
| mheidari-all | 0.717 | 33 | 13 | 46 |
| Surfboard-tg-mixed | 0.764 | 175 | 54 | 229 |
| Au1rxx-base64 | 0.955 | 365 | 17 | 382 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15793 | yes | 4.35 | 0 |
| SoliSpirit-all | 7945 | yes | 2.01 | 0 |
| Epodonios-all | 7701 | yes | 2.29 | 0 |
| Surfboard-tg-mixed | 7237 | yes | 3.56 | 0 |
| DeltaKronecker-all | 6335 | yes | 2.97 | 0 |
| barry-far-vless | 6237 | yes | 1.61 | 0 |
| Surfboard-tg-vless | 6022 | yes | 2.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 4671 | yes | 2.15 | 0 |
| mahdibland-V2RayAggregator | 4133 | yes | 1.09 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.47 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 142 |
| speed | 45 |
| cn-block | 24 |
| 204 | 22 |
