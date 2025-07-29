# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript to showcase your projects, skills, and experience to potential employers.

## Features

- 🎨 **Modern Design**: Clean, professional design with smooth animations
- 📱 **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Fast Loading**: Optimized for performance
- 🎯 **SEO Friendly**: Proper meta tags and semantic HTML
- 📧 **Contact Form**: Functional contact form with validation
- 📄 **Resume Download**: Easy resume download functionality
- 🌟 **Interactive Elements**: Hover effects, animations, and smooth scrolling

## Sections Included

1. **Hero Section** - Introduction and call-to-action
2. **About** - Personal information and statistics
3. **Skills** - Technical skills and technologies
4. **Experience** - Work history timeline
5. **Projects** - Featured projects showcase
6. **Contact** - Contact information and form

## Getting Started

### 1. Customize Your Information

Edit the `index.html` file to replace the placeholder content with your information:

#### Personal Information
- Replace "Your Name" with your actual name
- Update the hero subtitle with your title/role
- Modify the about section with your personal story
- Update contact information (email, phone, location)

#### Skills Section
- Add/remove skills based on your expertise
- Update skill icons using Font Awesome classes
- Organize skills into categories (Frontend, Backend, Tools)

#### Experience Section
- Replace the timeline items with your work experience
- Update company names, positions, and dates
- Add your specific achievements and responsibilities

#### Projects Section
- Replace project examples with your actual projects
- Add real project images (replace placeholder divs)
- Update project descriptions and technologies used
- Add actual links to live demos and GitHub repositories

### 2. Adding Your Resume

To add your resume for download:

1. **Convert your resume to PDF format** (recommended for consistency across devices)
2. **Name it `resume.pdf`** and place it in the same directory as `index.html`
3. The download button will automatically work once the file is added

**Alternative methods:**
- If you have a different file format, update the link in the HTML:
  ```html
  <a href="your-resume.pdf" class="btn btn-secondary" download>
  ```
- For a different filename, change both the `href` and the JavaScript fetch check

### 3. Adding Your Photo

To add your profile picture:

1. **Add your image** to the project directory
2. **Replace the placeholder** in the hero section:
   ```html
   <!-- Replace this: -->
   <div class="profile-placeholder">
       <i class="fas fa-user"></i>
   </div>
   
   <!-- With this: -->
   <img src="your-photo.jpg" alt="Your Name" class="profile-image">
   ```
3. **Add CSS for the image** in `styles.css`:
   ```css
   .profile-image {
       width: 300px;
       height: 300px;
       border-radius: 50%;
       object-fit: cover;
       border: 3px solid rgba(255, 255, 255, 0.2);
   }
   ```

### 4. Customizing Colors and Styling

The website uses a modern color scheme that you can customize:

#### Primary Colors (in `styles.css`):
- Primary Blue: `#2563eb`
- Secondary Blue: `#1d4ed8`
- Accent Yellow: `#fbbf24`
- Gradient: `#667eea` to `#764ba2`

#### To change colors:
1. Find the color values in `styles.css`
2. Replace them with your preferred colors
3. Update the gradient backgrounds if desired

### 5. Adding Project Images

For project screenshots:

1. **Add your project images** to the project directory
2. **Replace the placeholder divs** in the projects section:
   ```html
   <!-- Replace this: -->
   <div class="project-placeholder">
       <i class="fas fa-laptop-code"></i>
   </div>
   
   <!-- With this: -->
   <img src="project-screenshot.jpg" alt="Project Name" class="project-image">
   ```
3. **Update the CSS** for project images:
   ```css
   .project-image {
       width: 100%;
       height: 200px;
       object-fit: cover;
   }
   ```

## Deployment

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Get a custom URL instantly
4. Option to add custom domain

### Option 3: Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Deploy automatically on every push

## Customization Tips

### Adding More Sections
To add new sections (like Education, Certifications, etc.):
1. Add the HTML structure following the existing pattern
2. Add corresponding CSS styles
3. Update the navigation menu
4. Add any JavaScript functionality if needed

### Changing Fonts
The website uses Inter font from Google Fonts. To change:
1. Update the Google Fonts link in the HTML head
2. Change the font-family in CSS

### Adding Animations
The website includes several animations:
- Fade-in effects on scroll
- Hover effects on cards
- Typing animation for the hero title
- Smooth scrolling navigation

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance Optimization

The website is optimized for:
- Fast loading times
- Mobile performance
- SEO best practices
- Accessibility standards

## Troubleshooting

### Resume Download Not Working
- Ensure the file is named `resume.pdf`
- Check that the file is in the same directory as `index.html`
- Verify the file is not corrupted

### Images Not Loading
- Check file paths are correct
- Ensure image files exist in the specified location
- Verify image file formats are supported (JPG, PNG, WebP)

### Contact Form Not Working
- The form currently shows a success message
- To make it functional, you'll need to add backend processing
- Consider using services like Formspree, Netlify Forms, or your own backend

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio:
1. Check the comments in the code
2. Refer to this README
3. Look up HTML, CSS, and JavaScript documentation
4. Consider hiring a developer for complex customizations

---

**Good luck with your job search!** 🚀 