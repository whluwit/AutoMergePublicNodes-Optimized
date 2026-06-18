# AutoNodes Daily Report

Generated at: 2026-06-18 04:53:22

## Summary

| Metric | Value |
| --- | --- |
| Health status | warning |
| Health ok | True |
| Sources healthy | 64/64 |
| Cleanup disable/downweight | 0/1 |
| Cleanup prefer/observe | 4/59 |
| Raw nodes | 69566 |
| Dedup nodes | 22438 |
| TCP ok | 806 |
| Real ok | 622 |
| Verified output | 300 |
| Global output | 300 |
| All output | 22438 |
| All output mode | full |

## Stage Durations

| Stage | Seconds |
| --- | --- |
| fetch | 3.7 |
| generate | 17.5 |
| geo | 1.3 |
| probe | 94.9 |
| real_test | 23.1 |
| tcp | 63.9 |

## Protocol Pass Rate

| Protocol | Tested | Passed | Failed | Pass Rate |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 130 | 123 | 7 | 94.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 130 | 113 | 17 | 86.9% |
| vless | 512 | 353 | 159 | 68.9% |
| vmess | 5 | 5 | 0 | 100.0% |

## Main Real-Test Errors

| Error | Count |
| --- | --- |
| general:unknown | 176 |
| geo:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| cn-block:TimeoutError | 1 |

## TCP Precheck Errors

| Error | Count |
| --- | --- |
| TimeoutError | 3234 |
| ConnectionRefusedError | 634 |
| gaierror | 323 |
| OSError | 58 |

## Best Sources By Score

| Source | Score | Recommendation | Tested | Pass Rate | Parsed |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | prefer | 25 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.95 | prefer | 345 | 0.872 | 4586 |
| mheidari-all | 0.86 | prefer | 212 | 0.783 | 13927 |
| Au1rxx-base64 | 0.855 | prefer | 78 | 0.859 | 126 |
| DeltaKronecker-all | 0.52 | observe | 139 | 0.439 | 7763 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4274 |
| Epodonios-all | 0.255 | observe | 0 | None | 6401 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3977 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 5959 |

## Sources Needing Attention

| Source | Score | Recommendation | Tested | Pass Rate | Dead | Parsed |
| --- | --- | --- | --- | --- | --- | --- |
| ninja-vless | 0.145 | downweight | 5 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tonykong-base64 | 0.175 | observe | 0 | None | 0 | 5 |
| tonykong-clash | 0.175 | observe | 0 | None | 0 | 5 |
| Barabama-we | 0.176 | observe | 0 | None | 0 | 23 |
| Mr8AHAL | 0.176 | observe | 0 | None | 0 | 26 |
| Pawdroid | 0.176 | observe | 0 | None | 0 | 20 |
| abc-configs-readme-latest30 | 0.176 | observe | 0 | None | 0 | 22 |
| barabama-nodefree | 0.176 | observe | 0 | None | 0 | 23 |

## Source Cleanup Suggestions

| Bucket | Source | Score | Tested | Pass Rate | Dead | Reason |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.145 | 5 | 0.0 | 0 | low score with tested >= 5 |

## Worst Sources By Real-Test Pass Rate

| Source | Pass Rate | Passed | Failed | Tested |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 5 | 5 |
| DeltaKronecker-all | 0.439 | 61 | 78 | 139 |
| mheidari-all | 0.783 | 166 | 46 | 212 |
| Au1rxx-base64 | 0.859 | 67 | 11 | 78 |
| Surfboard-tg-mixed | 0.872 | 301 | 44 | 345 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 25 | 0 | 25 |

## Top Sources By Parsed Nodes

| Source | Nodes | OK | Duration | Consecutive Dead |
| --- | --- | --- | --- | --- |
| mheidari-all | 13927 | yes | 3.49 | 0 |
| DeltaKronecker-all | 7763 | yes | 3.58 | 0 |
| Epodonios-all | 6401 | yes | 2.32 | 0 |
| SoliSpirit-all | 5959 | yes | 2.03 | 0 |
| Surfboard-tg-mixed | 4586 | yes | 2.03 | 0 |
| mahdibland-V2RayAggregator | 4541 | yes | 1.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 4274 | yes | 1.56 | 0 |
| barry-far-vless | 4240 | yes | 1.76 | 0 |
| MatinGhanbari-all-sub | 3977 | yes | 0.76 | 0 |
| Surfboard-tg-vless | 3590 | yes | 2.14 | 0 |

## Trend Alerts

No trend alerts.

## Health Alerts

### Real-test error alerts
| Error | Count |
| --- | --- |
| general | 176 |
| geo | 4 |
| cn-block | 2 |
| 204 | 2 |
