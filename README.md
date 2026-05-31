# Sumit Singh - Motion Designer Portfolio

A static portfolio website built with HTML/CSS and deployed on Netlify with Netlify Forms for contact submissions.

## Features

- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Dark theme with amber accents (#000000 background, #f59e0b accent)
- ✅ Contact form with Netlify Forms integration
- ✅ Automatic email notifications on form submission
- ✅ Smooth scrolling navigation
- ✅ Portfolio showcase sections
- ✅ Skills and experience timeline
- ✅ Video gallery section

## Deployment to Netlify

### Option 1: Deploy via GitHub (Recommended)

1. **Create a GitHub repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Static portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/sumit-singh-portfolio.git
   git push -u origin main
   ```

2. **Deploy to Netlify:**
   - Go to https://netlify.com
   - Click "New site from Git"
   - Select GitHub and authorize
   - Choose your repository
   - Click "Deploy"
   - Your site will be live at `sumit-singh-portfolio.netlify.app`

### Option 2: Deploy via Netlify Drag & Drop

1. Go to https://app.netlify.com/drop
2. Drag and drop the entire folder
3. Your site will be live immediately

## Customization

### Update Resume Link
Edit `index.html` and replace the Dropbox resume link:
```html
<a href="YOUR_RESUME_URL" class="btn-secondary">Resume</a>
```

### Add YouTube Videos
In the video section, replace video placeholders with YouTube embeds:
```html
<iframe width="100%" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
```

### Update Profile Image
Replace the image URL in the hero section with your own image URL.

### Configure Email Notifications
1. Go to your Netlify site settings
2. Navigate to **Forms** → **Submissions**
3. Click **Edit settings**
4. Add your email address to receive notifications

## Contact Form

The contact form uses Netlify Forms. When someone submits the form:
1. Netlify captures the submission
2. You receive an email notification
3. All submissions are visible in your Netlify dashboard

## Support

For issues with Netlify Forms, visit: https://docs.netlify.com/forms/setup/

For deployment help, visit: https://docs.netlify.com/
