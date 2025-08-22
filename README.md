# Professional Portfolio Website

A modern, responsive, and interactive portfolio website built with HTML, CSS, and JavaScript. Features a clean design with smooth animations and professional styling.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Animated skill progress bars
  - Typing animation for hero section
  - Hover effects and transitions
  - Mobile-friendly hamburger menu
- **Contact Form**: Functional contact form with validation
- **Download Resume**: Direct link to your resume PDF
- **Social Media Integration**: Links to your professional social profiles
- **Performance Optimized**: Fast loading with optimized animations

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
└── Minimalist White and Grey Professional Resume.pdf  # Your resume
```

## 🛠️ Setup Instructions

1. **Download/Clone** the files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content as described below
4. **Deploy** to your preferred hosting service

## ✏️ Customization Guide

### 1. Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<span class="name">Your Name</span>
<p class="hero-subtitle">Professional Developer & Designer</p>
<p class="hero-description">
    Creating innovative digital experiences with passion and precision. 
    Specialized in modern web development and user-centered design.
</p>
```

#### About Section
```html
<p>
    I am a passionate and dedicated professional with expertise in modern web technologies. 
    My journey in software development has been driven by a desire to create meaningful 
    digital experiences that solve real-world problems.
</p>
```

#### Statistics
```html
<div class="stat">
    <span class="stat-number">3+</span>
    <span class="stat-label">Years Experience</span>
</div>
```

### 2. Skills Section

Update your skills and proficiency levels in the skills section:

```html
<div class="skill-item">
    <span class="skill-name">HTML5</span>
    <div class="skill-bar">
        <div class="skill-progress" data-percent="95"></div>
    </div>
</div>
```

**Available skill categories:**
- Frontend Development
- Backend Development
- Tools & Technologies

### 3. Projects Section

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description goes here...</p>
        <div class="project-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">Node.js</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live Demo</a>
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
        </div>
    </div>
</div>
```

### 4. Contact Information

Update your contact details:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### 5. Social Media Links

Update your social media profiles:

```html
<div class="social-links">
    <a href="https://linkedin.com/in/yourprofile" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="https://github.com/yourusername" class="social-link"><i class="fab fa-github"></i></a>
    <a href="https://twitter.com/yourhandle" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="https://instagram.com/yourprofile" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

### 6. Resume File

Replace `Minimalist White and Grey Professional Resume.pdf` with your actual resume file. Make sure to update the link in the hero section:

```html
<a href="Your-Resume-File.pdf" class="btn btn-secondary" target="_blank">
    <i class="fas fa-download"></i> Download Resume
</a>
```

## 🎨 Styling Customization

### Colors
The main color scheme can be customized in `styles.css`:

```css
/* Primary Blue */
--primary-color: #2563eb;

/* Gradient Colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Fonts
The website uses Inter font family. You can change it by updating the Google Fonts link in `index.html` and the font-family in `styles.css`.

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🚀 Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. You'll get a custom URL

### Vercel
1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Deploy automatically on every push

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them back!

## 📞 Support

If you need help customizing your portfolio or have questions, feel free to reach out!

---

**Happy coding! 🎉**
