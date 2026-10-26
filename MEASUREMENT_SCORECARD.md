# GroupChat | Evidence and Measurement Scorecard

**As-of:** October 26, 2026 · **Artifact version:** 1.1 · **Data status:** Defined metrics, not a live analytics dashboard.

## What we can substantiate now

| Indicator | Evidence | Interpretation |
| --- | --- | --- |
| Hosted delivery | Releases recorded through **v65** | Release history, not an accepted adoption outcome |
| v63 automated validation | **79/79** scoped tests passed | Automated suite scope only, not comprehensive user/device acceptance |
| v65 automated validation | **8/8** targeted checks passed | Account-help/rendered tests only |
| Affected-user/device signoff | **Pending at last documented review** | Cannot claim fully resolved recovery or iPhone behavior |
| End-to-end cross-user and returning-user acceptance | **Incomplete at last documented review** | Product reliability gate remains |
| Signup conversion, activation, D7 retention | **Not measured/published** | No invented percentages or sample sizes |

## Future performance measures (definitions only)

| Measure | Calculation | Required evidence | Status |
| --- | --- | --- | --- |
| Signup completion | Eligible completed signups / unique eligible signup starters | Privacy-reviewed signup events; cohort and time window | Planned |
| Activation | New accounts creating a permitted first post within 7 days / eligible new accounts | First-post event tied to privacy-safe user identifier | Planned |
| Cross-user delivery | Test posts confirmed visible by another authorized account / controlled cross-user test posts | Two-account test evidence; no private post contents | Pending real-user acceptance |
| D7 retention | Activated accounts active in next 7-day window / activated accounts eligible for full observation | Return actions; fixed cohort window | Planned |

**Do not interpret "not measured" as 0%**. There are no defensible published numerator, denominator, sampling window or baseline values yet.

## Decision gate

Do not expand recruitment solely because build checks pass. First verify new-user, returning-user and cross-user journeys on real devices. Then instrument a controlled 14-day cohort and compare conversion, activation, reliability and retention.

[Visual product story](PRODUCT_FLOW.md) · [Validation plan](VALIDATION_PLAN.md) · [Evidence policy](GOVERNANCE.md)
