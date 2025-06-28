# Deployment Guide for SierraLuxe Scents Website

This guide provides multiple options for deploying your SierraLuxe Scents website so that your friend can view it online. Since this is a static website (HTML, CSS, and JavaScript), there are several easy and free options available.

## Option 1: GitHub Pages (Recommended for Beginners)

GitHub Pages is a free hosting service provided by GitHub that allows you to publish your website directly from a GitHub repository.

### Step 1: Create a GitHub Account
If you don't already have one, sign up for a free GitHub account at [github.com](https://github.com/).

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner of GitHub and select "New repository"
2. Name your repository (e.g., "sierraluxe-scents")
3. Make sure it's set to "Public"
4. Click "Create repository"

### Step 3: Upload Your Website Files
1. Click on "uploading an existing file" on the repository page
2. Drag and drop all your website files (HTML, JS, etc.) or use the file selector
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository's "Settings" tab
2. Scroll down to the "GitHub Pages" section
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait a few minutes for your site to be published
6. GitHub will provide you with a URL (typically in the format `https://yourusername.github.io/repository-name/`)

### Step 5: Share with Your Friend
Send your friend the GitHub Pages URL. They can access your website from any device with an internet connection.

## Option 2: Netlify (Recommended for More Features)

Netlify offers free hosting with more advanced features like custom domains and form handling.

### Step 1: Create a Netlify Account
Sign up for a free Netlify account at [netlify.com](https://www.netlify.com/) using your email or GitHub account.

### Step 2: Deploy Your Site
1. Go to the Netlify dashboard
2. Drag and drop your entire website folder onto the designated area on the dashboard
3. Netlify will automatically upload and deploy your site
4. Once deployed, Netlify will provide you with a random URL (e.g., `https://random-name-123456.netlify.app`)

### Step 3: Customize Your Site URL (Optional)
1. From your site overview, go to "Site settings" → "Domain management"
2. Under "Custom domains", click "Add custom domain"
3. You can either:
   - Use a free Netlify subdomain (e.g., `sierraluxe-scents.netlify.app`)
   - Purchase and connect your own domain

### Step 4: Share with Your Friend
Send your friend the Netlify URL. They can access your website from any device with an internet connection.

## Option 3: Vercel

Vercel is another excellent platform for static site hosting with a generous free tier.

### Step 1: Create a Vercel Account
Sign up for a free Vercel account at [vercel.com](https://vercel.com/) using your email, GitHub, or other social accounts.

### Step 2: Install Vercel CLI (Optional)
If you prefer using the command line:
```
npm install -g vercel
```

### Step 3: Deploy Your Site
**Using the Dashboard:**
1. Go to the Vercel dashboard
2. Click "New Project"
3. Import your project from a Git repository or upload your files directly
4. Follow the configuration steps
5. Click "Deploy"

**Using the CLI:**
1. Navigate to your project directory in the terminal
2. Run `vercel`
3. Follow the prompts to configure your project

### Step 4: Share with Your Friend
Send your friend the Vercel URL (typically `https://your-project-name.vercel.app`).

## Option 4: Traditional Web Hosting

If you prefer traditional web hosting:

1. Sign up for a web hosting service (many offer free plans):
   - [InfinityFree](https://infinityfree.net/)
   - [000webhost](https://www.000webhost.com/)
   - [AwardSpace](https://www.awardspace.com/)

2. Use their file manager or FTP to upload your website files

3. Share the provided domain with your friend

## Conclusion

For your SierraLuxe Scents website, I recommend using **GitHub Pages** or **Netlify** as they are:
- Completely free
- Easy to set up
- Reliable with good performance
- Don't require any server maintenance

Once deployed, simply share the URL with your friend, and they'll be able to browse your beautiful perfume website from anywhere!
