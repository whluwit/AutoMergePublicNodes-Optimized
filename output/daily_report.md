# AutoNodes Daily Report

Generated at: 2026-06-20 19:52:48

## Summary

| Metric | Value |
| --- | --- |
| Health status | warning |
| Health ok | True |
| Sources healthy | 103/107 |
| Cleanup disable/downweight | 0/0 |
| Cleanup prefer/observe | 4/103 |
| Raw nodes | 72582 |
| Dedup nodes | 22076 |
| TCP ok | 766 |
| Real ok | 604 |
| Verified output | 300 |
| Global output | 300 |
| All output | 22076 |
| All output mode | full |

## Stage Durations

| Stage | Seconds |
| --- | --- |
| fetch | 4.5 |
| generate | 36.4 |
| geo | 1.3 |
| probe | 102.2 |
| real_test | 218.3 |
| tcp | 62.8 |

## Protocol Pass Rate

| Protocol | Tested | Passed | Failed | Pass Rate |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 96 | 86 | 10 | 89.6% |
| socks | 24 | 23 | 1 | 95.8% |
| trojan | 84 | 34 | 50 | 40.5% |
| vless | 529 | 428 | 101 | 80.9% |
| vmess | 6 | 6 | 0 | 100.0% |

## Main Real-Test Errors

| Error | Count |
| --- | --- |
| speed:ClientOSError | 56 |
| 204:TimeoutError | 34 |
| 204:ProxyError | 14 |
| speed:TimeoutError | 13 |
| geo:TimeoutError | 11 |
| cn-block:TimeoutError | 11 |
| 204:ClientOSError | 10 |
| geo:ClientOSError | 7 |
| cn-block:ClientOSError | 4 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP Precheck Errors

| Error | Count |
| --- | --- |
| TimeoutError | 3230 |
| ConnectionRefusedError | 664 |
| gaierror | 386 |
| OSError | 88 |

## Best Sources By Score

| Source | Score | Recommendation | Tested | Pass Rate | Parsed |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | prefer | 25 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.89 | prefer | 393 | 0.812 | 4899 |
| Au1rxx-base64 | 0.851 | prefer | 63 | 0.857 | 115 |
| mheidari-all | 0.823 | prefer | 259 | 0.745 | 14839 |
| DeltaKronecker-all | 0.542 | observe | 24 | 0.458 | 6810 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4507 |
| Epodonios-all | 0.255 | observe | 0 | None | 7191 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6750 |

## Sources Needing Attention

| Source | Score | Recommendation | Tested | Pass Rate | Dead | Parsed |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |

## Worst Sources By Real-Test Pass Rate

| Source | Pass Rate | Passed | Failed | Tested |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.458 | 11 | 13 | 24 |
| mheidari-all | 0.745 | 193 | 66 | 259 |
| Surfboard-tg-mixed | 0.812 | 319 | 74 | 393 |
| Au1rxx-base64 | 0.857 | 54 | 9 | 63 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 25 | 0 | 25 |

## Top Sources By Parsed Nodes

| Source | Nodes | OK | Duration | Consecutive Dead |
| --- | --- | --- | --- | --- |
| mheidari-all | 14839 | yes | 3.47 | 0 |
| Epodonios-all | 7191 | yes | 2.08 | 0 |
| DeltaKronecker-all | 6810 | yes | 3.39 | 0 |
| SoliSpirit-all | 6750 | yes | 2.19 | 0 |
| Surfboard-tg-mixed | 4899 | yes | 1.75 | 0 |
| mahdibland-V2RayAggregator | 4552 | yes | 0.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 4507 | yes | 1.62 | 0 |
| barry-far-vless | 4377 | yes | 1.12 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.93 | 0 |
| Surfboard-tg-vless | 3683 | yes | 0.99 | 0 |

## Trend Alerts

No trend alerts.

## Health Alerts

### Real-test error alerts
| Error | Count |
| --- | --- |
| speed | 70 |
| 204 | 58 |
| geo | 19 |
| cn-block | 15 |
