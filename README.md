# Personal Website

A modern, responsive personal website showcasing your projects, CV, and blog.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Projects Section**: Showcase your portfolio with project cards including images, descriptions, and tech tags
- **CV Section**: Display your professional experience, education, and skills
- **Blog Section**: Share your thoughts and articles
- **Contact Form**: Allow visitors to get in touch with you
- **Smooth Navigation**: Smooth scrolling and active section highlighting
- **Modern UI**: Clean design with gradients and animations

## Getting Started

1. **Clone or download this repository**

2. **Customize the content**:
   - Open `index.html` and replace placeholder text with your information:
     - Update "Your Name" with your actual name
     - Add your tagline and description
     - Update email and social media links
   - Add your projects, work experience, education, and skills
   - Add your blog posts

3. **Add your images**:
   - Replace the placeholder project images with actual screenshots
   - Add a profile picture if desired

4. **Customize colors** (optional):
   - Open `styles.css`
   - Modify the CSS variables in the `:root` section to match your preferred color scheme

5. **Deploy**:
   - Upload the files to your web hosting service
   - Or use GitHub Pages, Netlify, or Vercel for free hosting

## File Structure

```
personal-web-site/
├── index.html          # Main HTML file
├── styles.css          # All CSS styling
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## Customization Tips

### Adding a Profile Picture
Add an `<img>` tag in the hero section:
```html
<img src="your-photo.jpg" alt="Your Name" class="profile-photo">
```

### Adding Real Project Images
Replace the placeholder divs with actual images:
```html
<div class="project-image">
    <img src="project-screenshot.jpg" alt="Project Name">
</div>
```

### Connecting the Contact Form
To make the contact form functional, you'll need to:
- Use a service like Formspree, EmailJS, or Netlify Forms
- Or set up your own backend API

### Adding a Blog
For a full blog, you can:
- Create individual HTML pages for each blog post
- Use a static site generator like Jekyll or Hugo
- Integrate with a headless CMS

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your personal website.

## Next Steps

- [ ] Replace all placeholder content with your information
- [ ] Add your actual projects with screenshots
- [ ] Update CV details
- [ ] Add blog posts
- [ ] Set up contact form backend
- [ ] Deploy to hosting service
- [ ] Add your domain name
