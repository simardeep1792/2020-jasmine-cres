# 2020 Jasmine Crescent - Rental Property Website

A modern, responsive website for showcasing a premium 2-bedroom condo rental property at 2020 Jasmine Crescent, Beacon Hill South, Ottawa.

## Features

- 🏠 Premium single-page design with smooth animations
- 📸 Interactive photo gallery with lightbox
- 🎥 Video tour integration
- 📱 Fully responsive design for all devices
- 📧 Privacy-protected contact form
- 📄 Downloadable rental application (Form 410)

## Setup Instructions

1. **Fork or Clone this Repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/2020-jasmine-cres.git
   cd 2020-jasmine-cres
   ```

2. **Set up Form Integration**
   - Sign up for a free account at [Formspree](https://formspree.io/)
   - Create a new form
   - Copy your form ID
   - Replace `YOUR_FORM_ID` in `script.js` line 197 with your actual Formspree form ID

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save
   - Your site will be available at `https://YOUR-USERNAME.github.io/2020-jasmine-cres/`

## File Structure

```
2020-jasmine-cres/
├── index.html          # Main website file
├── styles.css          # All styling
├── script.js           # Interactive features
├── images/             # Property photos (1-8.jpeg)
├── assets/             # Video and PDF files
│   ├── 2020-Jasmince-Crescent.mp4
│   └── Form 410.pdf
└── README.md          # This file
```

## Alternative Form Solutions

If you prefer not to use Formspree, here are other options:

### Option 1: Google Forms
1. Create a Google Form with the required fields
2. Get the embed code
3. Replace the form in `index.html` with the Google Forms embed

### Option 2: Netlify Forms (if hosting on Netlify)
1. Add `data-netlify="true"` to the form tag
2. Remove the Formspree action URL

### Option 3: EmailJS
1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Set up your service and template
3. Update the form submission code in `script.js`

## Customization

- **Colors**: Edit CSS variables in `styles.css` (lines 7-15)
- **Content**: Update property details in `index.html`
- **Images**: Replace images in the `images/` folder (maintain same filenames)
- **Contact Info**: Update form endpoint in `script.js`

## SEO Optimization

The website includes:
- Meta descriptions
- Open Graph tags for social sharing
- Semantic HTML structure
- Optimized image loading

## Privacy Protection

- No personal contact information is displayed
- All inquiries go through the web form
- Form submissions are handled by third-party service
- No email addresses or phone numbers exposed

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This project is for the exclusive use of the property owner for rental purposes.