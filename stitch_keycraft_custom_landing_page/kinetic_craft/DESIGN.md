---
name: Kinetic Craft
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#5a4136'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#8e7164'
  outline-variant: '#e2bfb0'
  surface-tint: '#a04100'
  primary: '#a04100'
  on-primary: '#ffffff'
  primary-container: '#ff6b00'
  on-primary-container: '#572000'
  inverse-primary: '#ffb693'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#5d5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#989999'
  on-tertiary-container: '#2f3132'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#ffb693'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#7a3000'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style
The design system focuses on a premium, maker-centric aesthetic that balances industrial precision with consumer accessibility. The target audience includes design-conscious individuals looking for high-quality, personalized everyday carry (EDC) items. 

The visual style is **Corporate Modern with a Tactile Premium edge**. It utilizes expansive white space to denote luxury, punctuated by high-energy accents that guide the user toward conversion. The UI should feel substantial and reliable, using soft depth to simulate the physical quality of the custom keychains being sold.

## Colors
The palette is built on high-contrast functionalism. 
- **Primary (#FF6B00):** Used exclusively for high-conversion actions, price points, and active states. It represents the "spark" of customization.
- **Secondary (#1A1A1A):** Provides the "Deep Dark Gray" foundation for typography and structural elements, ensuring a grounded, professional feel.
- **Surface/Neutral:** Crisp White (#FFFFFF) is the primary background color to maintain a clean gallery feel, while Tertiary (#F5F5F5) is used for subtle section nesting.

## Typography
This design system pairs the geometric authority of **Montserrat** for headings with the high-legibility utilitarianism of **Inter** for body copy and interface labels. 

Headings must utilize generous letter-spacing (0.01em to 0.02em) to enhance the "premium" editorial feel. The "label-caps" style is specifically designed for small category tags and overlines, emphasizing the technical nature of the craft.

## Layout & Spacing
The layout follows a **fluid 12-column grid** for desktop and a **4-column grid** for mobile. 

A strict 8px spacing rhythm is applied to all internal padding and margins. Vertical rhythm is driven by three "stack" tiers (12px, 24px, 48px) to clearly group related product information. On mobile, side margins compress to 16px to maximize the visual area for product photography.

## Elevation & Depth
Depth is created through **Ambient Multi-layered Shadows**. Surfaces should not look flat but rather "lofted" above the canvas.

- **Level 1 (Product Cards):** A soft, expansive shadow using 10% opacity of the secondary color with a 20px blur and 4px vertical offset.
- **Level 2 (Modals/Dropdowns):** A more defined shadow using two layers: one tight 4px blur for definition and one 40px blur for environmental depth.
- **Interactive Depth:** On hover, product cards should "lift" by increasing the shadow blur and decreasing the vertical offset to simulate physical movement toward the user.

## Shapes
To align with the "custom" and "tactile" nature of keychains, the design system employs a **Rounded** philosophy. Standard elements like buttons and input fields use a 0.5rem (8px) radius, while larger containers like Product Cards and FAQ Accordions utilize a more pronounced 1rem (16px) radius to create a friendly, approachable silhouette.

## Components
### Buttons
- **Primary CTA:** Solid Vibrant Orange background with White text. Bold weight. High-contrast and center-staged.
- **Secondary:** Transparent with a 2px Deep Dark Gray border.
- **Interactive State:** Buttons should scale slightly (98%) on press to provide haptic-like visual feedback.

### Product Cards
- **Structure:** Clean white background with a 1px soft gray (#E5E5E5) border. 
- **Imagery:** Product photos should be centered with a slight internal margin to avoid touching the card edges.
- **Shadow:** Applied on hover to signify interactability.

### Accordions (FAQ)
- **Style:** Each item is contained in a soft-bordered box. 
- **Iconography:** Use a simple chevron that rotates 180 degrees. 
- **Transition:** Smooth height expansion with a focus state that adds a subtle orange left-border to the active item.

### Input Fields
- **Design:** Soft gray background (#F9F9F9) with no border until focused. On focus, a 2px Primary Orange border is applied to guide the user during the customization process.