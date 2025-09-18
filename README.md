# Ajay Raj Singh - Data Engineer Portfolio

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://ajayrajsingh2003.github.io/ajay-portfolio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Professional portfolio website showcasing my experience as a Data Engineer with 6+ years of experience in ETL pipelines, cloud solutions, and data analytics.

## 🚀 Live Demo

**Visit:** [https://ajayrajsingh2003.github.io/ajay-portfolio/](https://ajayrajsingh2003.github.io/ajay-portfolio/)

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [How to Run Locally](#how-to-run-locally)
- [Deployment](#deployment)
- [Customization](#customization)
- [Contact](#contact)

## 📖 About

This portfolio website features an Instagram-inspired design showcasing my professional journey, technical projects, and achievements in the field of data engineering. The site dynamically loads content from JSON files, making it easy to update and maintain.

## ✨ Features

- **Responsive Instagram-style Design** - Modern, visually appealing interface
- **Dynamic Content Loading** - Projects, experience, and skills loaded from JSON files
- **Interactive Project Showcase** - Detailed project cards with GitHub links
- **Modal Popups** - Detailed information for experience, skills, education, and awards
- **Smooth Animations** - Scroll-triggered animations and hover effects
- **Mobile Responsive** - Optimized for all device sizes
- **Fast Loading** - Optimized performance with minimal dependencies

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Icons:** Font Awesome 6.0
- **Design:** Custom CSS with gradient themes
- **Hosting:** GitHub Pages
- **Version Control:** Git

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── README.md              # Project documentation
├── css/
│   └── style.css          # All CSS styles
├── js/
│   └── main.js           # JavaScript logic
├── assets/
│   ├── images/
│   │   └── favicon.ico   # Site favicon
│   └── resume/
│       └── AjayRajSingh_Resume.pdf  # Resume PDF
└── data/
    ├── projects.json     # Project data
    ├── experience.json   # Work experience data
    └── skills.json       # Technical skills data
```

## 💻 Installation & Setup

### Prerequisites

- Git installed on your machine
- A text editor (VS Code, Sublime Text, etc.)
- A modern web browser

### Clone the Repository

```bash
# Clone the repository
git clone https://github.com/ajayrajsingh2003/portfolio.git

# Navigate to project directory
cd portfolio
```

## 🏃 How to Run Locally

### Method 1: Using Python (Recommended)

```bash
# For Python 3.x
python -m http.server 8000

# For Python 2.x
python -m SimpleHTTPServer 8000
```

Then open your browser and visit: `http://localhost:8000`

### Method 2: Using Node.js (http-server)

```bash
# Install http-server globally (one-time setup)
npm install -g http-server

# Run the server
http-server

# Or specify port
http-server -p 8000
```

Then visit: `http://localhost:8000`

### Method 3: Using VS Code Live Server

1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Method 4: Direct File Opening

Simply double-click `index.html` to open it in your default browser.

**Note:** Some features (like JSON loading) may not work properly when opening directly from file system due to CORS restrictions. Use one of the server methods above for full functionality.

## 🚀 Deployment

### Deploy to GitHub Pages

1. **Create a GitHub Repository**
   ```bash
   # Initialize git (if not already done)
   git init
   
   # Add all files
   git add .
   
   # Commit changes
   git commit -m "Initial portfolio commit"
   ```

2. **Push to GitHub**
   ```bash
   # Create a new repository on GitHub named 'portfolio'
   
   # Add remote origin
   git remote add origin https://github.com/ajayrajsingh2003/portfolio.git
   
   # Push to main branch
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose branch: `main`
   - Choose folder: `/ (root)`
   - Click "Save"

4. **Access Your Site**
   - Your site will be live at: `https://ajayrajsingh2003.github.io/portfolio`
   - May take 1-2 minutes for initial deployment

## 🎨 Customization

### Update Projects

Edit `data/projects.json`:

```json
{
    "id": 7,
    "title": "Your New Project",
    "description": "Brief description",
    "icon": "code",
    "tags": ["Tag1", "Tag2"],
    "github": "https://github.com/username/repo",
    "demo": "https://demo-link.com"
}
```

### Update Experience

Edit `data/experience.json`:

```json
{
    "company": "Company Name",
    "logo": "CN",
    "position": "Job Title",
    "duration": "Month Year – Month Year",
    "location": "City, State",
    "achievements": [
        "Achievement 1",
        "Achievement 2"
    ]
}
```

### Update Skills

Edit `data/skills.json`:

```json
{
    "category": "Category Name",
    "icon": "icon-name",
    "skills": ["Skill1", "Skill2", "Skill3"]
}
```

### Change Colors

Edit `css/style.css` and modify these gradient values:

```css
/* Main gradient background */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Profile picture gradient */
background: linear-gradient(45deg, #667eea 0%, #764ba2 100%);
```

## 📧 Contact

- **Email:** ajayrajsingh2003@gmail.com
- **LinkedIn:** [connectwithajayrajsingh](https://linkedin.com/in/connectwithajayrajsingh)
- **GitHub:** [ajayrajsingh2003](https://github.com/ajayrajsingh2003)
- **Phone:** +1 (732) 209-0281
- **Location:** Jersey City, NJ

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- GitHub Pages for hosting
- Inspiration from Instagram's UI design

## 🔄 Updates

To update your portfolio after deployment:

```bash
# Make changes to your files

# Stage changes
git add .

# Commit changes
git commit -m "Update portfolio content"

# Push to GitHub
git push origin main

# GitHub Pages will automatically redeploy (takes 1-2 minutes)
```

---

**Built with ❤️ by Ajay Raj Singh**