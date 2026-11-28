# Shehan Dilhara - Portfolio Website

## Overview

A modern, fully-responsive personal portfolio website showcasing the projects and technical skills of **Shehan Dilhara**, an Information Technology undergraduate at SLIIT interested in Software Development, Linux, DevOps, AI, and Machine Learning.

### Who It's For

- **Target Audience:** Recruiters, hiring managers, and potential collaborators
- **Developer Profile:** BSc (Hons) Information Technology undergraduate at SLIIT
- **Purpose:** Showcase technical skills, academic and personal projects, and professional background

---

## Live Site

[Live Site](https://shehand2004.github.io/shehandilhara.com/)

---

## Features

- 🔎 **SEO Metadata** – Page description, canonical URL, social-sharing metadata, and Person structured data
- 🎯 **Smooth Navigation** – Single-page scrolling with anchor links and active state indicators
- 🔄 **Tabbed Content** – Dynamic tabs for Skills, Experience, and Education sections
- 📱 **Fully Responsive Design** – Mobile-optimized hamburger menu and fluid layouts
- 🎨 **Modern Dark Theme** – Professional dark background with red accent colors (#ff004f, #b70505)
- ⌨️ **Changing Text Animation** – Rotating text effect for dynamic role descriptions
- 🎪 **Interactive Project Cards** – Project thumbnails and descriptions with smooth hover effects
- 🔗 **Projects Navigation** – Header link scrolls directly to the Projects section
- ⚡ **Smooth Scroll Behavior** – Native HTML scroll-behavior for seamless navigation
- 🎭 **Icon Integration** – FontAwesome 6 icons for visual enhancement

---

## Tech Stack

| Category | Technologies |
|----------|---------------|
| **Frontend** | HTML5, CSS3 (Flexbox, CSS Grid), Vanilla JavaScript |
| **Icons** | FontAwesome 6.x |
| **Styling** | CSS3 Animations, Transitions, Responsive Design |
| **Typography** | Poppins Font Family |
| **Design Approach** | Mobile-first, Progressive Enhancement |

---

## Project Structure

```
My-Portfolio/
├── index.html              # Main HTML document
├── style.css              # All styling (animations, layout, responsive)
├── README.md              # Project documentation
├── robots.txt             # Search engine crawler instructions
├── sitemap.xml            # Canonical indexable URL
├── images/
│   ├── Icon.png           # Navigation logo
│   ├── Icon.png           # Browser tab icon
│   ├── Neon Hacker Lair Overlooking the City.png  # Header background image
│   ├── aboutMe.jpg        # Portfolio illustration
│   ├── rag-personal-assistant.jpg
│   ├── system-health-monitor.jpg
│   ├── yt-transcript-extractor.png
│   └── stock-managment-system.png
```

---

## Installation & Setup

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) A local web server for development

### Steps to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shehanD2004/My-Portfolio.git
   cd My-Portfolio
   ```

2. **Open in browser (direct):**
   - Simply open `index.html` in your browser, or

3. **Run with a local server (recommended):**
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Python 2
   python -m SimpleHTTPServer 8000

   # Using Node.js (http-server)
   npx http-server

   # Using PHP
   php -S localhost:8000
   ```

4. **Access the site:**
   - Open `http://localhost:8000` in your browser

---

## Usage

### Navigation
- **Header** – Click nav links to jump to sections (About, Skills, Projects, Contact)
- **Mobile Menu** – Toggle hamburger icon (☰) on smaller screens
- **Smooth Scrolling** – All anchor links smoothly scroll to target sections

### Interactive Sections

#### About Me
- Navigate through **Skills**, **Experience**, and **Education** tabs
- Tabs highlight on click with animated underlines
- Contains profile image and detailed professional summary

#### Projects
- **4 Projects** displayed with:
  - Project thumbnail images
  - Brief descriptions
- Projects featured:
  1. **RAG Personal Assistant** – PDF indexing & AI Q&A system
  2. **System Health Monitor** – Python-based resource monitoring tool
  3. **YouTube Transcript Extractor** – Video transcript processing tool
  4. **Web-Based Stock Management System** – Inventory management application

#### Contact Section
- Placeholder for contact methods (email, LinkedIn, GitHub)
- "LET'S TALK" call-to-action button in header

---

## Customization

### Content Changes

#### Update Personal Information
1. **Name/Title** – Edit `<h1>` and `<span>` text in the header section
2. **About Text** – Modify content in `#about` section
3. **Profile Image** – Replace `images/aboutMe.jpg` with your photo

#### Update Projects
- Edit project details (title, description, image) in the `#projects` section
- Adjust project grid columns in CSS: `.projects-list { grid-template-columns: ... }`
- Replace project images in `images/` folder

#### Change Rotating Text
- Modify `.changing-text` spans to update role descriptions:
  ```html
  <span class="text active">Your First Role</span>
  <span class="text">Your Second Role</span>
  <span class="text">Your Third Role</span>
  ```

### Styling Customization

#### Color Scheme
- **Primary Accent:** `#ff004f` (hot pink) – Currently used for links, underlines, hover states
- **Secondary Accent:** `#b70505` (dark red) – Used for highlighted text and active states
- **Background:** `#000000` (black)
- **Card Background:** `#262626` (dark gray)

To customize, search and replace color values in `style.css`:
```css
/* Main accent color */
#ff004f

/* Secondary accent */
#b70505

/* Backgrounds */
#000000, #262626
```

#### Fonts
- Current: **Poppins** (Google Fonts)
- To change: Update `font-family: 'Poppins', sans-serif;` in CSS

#### Layout & Spacing
- Modify `.container { padding: 10px 10%; }` for content width
- Adjust breakpoints in `style.css` for different device sizes

---

## Deployment

### Option 1: GitHub Pages (Recommended)
1. Push your code to GitHub repository
2. Go to **Settings → Pages**
3. Set **Source** to `main` branch
4. Site publishes automatically at `https://username.github.io/My-Portfolio/`

### Option 2: Vercel
1. Sign up at [vercel.com](https://vercel.com)
2. Import GitHub repository
3. Select `index.html` as entry point
4. Deploy – instant live preview with each push

### Option 3: Netlify
1. Sign up at [netlify.com](https://netlify.com)
2. Connect GitHub or drag-and-drop folder
3. Auto-builds and deploys on each commit
4. Free HTTPS and custom domain support

### Option 4: Self-Hosted
- Upload files via FTP to any web hosting provider
- Ensure `index.html` is accessible at root directory

---

## Contact

### Get in Touch

- 📧 **Email:** [Gmail](dshehan588@gmail.com)
- 💼 **LinkedIn:** [LinkedIn profile](https://www.linkedin.com/in/shehandilhara/)
- 🐙 **GitHub:** [github.com/shehanD2004](https://github.com/shehanD2004)
- 🌐 **Portfolio:** [This website](https://shehand2004.github.io/My-Portfolio/)

### How to Reach Out
- Click the **"LET'S TALK"** button in the header
- Navigate to the **Contact** section (bottom of page)
- Use the provided email or social links

---

## JavaScript Features

### Menu Toggle
- `openmenu()` – Opens mobile navigation
- `closemenu()` – Closes mobile navigation

### Tab Switching
- `opentab(tabName, event)` – Switches between Skills, Experience, Education tabs
- Auto-highlights active tab with animated underlines

### Animations
- Changing text rotates through different role descriptions
- Cards and links have smooth hover effects
- Main page content is visible immediately without waiting for JavaScript

*Note: All scripts are inline in `index.html` for simplicity*

---

## Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| IE 11 | ⚠️ Limited (CSS Grid) |

---

## Performance Optimization Tips

1. **Compress Images** – Reduce image file sizes (especially background images)
2. **Lazy Loading** – Consider adding for project images if list grows
3. **CSS Minification** – Minify `style.css` for production
4. **Font Optimization** – Use system fonts or font-display: swap for Poppins
5. **Caching** – Enable browser caching headers on web server

---

## Future Enhancements

- [ ] Dark/Light mode toggle
- [ ] Add blog or articles section
- [ ] Search functionality for projects
- [ ] Testimonials/recommendations section
- [ ] Integration with external portfolio APIs
- [x] SEO metadata, canonical URL, structured data, robots.txt, and sitemap.xml
- [ ] Analytics integration

---

## License

MIT

---

## Author

**Shehan Dilhara**  
Information Technology Undergraduate | Full-Stack Development | AI/ML Enthusiast

---

## Changelog

- **v1.0** – Initial portfolio launch
  - Main page content is visible immediately
  - Multi-section layout (About, Services, Portfolio)
  - Responsive design
  - Dark theme with custom animations

---

## Support

For issues, questions, or improvements:
1. Open a GitHub issue in the repository
2. Contact via email (see Contact section)
3. Submit a pull request with suggestions

---

**Last Updated:** November 2026
**Status:** Active & Maintained
