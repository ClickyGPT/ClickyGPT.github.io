# ClickyGPT.github.io 🧠

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Website](https://img.shields.io/badge/Website-ClickyGPT.com-blue.svg)](https://clickygpt.com)
[![Twitter](https://img.shields.io/badge/Twitter-@ClickyGPT-1DA1F2.svg)](https://twitter.com/ClickyGPT)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen.svg)](https://clickygpt.github.io)

## 🎯 About This Repository

This is the official GitHub repository for **ClickyGPT Web Applications** - a collection of AI-driven web tools and utilities. This repository serves as the source for our GitHub Pages site.

🔗 **Live Site**: [clickygpt.github.io](https://clickygpt.github.io)

## 🚀 Repository Structure

```
ClickyGPT.github.io/
├── .github/workflows/          # GitHub Actions for deployment
├── .vscode/                    # VS Code configuration
├── .idea/                      # IntelliJ IDEA files
├── _config.yml                 # Jekyll configuration
├── index.md                    # Main landing page
├── README.md                   # This file - repository documentation
└── LICENSE                     # Unlicense (public domain)
```

## 🛠️ Development Setup

### Prerequisites
- [Jekyll](https://jekyllrb.com/docs/installation/)
- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Git](https://git-scm.com/downloads)

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ClickyGPT/ClickyGPT.github.io.git
   cd ClickyGPT.github.io
   ```

2. **Install Jekyll dependencies**:
   ```bash
   bundle install
   ```

3. **Serve locally**:
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site** at [http://localhost:4000](http://localhost:4000)

### VS Code Integration
- **Debug Configuration**: `.vscode/launch.json` configured for Chrome debugging
- **Port**: 4000 (Jekyll default)

## 📋 GitHub Actions

This repository uses **GitHub Actions** for automatic deployment to GitHub Pages:

- **Workflow**: `.github/workflows/jekyll-gh-pages.yml`
- **Trigger**: Automatic on push to `main` branch
- **Deployment**: Live at [clickygpt.github.io](https://clickygpt.github.io)

## 🚀 Available Tools

Visit our [live site](https://clickygpt.github.io) to access all tools, including:

- **Prompt Builder** - AI prompt optimization
- **Google-Dork Prompter** - Advanced search queries
- **Simulation Bender** - Creative AI simulations
- **NSFW/Adult Tools** - Age-restricted content (18+)

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### 🐛 Reporting Issues
1. Check existing [issues](https://github.com/ClickyGPT/ClickyGPT.github.io/issues)
2. Create a new issue with detailed description
3. Include steps to reproduce and expected behavior

### 💡 Suggesting Features
1. Open a [new issue](https://github.com/ClickyGPT/ClickyGPT.github.io/issues/new)
2. Use the "Feature Request" template
3. Describe the use case and expected functionality

### 🔧 Code Contributions
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Test locally: `bundle exec jekyll serve`
5. Commit: `git commit -m 'Add amazing feature'`
6. Push: `git push origin feature/amazing-feature`
7. Open a Pull Request

### 📝 Content Updates
- **Tool Links**: Update tool URLs in `index.md`
- **Documentation**: Improve this README
- **Descriptions**: Enhance tool descriptions

## 🧪 Testing

### Local Testing
```bash
# Test Jekyll build
bundle exec jekyll build

# Check for broken links
bundle exec htmlproofer ./_site

# Validate HTML
bundle exec htmlproofer ./_site --check-html
```

### GitHub Pages Testing
- **Staging**: Create a PR to test changes
- **Preview**: Use GitHub's deployment preview
- **Live**: Changes deploy automatically on merge

## 📊 Monitoring

- **GitHub Actions**: Check [Actions tab](https://github.com/ClickyGPT/ClickyGPT.github.io/actions)
- **Deployment Status**: Green checkmarks = live
- **Site Health**: [GitHub Pages status](https://www.githubstatus.com/)

## 🌐 Related Projects

- **[ClickyGPT.com](https://clickygpt.com)** - Main website
- **[Tool Collection](https://github.com/ClickyGPT/ClickyGPT)** - Additional tools
- **[Community](https://twitter.com/ClickyGPT)** - Twitter updates

## 📄 License

This project is released into the **public domain** under [The Unlicense](LICENSE).

---

<p align="center">
  <i>Built with ❤️ by the ClickyGPT community</i><br>
  <a href="https://clickygpt.github.io">🌐 clickygpt.github.io</a> |
  <a href="https://twitter.com/ClickyGPT">🐦 @ClickyGPT</a>
</p>
