## 🌸 Contributing to Anime-Ecstasy

Thank you for showing interest in contributing to **Anime-Ecstasy**! We welcome all contributions, whether it's fixing bugs, adding new features, or improving the existing UI and logic.

Please follow the instructions below to contribute effectively.


## 📌 Workflow: Fork → Fix → PR to `test` → Merge to `deploy`

1. Fork the Repository
   Click the **Fork** button at the top-right corner of this repository.

2. **Clone Your Fork**

   ```bash
   git clone https://github.com/YOUR-USERNAME/Anime-Ecstasy.git
   cd Anime-Ecstasy
   ```

3. **Add the Upstream Remote**

   ```bash
   git remote add upstream https://github.com/Anime-Ecstasy/Anime-Ecstasy.git
   ```

4. **Create a New Branch from `deploy`**
   Make sure you're working on the latest version of the `deploy` branch.

   ```bash
   git checkout deploy
   git pull upstream deploy
   git checkout -b your-branch-name
   ```

5. **Make Your Changes**

   * Fix the issue or add the feature.
   * Commit your changes with a clear message.

   ```bash
   git add .
   git commit -m "Fix: Fixed broken navbar UI on mobile"
   ```

6. **Push to Your Fork**

   ```bash
   git push origin your-branch-name
   ```

7. **Create a Pull Request to the `test` Branch**

   * Go to your fork on GitHub.
   * Click **"Compare & pull request"**.
   * Ensure the base branch is `test`, not `deploy`.
   * Follow the pull request format given below.

---

## 🌸 contributers can raise the issues

## 🪤 Issue Types and Format

When raising an issue, please follow the correct format and type:

### ✅ Allowed Issue Types

| Type          | Description                         |
| ------------- | ----------------------------------- |
| `Bug`         | Broken logic or UI                  |
| `Feature`     | New functionality from scratch      |
| `Enhancement` | Improvement in existing logic or UI |

### 📝 Issue Format

```markdown
**Title:** [Bug/Feature/Enhancement]: Short description

**Description:**
A detailed description of the problem or the feature/enhancement you'd like to work on.

**Screenshots (if applicable):**
(Attach relevant images)

**Would you like to work on this issue?**
Yes/No
```

---

## 🚀 Pull Request Format

Please use the following PR template when raising a pull request:

```markdown
## 📌 Related Issue
Fixes #[Issue Number]

## 🧠 Type of Change
- [ ] Bug fix 🐛
- [ ] New feature ✨
- [ ] Enhancement 💡

## 💡 Description
Describe the change you have made clearly and concisely.

## ✅ Checklist
- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings

## 📸 Screenshots (if applicable)
(Insert screenshots here)
```

---

## 🔁 Deployment

Once your PR is merged into the `test` branch and verified, the maintainers will handle merging into the `deploy` branch for production deployment.

---

## 💬 Need Help?

If you have any doubts, feel free to open a discussion or ask your query in the project’s communication channel.

Happy contributing! 💖
**Team Anime-Ecstasy**

