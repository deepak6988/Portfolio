# Deepak Kumar - Portfolio Website

Welcome to my professional portfolio website! This is a fully responsive, modern portfolio showcasing my skills, experience, projects, and achievements as a Full-Stack Developer.

## 🌐 Live Demo
Visit my portfolio: [Portfolio Website](https://portfolio-smoky-phi-69.vercel.app/)

## 📋 Table of Contents
- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Sections](#sections)
- [Installation & Setup](#installation--setup)
- [Projects Included](#projects-included)
- [Contact Information](#contact-information)

## 🎯 About

This portfolio website is a comprehensive display of my professional journey as a **Software Developer | Full-Stack Developer | AI Enthusiast**. It highlights my technical skills, professional experience, educational background, completed projects, and industry certifications.

### Key Highlights:
- **Full-Stack Development Experience** with React.js, Node.js, Express.js, MongoDB, and MySQL
- **Data Validation & Integrity** expertise in geospatial data processing
- **Quality Assurance** leadership and optimization workflows
- **3 Featured Projects** with detailed case studies
- **Responsive Design** for seamless viewing across all devices

## ✨ Features

✅ **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
✅ **Modern UI/UX** - Clean, professional, and visually appealing interface
✅ **Smooth Animations** - AOS (Animate On Scroll) for engaging transitions
✅ **Interactive Components** - Swiper carousels, hover effects, and smooth navigation
✅ **Multiple Project Pages** - Dedicated detail pages for each project
✅ **Skills Section** - Comprehensive display of technical competencies
✅ **Resume/Experience** - Professional background and achievements
✅ **Certificates Section** - Industry certifications and recognitions
✅ **Contact Section** - Multiple ways to get in touch
✅ **Dark Navigation Header** - Professional sidebar navigation

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **JavaScript** - Interactive functionality and DOM manipulation
- **Bootstrap 5.3.3** - Responsive grid layout and components

### Libraries & Frameworks
- **Swiper.js** - Touch-enabled carousel slider
- **AOS (Animate On Scroll)** - Scroll animation library
- **Bootstrap Icons** - Comprehensive icon library
- **Glightbox** - Lightbox image gallery
- **Isotope** - Filtering and sorting layouts
- **Typed.js** - Typing animation effect
- **Waypoints** - Scroll trigger detection

### Development
- **Git** - Version control
- **GitHub** - Repository hosting

## 📁 Project Structure

```
Portfolio/
├── index.html                          # Main portfolio page
├── portfolio-details.html              # Read Lab project details
├── portfolio-details-noteshub.html     # NotesHub project details
├── portfolio-details-chatapp.html      # Chat App project details
├── starter-page.html                   # Starter template
├── service-details.html                # Service details page
├── assets/
│   ├── css/
│   │   └── main.css                   # Main stylesheet
│   ├── js/
│   │   └── main.js                    # Main JavaScript
│   ├── img/
│   │   ├── my-profile-img.jpg         # Profile image
│   │   ├── hero-bg.jpg                # Hero background
│   │   └── portfolio/                 # Project images
│   ├── scss/                          # SCSS source files
│   └── vendor/                        # Third-party libraries
│       ├── bootstrap/
│       ├── swiper/
│       ├── aos/
│       ├── glightbox/
│       └── other libraries
├── forms/
│   └── contact.php                    # Contact form handler
└── README.md                          # This file
```

## 📄 Sections

### 1. **Hero Section**
- Dynamic introduction with profile image background
- Professional headline and tagline
- Text-shadow effects for enhanced readability

### 2. **About Section**
- Personal summary and professional overview
- Key information (contact details, education, etc.)
- Black-bordered profile image
- Comprehensive background

### 3. **Resume Section**
Includes three subsections:
- **Education** - Academic qualifications and achievements
- **Achievements** - Competitive accomplishments and milestones
- **Professional Experience** - Work history with detailed responsibilities

### 4. **Skills Section**
- Categorized technical skills
- Interactive skill cards with hover effects
- Detailed competencies with emphasis on key technologies

### 5. **Portfolio (Projects) Section**
Three featured projects with:
- Project showcase cards with GitHub and Details buttons
- Responsive image galleries
- Dedicated project detail pages
- Comprehensive project descriptions

#### Featured Projects:
1. **Read Lab** - Smart Library Seat Reservation System
   - Tech: React.js, Node.js, Express.js, MongoDB, JWT, Stripe
   
2. **NotesHub** - Academic Resource Sharing Platform
   - Tech: HTML, CSS, JavaScript, Bootstrap, PHP, MySQL
   
3. **Real-Time Chat Application** - Messaging Platform
   - Tech: HTML, CSS, JavaScript, PHP, MySQL

### 6. **Certificates Section**
- Display of professional certifications
- Certificate cards with hover animations
- Industry-recognized qualifications

### 7. **Contact Section**
Multiple contact options:
- LinkedIn profile link
- Email address
- Phone number
- Social media links
- Contact form integration

## 🚀 Installation & Setup

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime, etc.) - optional, for customization
- Git (for cloning the repository)

### Steps to Set Up Locally

1. **Clone the repository:**
```bash
git clone https://github.com/deepak6988/Portfolio.git
cd Portfolio
```

2. **Open in browser:**
```bash
# Simply open index.html in your web browser
# Or use a local server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

3. **Customize for your use:**
- Replace profile images with your own
- Update text content with your information
- Modify colors and styling in `assets/css/main.css`
- Update links and contact information

## 🎨 Navigation

**Header Navigation Menu:**
- Home - Hero section
- About - Personal overview
- Resume - Education and experience
- Skills - Technical competencies
- Projects - Featured work
- Certificates - Industry certifications
- Contact - Get in touch

**Mobile Navigation:**
- Responsive hamburger menu
- Touch-friendly navigation
- Slide-out sidebar

## 📱 Responsive Breakpoints

- **Desktop** (≥992px) - Full layout with sidebar
- **Tablet** (≥768px) - Adjusted grid and spacing
- **Mobile** (<768px) - Optimized single-column layout

## 📊 Key Features Explained

### Image Styling
- Profile image: Black border (5px) with rounded corners
- Hero background: Profile image with blur and saturation filters
- Responsive images with `img-fluid` class

### Color Scheme
- **Primary Brand Color:** #149ddd (Light Blue)
- **Deep Brand Color:** #0d6efd (Electric Blue)
- **Text Color:** #1f2a37 (Dark Slate)
- **Background:** #f5f7fb (Light Gray)
- **White Backgrounds:** rgba(255, 255, 255, 0.92)

### Animations
- **Scroll Animations:** AOS library for fade-up effects
- **Hover Effects:** Transform and shadow transitions
- **Carousel:** Auto-playing Swiper with pagination
- **Skills Display:** Animated skill cards

## 🔧 Customization Guide

### Change Profile Image
1. Replace `assets/img/my-profile-img.jpg` with your image
2. Update `portfolio-details*.html` files similarly

### Update Project Details
1. Edit individual project detail files
2. Update image URLs in carousel
3. Modify project descriptions and links

### Modify Colors
Edit `:root` CSS variables in `index.html`:
```css
:root {
  --brand: #149ddd;
  --brand-deep: #0d6efd;
  --ink: #1f2a37;
  --muted: #5f6f7f;
  --soft: #f4f8fb;
  --card-bg: #ffffff;
  --border: rgba(17, 24, 39, 0.08);
  --shadow: 0 18px 45px rgba(15, 23, 42, 0.10);
}
```

## 📚 Projects Included

### 1. Read Lab - Smart Library Seat Reservation System
**Status:** Completed (3 months)
- Full-stack web application
- Real-time seat availability
- Payment integration with Stripe
- JWT-based authentication

### 2. NotesHub - Academic Resource Sharing Platform
**Status:** Completed (2 months)
- Resource upload/download system
- Advanced search functionality
- User authentication
- Responsive design

### 3. Real-Time Chat Application
**Status:** Completed (1.5 months)
- One-to-one messaging
- User authentication
- Online status tracking
- Chat history persistence

## 📞 Contact Information

**Email:** deepakumar6988@gmail.com
**Phone:** +91 6200468014
**Location:** Hyderabad, Telangana

**Social Media:**
- [LinkedIn](https://www.linkedin.com/in/deepak5402)
- [GitHub](https://github.com/deepak6988)
- [Instagram](https://www.instagram.com/ig_deepak13)

## 📜 Professional Information

**Current Role:** Analyst @ Tata Consultancy Services (Nov 2024 - Present)

**Key Competencies:**
- Full-Stack Web Development
- Data Validation & Integrity
- Quality Assurance & Testing
- API Development & Integration
- Database Design (MongoDB, MySQL)
- Frontend & Backend Development
- Git & Version Control

**Education:**
- Bachelor of Science in Information Technology (2024)
  - Marwari College, Ranchi
  - CGPA: 8.6/10

## 🎓 Certifications

- Full Stack Web Development
- React.js Advanced
- JavaScript Certification

## 📈 Professional Achievements

- ⭐ Awarded **Best Performer of the Month** at TCS
- 💯 Solved 100+ DSA problems (LeetCode, GeeksforGeeks)
- 🏆 Data Validation & Integrity expertise
- 🚀 Led QA workflows for high-volume datasets

## 🔗 Resources

- [Bootstrap Documentation](https://getbootstrap.com/docs)
- [Swiper.js Documentation](https://swiperjs.com)
- [AOS Library](https://michalsnik.github.io/aos)
- [Bootstrap Icons](https://icons.getbootstrap.com)

## 📝 License

This portfolio website is open source and available for personal and educational use.

## 🙏 Acknowledgments

- **Bootstrap** - Responsive framework
- **Swiper.js** - Touch carousel library
- **AOS** - Scroll animation library
- **Bootstrap Icons** - Icon library
- **Glightbox** - Lightbox library

---

**Last Updated:** August 2026

For more information or inquiries, please visit my [LinkedIn Profile](https://www.linkedin.com/in/deepak5402) or [GitHub Profile](https://github.com/deepak6988).

**Happy Coding! 🚀**
