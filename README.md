# HIV Awareness & Education Website

A modern, responsive website providing comprehensive information about HIV prevention, testing, treatment, and awareness.

## 🚀 Deploy to Vercel

### Prerequisites
- Vercel account (sign up at [vercel.com](https://vercel.com))
- GitHub account (recommended)

### Deployment Steps

#### Option 1: Using Vercel CLI
1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy from project directory**
   ```bash
   cd c:\Users\HP\Desktop\Wafula\Gigs\Apollo
   vercel
   ```

4. **Follow the prompts**
   - Set up and deploy? `Yes`
   - Which scope? Choose your account
   - Link to existing project? `No` (first time)
   - Project name? (accept default or customize)
   - In which directory is your code located? `./`
   - Want to override settings? `No`

5. **Your site will be live!** Vercel will provide you with a URL.

#### Option 2: Using Vercel Web Dashboard
1. **Push to GitHub** (recommended)
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/hiv-awareness.git
   git push -u origin main
   ```

2. **Import to Vercel**
   - Go to [vercel.com/dashboard](https://vercel.com/dashboard)
   - Click "Add New..." → "Project"
   - Import your GitHub repository
   - Click "Deploy"

#### Option 3: Direct Upload
1. Go to [vercel.com/dashboard](https://vercel.com/dashboard)
2. Click "Add New..." → "Project"
3. Select "Upload" instead of GitHub
4. Drag and drop your project folder
5. Click "Deploy"

### 📁 Project Structure
```
Apollo/
├── index.html          # Main website file
├── hiv_website.html    # Original file (can be deleted)
├── vercel.json         # Vercel configuration
└── README.md          # This file
```

### ⚙️ Vercel Configuration
The `vercel.json` file includes:
- **URL Rewrites**: Root domain (`/`) redirects to `index.html`
- **Security Headers**: Added security headers for better protection
- **Static Hosting**: Optimized for static HTML/CSS/JS files

### 🌐 After Deployment
- Your website will be available at a `.vercel.app` domain
- You can add a custom domain in Vercel dashboard
- Automatic HTTPS is provided
- Global CDN deployment for fast loading worldwide

### 🔄 Updates
To update your site:
- **If using Git**: Push changes to GitHub, Vercel auto-deploys
- **If using CLI**: Run `vercel --prod` in project directory
- **If using Dashboard**: Re-upload files or connect to Git

### 📱 Features
- ✅ Fully responsive design
- ✅ Interactive symptom carousel
- ✅ Animated hero word cloud
- ✅ Team portfolio section
- ✅ Modern UI with smooth animations
- ✅ SEO optimized
- ✅ Fast loading performance

### 🛠️ Technologies Used
- **HTML5** semantic markup
- **CSS3** with custom properties
- **Vanilla JavaScript** (no dependencies)
- **Font Awesome** icons
- **Google Fonts** (DM Sans, DM Serif Display)

### 📞 Support
If you encounter any issues during deployment:
1. Check Vercel deployment logs
2. Ensure all files are in the root directory
3. Verify `vercel.json` configuration
4. Contact Vercel support at [vercel.com/support](https://vercel.com/support)

---

**Your HIV Awareness website is now ready for Vercel deployment! 🎉**
