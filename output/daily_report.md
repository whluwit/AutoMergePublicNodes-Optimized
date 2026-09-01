# AutoNodes 每日报告

生成时间：2026-09-01 11:04:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83381 |
| 去重后节点数 | 24538 |
| TCP 可达数 | 3000 |
| 真测通过数 | 606 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24538 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 34.4 |
| geo | 1.5 |
| probe | 84.4 |
| real_test | 129.3 |
| tcp | 40.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 20 | 3 | 87.0% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 140 | 124 | 16 | 88.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 36 | 24 | 12 | 66.7% |
| vless | 543 | 422 | 121 | 77.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 27 |
| cn-block:TimeoutError | 27 |
| 204:TimeoutError | 21 |
| geo:ClientOSError | 17 |
| geo:TimeoutError | 14 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 10 |
| cn-block:ClientOSError | 10 |
| 204:ClientOSError | 8 |
| 204:ProxyConnectionError | 3 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5503 |
| ConnectionRefusedError | 986 |
| gaierror | 355 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.898 | prefer | 319 | 0.834 | 1645 |
| mheidari-all | 0.884 | prefer | 212 | 0.807 | 17148 |
| zhangkai | 0.846 | prefer | 23 | 0.87 | 144 |
| Surfboard-tg-mixed | 0.825 | prefer | 194 | 0.747 | 6921 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 49 |
| DeltaKronecker-all | 0.255 | observe | 9 | 0.222 | 7294 |
| Epodonios-all | 0.255 | observe | 0 | None | 7334 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7933 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.222 | 2 | 7 | 9 |
| Surfboard-tg-mixed | 0.747 | 145 | 49 | 194 |
| mheidari-all | 0.807 | 171 | 41 | 212 |
| Au1rxx-base64 | 0.834 | 266 | 53 | 319 |
| zhangkai | 0.87 | 20 | 3 | 23 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17148 | yes | 5.08 | 0 |
| SoliSpirit-all | 7933 | yes | 3.14 | 0 |
| Epodonios-all | 7334 | yes | 3.97 | 0 |
| DeltaKronecker-all | 7294 | yes | 5.86 | 0 |
| Surfboard-tg-mixed | 6921 | yes | 4.2 | 0 |
| barry-far-vless | 6092 | yes | 2.1 | 0 |
| Surfboard-tg-vless | 5831 | yes | 3.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 4708 | yes | 1.9 | 0 |
| mahdibland-V2RayAggregator | 4013 | yes | 2.88 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.84 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 44 |
| cn-block | 39 |
| speed | 38 |
| geo | 35 |
