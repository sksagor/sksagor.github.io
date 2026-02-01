# SKSAM - Python Developer & AI Engineer Portfolio

A modern, professional portfolio website showcasing Python development, AI/ML projects, and SEO expertise. Built with clean HTML/CSS/JavaScript for GitHub Pages deployment.

## 🌟 Features

- **Modern Design**: Clean, cyberpunk-inspired aesthetic with smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Fast Loading**: Optimized HTML/CSS with no heavy frameworks
- **SEO Optimized**: Semantic HTML and meta tags for better search visibility
- **GitHub Pages Ready**: Deploy in minutes with zero configuration

## 🚀 Live Demo

Visit: `https://yourusername.github.io`

## 📂 Project Structure

```
portfolio/
├── index.html                          # Homepage with project showcase
├── resume.html                         # Professional resume/CV page
├── contact.html                        # Contact form and information
├── project-sentiment-analysis.html     # AI Sentiment Analysis project
├── project-seo-tracker.html           # SEO Rank Tracker project
├── project-crypto-prediction.html     # (Create this)
├── project-resume-analyzer.html       # (Create this)
├── project-sales-forecasting.html     # (Create this)
├── project-job-scraper.html           # (Create this)
└── README.md                          # This file
```

## 🛠️ Setup Instructions

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub Repository**
   ```bash
   # Create a new repository named: yourusername.github.io
   # Make it public
   ```

2. **Clone and Add Files**
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   
   # Copy all HTML files to this directory
   ```

3. **Customize Your Content**
   - Replace `SKSAM` with your name throughout all files
   - Update email addresses, GitHub links, and social media
   - Add your actual project details and descriptions
   - Replace placeholder links with your real URLs

4. **Deploy to GitHub Pages**
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git push origin main
   ```

5. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Save and wait 2-3 minutes

6. **Visit Your Site**
   - Your portfolio will be live at: `https://yourusername.github.io`

### Option 2: Local Development

```bash
# Simply open index.html in your browser
open index.html

# Or use Python's built-in server
python -m http.server 8000
# Visit: http://localhost:8000
```

## ✏️ Customization Guide

### 1. Update Personal Information

**In ALL HTML files**, replace:
- `SKSAM` → Your name
- `your.email@example.com` → Your email
- `yourusername` → Your GitHub username
- `yourprofile` → Your LinkedIn profile
- Social media links

### 2. Add Your Resume PDF

1. Create a professional PDF resume
2. Add it to the repository: `resume.pdf`
3. Update the download link in `resume.html`:
   ```html
   <a href="resume.pdf" class="download-btn" download>
       📄 Download PDF Resume
   </a>
   ```

### 3. Customize Colors (Optional)

Edit CSS variables in each HTML file's `<style>` section:

```css
:root {
    --primary: #00ff88;        /* Main accent color */
    --accent: #667eea;         /* Secondary accent */
    --bg-dark: #0a0e1a;       /* Background */
    --bg-card: #141824;       /* Card background */
}
```

### 4. Add More Projects

Create new project pages following the template of existing project files:
1. Copy `project-sentiment-analysis.html`
2. Rename to your project name
3. Update all content, features, and tech stack
4. Add link from `index.html`

### 5. Connect Contact Form

The contact form is currently a demo. To make it functional:

**Option A: FormSpree (Free)**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

**Option B: Netlify Forms (Free)**
```html
<form name="contact" method="POST" data-netlify="true">
```

**Option C: Your Own Backend**
- Build a FastAPI endpoint
- Deploy to Heroku/Railway
- Update form action URL

## 📊 Project Highlights

### Featured Projects Included:

1. **AI-Powered Sentiment Analysis Platform** 🏆
   - FastAPI + HuggingFace + React
   - Real-time NLP processing
   - 92% accuracy, 50k+ texts/hour

2. **SEO Rank Tracker & Analyzer** 🔥
   - FastAPI + SERP APIs + MongoDB
   - Automated keyword monitoring
   - Unique SEO + Programming combo

3. **Crypto Price Prediction System**
   - Machine Learning + Fintech
   - Live price tracking
   - ML-powered predictions

4. **AI Resume Analyzer & Job Matcher**
   - NLP + HR Tech
   - CV parsing and skills extraction
   - Intelligent job matching

5. **Business Sales Forecasting System**
   - Prophet + Time Series
   - Automated forecasting
   - PDF report generation

6. **Job Scraper & Market Analyzer**
   - Web Scraping + Data Engineering
   - Market intelligence
   - Skill demand analysis

## 🎨 Design Philosophy

- **Dark Theme**: Modern, eye-friendly cyberpunk aesthetic
- **Green Accents**: #00ff88 primary color for tech feel
- **Typography**: JetBrains Mono (code) + Syne (headings)
- **Animations**: Subtle, professional micro-interactions
- **Glassmorphism**: Modern blur effects and transparency

## 📱 Browser Support

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile browsers

## 🔧 Tech Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript
- **Fonts**: Google Fonts (JetBrains Mono, Syne)
- **Hosting**: GitHub Pages (Free)
- **Version Control**: Git

## 📈 SEO Optimization

Built-in SEO features:
- Semantic HTML structure
- Meta descriptions (add these!)
- Fast loading times
- Mobile responsive
- Clean URLs

**To improve SEO, add to each HTML file:**

```html
<head>
    <!-- Add these meta tags -->
    <meta name="description" content="Your description here">
    <meta name="keywords" content="Python, AI, Machine Learning, FastAPI">
    <meta name="author" content="Your Name">
    
    <!-- Open Graph for social sharing -->
    <meta property="og:title" content="Your Name - Python Developer">
    <meta property="og:description" content="Your description">
    <meta property="og:image" content="https://yourusername.github.io/preview.png">
    <meta property="og:url" content="https://yourusername.github.io">
</head>
```

## 🚀 Performance Tips

1. **Optimize Images**: Use WebP format, compress all images
2. **Add Favicon**: Create `favicon.ico` and add to root
3. **Enable Caching**: GitHub Pages handles this automatically
4. **Minimize Files**: Already optimized, but you can minify further

## 📝 TODO / Future Enhancements

- [ ] Add a blog section
- [ ] Integrate with Dev.to or Medium API
- [ ] Add project screenshots/demos
- [ ] Create video walkthroughs
- [ ] Add testimonials section
- [ ] Implement dark/light theme toggle
- [ ] Add Google Analytics

## 🤝 Contributing

This is a personal portfolio, but feel free to:
- Fork for your own use
- Suggest improvements via issues
- Share your customized version

## 📄 License

MIT License - Free to use and modify for your own portfolio

## 💬 Questions?

Feel free to reach out:
- Email: your.email@example.com
- LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)
- GitHub: [@yourusername](https://github.com/yourusername)

---

**Built with ❤️ by SKSAM**

*Python Developer | AI Engineer | SEO Expert*
