---
layout: default
title: Accessibility
---

# Accessibility

ParkPilot is designed to work with the accessibility features built into iOS.
The features below are supported — users can complete all primary app functions
(onboarding, getting a recommendation, managing their plan, and upgrading to Pro)
using each of them.

---

## VoiceOver

Interactive controls throughout the app include descriptive accessibility labels.
Recommendation cards announce the attraction name, wait time, decision badge, and
walk-time indicator. Paywall options announce the plan name, price, and billing period.
Onboarding selections announce their current state. Standard iOS controls (buttons,
navigation) follow system accessibility conventions automatically.

---

## Larger Text

All text in the app scales with the iOS text size setting, including accessibility
sizes. Font sizes are defined in the app's theme and respond to the system
`textScaler` — including chart axis labels on the wait-time forecast sheet.
No text in the app is fixed at a size that ignores the system text size preference.

---

## Reduce Motion

Animated elements respect the iOS **Reduce Motion** setting. The pulsing intensity
indicator on the recommendation card is replaced with a static display when Reduce
Motion is enabled. All other motion-heavy elements are reduced or removed where
practical.

---

## Sufficient Contrast

All informational text meets **WCAG 2.2 Level AA** contrast requirements in both
Light and Dark modes:

- Normal text (below 18 sp regular / 14 sp bold): minimum **4.5 : 1**
- Large text (18 sp regular or 14 sp bold and above): minimum **3 : 1**

Decorative text (such as subdued secondary labels used purely for visual rhythm)
is never used to convey information.

---

## Differentiate Without Color Alone

Status and category information is never communicated by color alone. Decision
badges (such as DEAL HUNTER, HEAT ESCAPE, and RAIN ESCAPE) use a text label
alongside color. Wait-time indicators pair numeric values with color. Special
event icons pair a symbol with a label. Live vs. estimated data is indicated
by a text label, not color alone.

---

## Dark Interface

The app supports Light, Dark, and System-matching appearances. The preference is
set in **Settings → Appearance** and persists across sessions. Both palettes meet
the contrast requirements above.

---

## Touch Targets

All interactive elements meet a minimum touch target of **48 × 48 dp** in
accordance with WCAG 2.5.5 (Target Size). Elements whose visible size is smaller
than this threshold are padded to meet the minimum without changing their
visual appearance.

---

## Contact

If you encounter an accessibility barrier or have suggestions for improvement,
please email us at [support@getparkpilot.com](mailto:support@getparkpilot.com).
We typically respond within **1–2 business days**.

---

*ParkPilot is an independent app and is not affiliated with, endorsed by, or
sponsored by The Walt Disney Company, Walt Disney Parks and Resorts, or any of
their subsidiaries.*
