# NutriHealth - Landing Page Project

## Project Overview

**NutriHealth** is a high-conversion landing page for a hair transplant (trasplante capilar) clinic based in the Dominican Republic. The site is designed to convert cold traffic from social media ads (Facebook, Instagram, TikTok) into scheduled consultations.

The clinic specializes in FUE + DHI hair transplant techniques, offering a comprehensive all-inclusive patient experience across 9+ branches in the Dominican Republic.

**Author:** Franklin Hernandez

## Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Single-page landing page structure |
| **Tailwind CSS v4** | Utility-first styling with custom theme |
| **Tailwind CLI** | CSS build pipeline |
| **Google Fonts** | Montserrat font family |
| **Meta Pixel** | Facebook/Instagram ad tracking |
| **WhatsApp API** | Lead capture via WhatsApp messaging |

## Project Structure

```
nutrihealth/
├── index.html              # Main landing page (single file application)
├── input.css               # Tailwind CSS input with custom theme
├── animation.css           # Carousel and animation keyframes
├── package.json            # Node.js dependencies (Tailwind)
├── .gitignore              # Git ignore rules
├── agent-landing-page-expert.md    # Landing page conversion strategy guide
├── agent-nutrihealth-brand-expert.md  # Brand identity and guidelines
└── .qwen/skills/           # Qwen Code skills (ai-image-generator, transplant-capilar-sales)
```

**Note:** Files listed in `.gitignore` (`Carrusel.html`, `script.js`, `style.css`) are excluded from the repository.

## Key Features

### Landing Page Sections (Conversion Funnel)
1. **Urgency Bar** - Limited availability messaging
2. **Navigation** - Sticky nav with logo and CTA
3. **Hero Section** - Headline, video embed, key benefits, quick form
4. **Problem Section** - Empathetic pain point identification
5. **Solution Section** - All-inclusive plan breakdown (Procedure + Post-op)
6. **Before/After Carousel** - Real patient results with lightbox
7. **How It Works** - 5-step process visualization
8. **About Us** - Clinic credentials and experience
9. **FAQ** - Common objections (accordion style)
10. **Final CTA** - Detailed contact form with hair loss zone selector
11. **WhatsApp Float Button** - Popup chat for instant lead capture

### Lead Capture
- **Three entry points:** Hero form, contact form, WhatsApp popup
- All forms redirect to WhatsApp (`+18299139470`) with pre-filled patient data
- Meta Pixel `Lead` events fire on each form submission

### Brand Colors (Tailwind Theme)
| Token | Hex | Usage |
|-------|-----|-------|
| `primary` | `#1e692d` | Green - main brand color, CTAs |
| `secondary` | `#c1cf46` | Lime green - accent, buttons |
| `softGrey` | `#f4f4f4` | Backgrounds, borders |
| `darkGrey` | `#444444` | Body text |
| `accent` | `#164d21` | Dark green - hover states |

## Building and Running

### Install Dependencies
```bash
npm install
```

### Build CSS (Tailwind)
```bash
npx @tailwindcss/cli -i ./input.css -o ./style.css --watch
```

### Development
The project currently references `style.css` and `script.js` (both gitignored). The landing page is primarily a single-file HTML application with inline styles and scripts. To run locally, serve the `index.html` file:

```bash
# Simple HTTP server
npx serve .
# or
python -m http.server 8000
```

## Development Conventions

- **Single-page architecture** - All content in `index.html`
- **Mobile-first responsive design** - Extensive use of Tailwind's `md:` breakpoints
- **Inline critical config** - Tailwind config is embedded in the HTML `<script>` tag
- **External assets** - Images and videos hosted on `nutrihealth.com.do` CDN
- **WhatsApp integration** - All forms lead to WhatsApp with formatted messages
- **Meta Pixel tracking** - PageView on load, Lead events on form submissions

## Brand Guidelines

The project follows the **NutriHealth** brand identity:
- **Tagline:** *(en actualización)*
- **Positioning:** #1 Hair Transplant Clinic in the Dominican Republic
- **Tone:** Professional yet empathetic, clinical but warm
- **Values:** Medical supervision, safety, sustainable results, personalized care
- **Target audience:** Men and women, 30-55 years, Dominican Republic

Detailed brand guidelines and conversion optimization strategies are documented in:
- `agent-nutrihealth-brand-expert.md` - Brand identity, voice, and content guidelines
- `agent-landing-page-expert.md` - Landing page conversion framework (PAS + AIDA)

## External Resources

- **Official website:** www.nutrihealth.com.do
- **WhatsApp number:** +18299139470
- **Meta Pixel ID:** 1763457057916073
- **YouTube embed:** Patient transformations video
