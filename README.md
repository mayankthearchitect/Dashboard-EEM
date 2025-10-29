# Energy Efficiency Measures Dashboard - Netlify Deployment

This package is ready to be deployed to Netlify.

## Quick Deploy Options

### Option 1: Drag & Drop (Easiest)

1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag the entire `netlify-deploy` folder onto the page
3. Your site will be live instantly with a random URL
4. Optionally customize the domain name in Netlify settings

### Option 2: Deploy from GitHub

1. Create a new GitHub repository
2. Upload all files from this folder to the repository
3. Go to [Netlify](https://app.netlify.com/)
4. Click "Add new site" > "Import an existing project"
5. Connect your GitHub account and select the repository
6. Netlify will automatically detect settings and deploy

### Option 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Navigate to this directory
cd netlify-deploy

# Deploy
netlify deploy --prod
```

## What's Included

- `index.html` - Main dashboard (renamed from energy-dashboard.html)
- `chart.min.js` - Chart.js library for offline use
- `netlify.toml` - Netlify configuration with security headers
- `README.md` - This deployment guide

## Custom Domain (Optional)

After deployment, you can:
1. Use Netlify's free subdomain (yourname.netlify.app)
2. Add your own custom domain in Netlify settings
3. Netlify provides free HTTPS certificates automatically

## Environment

- **Build**: Not required (static site)
- **Framework**: Vanilla JavaScript
- **Dependencies**: None (Chart.js included)
- **Node Version**: Not required

## Support

Once deployed, share the Netlify URL with your team. The dashboard will be accessible from anywhere with a web browser.

---

**Deployment Time**: ~30 seconds
**Cost**: Free (Netlify Free Tier)
