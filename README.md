# Shehan Dilhara - Portfolio Website

## Overview

A modern, fully-responsive personal portfolio website showcasing the professional work, skills, and projects of **Shehan Dilhara**, a Software Engineering undergraduate passionate about full-stack web development, AI, and innovative technology solutions.

### Who It's For

- **Target Audience:** Recruiters, hiring managers, and potential collaborators
- **Developer Profile:** Information & Technology undergraduate specializing in Information and Technology
- **Purpose:** Showcase technical expertise, academic projects, professional services, and facilitate networking/hiring opportunities

---

## Live Site

[Live Site](https://shehand2004.github.io/My-Portfolio/)

---

## Features

- ✨ **Animated Splash Screen** – Eye-catching intro with fade-in animation
- 🎯 **Smooth Navigation** – Single-page scrolling with anchor links and active state indicators
- 🔄 **Tabbed Content** – Dynamic tabs for Skills, Experience, and Education sections
- 📱 **Fully Responsive Design** – Mobile-optimized hamburger menu and fluid layouts
- 🎨 **Modern Dark Theme** – Professional dark background with red accent colors (#ff004f, #b70505)
- ⌨️ **Changing Text Animation** – Rotating text effect for dynamic role descriptions
- 🎪 **Interactive Service Cards** – Hover effects with smooth transforms and background transitions
- 🔗 **Project Showcase** – Portfolio section with project descriptions and direct GitHub links
- ⚡ **Smooth Scroll Behavior** – Native HTML scroll-behavior for seamless navigation
- 🎭 **Icon Integration** – FontAwesome 6 icons for visual enhancement
- 📄 **CV/Resume Access** – Quick access to downloadable CV

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
├── images/
│   ├── Icon.png           # Navigation logo
│   ├── favicon.ico        # Browser tab icon
│   ├── Back.jpg           # Header background image
│   ├── MBack.jpg          # Mobile background variant
│   ├── aboutMe.jpg        # Profile picture
│   ├── Shehan_Dilhara_CV.pdf  # Resume/CV
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
- **Header** – Click nav links to jump to sections (Home, About, Services, Portfolio, Contact)
- **Mobile Menu** – Toggle hamburger icon (☰) on smaller screens
- **Smooth Scrolling** – All anchor links smoothly scroll to target sections

### Interactive Sections

#### About Me
- Navigate through **Skills**, **Experience**, and **Education** tabs
- Tabs highlight on click with animated underlines
- Contains profile image and detailed professional summary

#### My Services
- **3 Service Cards** showcase main offerings:
  - Web Development
  - UI / UX Design
  - App Development
- Cards feature hover animations and icon indicators

#### Portfolio / Projects
- **4 Recent Projects** displayed with:
  - Project thumbnail images
  - Brief descriptions
  - Direct links to GitHub repositories
- Projects featured:
  1. **RAG Personal Assistant** – PDF indexing & AI Q&A system
  2. **System Health Monitor** – Python-based resource monitoring tool
  3. **YouTube Transcript Extractor** – Video transcript processing tool
  4. **Web-Based Stock Management System** – Inventory management application

#### Contact Section
- Placeholder for contact methods (email, LinkedIn, GitHub)
- "LET'S TALK" call-to-action button in header

---

## Screenshots / Preview

### Desktop View
- **Hero Section** – Full-screen header with background image and animated text
- **About Section** – Two-column layout (profile image + bio + tabs)
- **Services** – 3-column grid layout with service cards
- **Portfolio** – 2×2 grid or responsive layout of project cards

### Mobile View
- **Responsive Breakpoints** – Stack to single column on smaller screens
- **Mobile Menu** – Hamburger toggle with slide-out navigation
- **Touch-Friendly** – Larger tap targets, optimized spacing

*For actual screenshots, add images to this section after deploying*

---

## Customization

### Content Changes

#### Update Personal Information
1. **Name/Title** – Edit `<h1>` and `<span>` text in the header section
2. **About Text** – Modify content in `#about` section
3. **Profile Image** – Replace `images/aboutMe.jpg` with your photo
4. **CV/Resume** – Replace `images/Shehan_Dilhara_CV.pdf` with your resume

#### Modify Services
- Edit service descriptions in the `#services` section
- Change icons by updating FontAwesome class names
- Adjust grid columns in CSS: `.services-list { grid-template-columns: ... }`

#### Update Projects
- Edit project details (title, description, image) in the `#portfolio` section
- Update GitHub links: modify `href` in `<a>` tags
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
- 💼 **LinkedIn:** [LinkedIn profile URL](https://www.linkedin.com/in/shehan-dilhara)
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
- Fade-in splash screen on page load

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
- [ ] SEO metadata optimization
- [ ] Analytics integration

---

## License

Not specified in source. Consider adding an open-source license (MIT, Apache 2.0) if sharing.

---

## Author

**Shehan Dilhara**  
Information Technolology Undergraduate | Full Stack Developer | AI/ML Enthusiast

---

## Changelog

- **v1.0** – Initial portfolio launch
  - Splash screen animation
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

**Last Updated:** June 2026  
**Status:** Active & Maintained
