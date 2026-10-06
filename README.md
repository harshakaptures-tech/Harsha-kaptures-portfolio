# Harsha Kaptures - Photography Portfolio

A beautiful, responsive photography portfolio website hosted on GitHub Pages.

## 📋 Overview

This is a static website (no backend required) perfect for GitHub Pages hosting. All projects are managed through a simple `projects.json` file, and images are stored directly in the repository.

## 🚀 Getting Started

### Prerequisites
- GitHub account
- Git installed locally

### Installation & Setup

1. **Clone or Fork this repository**
   ```bash
   git clone https://github.com/yourusername/harsha-kaptures.git
   cd harsha-kaptures
   ```

2. **Add your images**
   - Place all project images in the `images/` folder
   - Recommended: Use descriptive filenames (e.g., `wedding-1.jpg`, `portfolio-2.jpg`)

3. **Update projects.json**
   - Edit `projects.json` to add your projects
   - Each project needs:
     - `_id`: Unique identifier
     - `title`: Project title
     - `description`: Short description
     - `coverImage`: Path to cover image (e.g., `images/wedding-1.jpg`)
     - `images`: Array of image paths for the album

   Example:
   ```json
   {
     "projects": [
       {
         "_id": "1",
         "title": "Wedding Photography",
         "description": "Capturing the essence of your special day",
         "coverImage": "images/wedding-1.jpg",
         "images": [
           "images/wedding-1.jpg",
           "images/wedding-2.jpg"
         ]
       }
     ],
     "viewMoreEnabled": true,
     "limit": 6
   }
   ```

4. **Customize content**
   - Edit `index.html` to update personal information
   - Modify testimonials in the testimonials section
   - Update social media links in the footer

5. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Update portfolio content"
   git push origin main
   ```

## 🌐 Hosting on GitHub Pages

### Steps to Enable GitHub Pages

1. Go to your repository settings
2. Scroll to **Pages** section
3. Under **Source**, select:
   - Branch: `main` (or your default branch)
   - Folder: `/ (root)`
4. Click **Save**
5. Your site will be available at: `https://yourusername.github.io/repository-name`

### Custom Domain (Optional)

To use a custom domain:
1. Create a `CNAME` file in the root with your domain name
2. Update your domain's DNS settings to point to GitHub Pages

## 📁 Project Structure

```
harsha-kaptures/
├── index.html          # Main website
├── script.js           # Frontend JavaScript
├── styles.css          # Website styling
├── projects.json       # Project data
├── images/             # All project images
├── MOBILE_RESPONSIVE_GUIDE.md  # Mobile design info
├── README.md           # This file
└── .gitignore          # Git ignore rules
```

## ✨ Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Fast loading with lazy image loading
- ✅ Image zoom and album view
- ✅ Smooth animations and transitions
- ✅ Dark mode support
- ✅ No backend server required
- ✅ No database needed
- ✅ Free hosting with GitHub Pages
- ✅ Easy to customize

## 🎨 Customization

### Change Colors & Styling
Edit `styles.css` to modify:
- Color scheme
- Fonts
- Animations
- Layout

### Update About Section
Edit the About section in `index.html`:
- Replace text with your bio
- Update the about photo path in `index.html`

### Modify Statistics
Update the stats section in `index.html`:
- Years of experience
- Number of projects
- Photos taken
- Happy clients

## 📸 Image Guidelines

- **Cover Images**: 800x600px recommended
- **Album Images**: 1200x800px recommended
- **Formats**: JPG, PNG, WebP
- **Optimization**: Use tools like TinyPNG to compress images

## 📝 Managing Projects

To add a new project:
1. Add images to `images/` folder
2. Update `projects.json` with project details
3. Commit and push changes

To remove a project:
1. Delete images from `images/` folder (optional)
2. Remove project entry from `projects.json`
3. Commit and push changes

## 🔍 SEO Optimization

The site includes:
- Semantic HTML structure
- Meta tags for social sharing
- Mobile-friendly viewport settings
- Fast loading images with lazy loading

### Additional SEO Tips:
- Add your GitHub Pages URL to Google Search Console
- Use descriptive image filenames
- Update project descriptions
- Share on social media

## 🐛 Troubleshooting

### Images not loading
- Check file paths in `projects.json` match actual image filenames
- Ensure images are in the `images/` folder
- File paths are case-sensitive

### Website looks broken
- Clear browser cache (Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows)
- Check browser console for JavaScript errors
- Verify all files are committed to GitHub

### Changes not showing up
- Wait 1-2 minutes for GitHub Pages to rebuild
- Refresh page with cache clear
- Check that files were pushed to GitHub

## 📱 Mobile & Responsive Design

The website is fully responsive and tested on:
- iPhone (all sizes)
- iPad and tablets
- Desktop (all major browsers)
- Android devices

See `MOBILE_RESPONSIVE_GUIDE.md` for more details.

## 🎯 Best Practices

1. **Keep images optimized** - Compress images to reduce load time
2. **Organize projects** - Group similar work in projects
3. **Update regularly** - Keep portfolio fresh with new work
4. **Test on devices** - Verify on mobile and desktop
5. **Use descriptive names** - Make filenames and titles clear

## ⚖️ License

This project is licensed under the MIT License.

## 🤝 Support

For issues or questions:
1. Check the troubleshooting section
2. Review `MOBILE_RESPONSIVE_GUIDE.md`
3. Refer to [GitHub Pages Documentation](https://docs.github.com/en/pages)

## 🎉 Ready to Deploy!

Your portfolio is ready to host on GitHub Pages. Just:
1. Add your images
2. Update `projects.json`
3. Customize content in `index.html`
4. Push to GitHub
5. Enable GitHub Pages in settings

That's it! Your photography portfolio is now live! 📸

---

**Happy Showcasing!** ✨

