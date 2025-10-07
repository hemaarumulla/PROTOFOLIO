# 🚀 Hema Arumulla - Portfolio Website

A stunning, modern portfolio website built with cutting-edge web technologies and design trends.

## ✨ Features

### 🎨 **Modern Design**
- **Glassmorphism Effects** - Beautiful frosted glass elements
- **Gradient Backgrounds** - Dynamic color schemes
- **Premium Typography** - Space Grotesk & JetBrains Mono fonts
- **Responsive Design** - Perfect on all devices

### 🎭 **Advanced Animations**
- **Particle System** - Interactive background particles
- **Scroll Animations** - Smooth reveal effects
- **3D Hover Effects** - Immersive interactions
- **Typing Animation** - Dynamic text effects
- **Parallax Scrolling** - Depth and movement

### 🛠 **Interactive Elements**
- **Code Window** - Live code preview in hero section
- **Floating Icons** - Animated technology badges
- **Contact Form** - Working form with validation
- **Theme Toggle** - Dark/Light mode support
- **Mobile Navigation** - Smooth hamburger menu

### 📱 **Responsive & Accessible**
- **Mobile-First Design** - Optimized for all screen sizes
- **Fast Loading** - Optimized performance
- **SEO Ready** - Proper meta tags and structure
- **Cross-Browser Compatible** - Works everywhere

## 🎯 Sections

1. **Hero Section** - Eye-catching introduction with animated code
2. **About** - Personal story and statistics
3. **Skills** - Technology showcase with icons
4. **Projects** - Portfolio with live demos
5. **Experience** - Professional timeline
6. **Contact** - Working contact form

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS/JS

### Installation
1. Clone or download the files
2. Open `index.html` in your browser
3. Customize the content to match your profile

### File Structure
```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Complete CSS styling
├── script.js           # Interactive JavaScript
├── README.md           # This file
└── Hema__Resume.docx.pdf # Your resume (reference)
```

## 🎨 Customization Guide

### 1. **Personal Information**
Update the following in `index.html`:
- Name and title in hero section
- About section content
- Contact information
- Social media links

### 2. **Skills & Technologies**
Modify the skills section in `index.html`:
```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React</span>
</div>
```

### 3. **Projects**
Update project cards with your actual projects:
```html
<div class="project-card">
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-demo" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

### 4. **Experience**
Update the timeline with your work experience:
```html
<div class="timeline-item">
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <span class="timeline-date">2023 - Present</span>
        <p>Job description...</p>
    </div>
</div>
```

### 5. **Colors & Styling**
Modify CSS variables in `styles.css`:
```css
:root {
    --primary: #6366f1;      /* Main brand color */
    --secondary: #ec4899;    /* Accent color */
    --accent: #06b6d4;       /* Highlight color */
}
```

### 6. **Particle Effects**
Customize particle system in `script.js`:
```javascript
// Adjust particle count and behavior
const particleCount = Math.floor((this.canvas.width * this.canvas.height) / 10000);
```

## 🌐 Deployment Options

### **GitHub Pages** (Free)
1. Create a GitHub repository
2. Upload your files
3. Enable GitHub Pages in settings
4. Your site will be live at `username.github.io/repository-name`

### **Netlify** (Free)
1. Drag and drop your folder to Netlify
2. Your site will be live instantly
3. Custom domain support available

### **Vercel** (Free)
1. Connect your GitHub repository
2. Deploy with one click
3. Automatic deployments on updates

### **Traditional Hosting**
Upload files to any web hosting service via FTP.

## 🎨 Design Features Explained

### **Glassmorphism**
Modern design trend using frosted glass effects:
```css
.glass {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.2);
}
```

### **Particle System**
Interactive background with connected particles that respond to mouse movement.

### **3D Effects**
CSS transforms create depth and perspective:
```css
transform: perspective(1000px) rotateY(-5deg) rotateX(5deg);
```

### **Smooth Animations**
CSS transitions and keyframes for fluid motion:
```css
transition: all 0.3s ease;
animation: slideInLeft 0.8s ease-out;
```

## 🔧 Technical Details

### **Performance Optimizations**
- Throttled scroll events
- Debounced resize handlers
- Optimized animations
- Efficient particle system

### **Browser Support**
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### **Mobile Optimization**
- Touch-friendly interactions
- Responsive breakpoints
- Optimized animations for mobile

## 📞 Support

If you need help customizing your portfolio:

1. **Check the code comments** - Detailed explanations throughout
2. **Modify one section at a time** - Start with content, then styling
3. **Test on different devices** - Ensure responsiveness
4. **Validate your HTML/CSS** - Use online validators

## 🎉 What Makes This Special

- **Professional Quality** - Enterprise-level code structure
- **Modern Trends** - Latest design and development practices
- **Performance Focused** - Fast loading and smooth animations
- **Fully Customizable** - Easy to modify and extend
- **Production Ready** - Can be deployed immediately

## 📝 License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Built with ❤️ for developers who want to showcase their skills in style!**

*Last updated: 2024*
