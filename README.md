<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0f3460&height=160&section=header" width="100%"/>

# QA & SDET Portfolio
## Ankit Kumar Sinha

<br/>

[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-ankitkumarsinha.com-0f3460?style=for-the-badge&logoColor=white)](https://ankitkumarsinha.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ankit%20Kumar%20Sinha-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ankitsinha07/)
[![GitHub](https://img.shields.io/badge/GitHub-Ankitsinha10-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ankitsinha10)

<br/>

<table>
  <tr>
    <td align="center"><b>3+</b><br/><sub>Years Experience</sub></td>
    <td align="center"><b>1,000+</b><br/><sub>Test Cycles</sub></td>
    <td align="center"><b>2,000+</b><br/><sub>Defects Found</sub></td>
    <td align="center"><b>3</b><br/><sub>Certifications</sub></td>
    <td align="center"><b>91%</b><br/><sub>Pass Rate</sub></td>
  </tr>
</table>

</div>

---

## 👤 About Me

**QA Automation Engineer / SDET** with 3+ years of experience across manual testing, SDET-level technical discovery, and QA documentation for international clients.

I specialise in **exploratory testing**, **structured test case design**, **buildability analysis**, **accessibility auditing**, and writing clear, developer-ready bug reports and QA discovery reports.

> *From mobile iOS onboarding flows to full-stack buildability audits — I deliver QA work that goes beyond finding bugs.*

---

## 📁 Repository Structure

```
QA-Documentation-and-Defect-Reporting/
│
├── README.md
├── iOS_Onboarding_Testing/
│   └── QA_iOS_Onboarding_Portfolio.xlsx
├── SDET_Buildability_Report/
│   └── QA_Buildability_Report_Portfolio.pdf
├── DBZ_Project_Testing/
│   └── Ankit_Sinha_DBZ_BugReports.xlsx
└── Website_Testing_Sheetal/
    └── Ankit_Sinha_Bug_Report_Sheetal_net.xlsx
```

---

## 🗂️ Projects

---

### 1. 📱 Language Learning App — iOS Onboarding Testing
#### *US Client · Confidential · March 2026*

<table>
  <tr><td><b>Type of Testing</b></td><td>Structured Test Cases · Functional · UI/UX · Edge Cases · Exploratory</td></tr>
  <tr><td><b>Platform</b></td><td>iOS · TestFlight · Physical Device</td></tr>
  <tr><td><b>Scope</b></td><td>Welcome → Sign-Up → Verification → Language → Fluency → Use Case → Milestone → Media → Pace → Time Summary → Awaits → Content Prep → Main Product Page</td></tr>
  <tr><td><b>Deliverable</b></td><td><code>QA_iOS_Onboarding_Portfolio.xlsx</code></td></tr>
</table>

**Summary:** Designed and executed a complete structured test suite for a language learning app onboarding flow (US client). Covered 62 test cases across 13 screens, discovered 9 bugs including 2 critical blockers, and delivered structured product feedback and risk analysis.

#### 📊 Test Execution Results

| Total TCs | ✅ Pass | ❌ Fail | 🐛 Bugs | 🔴 Critical | 🟠 High |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **62** | **57 (91%)** | **5 (9%)** | **9** | **2** | **3** |

#### 🔴 Bugs Found

| Bug ID | Screen | Title | Severity |
|---|---|---|:---:|
| BUG-04 | Language Selection | App freezes and **crashes** when typing in language search field | 🔴 Critical |
| BUG-06 | Verification | User **permanently locked out** after exiting before completing OTP — no recovery path | 🔴 Critical |
| BUG-08 | Milestone Selection | Two milestone cards show **identical descriptions** — data mapping error | 🟠 High |
| BUG-05 | Media Consumption | Two age groups show **identical slider values** — personalization broken | 🟠 High |
| BUG-09 | Settings | Disabling audio **silently also disables** display text — incorrectly coupled | 🟠 High |
| BUG-02 | Milestone Selection | 'Show more' button **nearly invisible** on selected card — low contrast | 🟡 Medium |
| BUG-01 | Content Library | 'Share' element looks tappable but **does nothing** — false affordance | 🟡 Medium |
| BUG-07 | Sign-Up | Error copy misleading: **'Invitation is already used'** — confusing to user | 🟢 Low |
| BUG-03 | Content Library | Hint card **text overflows** outside card boundary | 🟢 Low |

#### 💡 Key Findings

- **BUG-04 blocks 100% of users** who attempt to search for a language — complete onboarding blocker
- **BUG-06 creates permanent lockout** with no recovery path — highest user drop-off risk in the flow
- Identical milestone content undermines the core personalisation promise of the product
- Strong 8-step onboarding architecture — thoughtfully designed personalisation questionnaire

<details>
<summary><b>📋 View Structured Feedback Highlights</b></summary>

<br/>

**What Works Well:**
- Visual fluency slider with emoji system (🐣 → 🚶 → 🏃) — intuitive and low friction
- Time Summary screen reframes daily learning commitment as achievable — smart product thinking
- 8-step questionnaire collects meaningful signals for genuine personalisation

**UX Friction Points:**
- Error messages are grammatically incorrect and unhelpful — users don't know what to do next
- 'Show more' invisible on selected milestone card — uninformed goal selection risk
- Legend label truncated on Time Summary chart — damages polish before product entry

**Risk Areas for Next Test Cycle:**
- Personalisation accuracy end-to-end — mapping layer appears fragile
- Google Sign-In OAuth edge cases — not yet tested
- Web app / Android version — not yet available for this build

</details>

---

### 2. 🔧 TF2 Item Marketplace — SDET Buildability Report
#### *US Client · Confidential · March 2026*

<table>
  <tr><td><b>Type of Review</b></td><td>SDET Buildability & Setup Readiness · Code Review · Hands-On Build Testing · Production Smoke Test</td></tr>
  <tr><td><b>Repositories</b></td><td>Legacy Repo + Revamped Repo</td></tr>
  <tr><td><b>Stack</b></td><td>Python · FastAPI · React 19 · Vite · Tailwind CSS v4 · Redis · MySQL · Stripe · Twilio · Sentry · CI/CD</td></tr>
  <tr><td><b>Deliverable</b></td><td><code>QA_Buildability_Report_Portfolio.pdf</code></td></tr>
</table>

**Summary:** Full SDET-level technical discovery across two codebases for a live US-client marketplace. Assessed buildability, dependency health, environment configuration, CI/CD pipeline, and smoke tested the live production site. Delivered as Deliverable #1 of the QA engagement.

#### 📊 Repository Comparison

| Category | Legacy Repo | Revamped Repo |
|---|:---:|:---:|
| pip install | ❌ FAILED — 2 packages missing | ✅ PASSED — all 17 packages |
| Documentation | ❌ No setup guide | ✅ Inline comments throughout |
| Backend startup | ❌ Crashed on missing env keys | ✅ Reaches DB init cleanly |
| Caching | ❌ None | ✅ Redis integrated |
| Error tracking | ❌ Not present | ✅ Sentry integrated |
| CI/CD pipeline | ❌ Not present | ✅ Full auto-deploy |
| Test automation | ❌ None | ❌ None — to build |
| Time to first build | ⚠️ ~2 hours (manual fixes) | ✅ ~10 minutes |

#### 🔴 Production UI Bugs Found (Live Smoke Test)

| # | Bug | Severity |
|---|---|:---:|
| 1 | 'Let's Get Started' CTA → **404 error** (route `/getstarted` not defined in App.jsx) | 🔴 High |
| 2 | 'Sell Your Items' button → **404 error** (route `/sell` not defined in App.jsx) | 🔴 High |
| 3 | Footer Steam Sign-In → **blank white page** (incorrect URL / missing route) | 🔴 High |
| 4 | 'About' nav → **broken scroll-to-section** on homepage | 🟡 Medium |
| 5 | 'FAQ' nav → **broken scroll-to-section** on homepage | 🟡 Medium |
| 6 | 'Inventory Area' footer link → **404 error** | 🟡 Medium |
| 7 | Footer displays **Lorem Ipsum** placeholder text — not updated | 🟡 Medium |

#### 💡 Key Findings

- **Zero test automation** across both repos — full Playwright + pytest framework to be built from scratch
- Missing `cryptography` and `resend` in legacy `requirements.txt` — undocumented, causes crash on fresh install
- CI/CD uses HMAC webhook signature validation + zero-downtime atomic frontend swap — well-engineered
- 3 High severity bugs directly block core user onboarding and revenue journey on live site

<details>
<summary><b>📋 View QA Risk Matrix</b></summary>

<br/>

| Priority | Area | Risk |
|:---:|---|---|
| 🔴 HIGH | Stripe Payment Flow | Deposits, withdrawals, KYC — financial risk if untested |
| 🔴 HIGH | Steam Authentication | OpenID session handling and security must be validated |
| 🔴 HIGH | Broken CTA Routes | 3× 404 bugs block core user journey — fix before testing |
| 🟡 MED | Redis Cache | Stale data and cache invalidation risks |
| 🟡 MED | Twilio SMS | OTP delivery, expiry, and rate limiting |
| 🟡 MED | reCAPTCHA v3 | Score thresholds and bypass scenarios |

</details>

---

### 3. 🌐 Sheetal.net — Packers & Movers Website

<table>
  <tr><td><b>Type of Testing</b></td><td>Exploratory · UI/UX · Accessibility · Functional</td></tr>
  <tr><td><b>Environment</b></td><td>macOS · Google Chrome v145</td></tr>
  <tr><td><b>URL</b></td><td><a href="https://sheetal.net">sheetal.net</a></td></tr>
  <tr><td><b>Deliverable</b></td><td><code>Ankit_Sinha_Bug_Report_Sheetal_net.xlsx</code></td></tr>
</table>

**Summary:** Exploratory testing on a live packers and movers business website focusing on core lead-generation flows, WCAG accessibility compliance, and UI consistency.

#### 🔴 Bugs Found

| Bug ID | Module | Title | Severity | Priority |
|---|---|---|:---:|:---:|
| BUG-001 | Homepage | Poor text contrast on hero banner — fails WCAG standards | 🟡 Medium | High |
| BUG-002 | Homepage | Form submission fails with JS `ReferenceError` on invalid email | 🟠 High | High |
| BUG-003 | Homepage | Breadcrumb navigation overlaps hero image — illegible text | 🟡 Medium | Medium |
| BUG-004 | Homepage | "Call" button uses empty `#` anchor instead of `tel:` protocol | 🟡 Medium | High |
| BUG-005 | Homepage | Sticky "Get Free Quote" CTA button completely unresponsive | 🟠 High | High |

#### 💡 Key Findings

- **2 High severity bugs** blocking primary business conversion channels (lead form + CTA)
- `ReferenceError: Validator is not defined` exposed in browser console during form submission
- `tel:` protocol missing on phone CTA — broken on both desktop and mobile
- **3 accessibility/UI issues** impacting readability and first impressions

---

### 4. 🛒 DemoBlaze — E-Commerce Application

<table>
  <tr><td><b>Type of Testing</b></td><td>Exploratory · Functional · UI/UX · Validation</td></tr>
  <tr><td><b>Environment</b></td><td>macOS Sequoia 15.6 · MacBook Air M1 · Chrome v142</td></tr>
  <tr><td><b>URL</b></td><td><a href="https://demoblaze.com">demoblaze.com</a></td></tr>
  <tr><td><b>Scope</b></td><td>Homepage · Product Listing · Cart · Checkout · Login · Contact</td></tr>
  <tr><td><b>Deliverable</b></td><td><code>Ankit_Sinha_DBZ_BugReports.xlsx</code></td></tr>
</table>

**Summary:** Comprehensive exploratory testing on a demo e-commerce application. Uncovered critical checkout vulnerabilities, cart persistence failures, and missing form validations across the entire purchase flow.

#### 📊 Bug Summary

| 🔴 Critical | 🟠 High | 🟡 Medium | 🟢 Low | Total |
|:---:|:---:|:---:|:---:|:---:|
| 1 | 3 | 4 | 2 | **10** |

#### 🔴 Bugs Found

| Bug ID | Module | Title | Severity |
|---|---|---|:---:|
| DBZ-BUG-004 | Cart > Checkout | Purchase form accepts invalid payment data — **no validation** | 🔴 Critical |
| DBZ-BUG-002 | Cart | Cart empty after "Product added" confirmation — **state not persisting** | 🟠 High |
| DBZ-BUG-009 | Contact Form | Contact form submits with **all fields empty** — no validation | 🟠 High |
| DBZ-BUG-010 | Cart > Checkout | User can place order with **empty cart** — results in $0 transaction | 🟠 High |
| DBZ-BUG-001 | About Us > Video | Live Caption/Translate **unavailable in Fullscreen** mode | 🟡 Medium |
| DBZ-BUG-005 | Header | "Welcome [username]" button has **no functionality** after login | 🟡 Medium |
| DBZ-BUG-008 | Homepage Pagination | "Previous" **resets category filter** — shows all products | 🟡 Medium |
| DBZ-BUG-003 | Homepage Pagination | "Previous" button visible & clickable on Page 1 — **no action** | 🟢 Low |
| DBZ-BUG-006 | About Us > Video | Play icon **misaligned** — top-left instead of centered | 🟢 Low |
| DBZ-BUG-007 | Homepage > Categories | **No active state** shown on selected category | 🟢 Low |

#### 💡 Key Findings

- **Critical payment vulnerability** — checkout accepts letters/symbols in card fields, processes invalid orders
- **Cart persistence failure** — products disappear when navigating to cart page
- **Empty cart checkout** — users can confirm $0 orders with no items
- **Zero validation** on both Contact form and Purchase form (client-side + server-side)

<details>
<summary><b>📝 View Usability Suggestions</b></summary>

<br/>

| # | Suggestion | Module |
|---|---|---|
| 1 | Highlight the active/selected category | Homepage > Categories |
| 2 | Add confirmation before removing cart items | Cart |
| 3 | Auto-focus cursor when Contact form opens | Contact Page |
| 4 | Add product sorting (price low→high / high→low) | Product Listing |
| 5 | Show cart item count badge in header | Header |
| 6 | Add loading indicator when switching categories | Homepage |

</details>

---

## 🛠️ Skills Demonstrated

<div align="center">

![Exploratory Testing](https://img.shields.io/badge/Exploratory%20Testing-0f3460?style=flat-square&logoColor=white)
![Structured Test Cases](https://img.shields.io/badge/Structured%20Test%20Cases-0f3460?style=flat-square&logoColor=white)
![Functional Testing](https://img.shields.io/badge/Functional%20Testing-0f3460?style=flat-square&logoColor=white)
![SDET Buildability Analysis](https://img.shields.io/badge/SDET%20Buildability%20Analysis-16213e?style=flat-square&logoColor=white)
![CI/CD Pipeline Review](https://img.shields.io/badge/CI%2FCD%20Pipeline%20Review-16213e?style=flat-square&logoColor=white)
![Dependency Auditing](https://img.shields.io/badge/Dependency%20Auditing-16213e?style=flat-square&logoColor=white)
![Risk Stratification](https://img.shields.io/badge/Risk%20Stratification-16213e?style=flat-square&logoColor=white)
![iOS TestFlight Testing](https://img.shields.io/badge/iOS%20TestFlight%20Testing-1a1a2e?style=flat-square&logoColor=white)
![Accessibility Testing WCAG](https://img.shields.io/badge/Accessibility%20Testing%20WCAG-1a1a2e?style=flat-square&logoColor=white)
![UI/UX Bug Identification](https://img.shields.io/badge/UI%2FUX%20Bug%20Identification-1a1a2e?style=flat-square&logoColor=white)
![Form Validation Testing](https://img.shields.io/badge/Form%20Validation%20Testing-1a1a2e?style=flat-square&logoColor=white)
![Chrome DevTools](https://img.shields.io/badge/Chrome%20DevTools-1a1a2e?style=flat-square&logo=googlechrome&logoColor=white)
![Severity & Priority Classification](https://img.shields.io/badge/Severity%20%26%20Priority-1a1a2e?style=flat-square&logoColor=white)
![Developer-Ready Bug Documentation](https://img.shields.io/badge/Developer--Ready%20Docs-1a1a2e?style=flat-square&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=flat-square&logo=playwright&logoColor=white)

</div>

---

## 🔗 Related Projects

- **[Playwright TypeScript Automation Framework](https://github.com/Ankitsinha10/Playwright-TypeScript-Automation-Framework)** — Production-grade UI + API automation with POM, Allure reporting & CI/CD
- **[SauceDemo E2E Test Suite](https://github.com/Ankitsinha10/saucedemo-playwright-automation)** — E2E automated scenarios with GitHub Actions CI/CD

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0f3460&height=100&section=footer" width="100%"/>

<sub>All bug evidence (screenshots/videos) linked within the Excel reports via Google Drive. &nbsp;|&nbsp; Client identifiers have been anonymised in projects 1 and 2.</sub>

</div>
