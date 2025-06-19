# Smit Patel - Personal Portfolio

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a clean design with smooth animations and interactive elements.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design using Tailwind CSS
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Interactive Elements**: Hover effects, scroll animations, and form validation
- **Mobile Menu**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Navigation with smooth scroll to sections
- **Back to Top**: Floating back-to-top button

## 📁 File Structure

```
my-portfolio/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Sections

1. **Home**: Hero section with your name, intro, and call-to-action buttons
2. **About**: Personal information, experience stats, and what you do
3. **Projects**: Three featured projects with descriptions and tech stacks
4. **Skills**: Technical skills organized by categories
5. **Contact**: Contact information and contact form

## 🛠️ Customization

### Personal Information
Edit the following in `index.html`:

- **Name**: Change "Smit Patel" to your name
- **Intro**: Update the description in the home section
- **About**: Modify the about section content
- **Contact**: Update email, GitHub, and LinkedIn links

### Projects
Replace the dummy projects in the projects section with your actual projects:

```html
<div class="project-card">
    <div class="bg-gradient-to-br from-purple-400 to-pink-600 h-48 rounded-t-xl flex items-center justify-center">
        <i class="fas fa-robot text-6xl text-white"></i>
    </div>
    <div class="p-6 bg-white rounded-b-xl">
        <h3 class="text-xl font-bold mb-2">Your Project Title</h3>
        <p class="text-gray-600 mb-4">Your project description</p>
        <div class="flex flex-wrap gap-2 mb-4">
            <span class="tech-badge">Technology 1</span>
            <span class="tech-badge">Technology 2</span>
        </div>
        <div class="flex space-x-3">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Demo
            </a>
        </div>
    </div>
</div>
```

### Skills
Update the skills section with your actual skills. You can add more categories or modify existing ones:

```html
<div class="skill-item">
    <i class="fab fa-python text-4xl text-blue-600 mb-2"></i>
    <span>Python</span>
</div>
```

### Colors and Styling
The portfolio uses a blue color scheme. To change colors, edit the CSS variables in `styles.css`:

- Primary blue: `#2563eb`
- Secondary blue: `#1d4ed8`
- Accent colors: Various gradient combinations

## 🚀 Getting Started

1. **Download/Clone** the files to your local machine
2. **Customize** the content as described above
3. **Open** `index.html` in your web browser
4. **Deploy** to your preferred hosting service

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📧 Contact Form

The contact form includes:
- Form validation
- Success/error notifications
- Responsive design

Note: The form currently shows a success message but doesn't actually send emails. To make it functional, you'll need to integrate with a backend service or email service like:
- Formspree
- Netlify Forms
- EmailJS
- Custom backend

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with animations
- **JavaScript**: Interactive functionality
- **Tailwind CSS**: Utility-first CSS framework
- **Font Awesome**: Icons
- **Google Fonts**: Typography

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

## 📞 Support

If you have any questions or need help customizing the portfolio, feel free to reach out!

---

**Happy coding! 🎉** 