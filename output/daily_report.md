# AutoNodes 每日报告

生成时间：2026-09-05 09:57:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 83214 |
| 去重后节点数 | 22116 |
| TCP 可达数 | 3000 |
| 真测通过数 | 546 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22116 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 34.4 |
| geo | 1.4 |
| probe | 75.8 |
| real_test | 121.4 |
| tcp | 37.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 28 | 0 | 100.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 172 | 158 | 14 | 91.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 35 | 32 | 3 | 91.4% |
| vless | 413 | 311 | 102 | 75.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 43 |
| geo:ClientOSError | 20 |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 11 |
| speed:TimeoutError | 7 |
| geo:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:ClientOSError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5113 |
| ConnectionRefusedError | 887 |
| gaierror | 344 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.934 | prefer | 309 | 0.864 | 1813 |
| Surfboard-tg-mixed | 0.852 | prefer | 182 | 0.775 | 7332 |
| mheidari-all | 0.836 | prefer | 125 | 0.76 | 15508 |
| DeltaKronecker-all | 0.781 | prefer | 18 | 0.778 | 6212 |
| tg-oneclickvpnkeys | 0.444 | observe | 5 | 1.0 | 118 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7753 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8562 |

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
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.76 | 95 | 30 | 125 |
| Surfboard-tg-mixed | 0.775 | 141 | 41 | 182 |
| DeltaKronecker-all | 0.778 | 14 | 4 | 18 |
| Au1rxx-base64 | 0.864 | 267 | 42 | 309 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15508 | yes | 3.26 | 0 |
| SoliSpirit-all | 8562 | yes | 2.1 | 0 |
| Epodonios-all | 7753 | yes | 3.45 | 0 |
| Surfboard-tg-mixed | 7332 | yes | 2.75 | 0 |
| barry-far-vless | 6302 | yes | 0.94 | 0 |
| DeltaKronecker-all | 6212 | yes | 3.82 | 0 |
| Surfboard-tg-vless | 6108 | yes | 2.38 | 0 |
| 10ium-ScrapeCategorize-Vless | 4887 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 4095 | yes | 2.03 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 58 |
| geo | 27 |
| cn-block | 25 |
| speed | 10 |
