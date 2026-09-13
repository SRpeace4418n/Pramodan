# Pramodan — Artisan Healthy Snacking & Pantry Showcase

> **Bringing Healthy Snacking Into a More Joyful Future.**  
> A vibrant, editorial digital showcase for **Pramodan** — transforming healthy everyday snacks and pantry staples into desirable, emotionally engaging lifestyle products.

---

## 🌾 About The Project

Pramodan was conceived to challenge conventional snacking by proving that healthy snacks can be just as joyful, bold, and culturally vibrant as traditional junk foods. 

Named after one of the many names of Lord Vishnu, the brand infuses cultural storytelling with contemporary FMCG aesthetics:
- **Logo Symbolism**: The central "O" in the wordmark doubles as an illustrated popped makhana and a stylized Sudarshan Chakra.
- **Brand Personality**: Joy, playfulness, warmth, celebration, and positive energy inspired by Lord Krishna's joyful nature.
- **Product Architecture**: A master brand scaling across multiple product categories — from premium roasted makhana to raw monofloral honey and artisan lotus/millet cookies.

---

## 🚀 Live Showcase Pages

| Page | Description | Primary Visual System |
| :--- | :--- | :--- |
| **[`index.html`](index.html)** | **Main Entrypoint / Makhana Showcase** | Warm Cream, Pistachio, Turmeric, Crimson accents |
| **[`pramodan_showcase.html`](pramodan_showcase.html)** | **Roasted Makhana Collection** | 7 Signature Flavours with interactive switcher & floating doodles |
| **[`pramodan_honey.html`](pramodan_honey.html)** | **Raw Monofloral Honey** | Golden Amber, Forest Honey, Honeycomb doodles, Pollen textures |
| **[`pramodan_cookies.html`](pramodan_cookies.html)** | **Artisan Millet & Lotus Cookies** | Warm Baked Tones, Biscoff spice, Sugar-Free Almond, Artisanal cards |
| **[`pramodan_color_palette_system.html`](pramodan_color_palette_system.html)** | **Design Tokens & Palette Specs** | Full architectural color swatch & accessibility specifications |

---

## ✨ Key Features & UX Design

- **Interactive Category Switcher**: Seamless 1-click navigation between Makhana, Honey, and Cookies collections with persistent visual state.
- **Dynamic Flavour Switcher**: Live packet morphing, background hue shifts, nutrition chips, and ingredient callouts.
- **Fixed Floating Glassmorphic Navigation**: Seamless floating bar with blur backdrop, responsive brand logo, and responsive mobile Quick-Order CTA.
- **Zero-Dead-Space Layout**: Precision clamped vertical rhythm (`clamp()` formulas) eliminating dead viewport gaps across all monitor and mobile resolutions.
- **Responsive & Mobile Optimized**: Tested across desktop (1920x1080, 1440x900), tablets (768px), and mobile devices (375px - 430px).
- **Custom Brand Favicon & Touch Icons**: Bespoke Sudarshan Makhana emblem icon configured in multi-resolution formats (`16x16`, `32x32`, `48x48`, `192x192`, `512x512`, `apple-touch-icon`).

---

## 🎨 Tech Stack

- **Semantic HTML5**: Clean, accessible markup with structured heading hierarchies and meta tags.
- **Modern Vanilla CSS3**: Custom CSS custom properties (CSS variables), CSS Grid, Flexbox, backdrop filters, and fluid clamp units.
- **Lightweight Vanilla JavaScript**: Smooth transitions, tab state synchronization, and touch-friendly interactions without heavy framework dependencies.
- **Vector Assets & High-Res Imagery**: SVG doodles and optimized product photography for fast load times.

---

## 🛠️ Local Development & Preview

To preview the website locally:

```bash
# Clone the repository
git clone https://github.com/SRpeace4418n/Pramodan.git

# Navigate into the project folder
cd Pramodan

# Open index.html in your default browser
# (Windows)
start index.html
# (macOS)
open index.html
# (Linux)
xdg-open index.html
```

Or run any local development server:
```bash
npx serve .
# or
python -m http.server 8080
```

---

## 📦 Directory Structure

```text
Pramodan/
├── index.html                           # Root entrypoint (GitHub Pages ready)
├── pramodan_showcase.html               # Makhana flagship showcase
├── pramodan_honey.html                  # Raw honey collection
├── pramodan_cookies.html                # Artisan cookies collection
├── pramodan_color_palette_system.html   # Brand color token specifications
├── pramodan_assets/                     # Product packs, illustrations, SVG doodles
│   ├── doodles/                         # Vector ingredients & floral decorations
│   ├── Logo.png                         # Master brand stacked logo
│   ├── Secondry_Logo_crimson.png        # Emblemed wordmark logo
│   └── ...                              # Category photography & packshots
├── favicon.ico                          # Multi-size site favicon
├── apple-touch-icon.png                 # iOS touch icon
├── README.md                            # Project documentation
└── .gitignore                           # Ignored source/system files
```

---

## 👤 Author

- **Creative Direction & Design**: [SR Creative Studio](https://www.instagram.com/pramodan.store)
- **GitHub**: [@SRpeace4418n](https://github.com/SRpeace4418n)
