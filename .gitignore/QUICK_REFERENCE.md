# ⚡ Quick Reference Guide

Fast access to all tools, generators, and resources for your GitHub Profile README.

---

## 🛠️ Essential Tools & Generators

### Animations & SVGs

| Tool | Purpose | URL |
|------|---------|-----|
| **Typing SVG Generator** | Create animated typing text | [readme-typing-svg.demolab.com](https://readme-typing-svg.demolab.com) |
| **Capsule Render** | Generate custom header/footer waves | [github.com/kyechan99/capsule-render](https://github.com/kyechan99/capsule-render) |
| **Snake Animation** | Contribution snake animation | [github.com/Platane/snk](https://github.com/Platane/snk) |

### Stats & Metrics

| Tool | Purpose | URL |
|------|---------|-----|
| **GitHub Stats** | Dynamic GitHub statistics cards | [github.com/anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) |
| **Streak Stats** | Contribution streak tracking | [github.com/DenverCoder1/github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) |
| **Trophy Showcase** | GitHub achievement trophies | [github.com/ryo-ma/github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) |
| **Activity Graph** | Contribution activity visualization | [github.com/Ashutosh00710/github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) |
| **Visitor Counter** | Profile view tracking | [komarev.com/ghpvc](https://komarev.com/ghpvc/) |
| **WakaTime Stats** | Coding time statistics | [github.com/anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats#wakatime-week-stats) |

### Badges & Icons

| Tool | Purpose | URL |
|------|---------|-----|
| **Shields.io** | Custom badge generator | [shields.io](https://shields.io/) |
| **Simple Icons** | Brand icons for badges | [simpleicons.org](https://simpleicons.org/) |
| **Badge Styles** | Badge style reference | [shields.io/docs](https://shields.io/docs) |
| **Dev Icons** | Programming language icons | [devicon.dev](https://devicon.dev/) |

### Integrations

| Tool | Purpose | URL |
|------|---------|-----|
| **Spotify GitHub Profile** | Currently playing on Spotify | [github.com/kittinan/spotify-github-profile](https://github.com/kittinan/spotify-github-profile) |
| **Blog Post Workflow** | Auto-update blog posts | [github.com/gautamkrishnar/blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow) |
| **GitHub Gist Card** | Display GitHub gists | Part of github-readme-stats |

---

## 📋 URL Templates

### GitHub Stats Card

```markdown
![Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=THEME_NAME&hide_border=true&bg_color=0D1117&title_color=A855F7&icon_color=A855F7&text_color=FFFFFF)
```

**Parameters:**
- `username=` - Your GitHub username
- `show_icons=true` - Show icons
- `theme=` - Theme name (radical, dark, tokyonight, etc.)
- `count_private=true` - Count private repos
- `include_all_commits=true` - Include all commits
- `hide=stars,issues` - Hide specific stats
- `custom_title=` - Custom title text
- `hide_border=true` - Remove border
- `bg_color=` - Background color (hex without #)
- `title_color=` - Title color
- `icon_color=` - Icon color
- `text_color=` - Text color

### Top Languages Card

```markdown
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=THEME_NAME&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=FFFFFF)
```

**Layouts:**
- `layout=compact` - Compact layout
- `layout=donut` - Donut chart
- `layout=donut-vertical` - Vertical donut chart
- `layout=pie` - Pie chart

**Additional:**
- `langs_count=8` - Number of languages to show
- `hide=html,css` - Hide specific languages
- `exclude_repo=repo1,repo2` - Exclude repositories

### Streak Stats

```markdown
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=THEME_NAME&hide_border=true&background=0D1117&ring=A855F7&fire=A855F7&currStreakLabel=A855F7)
```

**Parameters:**
- `user=` - Your username
- `theme=` - Theme name
- `hide_border=true` - Remove border
- `background=` - Background color
- `ring=` - Ring color
- `fire=` - Fire color
- `currStreakLabel=` - Current streak label color
- `dates=` - Date text color

### Trophy Showcase

```markdown
![Trophy](https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=THEME_NAME&no-frame=true&no-bg=false&margin-w=4&column=7)
```

**Parameters:**
- `username=` - Your username
- `theme=` - Theme (discord, onedark, gruvbox, etc.)
- `column=` - Number of columns (1-8)
- `row=` - Number of rows
- `margin-w=` - Margin width
- `margin-h=` - Margin height
- `no-frame=true` - Remove frame
- `no-bg=true` - Transparent background
- `rank=` - Filter by rank (S,A,B,C)

### Activity Graph

```markdown
![Activity](https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=THEME_NAME&hide_border=true&area=true&custom_title=YOUR%20TITLE&bg_color=0D1117&color=A855F7&line=A855F7&point=FFFFFF)
```

**Parameters:**
- `username=` - Your username
- `theme=` - Theme name
- `area=true` - Show area under graph
- `hide_border=true` - Remove border
- `custom_title=` - Custom title
- `bg_color=` - Background color
- `color=` - Graph color
- `line=` - Line color
- `point=` - Point color

### Typing Animation

```markdown
![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=A855F7&center=true&vCenter=true&width=940&lines=Line+1;Line+2;Line+3)
```

**Parameters:**
- `font=` - Font name (URL encode spaces as +)
- `size=` - Font size (px)
- `duration=` - Typing duration per character (ms)
- `pause=` - Pause between lines (ms)
- `color=` - Text color (hex without #)
- `center=true` - Center horizontally
- `vCenter=true` - Center vertically
- `width=` - Width (px)
- `height=` - Height (px)
- `lines=` - Lines separated by semicolons
- `repeat=true` - Loop animation
- `separator=` - Custom separator (default: ;)

### Custom Badges

```markdown
![Badge](https://img.shields.io/badge/LEFT_TEXT-RIGHT_TEXT-COLOR?style=STYLE&logo=LOGO_NAME&logoColor=white)
```

**Badge Styles:**
- `flat` - Flat design (default)
- `flat-square` - Flat square
- `for-the-badge` - Large badge
- `plastic` - Plastic 3D
- `social` - Social style

**Colors:**
- Named: `red`, `blue`, `green`, `yellow`, `orange`, `purple`, `pink`, `black`, `white`
- Hex: `FF6B6B` (without #)
- Gradients: `blueviolet`, `brightgreen`, `yellowgreen`

**Logo Names:**
- Find at [simpleicons.org](https://simpleicons.org/)
- Examples: `python`, `javascript`, `react`, `github`, `linkedin`

### Visitor Counter

```markdown
![Visitors](https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Profile%20Views&color=blueviolet&style=for-the-badge)
```

**Parameters:**
- `username=` - Your GitHub username
- `label=` - Label text (URL encode spaces as %20)
- `color=` - Color name or hex
- `style=` - Badge style (flat, flat-square, for-the-badge, plastic)

---

## 🎨 Color Palettes

### Popular GitHub Themes

| Theme Name | Primary | Background | Accent |
|------------|---------|------------|--------|
| **Radical** | `FF428E` | `0D1117` | `FFA500` |
| **Dark** | `58A6FF` | `0D1117` | `1F6FEB` |
| **Dracula** | `FF6E96` | `282A36` | `FFB86C` |
| **Tokyonight** | `70A5FD` | `1A1B26` | `BB9AF7` |
| **Gruvbox** | `FABD2F` | `282828` | `FB4934` |
| **Nord** | `88C0D0` | `2E3440` | `81A1C1` |
| **Monokai** | `F92672` | `272822` | `A6E22E` |

### Custom Color Schemes

**Purple/Violet (Current):**
```
Primary: A855F7
Background: 0D1117
Text: FFFFFF
Accent: C084FC
```

**Blue:**
```
Primary: 4A90E2
Background: 0A192F
Text: FFFFFF
Accent: 64FFDA
```

**Green:**
```
Primary: 4CAF50
Background: 0D1117
Text: FFFFFF
Accent: 8BC34A
```

**Red:**
```
Primary: FF6B6B
Background: 1A1A1A
Text: FFFFFF
Accent: FF8E8E
```

---

## 📝 Emoji Cheatsheet

### Common Categories

**Activities:**
- 🎯 Target, 🚀 Rocket, ⚡ Lightning, 🔥 Fire, ⭐ Star, 💡 Lightbulb, 🎨 Palette

**Tech:**
- 💻 Laptop, 🖥️ Desktop, ⌨️ Keyboard, 🖱️ Mouse, 📱 Phone, ⚙️ Gear, 🔧 Wrench, 🛠️ Tools

**Symbols:**
- ✅ Check, ❌ X, ➡️ Arrow, 📊 Chart, 📈 Trending Up, 📉 Trending Down, 🏆 Trophy

**People:**
- 👋 Wave, 🧠 Brain, 👁️ Eye, 💜 Purple Heart, 🙏 Pray, 🤝 Handshake

**Full Emoji List:** [github.com/ikatyang/emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet)

---

## 🔗 Important Links

### Documentation
- [GitHub Profile README Docs](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)

### Inspiration Galleries
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- [Creative Profile READMEs](https://github.com/coderjojo/creative-profile-readme)
- [Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)

### Testing & Validation
- [Markdown Live Preview](https://markdownlivepreview.com/)
- [HTML Entity Encoder](https://www.freeformatter.com/html-entities.html)
- [URL Encoder](https://www.urlencoder.org/)

---

## ⚡ Quick Commands

### GitHub Actions

```bash
# View workflow status
gh workflow list

# Run workflow manually
gh workflow run snake.yml

# View workflow logs
gh run list
gh run view [RUN_ID]
```

### Git Commands

```bash
# Clone your profile repo
git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.git

# Add all changes
git add .

# Commit changes
git commit -m "Update README with new content"

# Push to GitHub
git push origin main

# Force refresh (if needed)
git push origin main --force-with-lease
```

### Testing Locally

```bash
# Preview README in VS Code
# Install "Markdown Preview Enhanced" extension
# Press Ctrl+Shift+V (Windows/Linux) or Cmd+Shift+V (Mac)

# Or use grip (GitHub README preview)
pip install grip
grip README.md

# Then open http://localhost:6419
```

---

## 🐛 Common Issues & Quick Fixes

| Issue | Quick Fix |
|-------|-----------|
| **Images not loading** | Hard refresh (Ctrl+Shift+R), check username spelling |
| **Snake not appearing** | Run Actions manually, check permissions |
| **Stats not updating** | Add `&cache_seconds=1800` to URL |
| **Typing animation broken** | Use the [generator](https://readme-typing-svg.demolab.com) |
| **Badges not showing** | Check logo name at [simpleicons.org](https://simpleicons.org/) |
| **Actions failing** | Enable Actions in Settings → Actions → General |
| **Repository not showing** | Must be public, named exactly as username |

---

## 📊 Best Practices Summary

### Content
✅ **DO:**
- Keep it concise and scannable
- Use bullet points and tables
- Show measurable achievements
- Include call-to-action
- Update regularly

❌ **DON'T:**
- Overcrowd with too many badges
- Use broken or placeholder links
- Include outdated information
- Exaggerate skills or experience
- Make it too long

### Visual
✅ **DO:**
- Maintain consistent color scheme
- Use high-quality images
- Test on mobile and desktop
- Keep loading time fast
- Use clear hierarchy

❌ **DON'T:**
- Mix too many color schemes
- Use slow-loading GIFs
- Overcomplicate the design
- Use tiny or hard-to-read text
- Ignore white space

### Technical
✅ **DO:**
- Test all links before publishing
- Enable GitHub Actions properly
- Use responsive images
- Keep README.md in root directory
- Back up before major changes

❌ **DON'T:**
- Use private images/links
- Forget to update usernames
- Leave TODO comments
- Use absolute paths unnecessarily
- Skip testing phase

---

## 🎯 Keyboard Shortcuts

### GitHub
- `T` - File finder
- `L` - Jump to line
- `W` - Branch selector
- `G` + `C` - Go to Code
- `G` + `I` - Go to Issues
- `G` + `P` - Go to Pull Requests

### Markdown Editing
- `Ctrl/Cmd + B` - Bold
- `Ctrl/Cmd + I` - Italic
- `Ctrl/Cmd + K` - Insert link
- `Ctrl/Cmd + Shift + V` - Preview (VS Code)

---

## 📞 Support Resources

### Communities
- [r/github](https://reddit.com/r/github) - Reddit community
- [GitHub Community](https://github.community/) - Official forum
- [Stack Overflow](https://stackoverflow.com/questions/tagged/github) - Q&A

### Learning Resources
- [GitHub Skills](https://skills.github.com/) - Interactive tutorials
- [Markdown Tutorial](https://www.markdowntutorial.com/) - Learn Markdown
- [Git Documentation](https://git-scm.com/doc) - Official Git docs

---

<div align="center">

## 🚀 Ready to Build?

**Everything you need is right here.**  
**Now go create something amazing!** 💜

</div>

---

**Last Updated:** October 2025  
**Version:** 1.0

