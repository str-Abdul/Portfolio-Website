# Abdul Ahad - Developer Portfolio Website

A modern, responsive developer portfolio website for Abdul Ahad, a MERN Stack Developer. Features a clean design, smooth animations, and mobile-first approach showcasing backend development expertise and real-time application projects.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling and active section highlighting
- **Mobile Menu**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Beautiful project cards with hover effects
- **Skills Section**: Organized skills display with icons
- **Experience Timeline**: Professional timeline layout
- **Social Links**: Easy integration with social media profiles
- **Loading Animations**: Smooth page load and scroll animations

## 📁 File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Clone or Download**: Download all files to your local machine
2. **Open in Browser**: Simply open `index.html` in your web browser
3. **Customize**: Follow the customization guide below
4. **Deploy**: Upload to your preferred hosting service

## 🎨 Customization Guide

### 1. Personal Information

Update the following sections in `index.html`:

#### Hero Section
```html
<!-- Line 47: Update your name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Abdul Ahad</span>
</h1>

<!-- Line 48: Update your title -->
<h2 class="hero-subtitle">MERN Stack Developer</h2>

<!-- Lines 49-52: Update your description -->
<p class="hero-description">
    BSCS undergraduate with hands-on MERN stack experience, passionate about building scalable applications 
    and contributing to real-world team environments. Specialized in backend development and real-time applications.
</p>
```

#### About Section
```html
<!-- Lines 95-105: Update your about text -->
<p>
    I'm a BSCS undergraduate with hands-on MERN stack experience, seeking opportunities to polish existing skills, 
    contribute to scalable applications, and grow through real-world team environments. 
    I specialize in backend development with Node.js, Express, and MongoDB.
</p>
```

#### Contact Information
```html
<!-- Lines 280-290: Update contact details -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>ahad22671@gmail.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>0317-8411366</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Karachi, Pakistan</span>
</div>
```

### 2. Social Media Links

Update the social media links in the hero section and contact section:

```html
<!-- Lines 58-61: Update social links -->
<div class="hero-social">
    <a href="https://github.com/str-Abdul" class="social-link"><i class="fab fa-github"></i></a>
    <a href="https://www.linkedin.com/in/abdul-ahad-400582253/" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="mailto:ahad22671@gmail.com" class="social-link"><i class="fas fa-envelope"></i></a>
</div>
```

### 3. Skills & Technologies

Update the skills section to match your expertise:

```html
<!-- Lines 130-180: Update skills -->
<div class="skill-items">
    <div class="skill-item">
        <i class="fab fa-html5"></i>
        <span>HTML5</span>
    </div>
    <div class="skill-item">
        <i class="fab fa-css3-alt"></i>
        <span>CSS3</span>
    </div>
    <!-- Add more skills as needed -->
</div>
```

### 4. Projects

Replace the sample projects with your own:

```html
<!-- Lines 200-250: Update projects -->
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-laptop-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project and what technologies you used.</p>
        <div class="project-tech">
            <span>React</span>
            <span>Node.js</span>
            <span>MongoDB</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourusername/project" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="https://yourproject.com" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### 5. Experience

Update the experience timeline with your work history:

```html
<!-- Lines 270-320: Update experience -->
<div class="timeline-item">
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="period">2022 - Present</span>
        </div>
        <p>Description of your role and achievements.</p>
        <ul>
            <li>Key achievement 1</li>
            <li>Key achievement 2</li>
            <li>Key achievement 3</li>
        </ul>
    </div>
</div>
```

### 6. Profile Image

To add your profile image:

1. Add your image to the project folder
2. Replace the placeholder in the hero section:

```html
<!-- Replace lines 65-70 -->
<div class="profile-image">
    <img src="your-image.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover;">
</div>
```

### 7. Colors and Styling

To customize colors, edit the CSS variables in `styles.css`:

```css
/* Main colors - update these values */
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --text-color: #333;
    --background-color: #ffffff;
    --accent-color: #667eea;
}
```

## 📱 Mobile Responsiveness

The website is fully responsive and includes:

- Mobile-first design approach
- Hamburger menu for mobile navigation
- Optimized layouts for different screen sizes
- Touch-friendly interactions

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🚀 Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. Get a custom domain or use the provided Netlify URL

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## 🔧 Advanced Customization

### Adding New Sections

To add a new section, follow this template:

```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">New Section</h2>
        <!-- Your content here -->
    </div>
</section>
```

### Custom Animations

Add custom CSS animations:

```css
@keyframes yourAnimation {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.your-element {
    animation: yourAnimation 0.6s ease-out;
}
```

### Form Integration

To connect the contact form to a backend service:

1. **EmailJS**: Easy email integration
2. **Netlify Forms**: Built-in form handling
3. **Custom Backend**: Connect to your own API

## 📞 Support

If you need help customizing your portfolio:

1. Check the comments in the code files
2. Review this README for common customizations
3. Modify the code to match your needs

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Credits

- Icons: [Font Awesome](https://fontawesome.com/)
- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Design inspiration from modern portfolio trends

---

**Happy coding! 🚀** 