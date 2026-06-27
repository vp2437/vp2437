# 🚀 GitHub Profile Setup Guide

Welcome to **GitHub Revamp**! Follow these steps to create your awesome GitHub profile README.

---

## 📋 Prerequisites

- A GitHub account
- Git installed on your computer
- Basic knowledge of markdown (optional but helpful)

---

## 🛠️ Setup Steps

### Step 1: Create Your Profile Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right → **New repository**
3. **Repository name:** Must be your exact GitHub username (e.g., if your username is `john-doe`, name the repo `john-doe`)
4. Set to **Public**
5. ✅ Check **"Add a README file"** (optional, we'll replace it anyway)
6. Click **Create repository**

---

### Step 2: Clone This Template

Open your terminal and run:

```bash
# Clone the template repository
git clone https://github.com/gulglitch/github-revamp.git [your-username]

# Example: git clone https://github.com/gulglitch/github-revamp.git john-doe

# Navigate into the folder
cd [your-username]
```

---

### Step 3: Change the Remote URL

Point your local repository to YOUR profile repository:

```bash
# Remove the template remote
git remote remove origin

# Add your profile repository as the new remote
git remote add origin https://github.com/[YOUR_USERNAME]/[YOUR_USERNAME].git

# Example: git remote add origin https://github.com/john-doe/john-doe.git

# Verify it's correct
git remote -v
```

---

### Step 4: Customize Your README

Open `README.md` and replace all placeholders with your information:

#### Required Replacements:

| Placeholder | Replace With | Example |
|------------|--------------|---------|
| `[YOUR_NAME]` | Your full name | `John Doe` |
| `[YOUR_USERNAME]` | Your GitHub username | `john-doe` |
| `[YOUR_EMAIL]` | Your email address | `john@example.com` |
| `[YOUR_LINKEDIN]` | Your LinkedIn username | `john-doe` |

#### Customize These Sections:

1. **Header Typing Animation**
   - `[YOUR_TAGLINE_1]`, `[YOUR_TAGLINE_2]`, `[YOUR_TAGLINE_3]`
   - Example: `Full-Stack Developer`, `AI/ML Enthusiast`, `Open Source Contributor`

2. **About Me Section**
   - `[YOUR_INTERESTS]` - What are you passionate about?
   - `[YOUR_CURRENT_WORK]` - What are you currently building?
   - `[YOUR_HOBBY_1]`, `[YOUR_HOBBY_2]`, `[YOUR_HOBBY_3]` - Your hobbies
   - `[INTEREST_1]`, `[INTEREST_2]`, `[INTEREST_3]` - Your technical interests

3. **Projects Section**
   - Update project names, descriptions, and repository links
   - Change emojis/icons: `[PROJECT_ICON_1]` → `🏥`, `💻`, `🎮`, etc.
   - Replace `[PROJECT_X_NAME]` and `[PROJECT_X_REPO]` with your actual projects

4. **Tech Stack**
   - Add/remove technology badges
   - Find more badges at: [shields.io](https://shields.io/) or [simple-icons](https://simpleicons.org/)
   - Format: `![Name](https://img.shields.io/badge/Name-HexColor?style=flat-square&logo=logoname&logoColor=white)`

5. **Highlights Section**
   - Update with your key achievements or focus areas

6. **Connect Section**
   - Add your social media links (Twitter, Portfolio, etc.)

7. **Quote**
   - `[YOUR_QUOTE]` - Add a personal quote or motto

#### Color Customization:

The default accent color is `D85A30` (orange). To change it:

- Find and replace `D85A30` with your preferred hex color (without `#`)
- Popular colors: 
  - Blue: `3B82F6`
  - Green: `10B981`
  - Purple: `8B5CF6`
  - Red: `EF4444`

---

### Step 5: Enable GitHub Actions

For the contribution snake animation to work:

1. Go to your profile repository on GitHub
2. Click **Settings** → **Actions** → **General**
3. Under **Workflow permissions**, select:
   - ✅ **"Read and write permissions"**
4. Click **Save**

---

### Step 6: Commit and Push

```bash
# Add all changes
git add .

# Commit with a message
git commit -m "Initial profile setup"

# Push to your profile repository
git push -u origin main
```

---

### Step 7: Trigger the Snake Animation

The snake animation will generate automatically, but you can trigger it manually:

1. Go to your repository on GitHub
2. Click **Actions** tab
3. Click **Generate Snake Animation** workflow
4. Click **Run workflow** → **Run workflow**
5. Wait ~1 minute for it to complete

---

## ✅ Verify Everything Works

1. Visit your GitHub profile: `https://github.com/[YOUR_USERNAME]`
2. Your README should now appear on your profile!
3. The contribution snake may take a few minutes to appear

---

## 🎨 Advanced Customization

### Change Stats Theme

Available themes for GitHub stats:
- `tokyonight` (default)
- `dark`, `radical`, `merko`, `gruvbox`, `dracula`, `monokai`, `vue`, `onedark`, `cobalt`, `synthwave`, `highcontrast`, `nightowl`

Replace `theme=tokyonight` in the stats URLs with your preferred theme.

### Add More Badges

Visit [shields.io](https://shields.io/) to create custom badges:

```markdown
![BadgeName](https://img.shields.io/badge/Text-HexColor?style=flat-square&logo=logoname&logoColor=white)
```

Find logo names at: [simpleicons.org](https://simpleicons.org/)

### Typing Animation Customization

Customize the typing SVG at: [readme-typing-svg.demolab.com](https://readme-typing-svg.demolab.com/)

---

## 🐛 Troubleshooting

### README doesn't appear on profile
- Verify repository name matches your username exactly (case-sensitive)
- Ensure the repository is **Public**
- README.md must be in the root directory

### Snake animation not showing
- Check if GitHub Actions workflow ran successfully (Actions tab)
- Verify workflow permissions are set to "Read and write"
- Wait up to 24 hours for first generation (or trigger manually)

### Stats cards not loading
- Replace `[YOUR_USERNAME]` with your actual GitHub username
- Check if stats API is down: [status.github.com](https://www.githubstatus.com/)

---

## 📚 Resources

- [GitHub Profile README Guide](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [Shields.io Badge Generator](https://shields.io/)
- [Simple Icons - Logo Names](https://simpleicons.org/)
- [GitHub Stats Cards](https://github.com/anuraghazra/github-readme-stats)
- [Contribution Snake Animation](https://github.com/Platane/snk)
- [Typing SVG Generator](https://readme-typing-svg.demolab.com/)

---

## 💡 Tips

- Keep it concise - profile READMEs work best when scannable
- Update regularly with new projects
- Use high-contrast colors for readability
- Test on both light and dark themes
- Pin your best repositories below the README

---

## 🤝 Contributing

Found a bug or want to add features? Feel free to:
- Open an issue
- Submit a pull request
- Fork and customize for your needs

---

## 📄 License

This template is open source and available under the MIT License. Feel free to use, modify, and share!

---

**Made with ❤️ by [gulglitch](https://github.com/gulglitch)**

*Happy coding! 🚀*
