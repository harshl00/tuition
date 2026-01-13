# Geminstitute Website

A professional, multi-page static website for a home tuition agency. Built with HTML, CSS, and JavaScript, designed to be hosted on GitHub Pages.

## 🌟 Features

### Pages
- **Home (index.html)**: Hero section, animated statistics, features, subjects, map preview, quick inquiry form, and testimonials
- **About (about.html)**: Mission statement, core values, process timeline, and trust & safety information
- **For Parents (parents.html)**: Comprehensive tutor request form with detailed requirements
- **For Tutors (tutors.html)**: Benefits section and detailed registration form
- **Contact (contact.html)**: Contact information, full-width map, contact form, FAQ section, and social media links

### Key Features
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Animated statistics counter with IntersectionObserver
- ✅ Sticky navigation with scroll effects
- ✅ Mobile hamburger menu
- ✅ FAQ accordion
- ✅ Form validation
- ✅ Smooth scrolling
- ✅ Active page highlighting
- ✅ Scroll-to-top button
- ✅ Professional color scheme (Royal Blue #1e3a8a)
- ✅ SEO-friendly structure
- ✅ Accessibility features

## 📁 File Structure

```
tuition/
├── index.html          # Homepage
├── about.html          # About Us page
├── parents.html        # For Parents page (Request Tutor)
├── tutors.html         # For Tutors page (Registration)
├── contact.html        # Contact page
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Getting Started

### Option 1: Open Locally
1. Simply open `index.html` in your web browser
2. All pages are linked and will work locally

### Option 2: Deploy to GitHub Pages
1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select the branch (usually `main`) and root folder
5. Click Save
6. Your site will be live at `https://yourusername.github.io/repository-name/`

## 🔧 Customization

### Update Contact Information
Search for the following in all HTML files and replace with your actual information:
- Phone: `7575882581`
- Email: `geminstitute13@gmail.com`
- Address: Update the office address in `contact.html`

### Configure Form Submissions
The forms currently use placeholder endpoints. You have two options:

#### Option 1: Formspree (Recommended)
1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form
3. Replace `https://formspree.io/f/YOUR_FORM_ID` with your actual Formspree endpoint in:
   - `index.html` (Quick Inquiry form)
   - `parents.html` (Request Tutor form)
   - `tutors.html` (Registration form)
   - `contact.html` (Contact form)

#### Option 2: Mailto (Simple but limited)
Replace form action with:
```html
<form action="mailto:your@email.com" method="post" enctype="text/plain">
```

### Update Google Maps
1. Go to [Google Maps](https://www.google.com/maps)
2. Search for your location
3. Click "Share" → "Embed a map"
4. Copy the iframe code
5. Replace the existing iframe in:
   - `index.html` (Map Preview section)
   - `contact.html` (Full Map section)

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-blue: #1e3a8a;
    --light-blue: #3b82f6;
    --dark-blue: #1e40af;
}
```

### Update Statistics
In `index.html`, find the counter elements and update the `data-target` attribute:
```html
<span class="counter" data-target="700">0</span>+
```

## 📱 Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Custom styles with Tailwind CSS via CDN
- **JavaScript**: Vanilla JS (no frameworks)
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📋 Features Breakdown

### Navigation
- Sticky header that changes on scroll
- Active page highlighting
- Mobile-responsive hamburger menu
- Smooth transitions

### Forms
- Client-side validation
- Phone number formatting
- Email validation
- Required field checking
- Checkbox group validation
- File upload handling

### Animations
- Counter animation on scroll
- Fade-in effects for sections
- Hover effects on cards
- Smooth page transitions

### Accessibility
- Semantic HTML structure
- ARIA labels where needed
- Keyboard navigation support
- Focus states for interactive elements
- Screen reader friendly

## 🔒 Security Notes
- All forms use POST method
- Phone number validation (10 digits)
- Email format validation
- No sensitive data stored client-side

## 📊 SEO Features
- Proper meta tags
- Semantic HTML structure
- Descriptive page titles
- Alt text ready for images
- Clean URL structure
- Mobile-friendly design

## 🐛 Troubleshooting

### Forms not submitting
- Check that you've configured Formspree or mailto
- Ensure form action URL is correct
- Check browser console for errors

### Statistics not animating
- Ensure JavaScript is enabled
- Check that you're scrolling to the statistics section
- Verify IntersectionObserver is supported (modern browsers)

### Mobile menu not working
- Clear browser cache
- Check that script.js is loaded
- Verify no JavaScript errors in console

## 📞 Support
For issues or questions about this website template, please check:
1. Browser console for errors
2. Network tab for failed requests
3. Ensure all files are in the same directory

## 📄 License
This is a template website. Feel free to customize and use for your home tuition business.

## 🎯 Next Steps
1. Replace all placeholder content with your actual information
2. Add real testimonials from parents
3. Configure form submission service
4. Update Google Maps with your location
5. Add your logo (replace text logo with image if desired)
6. Test on multiple devices
7. Deploy to GitHub Pages
8. Set up custom domain (optional)

## 📈 Future Enhancements
Consider adding:
- Blog section for educational content
- Online payment integration
- Student/parent login portal
- Tutor availability calendar
- Live chat support
- Gallery of success stories
- Video testimonials

---

**Built with ❤️ for Geminstitute**

*Last Updated: January 2024*
