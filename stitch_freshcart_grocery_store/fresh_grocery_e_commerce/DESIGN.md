---
name: Fresh Grocery E-Commerce
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#3e4a3d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#6e7b6c'
  outline-variant: '#bdcaba'
  surface-tint: '#006e2d'
  primary: '#006b2c'
  on-primary: '#ffffff'
  primary-container: '#00873a'
  on-primary-container: '#f7fff2'
  inverse-primary: '#62df7d'
  secondary: '#855300'
  on-secondary: '#ffffff'
  secondary-container: '#fea619'
  on-secondary-container: '#684000'
  tertiary: '#a72d51'
  on-tertiary: '#ffffff'
  tertiary-container: '#c74668'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7ffc97'
  primary-fixed-dim: '#62df7d'
  on-primary-fixed: '#002109'
  on-primary-fixed-variant: '#005320'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#ffd9de'
  tertiary-fixed-dim: '#ffb2bf'
  on-tertiary-fixed: '#3f0016'
  on-tertiary-fixed-variant: '#8a143c'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  layout-max-width: 1280px
  gutter-desktop: 24px
  gutter-tablet: 16px
  gutter-mobile: 12px
  margin-desktop: 32px
  margin-mobile: 16px
  unit-1: 4px
  unit-2: 8px
  unit-3: 12px
  unit-4: 16px
  unit-6: 24px
  unit-8: 32px
---

## Brand & Style

This design system embodies a friendly, modern retail aesthetic tailored for a fresh grocery e-commerce experience. The brand personality is approachable, trustworthy, and vibrant, designed to evoke the feeling of stepping into a sunlit, premium farmers market combined with the efficiency of modern digital retail. 

The visual style leans into a clean, highly legible minimalist approach enriched with tactile warmth. It prioritizes frictionless navigation, immediate readability of nutritional and pricing information, and an appetizing presentation of fresh produce.

## Colors

The color palette is anchored by a vibrant, natural green primary color that signals freshness, health, and vitality. High-contrast dark charcoal is utilized for all primary typography to ensure maximum legibility across product listings and details. 

A warm orange-yellow secondary tone is reserved exclusively for promotional badges, discounts, and urgent callouts. The neutral scale relies on crisp white structural backgrounds layered over soft light gray surfaces, creating a clean canvas that lets product photography pop.

## Typography

The typography system utilizes Plus Jakarta Sans for its soft, rounded, and welcoming geometric characteristics that maintain high legibility at small scales. 

Type scales are optimized for dense product catalogs and rapid scanning. Headlines are weighted heavily for clear section partitioning, while body and label styles prioritize high contrast against light backgrounds to reduce cognitive load during checkout and browsing flows.

## Layout & Spacing

The layout is built on a responsive 12-column fluid grid system designed to scale seamlessly from compact mobile viewports to expansive desktop displays. 

A compact and consistent spacing rhythm based on a 4px foundational unit ensures high-density information display—critical for grocery browsing where users compare prices, quantities, and freshness tags side by side. Margins and gutters scale down appropriately on mobile devices to maximize usable screen estate for product cards.

## Elevation & Depth

Visual hierarchy is communicated through a hybrid approach of subtle ambient shadows and crisp 1px structural borders (`#e2e8f0`). 

Surfaces remain primarily flat with clean boundaries to mirror physical product packaging and shelf tags. Interactive elements such as floating action bars, dropdown menus, and modal dialogs employ soft, diffused shadows with low opacity to gently lift them from the white background without feeling overly dramatic or artificial.

## Shapes

The shape language relies on a friendly, approachable roundedness level (0.5rem base radius). 

Buttons, product cards, input fields, and structural containers feature soft, welcoming corners that eliminate harsh angles while maintaining structural integrity. Smaller interactive elements like category chips and tags utilize pill-shaped variants to denote selectable filter states clearly.

## Components

### Buttons
Primary action buttons utilize the solid fresh green (`#16a34a`) background with crisp white text, rounded corners, and a subtle active scale-down state. Secondary buttons feature a clean white background with a 1px neutral border and dark charcoal text. Destructive or promotional variations incorporate the secondary warm orange/yellow where appropriate.

### Chips & Tags
Category filters and product attributes (e.g., "Organic", "Local", "Gluten-Free") are rendered as compact pills with soft background tints. Selected states invert to solid primary green with white text for immediate visual feedback.

### Input Fields
Search bars and checkout inputs feature a 1px neutral border, soft gray background fills, and generous internal padding. Focus states transition smoothly to the primary green border with a glowing subtle ring.

### Cards
Product cards utilize a crisp white background enclosed within a 1px light gray border. They incorporate generous spacing for product imagery, clear typographic hierarchy for pricing, and a persistent quick-add quantity stepper anchored to the bottom right.

### Additional Components: Quantity Steppers & Delivery Banners
- **Quantity Steppers:** Compact inline controls allowing users to increment or decrement item counts instantly within product cards or the slide-over cart.
- **Delivery Banners:** Persistent top-of-page notifications utilizing soft green or warm yellow accents to communicate real-time delivery windows and minimum order thresholds for free shipping.