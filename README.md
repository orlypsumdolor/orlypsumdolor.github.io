# Orlando Yanson Jr - Professional Portfolio

A modern, responsive portfolio website showcasing 12+ years of experience in mobile and backend development.

## 🌟 Features

- **Modern Dark Theme Design**: Clean, professional layout with smooth animations and transitions
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Multi-Page Navigation**: Dedicated pages for Home, About, Services, Portfolio, and Contact
- **Profile Integration**: Professional headshot with hover effects
- **Social Media Links**: Quick access to GitHub, LinkedIn, Email, and Phone
- **Interactive Elements**: Hover effects on cards, buttons, and links
- **Skill Tags**: Visual display of technical expertise
- **Timeline Experience**: Professional journey with detailed company information
- **Interactive Project Showcase**: 15 featured projects with hover effects, skill tags, and external links
- **Project Cards**: Modern grid layout with gradient accents, smooth animations, and responsive design
- **Contact Form**: Professional contact form with social links
- **No Dependencies**: Pure HTML5 and CSS3 with no external libraries

## 🚀 Quick Start

### Local Development

1. Clone this repository
2. Open `index.html` in your browser
3. All styles are embedded, no build process required!

### Deploy to GitHub Pages

1. **Create a GitHub repository** named `username.github.io` (replace `username` with your GitHub username)

2. **Upload files** to the repository:
   - `index.html`
   - `about.html`
   - `services.html`
   - `portfolio.html`
   - `contact.html`
   - `profile.jpg`

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Navigate to "Pages" section
   - Under "Source", select the `main` branch
   - Click "Save"

4. **Your site will be live at**: `https://username.github.io`

## 🔧 Customization

### Update Social Media Links

Edit the social links in the hero section (lines 521-544):

```html
<a href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer" class="social-link">
<a href="https://linkedin.com/in/YOUR_PROFILE" target="_blank" rel="noopener noreferrer" class="social-link">
<a href="mailto:YOUR_EMAIL@example.com" class="social-link">
<a href="https://twitter.com/YOUR_HANDLE" target="_blank" rel="noopener noreferrer" class="social-link">
```

### Update Email Address

Replace `orlando.yanson@example.com` with your actual email address in:
- Hero section email link (line 533)
- Contact CTA button (line 752)

### Change Profile Image

Replace `profile.jpg` with your own professional photo. For best results:
- Use a square image (recommended: 500x500px or larger)
- Ensure good lighting and professional appearance
- The image will be automatically cropped to a circle

### Modify Colors

Update the CSS variables in the `:root` section (lines 16-23):

```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --secondary-color: #1e40af;    /* Darker blue */
    --text-primary: #1f2937;       /* Dark text */
    --text-secondary: #6b7280;     /* Gray text */
    --bg-light: #f9fafb;          /* Light background */
    --bg-white: #ffffff;          /* White background */
    --border-color: #e5e7eb;      /* Border color */
    --accent-color: #10b981;      /* Green accent */
}
```

### Add More Skills

Add more skill tags in the skills container (lines 568-583):

```html
<span class="skill-tag">Your Skill</span>
```

### Add More Projects

Add more project cards in the Projects section:

```html
<div class="project-card">
    <div class="project-header">
        <div class="project-title">Project Name</div>
        <div class="project-company">Company Name</div>
    </div>
    <div class="project-body">
        <p class="project-description">Project description...</p>
        <div class="project-skills">
            <span class="project-skill">Skill</span>
        </div>
        <a href="https://project-url.com" target="_blank" rel="noopener noreferrer" class="project-link">
            View Project
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path d="M7 7h10v10M7 17l10-10"/>
            </svg>
        </a>
    </div>
</div>
```

## 📱 Social Media Links

The portfolio includes pre-configured links for:

- **GitHub**: Showcase your repositories and open-source contributions
- **LinkedIn**: Professional networking and career history
- **Email**: Direct contact for opportunities
- **Phone**: Direct communication for urgent matters

## 🎨 Design Features

- **Color Scheme**: Modern dark theme with teal cyan accent colors (#00d9ff)
- **Typography**: System fonts for fast loading and native appearance
- **Animations**: Smooth fade-in effects on page load and scroll
- **Accessibility**: Semantic HTML with proper ARIA labels
- **SEO Optimized**: Meta tags for better search engine visibility
- **Navigation**: Fixed navbar with smooth scrolling and active page highlighting

## 📄 Pages

### 🏠 Home (index.html)
1. **Hero Section**: Split layout with greeting, name, title, and profile image
2. **Summary**: Professional overview with key achievements and skills
3. **Experience**: Detailed work history with 9 companies
4. **Featured Projects**: 15 interactive project cards showcasing major work
5. **Education**: Academic background
6. **Contact CTA**: Call-to-action for collaboration
7. **Footer**: Copyright information

### ℹ️ About (about.html)
- Professional background and journey
- Technical skills showcase
- Education details

### 💼 Services (services.html)
- Mobile App Development
- Cross-Platform Development
- Backend Architecture
- Technical Leadership
- System Integration
- Consulting & Strategy

### 🎨 Portfolio (portfolio.html)
- All 15 featured projects with descriptions
- Skill tags for each project
- External links to live projects

### 📧 Contact (contact.html)
- Contact information
- Professional contact form
- Social media links

## 🛠️ Technologies Used

- Pure HTML5
- CSS3 with modern features (Grid, Flexbox, Animations)
- SVG icons for social media
- No external dependencies or frameworks

## 📊 Performance

- **Fast Loading**: Single HTML file with embedded CSS
- **Optimized Images**: Recommended image compression for profile photo
- **Minimal HTTP Requests**: All resources embedded or local
- **Mobile-First**: Responsive design for all screen sizes

## 📝 License

© 2025 Orlando Yanson Jr. All rights reserved.

## 🤝 Support

For issues or questions about this portfolio template, please update the content to match your information.

---

Built with passion for clean code and great user experiences.

