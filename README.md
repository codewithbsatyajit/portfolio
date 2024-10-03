# Responsive Web Portfolio

This is a fully responsive web portfolio designed to showcase personal details, experiences, projects, and contact information. It uses HTML, CSS (including media queries for responsiveness), and JavaScript for interactive features like a hamburger menu.

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Technologies](#technologies)
- [File Structure](#file-structure)
- [Usage](#usage)
- [Media Queries](#media-queries)
- [Contact](#contact)

## Demo
You can check out the live demo of the website [here](#).

## Features
- **Responsive Design:** Adapts to different screen sizes, providing an optimal experience across devices.
- **Smooth Scrolling:** HTML and CSS features enable smooth scrolling between sections.
- **Hamburger Menu:** A mobile-friendly navigation menu implemented with JavaScript.
- **Interactive Hover Effects:** Links and buttons feature hover effects for better UX.
- **About, Projects, Experience, and Contact sections:** These sections provide a detailed look into personal details, skills, work, and ways to get in touch.
- **Social Media Links:** Icons with links to various social platforms.

## Technologies
- **HTML5**: Markup structure for the web portfolio.
- **CSS3**: Styling, including media queries for responsiveness and hover effects.
- **JavaScript**: Interactive features like the hamburger menu for mobile navigation.

## File Structure
```
📦 Responsive Web Portfolio
│
├── index.html            # Main HTML file for the web portfolio
├── style.css             # Main CSS file for styling
├── mediaqueries.css      # CSS file for handling responsiveness with media queries
└── script.js             # JavaScript file for interactive elements
```

### HTML (`index.html`)
The main structure of the portfolio, featuring sections like:
- **Profile**
- **About**
- **Experience**
- **Projects**
- **Contact**

### CSS (`style.css`)
Styles the website with consistent colors, typography, and layout. It also includes:
- **Navbar**
- **Buttons**
- **Sections (Profile, About, Experience, Projects, Contact)**
- **Social Media Icons**

### Media Queries (`mediaqueries.css`)
The media queries ensure the portfolio is responsive and adjusts perfectly on various screen sizes (large screens, tablets, mobile devices). It modifies:
- **Nav Links**
- **Profile Picture**
- **Section Heights**
- **Typography Adjustments**

### JavaScript (`script.js`)
Handles the functionality of the hamburger menu for mobile screens, enabling users to open and close the menu.

```javascript
function toggleMenu() {
  const menu = document.querySelector(".menu-links");
  const icon = document.querySelector(".hamburger-icon");
  menu.classList.toggle("open");
  icon.classList.toggle("open");
}
```

## Usage
1. Clone the repository:
   ```
   git clone https://github.com/codewithbsatyajit/responsive-web-portfolio.git
   ```
2. Open `index.html` in your browser to view the portfolio.

## Media Queries
The portfolio has been optimized for the following screen sizes:
- **Desktops (1400px and above)**
- **Tablets (1200px and below)**
- **Mobile Devices (600px and below)**

## Contact
For any inquiries or feedback, feel free to reach out:
- **Email:** [mail.bsatyajit@gmail.com](mailto:mail.bsatyajit@gmail.com)
- **LinkedIn:** [Satyajit Behera](https://www.linkedin.com/in/satyajit-behera-79a993330/)
- **GitHub:** [codewithbsatyajit](https://github.com/codewithbsatyajit)

---

Thank you for visiting my portfolio!
```

This `README.md` provides an overview of your project and guides users on how to use and navigate the code effectively. Let me know if you need any changes!
