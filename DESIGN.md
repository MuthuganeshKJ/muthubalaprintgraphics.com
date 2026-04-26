---
name: Vibrant Heritage
colors:
  surface: '#f5fbf3'
  surface-dim: '#d6dcd4'
  surface-bright: '#f5fbf3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f5ee'
  surface-container: '#eaefe8'
  surface-container-high: '#e4eae2'
  surface-container-highest: '#dee4dd'
  on-surface: '#171d19'
  on-surface-variant: '#3e4a41'
  inverse-surface: '#2c322d'
  inverse-on-surface: '#edf2eb'
  outline: '#6e7a70'
  outline-variant: '#bdcabe'
  surface-tint: '#006d40'
  primary: '#006b3f'
  on-primary: '#ffffff'
  primary-container: '#008751'
  on-primary-container: '#fdfff9'
  inverse-primary: '#70db9d'
  secondary: '#13677b'
  on-secondary: '#ffffff'
  secondary-container: '#a1e7ff'
  on-secondary-container: '#18697e'
  tertiary: '#7a5600'
  on-tertiary: '#ffffff'
  tertiary-container: '#9a6d00'
  on-tertiary-container: '#fffdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#8df8b7'
  primary-fixed-dim: '#70db9d'
  on-primary-fixed: '#002110'
  on-primary-fixed-variant: '#00522f'
  secondary-fixed: '#b2ebff'
  secondary-fixed-dim: '#8bd1e8'
  on-secondary-fixed: '#001f27'
  on-secondary-fixed-variant: '#004e5f'
  tertiary-fixed: '#ffdea9'
  tertiary-fixed-dim: '#ffba27'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5e4100'
  background: '#f5fbf3'
  on-background: '#171d19'
  surface-variant: '#dee4dd'
typography:
  headline-xl:
    fontFamily: Epilogue
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Epilogue
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Epilogue
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Epilogue
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Epilogue
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 32px
---

## Brand & Style
The design system is a celebration of cultural richness and modern craftsmanship. It is designed for a printing company that bridges the gap between traditional heritage and contemporary digital precision. The brand personality is energetic, festive, and deeply rooted in Tamil aesthetics, evoking the warmth of a community celebration and the reliability of expert artistry.

The design style follows a **High-Contrast / Bold** approach. It utilizes massive typography, saturated color blocks, and generous whitespace to ensure every element feels intentional and celebratory. This aesthetic avoids the clinical nature of standard corporate design, opting instead for a "Hyper-Vibrant" atmosphere that mirrors the physical vibrancy of high-quality ink and textile dyes.

## Colors
The color palette of this design system is inspired by the saturated tones found in traditional Tamil festivals, textiles, and spices. 

- **Emerald Green**: The primary brand driver, representing growth and vitality.
- **Peacock Blue**: A sophisticated secondary tone that adds depth and a regal quality.
- **Turmeric Yellow**: Used for highlights and primary calls-to-action to evoke warmth and auspiciousness.
- **Deep Crimson**: A striking accent color reserved for critical notifications or celebratory highlights.

The background is a soft, paper-like off-white (#FDFAF5) to ensure that the high-contrast colors pop without causing visual fatigue. Neutral tones are kept minimal, leaning toward deep indigo-charcoals rather than flat greys to maintain the richness of the palette.

## Typography
This design system employs **Epilogue** across all levels. As a geometric sans-serif with a heavy weight range, it provides the "editorial" feel necessary for a printing brand while remaining distinctly modern. 

Headlines should be set with tight line height and negative letter spacing to create high-impact, poster-like layouts. Body text maintains generous line height for readability. Labels use an increased letter spacing and bold weights to provide a structured, instructional feel to the UI. When highlighting cultural keywords, a heavier weight of Epilogue should be used to mimic the presence of traditional woodblock printing.

## Layout & Spacing
The layout philosophy relies on a **fixed grid** system that centers content within a max-width container, emphasizing a structured, rhythmic flow. A 12-column grid is standard for desktop, collapsing to 4 columns for mobile.

The spacing rhythm is based on an 8px scale. Large vertical "breathing rooms" (48px to 80px) are used between major sections to mimic the margins of high-end print media. Gutters are kept wide at 24px to ensure that the hyper-vibrant components do not feel cluttered. Elements should align strictly to the grid edges to provide a sense of precision and professional craft.

## Elevation & Depth
In this design system, hierarchy is primarily conveyed through **vibrant shadows** and **tonal layering**. 

Rather than using neutral grey shadows, surfaces use low-opacity shadows tinted with the primary Emerald or secondary Peacock colors. This creates a "glowing" effect that contributes to the celebratory aesthetic. 

- **Level 1 (Base)**: Flat surfaces with subtle 1px inner borders in a darker tint of the background color.
- **Level 2 (Interactive)**: Soft, medium-spread shadows with a 10% opacity tint of the component's own color.
- **Level 3 (Overlays/Modals)**: Large, diffused shadows that create a "lifted" effect, paired with a backdrop blur to keep focus on the foreground celebratory elements.

## Shapes
The shape language is defined by **High Roundness (Pill-shaped)**. This decision softens the high-contrast color palette, making the interface feel approachable and friendly rather than aggressive.

All buttons, input fields, and tags must use full pill-shaped rounding. Cards and larger containers should use a `rounded-xl` (1.5rem) or `rounded-2xl` (2rem) setting. This fluid, organic geometry echoes the curves found in Tamil typography and traditional Kolam patterns, providing a visual bridge between the digital interface and cultural heritage.

## Components
Consistent styling of components ensures the design system remains cohesive across all touchpoints:

- **Buttons**: Every button is a full pill shape. Primary buttons use Turmeric Yellow with black text for maximum visibility. Secondary buttons use Peacock Blue with white text.
- **Input Fields**: Fields have a thick 2px border in a muted Peacock Blue that turns Emerald Green on focus. The rounding is set to maximum (pill) to match the button style.
- **Chips & Tags**: These are used extensively for "Print Categories." They utilize highly saturated backgrounds (Crimson, Emerald, Blue) with white text, using the `label-bold` typographic style.
- **Cards**: Cards feature a soft, tinted shadow and a 24px internal padding. They often include a "header strip" of color at the top to categorize content.
- **Lists**: List items are separated by generous spacing and utilize custom iconography inspired by traditional motifs, contained within small circular containers.
- **Decorative Accents**: Incorporate "Kolam" pattern fragments as low-opacity background watermarks or as dividers between sections to reinforce the cultural narrative.
- **Status Indicators**: Use the high-contrast palette—Emerald for success, Crimson for errors—rendered as solid, vibrant circular dots.