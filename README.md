# FIELDTRACE

![FIELDTRACE primary logo](assets/logo/fieldtrace-primary.svg)

### Intelligent Design System Studio

**A working exploration of how a design system can guide product decisions, not just display components.**

[**Try the live FIELDTRACE Studio**](https://fieldtrace-studio.pages.dev/) | [Meet the creator](https://github.com/sandeepariyar)

A dedicated visual project page is ready in [`docs/index.html`](docs/index.html). It can be served through GitHub Pages from `main` / `docs` without copying the Studio implementation into this repository.

FIELDTRACE is a reusable, web-first design-system concept for teams building complex digital products. It brings live UI patterns, context-aware recommendations, cross-surface state modeling and design governance into one interactive experience.

The current public experience includes a **network operations** example pack. FIELDTRACE itself is not tied to any one company or industry.

## Brand identity

The geometric F and signal-blue detail stay consistent across product and presentation contexts.

| Light / precise | Night / operational | Signal / launch |
| --- | --- | --- |
| ![Primary FIELDTRACE logo](assets/logo/fieldtrace-primary.svg) | ![Night FIELDTRACE logo](assets/logo/fieldtrace-night.svg) | ![Signal FIELDTRACE logo](assets/logo/fieldtrace-signal.svg) |

The system also includes a monochrome lockup, square app icon and 16, 24, 48 and 128 pixel mark exports. See [brand usage guidance](BRAND.md).

## Explore the studio

The working interfaces are available in the [live FIELDTRACE Studio](https://fieldtrace-studio.pages.dev/). Verified screenshots from the Studio itself will be added after the next visual capture review.

### 01. The experience

A modern workspace for discovering patterns, testing behavior and tracing design decisions.

### 02. Pattern advisor

Describe what you need to build. The current advisor demonstrates deterministic, explainable pattern recommendations and their design rationale. It is **not** presented as generative AI.

### 03. Device and cloud state lab

Change a measurement outcome, its transfer state and cloud-data freshness independently. The simulated interface shows why these facts must not collapse into a single success or failure indicator.

### 04. Component workbench

Explore live component variants and concise interaction contracts. The public specimens demonstrate behavior, not a production-ready component package.

### 05. Mobile presentation

The same design language adapts to smaller screens. Device-specific physical controls, glove operation and sunlight legibility still require hardware testing.

## Why FIELDTRACE?

Traditional design systems answer: **"What does this component look like?"**

FIELDTRACE explores a more useful question: **"What should I build for this situation, why, and how do I keep it consistent across platforms?"**

| Capability | What the public demo shows |
| --- | --- |
| Intent-first discovery | A rule-based advisor that explains suggested UI patterns |
| Living components | Interactive specimens with visible states and keyboard considerations |
| Cross-surface semantics | Independent outcome, transfer and freshness states |
| Design decisions | Reasons, proposed rules and clear evidence labels |
| Adaptive foundations | Light/dark presentation, semantic colors, type and spacing |
| Engineer self-service | A direction toward reusable decisions without mandatory Figma handoff |

## Tested live

The public deployment at [fieldtrace-studio.pages.dev](https://fieldtrace-studio.pages.dev/) was exercised on 25 November 2026.

| Check | Observed result |
| --- | --- |
| Cloudflare build from private GitHub | Deployed successfully |
| Advisor: settings and table requests | Different, relevant recommendations returned |
| Device/cloud state changes | Failed + offline + missing evidence rendered independently |
| State audit | Flagged offline-queue handling and validation requirements |
| Component lab | Toggle selection and state variants responded correctly |
| Appearance | Light/dark switching worked |
| Browser diagnostics | No JavaScript errors captured during tested interactions |
| Responsive check | No horizontal overflow at a tested 375px content viewport |

These are **exploratory browser checks**, not full accessibility certification, production QA or native-device validation.

## Beyond the demonstration

FIELDTRACE's longer-term product direction includes:

- Structured, platform-agnostic design tokens as a source of truth.
- Reusable web patterns with documented accessibility and behavior.
- A visual decision workbench for designers, engineers and stakeholders.
- Adaptation contracts for embedded, mobile and cloud interfaces.
- Governed export workflows, review gates and traceable decisions.
- Separate domain packs so teams can explore different product contexts without duplicating the system.

These are **product directions**, not claims that every capability is released today.

## Source code and collaboration

This public repository is a **showcase only**. It contains brand vectors and the separate static presentation page, but no FIELDTRACE Studio implementation source, private export engine or proprietary engineering assets.

The implementation is maintained privately. **If you are interested in reviewing the source, discussing the architecture or exploring a company-specific use case, please contact [Sandeep Pariyar](https://github.com/sandeepariyar).** Relevant code can be shared upon request.

## Independence

FIELDTRACE is an independent design-engineering concept. All sample measurements and sessions are synthetic. The network-operations example is informed by public product documentation; no company affiliation, endorsement or connection to live device/cloud systems is implied.

---

**[Open the interactive FIELDTRACE Studio](https://fieldtrace-studio.pages.dev/)**
