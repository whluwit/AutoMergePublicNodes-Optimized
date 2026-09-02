# AutoNodes 每日报告

生成时间：2026-09-02 20:31:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 82604 |
| 去重后节点数 | 23711 |
| TCP 可达数 | 3000 |
| 真测通过数 | 547 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23711 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 35.7 |
| geo | 1.4 |
| probe | 84.3 |
| real_test | 121.4 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 146 | 139 | 7 | 95.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 17 | 15 | 2 | 88.2% |
| vless | 423 | 347 | 76 | 82.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 18 |
| 204:TimeoutError | 15 |
| cn-block:TimeoutError | 14 |
| cn-block:ClientOSError | 13 |
| 204:ProxyError | 10 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 5 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| geo:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5098 |
| ConnectionRefusedError | 907 |
| gaierror | 377 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.993 | prefer | 341 | 0.924 | 1798 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.898 | prefer | 75 | 0.827 | 7091 |
| mheidari-all | 0.863 | prefer | 118 | 0.788 | 15504 |
| DeltaKronecker-all | 0.773 | prefer | 73 | 0.699 | 7295 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 131 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4765 |
| Epodonios-all | 0.255 | observe | 0 | None | 7530 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| DeltaKronecker-all | 0.699 | 51 | 22 | 73 |
| mheidari-all | 0.788 | 93 | 25 | 118 |
| Surfboard-tg-mixed | 0.827 | 62 | 13 | 75 |
| Au1rxx-base64 | 0.924 | 315 | 26 | 341 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15504 | yes | 4.45 | 0 |
| SoliSpirit-all | 7745 | yes | 3.04 | 0 |
| Epodonios-all | 7530 | yes | 4.67 | 0 |
| DeltaKronecker-all | 7295 | yes | 5.14 | 0 |
| Surfboard-tg-mixed | 7091 | yes | 3.49 | 0 |
| barry-far-vless | 6223 | yes | 1.17 | 0 |
| Surfboard-tg-vless | 6013 | yes | 3.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4765 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 4066 | yes | 0.13 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 0.96 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 30 |
| cn-block | 29 |
| geo | 20 |
| speed | 8 |
