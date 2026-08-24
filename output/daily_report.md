# AutoNodes 每日报告

生成时间：2026-08-24 06:51:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 78516 |
| 去重后节点数 | 21926 |
| TCP 可达数 | 3000 |
| 真测通过数 | 715 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21926 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 36.7 |
| geo | 1.4 |
| probe | 58.7 |
| real_test | 173.2 |
| tcp | 34.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 201 | 185 | 16 | 92.0% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 78 | 67 | 11 | 85.9% |
| vless | 654 | 324 | 330 | 49.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 154 |
| geo:ClientOSError | 64 |
| speed:ClientOSError | 62 |
| speed:TimeoutError | 28 |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 10 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4864 |
| ConnectionRefusedError | 821 |
| gaierror | 265 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| Au1rxx-base64 | 0.966 | prefer | 379 | 0.9 | 1718 |
| Surfboard-tg-mixed | 0.868 | prefer | 144 | 0.792 | 6363 |
| mheidari-all | 0.84 | prefer | 17 | 0.882 | 14629 |
| DeltaKronecker-all | 0.393 | observe | 416 | 0.312 | 5914 |
| nscl5-all | 0.309 | observe | 3 | 0.667 | 1008 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 177 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4899 |
| Epodonios-all | 0.255 | observe | 0 | None | 6867 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.312 | 130 | 286 | 416 |
| nscl5-all | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.792 | 114 | 30 | 144 |
| mheidari-all | 0.882 | 15 | 2 | 17 |
| Au1rxx-base64 | 0.9 | 341 | 38 | 379 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14629 | yes | 3.09 | 0 |
| SoliSpirit-all | 7231 | yes | 3.38 | 0 |
| Epodonios-all | 6867 | yes | 3.27 | 0 |
| Surfboard-tg-mixed | 6363 | yes | 2.68 | 0 |
| DeltaKronecker-all | 5914 | yes | 3.74 | 0 |
| barry-far-vless | 5530 | yes | 1.74 | 0 |
| Surfboard-tg-vless | 5242 | yes | 3.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 4899 | yes | 2.25 | 0 |
| mahdibland-V2RayAggregator | 4097 | yes | 0.23 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 218 |
| speed | 92 |
| cn-block | 27 |
| 204 | 23 |
