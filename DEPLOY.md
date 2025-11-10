# Deploy Portfolio Example

This is a complete portfolio website example that you can deploy and showcase on your Webs4U website.

## Quick Deploy Options

### Option 1: Netlify Drop (Easiest - 30 seconds!)

1. Go to https://app.netlify.com/drop
2. Drag and drop this entire `portfolio-example` folder
3. You'll get a URL like: `https://random-name-123.netlify.app`
4. Copy that URL and update your Webs4U portfolio section!

### Option 2: GitHub Pages

1. Create a new repository on GitHub (e.g., `portfolio-example`)
2. Upload all files from this folder
3. Go to Settings → Pages
4. Select main branch and `/root` folder
5. Your site will be at: `https://yourusername.github.io/portfolio-example`
6. Update the link in your Webs4U website!

### Option 3: Vercel

1. Go to https://vercel.com
2. Drag and drop this folder
3. Get instant URL
4. Update your Webs4U portfolio link!

## Update Your Webs4U Website

Once you have the deployed URL, update the portfolio link in:
- File: `app/page.tsx`
- Find the portfolio item with "Portfolio Website"
- Change the href to your deployed URL

Example:
```tsx
<a href="https://your-portfolio.netlify.app" target="_blank" rel="noopener noreferrer" className="portfolio-link">View Live Demo →</a>
```

## Customize Before Deploying

1. **Change the name**: Edit `index.html` - replace "Sarah Johnson" with your client's name
2. **Update contact info**: Change email, phone, location
3. **Add real images**: Replace gradient backgrounds with actual project images
4. **Customize colors**: Edit `styles.css` if needed

## That's It!

Once deployed, you'll have a live portfolio example to showcase on your Webs4U website! 🎉

