# AutoNodes 每日报告

生成时间：2026-08-31 22:24:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78305 |
| 去重后节点数 | 22288 |
| TCP 可达数 | 3000 |
| 真测通过数 | 609 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22288 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 31.6 |
| geo | 1.5 |
| probe | 79.9 |
| real_test | 126.0 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 19 | 3 | 86.4% |
| hysteria2 | 26 | 25 | 1 | 96.2% |
| shadowsocks | 175 | 165 | 10 | 94.3% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 27 | 26 | 1 | 96.3% |
| vless | 437 | 369 | 68 | 84.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 15 |
| geo:ClientOSError | 10 |
| cn-block:ClientOSError | 10 |
| speed:ClientOSError | 7 |
| 204:ProxyError | 5 |
| speed:TimeoutError | 4 |
| 204:ProxyConnectionError | 3 |
| geo:TimeoutError | 3 |
| speed:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4814 |
| ConnectionRefusedError | 931 |
| gaierror | 358 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.961 | prefer | 289 | 0.917 | 1182 |
| Surfboard-tg-mixed | 0.953 | prefer | 69 | 0.884 | 6899 |
| mheidari-all | 0.945 | prefer | 183 | 0.869 | 14929 |
| DeltaKronecker-all | 0.886 | prefer | 127 | 0.811 | 5904 |
| zhangkai | 0.846 | prefer | 23 | 0.87 | 144 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| Epodonios-all | 0.255 | observe | 0 | None | 7323 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7470 |

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
| DeltaKronecker-all | 0.811 | 103 | 24 | 127 |
| mheidari-all | 0.869 | 159 | 24 | 183 |
| zhangkai | 0.87 | 20 | 3 | 23 |
| Surfboard-tg-mixed | 0.884 | 61 | 8 | 69 |
| Au1rxx-base64 | 0.917 | 265 | 24 | 289 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14929 | yes | 3.67 | 0 |
| SoliSpirit-all | 7470 | yes | 2.41 | 0 |
| Epodonios-all | 7323 | yes | 3.1 | 0 |
| Surfboard-tg-mixed | 6899 | yes | 2.41 | 0 |
| barry-far-vless | 6031 | yes | 1.21 | 0 |
| DeltaKronecker-all | 5904 | yes | 4.78 | 0 |
| Surfboard-tg-vless | 5842 | yes | 2.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 1.69 | 0 |
| mahdibland-V2RayAggregator | 4025 | yes | 1.9 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 31 |
| 204 | 24 |
| geo | 15 |
| speed | 14 |
