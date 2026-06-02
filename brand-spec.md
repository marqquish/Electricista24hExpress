# Brand Spec — Electricistas Madrid 24h Express

Extracted from reference design (Voltage Service Framework):

## Color Tokens (OKLch)

```css
--bg:       oklch(97.5% 0.005 250);  /* #f8f9fa */
--surface:  oklch(100% 0 0);         /* #ffffff */
--fg:       oklch(12% 0.01 250);     /* #191c1d */
--muted:    oklch(35% 0.015 260);    /* #424752 */
--border:   oklch(88% 0.01 260);     /* #c2c6d4 */
--accent:   oklch(42% 0.14 265);     /* #003f87 — electric blue */
--accent-light: oklch(45% 0.16 260); /* #0056b3 */
--gold:     oklch(65% 0.12 85);      /* #feb700 — safety gold, for urgency badges */
```

## Typography
- **Display / headings:** Inter, 800/700 weight, -0.02em letter-spacing on XL
- **Body:** Inter, 400 weight, 1.5 line-height
- **Mono:** JetBrains Mono / ui-monospace
- Scale: 12 · 14 · 16 · 18 · 24 · 32 · 40px

## Layout Posture
- Mobile-first with 12-col grid on desktop
- 8px linear spacing grid
- Max-width 1200px container
- Fixed bottom CTA nav on mobile (call always visible)
- Generous section spacing (80–120px desktop, 48px mobile)
- Soft rounded corners: 8px buttons, 12px cards, full for pills
- 1px solid borders do the work; shadows only on CTAs
- No heavy gradients — tonal layering + low-contrast outlines
