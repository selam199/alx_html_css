# 😄 SmileSchool — Advanced HTML & CSS Project

Welcome to the **SmileSchool Landing Page**, a responsive and visually engaging HTML project crafted as part of the **ALX Front-End Curriculum**. This advanced concept exercise showcases clean layout structuring, modular content, and semantic markup — all aimed at delivering a high-quality user experience.

---

## 📁 Project Contents

This folder (`css_advanced`) contains:

- `index.html` – Main landing page HTML file
- `README.md` – Project documentation (this file)
- `images/` – Folder with all required image assets such as:
  - `logo1.png`, `logo.png`
  - Instructor avatars: `phillip massay.png`, `nanni.png`, `henry.png`, `bruce.png`
  - Smiles: `happy.png`, `sad.png`, `natural.png`
  - Other assets: `person name.png`, `diagonal.png`

## 🌟 Key Features

- **Semantic HTML5** layout with accessible elements
- Clear sectioning for maintainability
- Font Awesome social and rating icons (loaded via CDN)
- Realistic testimonials and instructor highlights
- Reusable content blocks for pricing, tutorials, and FAQs
- CTA (Call-to-Action) and consistent footer

---

## 🧩 Features

- Responsive layout using **flexbox**
- Custom fonts from **Google Fonts** (`Source Sans Pro`)
- Styled navigation and hero sections
- Background image with full-screen height
- Highlighted text spans for emphasis (`SMILES`, `GRIN`, `LAUGH`)
- Accessible and clean HTML5 structure

## 🛠️ Technologies Used

- **HTML5**
- **CSS3 (Flexbox, custom fonts, text transforms)**
---

## 📥 Setup Instructions

To run this project locally:

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/alx_html_css.git
   cd alx_html_css/css_advanced

# 💬 Quote Section Styles
- **Background Styling**
  - Uses a distinctive purple (`#C271FF`) background to highlight the section.
- **Flexbox Layout**
  - The `.quote-block` class uses `display: flex` to horizontally align quote text and images.
- **Typography**
  - White text with bold author names
  - Smaller font size for quotes for visual hierarchy
- **Responsive Alignment**
  - Uses `max-width` and `margin: auto` for center alignment and layout control
---
## 🔤 CSS Classes Explained

### `.quote-section`
- Sets the section background color
- Adds padding for spacing above and below

### `.quote-block`
- Creates a horizontal flex layout
- Centers the content and controls width
- Adds space between avatar and quote text

# 🎬 Video Tutorial Section - Responsive Flex Layout
- Responsive layout using Flexbox
- Each video block includes:
  - Thumbnail with play icon
  - Title and description
  - Author info
  - 5-star rating and duration
- Mobile-friendly design with wrapping behavior
