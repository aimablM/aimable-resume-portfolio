# Developer Resume Portfolio Website - Based on Vanilla HTML/CSS/Javascript

<div align="center">
  <img src="img/amlogo.svg" alt="AM Logo" width="120" height="120"/>
  <h3>A Modern, Responsive Developer Portfolio</h3>
  <p>Showcase your skills, projects, and experience with this sleek portfolio template</p>
</div>

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Usage & Customization](#usage--customization)
- [Design Approach](#design-approach)
- [Performance Optimizations](#performance-optimizations)
- [Browser Compatibility](#browser-compatibility)
- [Future Development](#future-development)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

This developer resume is a clean, responsive single-page website designed to showcase your professional background, skills, projects, and experience in an elegant and modern format.

The dark-themed design creates visual appeal while maintaining excellent readability, and the responsive layout ensures a seamless experience across all devices, from mobile phones to large desktop screens.

## Features

### Professional Profile Section
- **Prominent personal branding** with logo and name display
- **Contact information** with social media integration
- **Educational background** showcasing academic achievements
- **Certifications section** highlighting professional credentials
- **Resume download option** for easy access to detailed credentials

### Content Sections
- **About Me** - A concise professional summary
- **Skills Showcase** - Organized by categories:
  - Programming Languages
  - Web Technologies
  - Databases
  - Tools & Platforms
- **Project Portfolio** - Featuring:
  - Project descriptions
  - Technologies used
  - Direct GitHub links
- **Work Experience** - Detailed professional history with:
  - Role descriptions
  - Company information
  - Key achievements
- **Interests & Coursework** - Providing additional context and qualifications

### UI/UX Design
- **Dark theme** with accented elements for visual interest
- **Responsive grid layout** adapting to any screen size
- **Fixed sidebar** on larger screens for easy navigation
- **Interactive elements** with hover effects for improved engagement
- **Icon integration** for visual context and hierarchy

## Technology Stack

### Core Technologies
- **HTML5**: Semantic markup for improved accessibility and SEO
- **CSS3**: Modern styling with:
  - CSS Grid for two-dimensional layouts
  - Flexbox for one-dimensional component arrangements
  - CSS Variables for consistent theming
  - Media queries for responsive design

### External Resources
- **Font Awesome 6.4.0**: Comprehensive icon library for visual enhancements
- **Google Fonts**: Typography options for consistent cross-platform text rendering

### Development Approach
- **Mobile-first design**: Ensuring compatibility with all device sizes
- **Progressive enhancement**: Core functionality works everywhere with enhanced experiences on modern browsers
- **Semantic HTML**: Properly structured content for accessibility and SEO benefits

## Project Structure

```
portfolio-website/
├── index.html              # Main HTML document
├── styles.css              # CSS styling
├── img/                    # Image assets
│   └── amlogo.svg          # Personal brand logo
├── AimableMugwaneza_Resume.pdf  # Downloadable resume
└── README.md               # Project documentation
```

## Installation & Setup

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   cd portfolio-website
   ```

2. **Open with a local server**:
   - Using Python:
     ```bash
     # Python 3
     python -m http.server 8000
     # Python 2
     python -m SimpleHTTPServer 8000
     ```
   - Using Node.js and npm:
     ```bash
     # Install serve globally
     npm install -g serve
     # Run server
     serve
     ```
   - Using VS Code:
     Install the "Live Server" extension and click "Go Live" in the status bar

3. **View in browser**:
   Open your browser and navigate to `http://localhost:8000` (or the port shown in your terminal)

### Deployment Options

#### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select your main branch as the source
4. Your site will be published at `https://yourusername.github.io/repository-name/`

#### Netlify
1. Sign up for a Netlify account
2. Click "New site from Git"
3. Select your repository
4. Deploy with default settings
5. Your site will be published with a Netlify subdomain (customizable)

#### Vercel
1. Sign up for a Vercel account
2. Import your repository
3. Configure as needed
4. Deploy to receive a Vercel subdomain (customizable)

## Usage & Customization

### Personal Information

Edit `index.html` to update:
- Your name and location
- Social media links
- Education details
- Work experience
- Projects
- Skills

### Styling Customization

Modify `styles.css` to change:
- Color scheme (update CSS variables in `:root`)
- Layout proportions
- Typography
- Spacing and sizing

```css
/* Example custom color scheme */
:root {
    --dark-bg: #121212;
    --text-color: #f5f5f5;
    --accent-color: #64ffda;
    --secondary-bg: #1e1e1e;
    --border-color: #333;
    --hover-color: #7efff0;
}
```

### Adding Projects

To add a new project, copy and modify the following HTML structure:

```html
<div class="project-card">
    <h3><i class="fas fa-icon-name"></i> Project Title</h3>
    <p class="project-tech">Technologies Used</p>
    <p>Project description with key features and accomplishments.</p>
    <a href="https://github.com/yourusername/project-name" class="project-link">
        <i class="fab fa-github"></i> View on GitHub
    </a>
</div>
```

## Design Approach

### Visual Design Principles

This portfolio follows key design principles:

1. **Visual Hierarchy**: Important elements receive more visual weight through size, color, and positioning
2. **Contrast**: Dark background with light text ensures readability and reduces eye strain
3. **Consistency**: Repeated visual patterns and unified color scheme create cohesion
4. **Balance**: Grid layout provides structural stability while allowing for visual interest
5. **Whitespace**: Generous spacing improves content comprehension and visual appeal

Contributions are welcome! If you'd like to improve this portfolio template:

1. **Fork the repository**
2. **Create a feature branch**:
   ```bash
   git checkout -b feature/awesome-improvement
   ```
3. **Make your changes**
4. **Commit with meaningful messages**:
   ```bash
   git commit -m "Add awesome feature XYZ"
   ```
5. **Push to your branch**:
   ```bash
   git push origin feature/awesome-improvement
   ```
6. **Open a pull request**

### Contribution Guidelines
- Follow existing code style
- Update documentation for any new features
- Test changes across browsers and device sizes
- Keep accessibility in mind

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Aimable Mugwaneza - [aimable.mugwaneza@gmail.com](mailto:aimable.mugwaneza@gmail.com)

Project Link: [https://github.com/aimablM/portfolio-website](https://github.com/aimablM/portfolio-website)

Portfolio: [https://aimablem.dev](https://aimablem.dev)

---

<div align="center">
  <p>Built with ❤️ by <a href="https://github.com/aimablM">Aimable Mugwaneza</a></p>
</div>
