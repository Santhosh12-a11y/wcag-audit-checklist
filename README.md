# ✅ WCAG 2.1/2.2 Accessibility Audit Checklist

A comprehensive checklist for conducting web accessibility audits aligned with **WCAG 2.1/2.2** and **Section 508** standards.

> Maintained by [Santhosh K](https://github.com/santhosh-a11y) — Accessibility QA Analyst | DHS Trusted Tester

---

## 📌 How to Use This Checklist

- ✅ Pass — Criterion is met
- ❌ Fail — Criterion is not met (raise a defect)
- ⚠️ Partial — Criterion is partially met
- N/A — Not applicable to the page/component being tested

---

## 1️⃣ Perceivable

### 1.1 Text Alternatives
| # | Criteria | Level | Status |
|---|---|---|---|
| 1.1.1 | All images have meaningful alt text | A | ☐ |
| 1.1.1 | Decorative images have empty alt (`alt=""`) | A | ☐ |
| 1.1.1 | Complex images have extended descriptions | A | ☐ |
| 1.1.1 | Icons with meaning have accessible labels | A | ☐ |

### 1.2 Time-Based Media
| # | Criteria | Level | Status |
|---|---|---|---|
| 1.2.1 | Audio-only content has a transcript | A | ☐ |
| 1.2.2 | Videos have captions | A | ☐ |
| 1.2.3 | Videos have audio descriptions or transcript | A | ☐ |
| 1.2.5 | Pre-recorded videos have audio descriptions | AA | ☐ |

### 1.3 Adaptable
| # | Criteria | Level | Status |
|---|---|---|---|
| 1.3.1 | Headings are properly structured (H1–H6) | A | ☐ |
| 1.3.1 | Lists are marked up as `<ul>`, `<ol>`, `<dl>` | A | ☐ |
| 1.3.1 | Tables have proper headers (`<th>`, scope) | A | ☐ |
| 1.3.1 | Forms have associated labels | A | ☐ |
| 1.3.2 | Reading order is logical | A | ☐ |
| 1.3.3 | Instructions don't rely on shape/color alone | A | ☐ |
| 1.3.4 | Content is not restricted to one orientation | AA | ☐ |
| 1.3.5 | Input fields have autocomplete attributes | AA | ☐ |

### 1.4 Distinguishable
| # | Criteria | Level | Status |
|---|---|---|---|
| 1.4.1 | Color is not the only way to convey info | A | ☐ |
| 1.4.2 | Audio doesn't auto-play for more than 3 seconds | A | ☐ |
| 1.4.3 | Normal text contrast ratio is at least 4.5:1 | AA | ☐ |
| 1.4.4 | Large text contrast ratio is at least 3:1 | AA | ☐ |
| 1.4.4 | Text can be resized up to 200% without loss | AA | ☐ |
| 1.4.5 | Text is used instead of images of text | AA | ☐ |
| 1.4.10 | Content reflows at 320px without horizontal scroll | AA | ☐ |
| 1.4.11 | Non-text contrast ratio is at least 3:1 | AA | ☐ |
| 1.4.12 | Text spacing can be adjusted without loss | AA | ☐ |
| 1.4.13 | Hover/focus content is dismissible and persistent | AA | ☐ |

---

## 2️⃣ Operable

### 2.1 Keyboard Accessible
| # | Criteria | Level | Status |
|---|---|---|---|
| 2.1.1 | All functionality is accessible via keyboard | A | ☐ |
| 2.1.2 | No keyboard trap exists | A | ☐ |
| 2.1.4 | Single-key shortcuts can be turned off/remapped | A | ☐ |

### 2.2 Enough Time
| # | Criteria | Level | Status |
|---|---|---|---|
| 2.2.1 | Time limits can be turned off or extended | A | ☐ |
| 2.2.2 | Moving/blinking content can be paused/stopped | A | ☐ |

### 2.3 Seizures & Physical Reactions
| # | Criteria | Level | Status |
|---|---|---|---|
| 2.3.1 | No content flashes more than 3 times per second | A | ☐ |

### 2.4 Navigable
| # | Criteria | Level | Status |
|---|---|---|---|
| 2.4.1 | Skip navigation link is provided | A | ☐ |
| 2.4.2 | Page has a descriptive title | A | ☐ |
| 2.4.3 | Focus order is logical and meaningful | A | ☐ |
| 2.4.4 | Link purpose is clear from context | A | ☐ |
| 2.4.5 | Multiple ways to find pages exist | AA | ☐ |
| 2.4.6 | Headings and labels are descriptive | AA | ☐ |
| 2.4.7 | Keyboard focus is visible | AA | ☐ |
| 2.4.11 | Focus is not hidden by sticky headers (WCAG 2.2) | AA | ☐ |
| 2.4.12 | Focus indicator has sufficient size (WCAG 2.2) | AA | ☐ |

### 2.5 Input Modalities
| # | Criteria | Level | Status |
|---|---|---|---|
| 2.5.1 | Complex gestures have single-pointer alternatives | A | ☐ |
| 2.5.3 | Labels match visible text (accessible name) | A | ☐ |
| 2.5.4 | Motion-activated features have alternatives | A | ☐ |
| 2.5.7 | Dragging actions have single-pointer alternatives (WCAG 2.2) | AA | ☐ |
| 2.5.8 | Touch targets are at least 24x24 CSS pixels (WCAG 2.2) | AA | ☐ |

---

## 3️⃣ Understandable

### 3.1 Readable
| # | Criteria | Level | Status |
|---|---|---|---|
| 3.1.1 | Page language is identified in HTML | A | ☐ |
| 3.1.2 | Language changes within content are identified | AA | ☐ |

### 3.2 Predictable
| # | Criteria | Level | Status |
|---|---|---|---|
| 3.2.1 | Focus does not trigger unexpected context change | A | ☐ |
| 3.2.2 | Input does not trigger unexpected context change | A | ☐ |
| 3.2.3 | Navigation is consistent across pages | AA | ☐ |
| 3.2.4 | Components are identified consistently | AA | ☐ |
| 3.2.6 | Help is available consistently (WCAG 2.2) | A | ☐ |

### 3.3 Input Assistance
| # | Criteria | Level | Status |
|---|---|---|---|
| 3.3.1 | Errors are clearly identified | A | ☐ |
| 3.3.2 | Labels and instructions are provided | A | ☐ |
| 3.3.3 | Error suggestions are provided | AA | ☐ |
| 3.3.4 | Error prevention for legal/financial submissions | AA | ☐ |
| 3.3.7 | Redundant entry is avoided (WCAG 2.2) | A | ☐ |
| 3.3.8 | Accessible authentication without cognitive test (WCAG 2.2) | AA | ☐ |

---

## 4️⃣ Robust

### 4.1 Compatible
| # | Criteria | Level | Status |
|---|---|---|---|
| 4.1.1 | HTML is valid and well-structured | A | ☐ |
| 4.1.2 | UI components have name, role, and value | A | ☐ |
| 4.1.3 | Status messages are programmatically determined | AA | ☐ |

---

## 🛠️ Tools Used for Auditing

- **NVDA** — Screen reader (Windows)
- **JAWS** — Screen reader (Windows)
- **Axe DevTools** — Automated accessibility testing
- **WAVE** — Web accessibility evaluation tool
- **ANDI** — Accessible Name & Description Inspector
- **ARC Toolkit** — Accessibility testing extension
- **Lighthouse** — Automated auditing (Chrome DevTools)
- **Colour Contrast Analyser (CCA)** — Color contrast checking

---

## 📎 References

- [WCAG 2.1 Guidelines](https://www.w3.org/TR/WCAG21/)
- [WCAG 2.2 Guidelines](https://www.w3.org/TR/WCAG22/)
- [Section 508 Standards](https://www.section508.gov/)
- [WAI-ARIA Practices](https://www.w3.org/WAI/ARIA/apg/)
