DESIGN RULES (apply to every page and component)
Overall feel: calm, classy, minimal. Clarity and readability come first.
Nothing decorative.
Color (use only these):
- Background: #FFFFFF, with #F8FAFC for alternate sections
- Text: #0F172A (headings), #475569 (body), #94A3B8 (muted only)
- Borders: #E2E8F0, 1px
- Primary: #1E3A8A (deep navy blue), used for buttons, links, active states
- Primary hover: #172554
- Success #15803D, Error #B91C1C, Warning #B45309 (status only)
- No gradients, no orange or second accent color, no purple, no
glassmorphism.
Typography (Inter only):
- Page title 30px/semibold, section title 20px/semibold, card title
16px/semibold, body 15-16px/regular, small 13-14px
- Line height 1.6 for body. Max line length ~65 characters.
- Sentence case everywhere. No ALL CAPS except tiny labels.
Layout and spacing:
- Max content width 1152px, centered, 16px side padding on mobile, 24px on
desktop
- Use an 8px spacing scale. Generous whitespace between sections (64px
desktop, 40px mobile).
- Cards: white, 1px border, rounded-lg (8px), NO shadow by default. On hover,
only a subtle border darkening. No lift or scale animations.
- Buttons: rounded-md, 40px height, one primary style (solid navy) and one
secondary (white with border). Maximum one primary button per card or
section.
- Inputs: 40px height, 1px border, visible labels above fields (never
placeholder-only), clear focus ring in primary color.

Icons and imagery:
- Use lucide-react icons only, 1.5px stroke, consistent size (20px). No
emojis anywhere.
- Images use object-cover with consistent aspect ratios (4:3 for cards).
Components:
- Use shadcn/ui for everything. Do not create custom components when a shadcn
one exists.
- Badges are small, muted, and used sparingly (status or category only).
- Empty, loading (skeleton), and error states are required on every datadriven view.
Accessibility and responsiveness:
- Text contrast at least WCAG AA. Tap targets at least 44px on mobile.
- Design mobile-first. Test at 375px, 768px, 1280px.
- No horizontal scrolling on any page.

Never do: gradient backgrounds, drop-shadow-heavy cards, bouncing or fading
animations, decorative blobs, centered hero text over gradients, more than
one font, more than 2 font weights per view.