# Inevitable — graphic standards

Signed off 1 September 2026.

**inevitable** is Sal’s weekly LinkedIn newsletter about Solana in AU/NZ. Community register, not Milysec lab. Taste: Jobs / Ive / Rams / Vignelli.

The I is the display character.

The page `index.html` is the artefact. This file is the same rules in writing.

---

## Mark

A capital I. Three copies of one official Solana parallelogram — the top bar of `solanaLogoMark.svg`. Official rounding is kept. No gradient.

Unit bar: `logo/unit-bar.svg`. Size **101 × 22**. Centre **50.5, 10.9**.

Path `d`:

```
M1.93563 21.7905H80.9743C81.5055 21.7907 82.0312 21.6845 82.5185 21.4783C83.0058 21.2721 83.4444 20.9704 83.8068 20.592L100.48 3.17219C100.737 2.90357 100.908 2.56758 100.972 2.2055C101.036 1.84342 100.99 1.47103 100.84 1.13408C100.689 0.79713 100.441 0.510296 100.126 0.308823C99.8104 0.107349 99.4415 1.24074e-05 99.0644 0L20.0301 0C19.5002 0.000878397 18.9762 0.107699 18.4904 0.313848C18.0047 0.519998 17.5676 0.821087 17.2061 1.19848L0.524723 18.6183C0.267681 18.8866 0.0966198 19.2223 0.0325185 19.5839C-0.0315829 19.9456 0.0140624 20.3177 0.163856 20.6545C0.31365 20.9913 0.561081 21.2781 0.875804 21.4799C1.19053 21.6817 1.55886 21.7896 1.93563 21.7905Z
```

### Construction

On a **1080** canvas:

1. Group: `translate(540, 540) scale(5.1)`
2. **Stem:** `rotate(-90) translate(-50.5, -10.9)`
3. **Top:** `translate(-50.5, -79.3)` — original orientation
4. **Bottom:** `translate(-50.5, 57.5)` — original orientation, **not flipped**

Gap between stem and slabs is **7** (bar units). The gaps are the field. They do not touch.

### Files

| File | Use |
|---|---|
| `logo/mark-on-black.svg` (+ `.png`, `-384.png`, `-48.png`) | Primary. Ink on ground. |
| `logo/mark-on-white.svg` (+ pngs) | Invert. Allowed, not default. |
| `logo/mark-white.svg` | White I, transparent. |
| `logo/mark-black.svg` | Black I, transparent. |
| `logo/unit-bar.svg` | The single parallelogram. |

Primary is white I on `#000000`. Invert is black I on `#FFFFFF`.

### Clear space

One stem-width on all sides. Stem-width is the bar’s short side: **22** in bar units, **112.2px** on the 1080 canvas.

### Size

Minimum **48px** square. Never below **32px**.

### LinkedIn

The newsletter avatar is the **1080 square**: `logo/mark-on-black.png`.

---

## Colour

Mark: monochrome only.

| Token | Hex |
|---|---|
| Ground | `#000000` |
| Ink | `#FFFFFF` |

Invert (black I on white) is allowed, not default.

Editorial accents — never on the mark, never as a gradient I, one at a time:

| Token | Hex |
|---|---|
| Purple | `#800080` |
| Blue | `#0000FF` |
| Red | `#FF0000` |

Do not invent extra colours. Do not use grey. Do not use a gradient on the I.

### Forbidden (Milysec lab)

`#08D592` `#9C32DF` `#070A08` `#0C100D`

This is not the lab.

---

## Type

One family: **Inter** 400 / 500 / 600, from Google Fonts.

Wordmark: lowercase **inevitable**, Inter 600, slight negative tracking (`-0.03em`).

System `ui-monospace` only for hex values and sizes in the guide.

### Forbidden

MoonWalk, Bricolage Grotesque, EconoSans, Monoton, Orbitron, Geist.

---

## Don’t

| File | Error |
|---|---|
| `logo/dont-recolour.svg` | I filled with `#800080` |
| `logo/dont-stack.svg` | Three horizontal bars stacked like the Solana S |
| `logo/dont-flip.svg` | Bottom bar flipped |

Do not stretch, outline, drop-shadow, or rotate the I as a lockup. Do not put type inside the gaps.

---

## What this is not

Not an official Solana logo. Not an official Solana ANZ logo. Not Milysec. The parallelogram geometry comes from the official Solana logo mark (Solana Foundation). This I is a derived community mark for the Inevitable newsletter. Do not claim the Solana trademark.
