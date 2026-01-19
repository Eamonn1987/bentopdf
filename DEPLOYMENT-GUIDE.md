# Quick Deployment Guide for BentoPDF

This guide will help you deploy BentoPDF as a webpage using popular hosting platforms.

## 🚀 One-Click Deployments (Easiest)

### Deploy to Vercel

1. Click the button: [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/alam00000/bentopdf&project-name=bentopdf&repository-name=bentopdf)
2. Sign in with GitHub
3. Click "Create" - Vercel will automatically:
   - Fork the repository to your account
   - Configure build settings
   - Deploy your site
4. Your site will be live at `https://your-project.vercel.app` in ~2-3 minutes

### Deploy to Netlify

1. Click the button: [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/alam00000/bentopdf)
2. Sign in with GitHub
3. Click "Connect to GitHub" and authorize
4. Click "Save & Deploy" - Netlify will automatically:
   - Fork the repository to your account
   - Configure build settings
   - Deploy your site
5. Your site will be live at `https://your-project.netlify.app` in ~3-4 minutes

## ✅ Verify Your Deployment

After deployment, visit your site and check:

- ✅ Homepage loads correctly
- ✅ PDF tools are accessible
- ✅ You can upload a test PDF file
- ✅ Basic PDF operations work (e.g., merge, split)

## 🔧 Configuration Options

### Environment Variables

Both platforms support environment variables for customization:

**SIMPLE_MODE** (optional)

- Set to `true` to hide branding and show only PDF tools
- Good for internal company use

**BASE_URL** (optional)

- Set if deploying to a subdirectory
- Example: `/tools/pdf/`
- Must include leading and trailing slashes

### Adding Environment Variables

**Vercel:**

1. Go to Project Settings → Environment Variables
2. Add your variables
3. Redeploy to apply changes

**Netlify:**

1. Go to Site Settings → Environment Variables
2. Add your variables
3. Trigger a new deploy

## 📝 Custom Domain

### Vercel

1. Go to Project Settings → Domains
2. Add your custom domain
3. Update DNS records as instructed

### Netlify

1. Go to Domain Settings → Custom Domains
2. Add your custom domain
3. Update DNS records as instructed

## 🔄 Auto-Updates

Both platforms automatically redeploy when you push changes to your repository:

1. Fork the BentoPDF repository to your GitHub account
2. Make changes or sync from upstream
3. Push to your fork
4. Platform automatically detects changes and redeploys

## 🐛 Troubleshooting

### Build Fails

- Check build logs in your platform dashboard
- Verify Node.js version is 18 or higher
- Ensure all dependencies installed correctly

### Site Not Loading

- Check that the build completed successfully
- Verify the output directory is set to `dist`
- Check browser console for errors

### PDF Tools Not Working

- Ensure JavaScript is enabled
- Check browser compatibility (use modern browsers)
- Clear browser cache and reload

## 📚 Additional Resources

- [Full Static Hosting Guide](./STATIC-HOSTING.md)
- [BentoPDF Documentation](https://bentopdf.com/docs/)
- [GitHub Repository](https://github.com/alam00000/bentopdf)

## 💡 Need Help?

- Join our [Discord server](https://discord.gg/Bgq3Ay3f2w)
- Open an [issue on GitHub](https://github.com/alam00000/bentopdf/issues)
- Check the [FAQ](https://bentopdf.com/faq.html)
