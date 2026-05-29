---
title: Dark Knight — Theme Showcase
tags: [gotham, demo, theme]
status: active
created: 2026-05-29
---

# H1 — The Bat-Signal Over Gotham
## H2 — Steel and Shadow
### H3 — Asphalt at Midnight
#### H4 — Steel-Blue Hour
##### H5 — Fog Rolling In
###### H6 — A Whisper in the Alley

A paragraph of **normal body text** to check contrast against Gotham black.
Here is **bold (gold)**, *italic (steel-blue)*, ==a highlight==, and `inline code`.
An [internal link](#), an [external link](https://obsidian.md), and a
[[Nonexistent Note]] to show the unresolved-link red. Reserved Joker red also
shows on destructive actions.

> "It's not who I am underneath, but what I do that defines me."
> — A blockquote with the gold signal bar and faint glow.

## Lists & Tasks

- Grappling hook
- Batarang
  - Standard
  - Sonic
- Smoke pellets

1. Patrol the Narrows
2. Check Wayne Enterprises R&D
3. Return before dawn

- [x] Recharge the Tumbler
- [ ] Decode the Riddler's message
- [ ] Meet Gordon on the rooftop

## Code Block

```python
def light_signal(city: str, intensity: float = 1.0) -> bool:
    """Project the Bat-Signal over the given city."""
    if intensity <= 0:
        return False  # no signal
    signal = {"city": city, "lit": True, "color": "#f5c518"}
    print(f"Signal lit over {city} at {intensity:.0%}")
    return signal["lit"]

light_signal("Gotham", intensity=0.85)
```

```css
.theme-dark .bat-signal { color: var(--dk-gold); box-shadow: 0 0 18px gold; }
```

## Table

| District      | Threat Level | Status      |
| ------------- | :----------: | ----------- |
| The Narrows   |     High     | Patrolling  |
| Wayne Tower   |      Low     | Secure      |
| Arkham Asylum |   Critical   | Breach      |
| Gotham Docks  |    Medium    | Monitoring  |

## Callouts

> [!note] Note
> Standard intel — gold accent.

> [!tip] Tip
> Riddler-green for success and hints.

> [!warning] Warning
> Gold caution stripe.

> [!danger] Danger
> Joker-red reserved for real threats.

> [!quote] Quote
> Purple for citations.

## Tags

#gotham #batman #wayne-enterprises #case-file

---

That's the full surface area. Switch between dark and light mode to compare.
