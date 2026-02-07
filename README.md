# Cursor Website Clone

This project is a frontend clone of the **Cursor** marketing website, built using **HTML** and **CSS**.  
<img width="1906" height="947" alt="image" src="https://github.com/user-attachments/assets/4237c8e2-e4dc-4249-ac14-56b51e2c57e8" />

---

## Recreated Sections

The following sections were recreated based on the original Cursor website:

- **Header / Navigation**
  - Logo, product name
  - Navigation links (Features, Enterprise, Pricing, Resources)
  - Sign in and Download buttons
  - Fixed header layout

- **Hero Section**
  - Main headline and subtext
  - Primary CTA (Download for Windows)
  - Hero image

- **Partners / Trust Section**
  - “Trusted by developers” text
  - Partner logo grid (Stripe, Linear, OpenAI, Figma, etc.)

- **Features Section**
  - Three main feature blocks
  - Alternating text + image layout
  - Accent links for feature exploration

- **Testimonials / Reviews**
  - Grid-based testimonial cards
  - Author avatars, names, and roles

- **Frontier Features**
  - Three-column feature cards
  - Headings, descriptions, and CTA links

- **Changelog**
  - Version tags
  - Release dates
  - Update descriptions

- **Highlights Overlay**
  - Recent highlights list
  - Research posts with descriptions and dates

- **Call To Action**
  - “Try Cursor now” section
  - Large headline with download button

- **Footer**
  - Product, Resources, Company, Legal, and Connect links
  - Copyright notice

---

## Fonts Used

- **Primary Display Font**
  - `Space Grotesk`
  - Used for headings, branding, and prominent text

- **System Font Stack**
  - `system-ui, -apple-system, sans-serif`
  - Used for body text and UI elements for better performance and consistency

```css
--ff-display: "Space Grotesk", sans-serif;
--ff-sans: system-ui, -apple-system, sans-serif;
```
## Colors Used

The project uses **CSS variables** for consistency and easy theming.

### Background Colors
- **Main Background:** `#14120b`
- **Surface / Cards:** `#1b1913`

### Text Colors
- **Primary Text:** `#edecec`
- **Muted Text:** `color-mix(in oklab, #edecec 60%, transparent)`
- **Accent Color:** `#f54e00`

### Borders
- **Subtle Border:**  
  `color-mix(in oklab, #edecec 20%, transparent)`

```
--bg-main: #14120b;
--bg-surface: #1b1913;
--text-main: #edecec;
--text-muted: color-mix(in oklab, var(--text-main) 60%, transparent);
--text-accent: #f54e00;
--border: color-mix(in oklab, var(--text-main) 20%, transparent);
```
