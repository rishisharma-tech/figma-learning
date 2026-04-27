# Aero DS Token Reference
> Use this file in every Claude Design session. Paste it at the start and say: "Design using these exact Aero DS tokens from Birdeye's Elemental design system."

---

## Colors

### Gray (UI foundations — use most often)
| Token | Value | Use for |
|-------|-------|---------|
| `$gray0` | `#ffffff` | White, card backgrounds |
| `$gray10` | `#fafafa` | Page background, sidebar bg |
| `$gray20` | `#f5f5f5` | Input backgrounds, hover states |
| `$gray30` | `#efefef` | Dividers, skeleton loaders |
| `$gray40` | `#eaeaea` | Subtle borders |
| `$gray50` | `#e5e5e5` | Default borders |
| `$gray60` | `#cccccc` | Disabled borders, kbd bottom border |
| `$gray70` | `#b8b8b8` | Placeholder text |
| `$gray80` | `#a3a3a3` | Inactive icons |
| `$gray90` | `#8f8f8f` | Muted text, hints, secondary labels |
| `$gray100` | `#757575` | Secondary text |
| `$gray200` | `#656565` | Body text (secondary) |
| `$gray300` | `#555555` | Medium emphasis text |
| `$gray400` | `#454545` | High emphasis text |
| `$gray500` | `#353535` | Strong text |
| `$gray600` | `#303030` | Near-black text |
| `$gray900` | `#212121` | Primary text, headings |
| `$gray1000` | `#2c3e50` | Dark navy (special use) |
| `$gray2000` | `#e5e9f0` | Light blue-gray (special use) |

### Blue (Primary brand + interactive)
| Token | Value | Use for |
|-------|-------|---------|
| `$blue10` | `#f6fafe` | Lightest blue tint |
| `$blue20` | `#ecf5fd` | Active tab background, selected bg |
| `$blue30` | `#e3effc` | Hover states on blue elements |
| `$blue40` | `#daeafb` | Light blue backgrounds |
| `$blue50` | `#d1e5f9` | Selected row background |
| `$blue60` | `#a4ccf4` | Light blue accents |
| `$blue70` | `#7fb8f0` | Medium blue |
| `$blue80` | `#5ba4ec` | Progress bars, charts |
| `$blue90` | `#3790e7` | Links, secondary actions |
| `$blue100` | `#1976d2` | Primary blue, active borders |
| `$blue200` | `#1565b4` | Primary buttons, active states |
| `$blue300` | `#125598` | Button hover |
| `$blue400` | `#0f457c` | Dark blue |
| `$blue500` | `#0b355f` | Darker blue |
| `$blue900` | `#07213a` | Darkest blue |

### Red (Errors + destructive)
| Token | Value | Use for |
|-------|-------|---------|
| `$red10` | `#fef6f5` | Error background (lightest) |
| `$red20` | `#feeceb` | Error banner background |
| `$red30` | `#fde3e1` | Light error tint |
| `$red70` | `#f88078` | Error icons |
| `$red80` | `#f65d51` | Error text |
| `$red90` | `#f3382b` | Error color (main) |
| `$red100` | `#de1b0c` | Strong error |
| `$red200` | `#bf170a` | Destructive actions, validation errors |

### Green (Success + positive)
| Token | Value | Use for |
|-------|-------|---------|
| `$green10` | `#f8fcf7` | Success background (lightest) |
| `$green20` | `#f1faf0` | Success banner background |
| `$green50` | `#dcf1d9` | Light success tint |
| `$green90` | `#68c559` | Success icons |
| `$green100` | `#4cae3d` | Success color (main) |
| `$green200` | `#419535` | Strong success |

### Yellow (Warning)
| Token | Value | Use for |
|-------|-------|---------|
| `$yellow10` | `#fffcf5` | Warning background (lightest) |
| `$yellow20` | `#fff9ea` | Warning banner background |
| `$yellow50` | `#fef1cc` | Light warning tint |
| `$yellow90` | `#fbc123` | Warning icons, stars |
| `$yellow100` | `#e6aa04` | Warning color (main) |
| `$yellow200` | `#c69204` | Strong warning |

---

## Typography

### Font Family
- **Primary:** Poppins (UI text, headings)
- **Mono:** SF Mono / system monospace (code, kbd keys)

### Font Sizes
| Token | Value | Use for |
|-------|-------|---------|
| `$fs10` | `10px` | Labels, badges, section headings (uppercase) |
| `$fs12` | `12px` | Captions, helper text, secondary info |
| `$fs14` | `14px` | Body text, table rows |
| `$fs16` | `16px` | Default body, input text |
| `$fs18` | `18px` | Subheadings |
| `$fs20` | `20px` | Page titles (small) |
| `$fs24` | `24px` | Page titles (medium) |
| `$fs28` | `28px` | Large numbers, stats |
| `$fs32` | `32px` | Hero numbers |

### Font Weights
| Token | Value | Use for |
|-------|-------|---------|
| `$fwRegular` | `400` | Body text, descriptions |
| `$fwMedium` | `500` | Labels, nav items, emphasis |
| `$fwBold` | `700` | Headings, strong emphasis |

### Line Heights
| Token | Value | Paired with font size |
|-------|-------|-----------------------|
| `$lh10` | `15px` | `$fs10` |
| `$lh12` | `18px` | `$fs12` |
| `$lh14` | `21px` | `$fs14` |
| `$lh16` | `24px` | `$fs16` |
| `$lh18` | `27px` | `$fs18` |
| `$lh20` | `30px` | `$fs20` |
| `$lh24` | `36px` | `$fs24` |
| `$lh28` | `42px` | `$fs28` |
| `$lh32` | `48px` | `$fs32` |

---

## Spacing

### Margin
| Token | Value |
|-------|-------|
| `$md0` | `0px` |
| `$md2` | `2px` |
| `$md4` | `4px` |
| `$md8` | `8px` |
| `$md12` | `12px` |
| `$md16` | `16px` |
| `$md20` | `20px` |
| `$md24` | `24px` |

### Padding
| Token | Value |
|-------|-------|
| `$pd0` | `0px` |
| `$pd2` | `2px` |
| `$pd4` | `4px` |
| `$pd8` | `8px` |
| `$pd12` | `12px` |
| `$pd16` | `16px` |
| `$pd20` | `20px` |
| `$pd24` | `24px` |

---

## Border Radius
| Token | Value | Use for |
|-------|-------|---------|
| `$xsBorderRadius` | `2px` | Subtle rounding, tags |
| `$smBorderRadius` | `4px` | Buttons, inputs, chips |
| `$mdBorderRadius` | `8px` | Cards, dropdowns |
| `$lgBorderRadius` | `12px` | Modals, panels |
| `$xlBorderRadius` | `16px` | Large cards |
| `$xxlBorderRadius` | `24px` | Extra large containers |
| `$xxxlBorderRadius` | `999px` | Pills, avatars, fully rounded |

---

## Common UI Patterns (Semantic Usage)

### Text hierarchy
```
Page title:      $fs20–24, $fwBold, $gray900
Section heading: $fs10, $fwBold, $gray90, UPPERCASE, letter-spacing: 0.07em
Body text:       $fs14, $fwRegular, $gray900
Secondary text:  $fs12, $fwRegular, $gray200
Muted/hint:      $fs12, $fwRegular, $gray90
```

### Borders
```
Default border:  1px solid $gray50
Subtle border:   1px solid $gray40
Active border:   1px solid $blue100
Error border:    1px solid $red90
```

### Backgrounds
```
Page bg:         $gray10
Card bg:         $gray0
Sidebar bg:      $gray10
Active tab bg:   $blue20
Hover bg:        $gray20
Error bg:        $red20
Warning bg:      $yellow20
Success bg:      $green20
```

### Interactive states
```
Primary button:  bg $blue200, hover $blue300, text $gray0
Active tab:      bg $blue20, border-right $blue100, text $blue200
Link:            $blue90, hover $blue100
Disabled:        $gray60 text, $gray30 bg
```

### Status colors
```
Success:  $green100 (icon), $green20 (bg)
Warning:  $yellow90 (icon), $yellow20 (bg)
Error:    $red90 (icon), $red20 (bg)
Info:     $blue90 (icon), $blue20 (bg)
```

---

## How to use this file in Claude Design

Paste this at the top of your prompt:

> "I'm designing for Birdeye. Use only the Aero DS tokens below. Do not invent colors or spacing. Match the token names exactly."

Then paste this file, then describe what you want designed.
