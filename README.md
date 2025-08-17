<<<<<<< HEAD
# 4ier.github.io
=======
# 4ier.github.io Documentation Site

This is the source code for the [4ier.github.io](https://4ier.github.io) documentation site, hosting documentation for all 4ier open source projects.

## 🚀 Quick Deployment to your GitHub Pages

### Step 1: Create your GitHub Pages repository

1. Go to GitHub and create a new repository named `4ier.github.io` (or `yourusername.github.io`)
2. Make sure the repository is **public**
3. Clone the repository to your local machine

### Step 2: Copy the documentation site

```bash
# Copy all files from this docs-site directory to your GitHub Pages repository
cp -r docs-site/* /path/to/your/4ier.github.io/

# Or if you're in the retire-cluster repository:
cp -r docs-site/* ../4ier.github.io/
```

### Step 3: Configure GitHub Pages

1. Go to your repository settings on GitHub
2. Navigate to **Pages** section in the sidebar
3. Under **Source**, select **GitHub Actions**
4. The workflow will automatically deploy your site

### Step 4: Push and deploy

```bash
cd /path/to/your/4ier.github.io
git add .
git commit -m "Initial documentation site deployment

- Added 4ier projects landing page
- Added complete Retire-Cluster documentation in English and Chinese
- Configured GitHub Actions for automatic deployment
- Created responsive design with bilingual support"

git push origin main
```

## 📁 Site Structure

```
/
├── index.html                 # Main landing page for all 4ier projects
├── retire-cluster/            # Retire-Cluster documentation
│   ├── index.html            # Retire-Cluster documentation index
│   ├── README.md             # English documentation files
│   ├── README_CN.md          # Chinese documentation files
│   ├── architecture.md       # System architecture
│   ├── architecture_CN.md    # 系统架构
│   ├── deployment-guide.md   # Deployment guide
│   ├── deployment-guide_CN.md # 部署指南
│   └── ...                   # Other documentation files
└── .github/
    └── workflows/
        └── deploy.yml         # GitHub Actions deployment workflow
```

## 🌐 Features

### Multi-language Support
- **English**: Primary documentation language
- **中文**: Complete Chinese translations for all documentation

### Responsive Design
- Mobile-first responsive design
- Optimized for desktop, tablet, and mobile devices
- Clean, professional styling

### Automatic Deployment
- GitHub Actions workflow for automatic deployment
- Markdown to HTML conversion with syntax highlighting
- Consistent styling across all documentation pages

### SEO Optimized
- Proper meta tags and descriptions
- Semantic HTML structure
- Fast loading times

## 🎨 Customization

### Updating the Landing Page

Edit `index.html` to add new projects or update project information:

```html
<!-- Add new project card -->
<div class="project-card">
    <div class="project-header">
        <div class="project-icon">🔧</div>
        <div>
            <h2 class="project-title">Your New Project</h2>
            <span class="project-status status-active">Active</span>
        </div>
    </div>
    <!-- Project content -->
</div>
```

### Adding New Documentation

1. Create a new directory under the root (e.g., `/new-project/`)
2. Add your markdown files
3. Create an `index.html` for the project
4. Update the main landing page to include links to your new project

### Styling

The site uses CSS custom properties for easy theming:

```css
:root {
    --primary-color: #007acc;     /* Primary blue */
    --secondary-color: #005a99;   /* Darker blue */
    --bg-color: #ffffff;          /* Background */
    --text-color: #333333;        /* Text color */
    --border-color: #e1e5e9;      /* Borders */
    --hover-bg: #f8f9fa;          /* Hover backgrounds */
}
```

## 🔧 Development

### Local Development

To test the site locally:

```bash
# Serve the site locally (requires Python)
cd /path/to/your/4ier.github.io
python -m http.server 8000

# Open http://localhost:8000 in your browser
```

### Adding New Markdown Documentation

The GitHub Actions workflow automatically converts `.md` files to `.html` with:
- Proper styling and navigation
- Syntax highlighting for code blocks
- Table of contents generation
- Responsive design

Simply add your `.md` files to the appropriate directory and they'll be converted automatically.

## 📱 Supported Platforms

The documentation site is optimized for:
- **Desktop browsers** (Chrome, Firefox, Safari, Edge)
- **Mobile browsers** (iOS Safari, Chrome Mobile, Firefox Mobile)
- **CLI browsers** (w3m, lynx) - Basic support
- **Screen readers** - Accessible markup

## 🌟 Live Example

Visit [https://4ier.github.io](https://4ier.github.io) to see the live documentation site.

### Project URLs:
- **Main site**: https://4ier.github.io
- **Retire-Cluster English**: https://4ier.github.io/retire-cluster/
- **Retire-Cluster Chinese**: https://4ier.github.io/retire-cluster/README_CN.html

## 📄 License

This documentation site is open source under the MIT License. Individual projects may have their own licenses.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

For issues or suggestions, please open an issue in the respective project repository.

---

Built with ❤️ for the open source community | [GitHub](https://github.com/4ier)
>>>>>>> master
