---
name: Terra Nova Collective
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#404944'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#707974'
  outline-variant: '#bfc9c3'
  surface-tint: '#2b6954'
  primary: '#003527'
  on-primary: '#ffffff'
  primary-container: '#064e3b'
  on-primary-container: '#80bea6'
  inverse-primary: '#95d3ba'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#2d2f2e'
  on-tertiary: '#ffffff'
  tertiary-container: '#434545'
  on-tertiary-container: '#b1b2b1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b0f0d6'
  primary-fixed-dim: '#95d3ba'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#0b513d'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c7c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display-xl:
    fontFamily: Montserrat
    fontSize: 60px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system focuses on a **Modern-Minimalist** aesthetic tailored for high-end residential land development. The brand personality is rooted in the intersection of nature and architecture—conveying stability, growth, and environmental harmony. 

The UI prioritizes clarity and breathability, utilizing ample whitespace to reduce cognitive load during the high-stakes decision of purchasing property. Visual cues are drawn from architectural blueprints and natural landscapes, favoring precise alignment and organic textures. The emotional response should be one of "aspirational tranquility"—making the prospect of land ownership feel both prestigious and attainable.

## Colors
The palette is inspired by "Earth and Prestige." 
- **Primary (Emerald Green):** Used for primary brand elements and high-priority states. It represents life and growth.
- **Secondary (Gold):** Reserved exclusively for primary Call-to-Action (CTA) buttons and key highlights to suggest value and exclusivity.
- **Neutral (Charcoal):** Used for typography and structural borders to provide a solid, professional foundation.
- **Surface (Stone/Sand):** Light earthy tones are used for section backgrounds to break the monotony of pure white without sacrificing the minimalist feel.

## Typography
The typography strategy pairs the geometric strength of **Montserrat** for headlines with the utilitarian clarity of **Inter** for body text. 
- **Headlines:** Use Montserrat to evoke a sense of modern structure. Keep letter-spacing tight on larger sizes to maintain a "high-end editorial" feel.
- **Body Text:** Inter is utilized for its high legibility in data-dense sections like lot specifications.
- **Labels:** Small labels and captions use Inter with increased letter spacing and uppercase styling to denote technical details or categories.

## Layout & Spacing
This design system utilizes a **12-column fixed grid** for desktop, centering the content at a maximum width of 1280px. 
- **Rhythm:** A 120px vertical gap between major sections ensures the "minimalist" and "airy" brand promise.
- **Mobile Adaption:** On mobile, the layout collapses to a single column with 20px side margins. Section gaps reduce to 64px to maintain momentum.
- **Alignment:** Elements should adhere to a strict baseline grid. Grouped items (like lot attributes) use a 16px (stack-md) spacing rule.

## Elevation & Depth
In line with a minimalist real estate aesthetic, depth is achieved through **Tonal Layering** and **Subtle Ambient Shadows**.
- **Surfaces:** Use the `#F9FAFB` surface color to lift cards slightly off the `#FFFFFF` background.
- **Shadows:** Avoid heavy, dark shadows. Use a "Natural Light" shadow: `0px 4px 20px rgba(6, 78, 59, 0.04)`—a very faint tint of the primary green to give a soft, organic lift to lot cards and interactive elements.
- **Borders:** Use 1px borders in a very light neutral (e.g., `#E5E7EB`) for input fields and card outlines to maintain a crisp, professional look without visual noise.

## Shapes
The design system employs **Soft (0.25rem)** roundedness. This "near-sharp" approach communicates professional precision and architectural structure while remaining approachable. 
- **Buttons and Inputs:** Use the standard 4px radius.
- **Property Cards:** Use the `rounded-lg` (8px) setting to provide a slightly softer container for imagery, suggesting a welcoming residential environment.

## Components
- **Primary Buttons:** High-contrast Gold (`#D4AF37`) background with dark charcoal text. No icons unless they indicate a literal action (e.g., an arrow for "View Map").
- **Secondary Buttons:** Ghost style with a Primary Green (`#064E3B`) border and text.
- **Lot Cards:** Feature high-quality photography at the top, followed by a structured grid of metadata (e.g., "M2", "Status", "Price"). Use a "Status Chip" in the top corner (Emerald for Available, Slate for Reserved).
- **Process Steps:** Use thin-stroke icons in Primary Green. Connect steps with a subtle dashed line to indicate the linear journey of land acquisition.
- **Contact Form:** Use "Floating Label" inputs with a focus state that changes the border color to Primary Green. The form container should be a clean, elevated surface with a subtle shadow.
- **Interactive Map Toggle:** A segmented control allowing users to switch between a list view and a satellite map view of the development.