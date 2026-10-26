# Acceptance and Measurement Plan

**Hypothesis:** If an invited member can reliably register, return and publish content visible to another authorized member, the beta has a foundation for repeated group participation.

## Required journeys

| Journey | Acceptance standard | Proof required |
| --- | --- | --- |
| New invitee | Registers, enters canonical group, publishes permitted content | Real tester, date, browser/device, outcome |
| Returning member | Reopens or logs in without losing relevant membership | Repeat session/cross-device evidence |
| Another group member | Sees permitted post or reply | Separate authorized account |
| Account recovery | Valid path works; invalid or expired attempts fail safely | Positive and negative tests, affected-user signoff |
| Mobile layout | Core feed/group/profile controls work in portrait | Physical mobile browser checks |

A successful build or passing targeted test **does not** replace real-user acceptance.

## Minimal analytics events

| Event | Purpose |
| --- | --- |
| `signup_completed` | Measure registration completion |
| `login_completed` | Observe return access |
| `first_post_created` | Measure activation |
| `post_visible_to_member` | Validate cross-user delivery |

Allowed event metadata: privacy-safe random user identifier, time, invite cohort and post type. Do **not** include email, real name, message body, passwords, reset codes or private invite links.

## Proposed measures

- **Signup completion:** successfully registered invitees / unique eligible invite starters.
- **Activation:** invitees who make an initial permitted post within seven days / invitees who successfully register.
- **Returning activity:** activated users with a meaningful action in the subsequent seven-day observation window / activated users eligible for that window.
- **Reliability:** failed access and cross-user delivery journeys tracked as separate quality metrics.

No observed rates, cohort sizes or retention outcomes are claimed in this case study.

## Recruitment gate

Hold expanded beta recruitment until access, cross-user visibility and returning-user acceptance are demonstrated with real testers and analytics collection is privacy-reviewed.
