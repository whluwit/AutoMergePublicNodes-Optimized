# AutoNodes 每日报告

生成时间：2026-08-31 12:35:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 79305 |
| 去重后节点数 | 22260 |
| TCP 可达数 | 3000 |
| 真测通过数 | 542 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22260 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 37.3 |
| geo | 1.6 |
| probe | 85.5 |
| real_test | 116.3 |
| tcp | 35.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 21 | 2 | 91.3% |
| hysteria2 | 15 | 12 | 3 | 80.0% |
| shadowsocks | 164 | 152 | 12 | 92.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 38 | 30 | 8 | 78.9% |
| vless | 391 | 323 | 68 | 82.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 15 |
| 204:ProxyError | 14 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 6 |
| geo:TimeoutError | 6 |
| cn-block:ProxyError | 5 |
| speed:ClientOSError | 4 |
| 204:ProxyConnectionError | 2 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4996 |
| ConnectionRefusedError | 891 |
| gaierror | 197 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | prefer | 304 | 0.928 | 1804 |
| zhangkai | 0.89 | prefer | 24 | 0.917 | 144 |
| mheidari-all | 0.872 | prefer | 70 | 0.8 | 14620 |
| DeltaKronecker-all | 0.858 | prefer | 61 | 0.787 | 5904 |
| Surfboard-tg-mixed | 0.836 | prefer | 174 | 0.759 | 6828 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| ermaozi | 0.256 | observe | 1 | 1.0 | 22 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| Epodonios-all | 0.255 | observe | 0 | None | 7174 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.759 | 132 | 42 | 174 |
| DeltaKronecker-all | 0.787 | 48 | 13 | 61 |
| mheidari-all | 0.8 | 56 | 14 | 70 |
| zhangkai | 0.917 | 22 | 2 | 24 |
| Au1rxx-base64 | 0.928 | 282 | 22 | 304 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14620 | yes | 4.14 | 0 |
| SoliSpirit-all | 7956 | yes | 4.97 | 0 |
| Epodonios-all | 7174 | yes | 2.92 | 0 |
| Surfboard-tg-mixed | 6828 | yes | 5.17 | 0 |
| DeltaKronecker-all | 5904 | yes | 4.3 | 0 |
| barry-far-vless | 5864 | yes | 2.5 | 0 |
| Surfboard-tg-vless | 5768 | yes | 3.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 2.27 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.08 | 0 |
| mahdibland-V2RayAggregator | 3987 | yes | 2.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 36 |
| cn-block | 27 |
| geo | 21 |
| speed | 10 |
