# Kaviyarasu Chandran - Portfolio

A modern, responsive portfolio website built with HTML, CSS, JavaScript, and Bootstrap.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Modern UI**: Clean and professional design with smooth animations
- **Contact Form**: Working EmailJS integration for contact functionality
- **Portfolio Gallery**: Filterable portfolio section with lightbox
- **Skills Section**: Animated progress bars for skills
- **Testimonials**: Client testimonials with masonry layout

## 📧 Email Functionality

The contact form uses EmailJS to send emails. The configuration is already set up:

- **Public Key**: `5IIevUEmDg6snwEJI`
- **Service ID**: `service_0p6dojp`
- **Template ID**: `template_00altxm`

### To test the email functionality:

1. Open `index.html` in your browser
2. Navigate to the Contact section
3. Fill out the form and submit
4. Check your email inbox for the message

## 🛠️ How to Run

### Option 1: Simple File Opening
- Double-click `index.html` to open in your browser

### Option 2: Local Server (Recommended)
```bash
# Navigate to the project folder
cd myportfolio-main

# Start a local server
python -m http.server 8000

# Open in browser
# Go to: http://localhost:8000
```

## 📁 File Structure

```
myportfolio-main/
├── index.html              # Main portfolio page
├── assets/
│   ├── css/
│   │   └── main.css        # Main stylesheet
│   ├── js/
│   │   └── main.js         # Main JavaScript file
│   ├── img/                # Images and photos
│   └── vendor/             # Third-party libraries
└── README.md               # This file
```

## 🎨 Customization

### Personal Information
Update the following sections in `index.html`:
- Hero section: Name, title, description
- About section: Personal details, contact info
- Resume section: Work experience, education
- Contact section: Contact details

### Colors
Modify the CSS variables in `assets/css/main.css`:
```css
:root { 
  --background-color: #1f1f1f;
  --accent-color: #9b805a;
  --default-color: #ffffff;
  /* ... other colors */
}
```

### Images
Replace images in `assets/img/` folder:
- Profile photos: `assets/img/profile/`
- Portfolio images: `assets/img/portfolio/`
- Other images: `assets/img/`

## 🔧 Troubleshooting

### Contact Form Not Working
1. Check EmailJS dashboard for service status
2. Verify your EmailJS account has credits
3. Check browser console for error messages
4. Ensure internet connection is active

### Images Not Loading
1. Check file paths in HTML
2. Ensure image files exist in correct folders
3. Verify image file names match HTML references

### Styling Issues
1. Clear browser cache
2. Check CSS file paths
3. Verify Bootstrap CSS is loading

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📄 License

This portfolio template is based on SnapFolio by BootstrapMade.

## 📞 Contact

For any issues or questions:
- Email: kaviyarasuchand@gmail.com
- Phone: +91 9629 9449 07

---

**Note**: Make sure to update all placeholder content with your actual information before deploying! 