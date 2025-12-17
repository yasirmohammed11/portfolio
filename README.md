# Yasir Mohammed - Professional Portfolio

## 📋 Overview

This is a **professional and modern portfolio website** for **Yasir Mohammed**, a Software Engineer graduate from the Sudanese-Jordanian College of Science and Technology. The portfolio showcases projects, skills, education, and provides a way to get in touch.

### ✨ Features

- **Dark Theme Design** - Modern, sleek dark interface with professional aesthetics
- **Responsive Layout** - Works perfectly on desktop, tablet, and mobile devices
- **Smooth Navigation** - Easy-to-use navigation with smooth transitions
- **Project Showcase** - Display of completed projects with GitHub links
- **Skills Section** - Progress bars showing technical proficiency
- **Timeline** - Education and experience timeline
- **Blog Section** - Articles and thoughts on web development
- **Contact Form** - Get in touch section with contact information
- **Social Links** - Links to GitHub, LinkedIn, and other social profiles

## 📁 Project Structure

```
yasir_portfolio_dark/
├── index.html           # Main HTML file
├── app.js              # JavaScript for interactivity
├── styles/
│   └── styles.css      # All styling and layout
├── img/
│   ├── hero.png        # Profile picture
│   ├── port1.jpg       # Project 1 image
│   ├── port2.jpg       # Project 2 image
│   ├── port3.jpg       # Project 3 image
│   ├── port4.jpg       # Project 4 image
│   ├── blog1.jpg       # Blog 1 image
│   ├── blog2.jpg       # Blog 2 image
│   └── blog3.jpg       # Blog 3 image
└── README.md           # This file
```

## 🚀 How to Use

### 1. Extract the Files
Unzip the `yasir_portfolio_dark.zip` file to your desired location.

### 2. Open in Browser
Simply open `index.html` in your web browser:
- **Windows**: Double-click `index.html`
- **Mac**: Right-click → Open with → Your Browser
- **Linux**: `xdg-open index.html`

### 3. Local Server (Optional)
For better performance and to avoid CORS issues, run a local server:

**Using Python 3:**
```bash
python -m http.server 8000
```

**Using Node.js (http-server):**
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 🎨 Customization

### Change Profile Picture
1. Replace `img/hero.png` with your own profile picture
2. Keep the same filename or update the reference in `index.html`

### Update Personal Information
Edit `index.html` and update:
- Name and title in the header section
- About me description
- Skills and proficiency levels
- Project information and GitHub links
- Contact information
- Social media links

### Modify Colors
Edit `styles/styles.css` to change the color scheme:
```css
:root {
  --color-primary: #191d2b;      /* Dark background */
  --color-secondary: #27AE60;    /* Green accent color */
  --color-white: #FFFFFF;        /* Text color */
  /* ... other colors ... */
}
```

### Update Project Images
Replace images in the `img/` folder:
- `port1.jpg`, `port2.jpg`, `port3.jpg`, `port4.jpg` - Project thumbnails
- `blog1.jpg`, `blog2.jpg`, `blog3.jpg` - Blog post images

## 📱 Navigation

The portfolio uses a sidebar navigation system:
- **Home** (House icon) - Main introduction
- **About** (User icon) - About me, skills, and timeline
- **Portfolio** (Briefcase icon) - Project showcase
- **Blog** (Blog icon) - Articles and thoughts
- **Contact** (Envelope icon) - Contact information and form

Click the icons on the right side to navigate between sections.

## 🌐 Deployment

You can deploy this portfolio to various platforms:

### GitHub Pages
1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select the branch and save
5. Your portfolio will be live at `https://yourusername.github.io/portfolio`

### Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the folder or connect your GitHub repo
3. Your site will be deployed automatically

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import your project
3. Deploy with one click

### Traditional Hosting
Upload all files to your web hosting provider using FTP or file manager.

## 📞 Contact Information

- **Email**: yasirmohammed@example.com
- **Phone**: +249 123 456 789
- **GitHub**: [github.com/yasirmohammed11](https://github.com/yasirmohammed11)
- **LinkedIn**: [linkedin.com/in/yasir-mohammed-166783318](https://www.linkedin.com/in/yasir-mohammed-166783318)
- **Location**: Sudan

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox and grid
- **JavaScript** - Interactive features and navigation
- **Font Awesome** - Icons
- **Google Fonts** - Poppins font family

## 📝 Tips for Best Results

1. **Keep Images Optimized** - Compress images to reduce file size
2. **Update Content Regularly** - Keep your portfolio fresh with new projects
3. **Test on Mobile** - Ensure it looks good on all devices
4. **Use SEO** - Add meta tags for better search engine visibility
5. **Get Feedback** - Ask friends and colleagues for feedback

## 🔧 Troubleshooting

### Images Not Showing
- Ensure image files are in the `img/` folder
- Check that file paths in `index.html` are correct
- Use relative paths like `img/hero.png`

### Navigation Not Working
- Make sure `app.js` is in the root directory
- Check browser console for JavaScript errors
- Ensure all HTML elements have correct IDs

### Styling Issues
- Clear browser cache (Ctrl+Shift+Delete)
- Check that `styles/styles.css` is properly linked
- Verify CSS file path in `index.html`

## 📄 License

This portfolio template is free to use and modify for personal use.

## 🙏 Credits

- **Design Inspiration**: Modern portfolio templates
- **Icons**: Font Awesome
- **Fonts**: Google Fonts
- **Images**: AI-generated professional images

---

**Last Updated**: December 2024
**Version**: 1.0.0

Enjoy your new portfolio! 🚀
