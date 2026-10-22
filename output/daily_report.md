# AutoNodes 每日报告

生成时间：2026-10-22 16:40:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96308 |
| 去重后节点数 | 26641 |
| TCP 可达数 | 3000 |
| 真测通过数 | 314 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26641 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 82.2 |
| geo | 1.6 |
| probe | 244.8 |
| real_test | 199.7 |
| tcp | 45.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 45 | 13 | 32 | 28.9% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 148 | 131 | 17 | 88.5% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 50 | 39 | 11 | 78.0% |
| vless | 185 | 117 | 68 | 63.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 26 |
| 204:ProxyError | 25 |
| cn-block:TimeoutError | 18 |
| speed:TimeoutError | 16 |
| speed:ClientOSError | 15 |
| 204:ProxyConnectionError | 12 |
| geo:ClientOSError | 10 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6607 |
| ConnectionRefusedError | 1032 |
| OSError | 236 |
| gaierror | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | prefer | 40 | 0.875 | 24062 |
| Au1rxx-base64 | 0.842 | prefer | 249 | 0.783 | 1529 |
| Surfboard-tg-mixed | 0.743 | prefer | 102 | 0.667 | 7043 |
| ermaozi | 0.321 | observe | 45 | 0.289 | 573 |
| DeltaKronecker-all | 0.3 | observe | 5 | 0.4 | 3641 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 7538 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10202 |

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
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.289 | 13 | 32 | 45 |
| DeltaKronecker-all | 0.4 | 2 | 3 | 5 |
| Surfboard-tg-mixed | 0.667 | 68 | 34 | 102 |
| Au1rxx-base64 | 0.783 | 195 | 54 | 249 |
| mheidari-all | 0.875 | 35 | 5 | 40 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24062 | yes | 5.23 | 0 |
| SoliSpirit-all | 10202 | yes | 4.24 | 0 |
| Epodonios-all | 7538 | yes | 6.18 | 0 |
| Surfboard-tg-mixed | 7043 | yes | 4.32 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.06 | 0 |
| barry-far-vless | 5601 | yes | 1.3 | 0 |
| Surfboard-tg-vless | 5382 | yes | 4.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.09 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 2.74 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 66 |
| speed | 31 |
| cn-block | 22 |
| geo | 12 |
