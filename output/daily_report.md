# AutoNodes 每日报告

生成时间：2026-08-30 03:19:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 86414 |
| 去重后节点数 | 21970 |
| TCP 可达数 | 3000 |
| 真测通过数 | 772 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21970 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 50.2 |
| geo | 1.5 |
| probe | 58.0 |
| real_test | 166.8 |
| tcp | 35.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 187 | 181 | 6 | 96.8% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 19 | 17 | 2 | 89.5% |
| vless | 748 | 521 | 227 | 69.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 72 |
| geo:ClientOSError | 49 |
| speed:TimeoutError | 38 |
| cn-block:TimeoutError | 25 |
| speed:ClientOSError | 17 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 8 |
| 204:TimeoutError | 7 |
| cn-block:ProxyError | 5 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 3 |
| geo:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5055 |
| ConnectionRefusedError | 884 |
| gaierror | 207 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | prefer | 387 | 0.917 | 1860 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.832 | prefer | 208 | 0.755 | 6910 |
| DeltaKronecker-all | 0.797 | prefer | 97 | 0.722 | 4926 |
| mheidari-all | 0.65 | observe | 284 | 0.57 | 18105 |
| nscl5-all | 0.349 | observe | 3 | 0.667 | 4310 |
| tg-oneclickvpnkeys | 0.318 | observe | 2 | 1.0 | 169 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4635 |
| Epodonios-all | 0.255 | observe | 0 | None | 7323 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.57 | 162 | 122 | 284 |
| nscl5-all | 0.667 | 2 | 1 | 3 |
| DeltaKronecker-all | 0.722 | 70 | 27 | 97 |
| Surfboard-tg-mixed | 0.755 | 157 | 51 | 208 |
| Au1rxx-base64 | 0.917 | 355 | 32 | 387 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18105 | yes | 4.11 | 0 |
| SoliSpirit-all | 7549 | yes | 2.62 | 0 |
| Epodonios-all | 7323 | yes | 4.28 | 0 |
| Surfboard-tg-mixed | 6910 | yes | 3.23 | 0 |
| barry-far-vless | 5912 | yes | 0.97 | 0 |
| Surfboard-tg-vless | 5726 | yes | 3.03 | 0 |
| DeltaKronecker-all | 4926 | yes | 4.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 4635 | yes | 1.21 | 0 |
| nscl5-all | 4310 | yes | 1.08 | 0 |
| mahdibland-V2RayAggregator | 4012 | yes | 2.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 124 |
| speed | 58 |
| cn-block | 38 |
| 204 | 19 |
