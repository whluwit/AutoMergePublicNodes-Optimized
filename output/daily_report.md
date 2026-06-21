# AutoNodes Daily Report

Generated at: 2026-06-21 05:01:30

## Summary

| Metric | Value |
| --- | --- |
| Health status | warning |
| Health ok | True |
| Sources healthy | 103/107 |
| Cleanup disable/downweight | 0/1 |
| Cleanup prefer/observe | 4/102 |
| Raw nodes | 71786 |
| Dedup nodes | 22143 |
| TCP ok | 937 |
| Real ok | 715 |
| Verified output | 300 |
| Global output | 300 |
| All output | 22143 |
| All output mode | full |

## Stage Durations

| Stage | Seconds |
| --- | --- |
| fetch | 4.2 |
| generate | 30.8 |
| geo | 1.3 |
| probe | 89.7 |
| real_test | 204.8 |
| tcp | 65.3 |

## Protocol Pass Rate

| Protocol | Tested | Passed | Failed | Pass Rate |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 123 | 121 | 2 | 98.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 127 | 109 | 18 | 85.8% |
| vless | 652 | 451 | 201 | 69.2% |
| vmess | 6 | 6 | 0 | 100.0% |

## Main Real-Test Errors

| Error | Count |
| --- | --- |
| speed:ClientOSError | 81 |
| geo:TimeoutError | 76 |
| geo:ClientOSError | 18 |
| cn-block:TimeoutError | 14 |
| speed:TimeoutError | 9 |
| 204:TimeoutError | 9 |
| 204:ClientOSError | 5 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP Precheck Errors

| Error | Count |
| --- | --- |
| TimeoutError | 3297 |
| ConnectionRefusedError | 662 |
| gaierror | 395 |
| OSError | 109 |

## Best Sources By Score

| Source | Score | Recommendation | Tested | Pass Rate | Parsed |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | prefer | 25 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.963 | prefer | 364 | 0.885 | 4616 |
| mheidari-all | 0.832 | prefer | 353 | 0.754 | 14773 |
| Au1rxx-base64 | 0.717 | prefer | 81 | 0.716 | 149 |
| DeltaKronecker-all | 0.482 | observe | 105 | 0.4 | 6810 |
| nscl5-all | 0.303 | observe | 1 | 1.0 | 1204 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4507 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6744 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3454 |

## Sources Needing Attention

| Source | Score | Recommendation | Tested | Pass Rate | Dead | Parsed |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-vless | 0.145 | downweight | 5 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## Source Cleanup Suggestions

| Bucket | Source | Score | Tested | Pass Rate | Dead | Reason |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.145 | 5 | 0.0 | 0 | low score with tested >= 5 |

## Worst Sources By Real-Test Pass Rate

| Source | Pass Rate | Passed | Failed | Tested |
| --- | --- | --- | --- | --- |
| Epodonios-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 5 | 5 |
| DeltaKronecker-all | 0.4 | 42 | 63 | 105 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| Au1rxx-base64 | 0.716 | 58 | 23 | 81 |
| mheidari-all | 0.754 | 266 | 87 | 353 |
| Surfboard-tg-mixed | 0.885 | 322 | 42 | 364 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 25 | 0 | 25 |

## Top Sources By Parsed Nodes

| Source | Nodes | OK | Duration | Consecutive Dead |
| --- | --- | --- | --- | --- |
| mheidari-all | 14773 | yes | 3.1 | 0 |
| Epodonios-all | 7046 | yes | 2.26 | 0 |
| DeltaKronecker-all | 6810 | yes | 3.17 | 0 |
| SoliSpirit-all | 6744 | yes | 1.43 | 0 |
| Surfboard-tg-mixed | 4616 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 4552 | yes | 1.38 | 0 |
| 10ium-ScrapeCategorize-Vless | 4507 | yes | 1.12 | 0 |
| barry-far-vless | 4153 | yes | 0.52 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 3454 | yes | 1.7 | 0 |

## Trend Alerts

No trend alerts.

## Health Alerts

### Low-pass protocols
| Protocol | Pass Rate |
| --- | --- |
| socks | 0.0 |

### Real-test error alerts
| Error | Count |
| --- | --- |
| geo | 95 |
| speed | 91 |
| cn-block | 18 |
| 204 | 18 |
