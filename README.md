# Prakshep Goswami - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my skills, experience, projects, and achievements as a Software Developer and Research Scholar.

![Portfolio Preview]([https://via.placeholder.com/800x400/ea580c/ffffff?text=Portfolio+Preview](https://prakshep-goswami.github.io/Prakshep-Portfolio/))

## 🌟 Features

### ✨ Modern Design
- **Responsive Design**: Fully responsive across all devices and screen sizes
- **Dark/Light Theme**: Toggle between dark and light themes with smooth transitions
- **Animated Background**: Dynamic floating shapes and particle effects
- **Smooth Animations**: Fade-in animations and smooth scrolling navigation
- **Professional UI**: Clean, modern interface with gradient accents

### 📧 Contact Integration
- **EmailJS Integration**: Functional contact form that sends emails directly
- **Form Validation**: Client-side validation for required fields
- **Success/Error Messages**: Real-time feedback for form submissions
- **WhatsApp Integration**: Optional WhatsApp contact field

### 🎯 Interactive Elements
- **Progress Bars**: Animated skill progress indicators
- **Hover Effects**: Interactive cards and buttons
- **Scroll Progress**: Visual progress bar showing page scroll position
- **Smooth Navigation**: One-click navigation to different sections

### 📱 Sections Included
- **Hero Section**: Introduction with call-to-action buttons
- **About**: Personal introduction and background
- **Skills**: Technical skills with animated progress bars
- **Experience**: Professional timeline with detailed descriptions
- **Education**: Academic background and achievements
- **Projects**: Featured projects with technology stacks
- **Publications**: Research papers and publications
- **Achievements**: Certifications and accomplishments
- **Social Links**: Centralized social media hub
- **Contact**: Functional contact form

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with custom properties and animations
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation
- **Font Awesome**: Professional icons and symbols

### External Services
- **EmailJS**: Email service for contact form functionality
- **Google Fonts**: Typography (Inter font family)

### Features & APIs
- **Intersection Observer API**: Scroll-triggered animations
- **Local Storage API**: Theme preference persistence
- **CSS Custom Properties**: Dynamic theming system

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- EmailJS account (for contact form functionality)

### Installation

1. **Clone the repository**
   \`\`\`bash
   git clone https://github.com/Prakshep-goswami/portfolio-website.git
   cd portfolio-website
   \`\`\`

2. **Open the project**
   \`\`\`bash
   # Simply open index.html in your browser
   open index.html
   # OR use a local server
   python -m http.server 8000
   # OR use Live Server extension in VS Code
   \`\`\`

3. **Configure EmailJS (Required for contact form)**
   - Sign up at [EmailJS](https://www.emailjs.com/)
   - Create an email service (Gmail, Outlook, etc.)
   - Create an email template
   - Replace the following in `index.html`:
     \`\`\`javascript
     emailjs.init("YOUR_PUBLIC_KEY"); // Replace with your public key
     emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', formData) // Replace IDs
     \`\`\`

## ⚙️ EmailJS Configuration

### Step 1: Create EmailJS Account
1. Go to [EmailJS](https://www.emailjs.com/) and sign up
2. Verify your email address

### Step 2: Add Email Service
1. Go to Email Services and click "Add New Service"
2. Choose your email provider (Gmail recommended)
3. Follow the setup instructions
4. Note your **Service ID**

### Step 3: Create Email Template
Create a template with these variables:
\`\`\`
From: {{from_name}} <{{from_email}}>
Subject: {{subject}}

Name: {{from_name}}
Email: {{from_email}}
WhatsApp: {{whatsapp_number}}
Subject: {{subject}}

Message:
{{message}}
\`\`\`

### Step 4: Update Configuration
Replace these values in the JavaScript section:
\`\`\`javascript
// Replace with your actual values
emailjs.init("YOUR_PUBLIC_KEY");
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', formData)
\`\`\`

## 📁 Project Structure

\`\`\`
portfolio-website/
│
├── index.html              # Main HTML file
├── README.md              # Project documentation
├── LICENSE                # MIT License
│
└── assets/                # (Optional: for additional assets)
    ├── images/           # Image files
    ├── icons/            # Custom icons
    └── documents/        # Resume, certificates, etc.
\`\`\`

## 🎨 Customization

### Personal Information
Update the following sections in `index.html`:

1. **Personal Details**: Name, title, description
2. **Contact Information**: Email, phone, location
3. **Social Links**: LinkedIn, GitHub, other profiles
4. **Skills**: Add/remove skills and adjust percentages
5. **Experience**: Update work history and descriptions
6. **Projects**: Replace with your own projects
7. **Achievements**: Add your accomplishments

### Styling
- **Colors**: Modify CSS custom properties in `:root`
- **Fonts**: Change font family in CSS
- **Animations**: Adjust animation durations and effects
- **Layout**: Modify grid layouts and spacing

### Theme Colors
\`\`\`css
:root {
    --primary-color: #ea580c;      /* Orange primary */
    --secondary-color: #f97316;    /* Orange secondary */
    --accent-color: #fb923c;       /* Orange accent */
    /* Modify these to change the color scheme */
}
\`\`\`

## 📱 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Performance Features

- **Optimized Animations**: Hardware-accelerated CSS animations
- **Lazy Loading**: Intersection Observer for performance
- **Minimal Dependencies**: No heavy frameworks
- **Compressed Assets**: Optimized images and icons
- **Efficient JavaScript**: Event delegation and optimized DOM manipulation

## 📈 SEO Features

- **Semantic HTML**: Proper heading hierarchy and semantic elements
- **Meta Tags**: Optimized meta descriptions and titles
- **Structured Data**: Schema markup for better search visibility
- **Accessibility**: ARIA labels and keyboard navigation support

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas for Contribution
- 🐛 Bug fixes
- ✨ New features
- 📱 Mobile responsiveness improvements
- ♿ Accessibility enhancements
- 🎨 UI/UX improvements
- 📝 Documentation updates

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Prakshep Goswami**
- 🎓 MCA Graduate | Research Scholar | Software Developer
- 🏢 Currently working at Techritzy Pvt Ltd
- 🎯 Research focus: Learning Analytics & Data Mining
- 📧 Email: Prakshepgoswami@gmail.com
- 💼 LinkedIn: [prakshep9876](https://www.linkedin.com/in/prakshep9876/)
- 🐱 GitHub: [Prakshep-goswami](https://github.com/Prakshep-goswami)
- 🔗 All Links: [linktr.ee/prakshep](https://linktr.ee/prakshep)

## 🏆 Achievements Highlighted

- ✅ UGC NET 2024 Qualified
- 📚 Published research papers in Springer conferences
- 💻 400+ coding problems solved across platforms
- 🏆 Top 10 in Prayatnn Hackathon
- 📜 Financial Literacy Certification (NISM)
- 🎓 Academic Excellence: 8.40 CGPA (MCA), 8.59 CGPA (BCA)

## 🚀 Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to repository Settings
3. Scroll to Pages section
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty for static site)
3. Set publish directory: `/` (root)
4. Deploy!

### Vercel
1. Import your GitHub repository to Vercel
2. Configure build settings (auto-detected for static sites)
3. Deploy with one click

## 📞 Support

If you have any questions or need help with setup, feel free to:
- 📧 Email me at Prakshepgoswami@gmail.com
- 💬 Connect on LinkedIn
- 🐛 Open an issue on GitHub

## ⭐ Show Your Support

If you found this project helpful, please consider:
- ⭐ Starring the repository
- 🍴 Forking for your own use
- 📢 Sharing with others
- 🐛 Reporting issues
- 💡 Suggesting improvements

---

**Made with ❤️ by Prakshep Goswami**

*Last updated: July 2025*
