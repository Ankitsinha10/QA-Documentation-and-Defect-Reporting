# Manual Testing Portfolio — Ankit Kumar Sinha

> A collection of real-world manual testing projects showcasing exploratory testing, bug reporting, and UX analysis across live web applications.

---

## About Me

**QA Engineer** with 3+ years of experience in manual and automation testing across SaaS, e-commerce, and mobile platforms. I specialize in exploratory testing, accessibility auditing, and writing clear, developer-ready bug reports.

🔗 [Portfolio](https://www.ankitkumarsinha.com) · [LinkedIn](https://linkedin.com/in/ankitsinha07) · [GitHub](https://github.com/Ankitsinha10)

---

## 📁 Repository Structure

```
QA-Documentation-and-Defect-Reporting/
│
├── README.md
├── DBZ_Project_Testing/
│   └── Ankit_Sinha_DBZ_BugReports.xlsx
└── Website_Testing_Sheetal/
    └── Ankit_Sinha_Bug_Report_Sheetal_net.xlsx
```

---

## Projects

---

### 1. 🌐 Sheetal.net — Packers & Movers Website

| | |
|---|---|
| **Type of Testing** | Exploratory · UI/UX · Accessibility · Functional |
| **Environment** | macOS · Google Chrome v145 |
| **URL** | [sheetal.net](https://sheetal.net) |

**Summary:** Performed exploratory testing on a live packers and movers business website, focusing on core lead-generation flows, accessibility compliance (WCAG), and UI consistency.

#### 🔴 Bugs Found

| Bug ID | Module | Title | Severity | Priority |
|--------|--------|-------|----------|----------|
| BUG-001 | Homepage | Poor text contrast on hero banner — fails WCAG standards | Medium | High |
| BUG-002 | Homepage | Form submission fails with JS `ReferenceError` on invalid email | High | High |
| BUG-003 | Homepage | Breadcrumb navigation overlaps hero image — illegible text | Medium | Medium |
| BUG-004 | Homepage | "Call" button uses empty `#` anchor instead of `tel:` protocol | Medium | High |
| BUG-005 | Homepage | Sticky "Get Free Quote" CTA button completely unresponsive | High | High |

#### Key Findings

- **2 High severity bugs** blocking primary business conversion channels (lead form + CTA)
- `ReferenceError: Validator is not defined` exposed in browser console during form submission
- `tel:` protocol missing on phone CTA — broken on both desktop and mobile
- **3 accessibility/UI issues** impacting readability and first impressions

---

### 2. 🛒 DemoBlaze — E-Commerce Application

| | |
|---|---|
| **Type of Testing** | Exploratory · Functional · UI/UX · Validation |
| **Environment** | macOS Sequoia 15.6 · MacBook Air M1 · Chrome v142 |
| **URL** | [demoblaze.com](https://www.demoblaze.com) |
| **Scope** | Homepage · Product Listing · Cart · Checkout · Login · Contact |

**Summary:** Conducted comprehensive exploratory testing on a demo e-commerce application. Uncovered critical checkout vulnerabilities, cart persistence failures, and missing form validations across the entire purchase flow.

#### 📊 Bug Summary

| 🔴 Critical | 🟠 High | 🟡 Medium | 🟢 Low | Total |
|:-----------:|:-------:|:---------:|:------:|:-----:|
| 1 | 3 | 4 | 2 | **10** |

#### 🔴 Bugs Found

| Bug ID | Module | Title | Severity | Priority |
|--------|--------|-------|----------|----------|
| DBZ-BUG-001 | About Us > Video | Live Caption/Translate unavailable in Fullscreen mode | Medium | High |
| DBZ-BUG-002 | Cart | Cart empty after "Product added" confirmation — state not persisting | High | High |
| DBZ-BUG-003 | Homepage Pagination | "Previous" button visible & clickable on Page 1 with no action | Low | Medium |
| DBZ-BUG-004 | Cart > Checkout | **Purchase form accepts invalid payment data — no validation** | **Critical** | High |
| DBZ-BUG-005 | Header | "Welcome [username]" button has no functionality after login | Medium | High |
| DBZ-BUG-006 | About Us > Video | Play icon misaligned — top-left instead of centered | Low | Low |
| DBZ-BUG-007 | Homepage > Categories | No active state shown on selected category | Low | Low |
| DBZ-BUG-008 | Homepage > Pagination | "Previous" resets category filter — shows all products | Medium | Medium |
| DBZ-BUG-009 | Contact Form | Contact form submits with all fields empty — no validation | High | High |
| DBZ-BUG-010 | Cart > Checkout | User can place order with empty cart — results in $0 transaction | High | High |

#### 💡 Key Findings

- **Critical payment vulnerability** — checkout accepts letters/symbols in card fields, processes invalid orders successfully
- **Cart persistence failure** — products disappear when navigating to cart page
- **Empty cart checkout** — users can confirm $0 orders with no items
- **Zero validation** on both Contact form and Purchase form (client-side + server-side)
- **Accessibility gap** — Live Caption unavailable in fullscreen video mode

#### 📝 Usability Suggestions

| # | Suggestion | Module |
|---|-----------|--------|
| 1 | Highlight the active/selected category | Homepage > Categories |
| 2 | Add confirmation before removing cart items | Cart |
| 3 | Auto-focus cursor when Contact form opens | Contact Page |
| 4 | Add product sorting (price low→high / high→low) | Product Listing |
| 5 | Show cart item count badge in header | Header |
| 6 | Add loading indicator when switching categories | Homepage |

---

## 🛠️ Skills Demonstrated

`Exploratory Testing` `Functional Testing` `Accessibility Testing (WCAG)` `UI/UX Bug Identification` `Form Validation Testing` `Cross-Browser Testing` `Severity & Priority Classification` `Chrome DevTools` `Developer-Ready Bug Documentation`

---

## 🔗 Related Projects

- 🤖 [Playwright TypeScript Automation Framework](https://github.com/Ankitsinha10/Playwright-TypeScript-Automation-Framework) — Production-grade UI + API automation with POM, Allure reporting & CI/CD
- 🧪 [SauceDemo E2E Test Suite](https://github.com/Ankitsinha10/saucedemo-playwright-automation) — E2E automated scenarios with GitHub Actions CI/CD

---

*All bug evidence (screenshots/videos) linked within the Excel reports via Google Drive.*
