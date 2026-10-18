# 🚀 How to Apply Your Custom GitHub Profile

To make this custom profile appear on your GitHub page (`https://github.com/Sanji4126`), follow these quick steps:

---

## 1. Create the Special GitHub Profile Repository
GitHub has a special feature where creating a repository with the exact same name as your GitHub username displays its `README.md` right on your profile page.

1. Go to [https://github.com/new](https://github.com/new).
2. Set **Repository name** to: `Sanji4126`
   *(GitHub will show: "You found a secret! Sanji4126/Sanji4126 is a ✨special✨ repository...")*
3. Make sure it is set to **Public** (Private repositories will not show on your public profile).
4. Leave **"Add a README file" unchecked** (you already have your custom files locally).
5. Click **Create repository**.

---

## 2. Push Your Files
In your local folder `D:\github-customize`, open PowerShell and run:

```bash
# Link to your new repository
git remote set-url origin https://github.com/Sanji4126/Sanji4126.git

# Push to GitHub
git push -u origin main
```

*(Alternatively, you can open your newly created `Sanji4126` repository in your web browser, click **Add file > Upload files**, drag `README.md`, `banner.png`, and `banner-alt.png`, and click **Commit changes**).*

---

## 3. Choose Your Preferred Banner
Two custom One Piece Sanji banners have been generated for you:
* `banner.png`: Dark moody anime theme with Sanji & centered typography **"PILA backend engineer"** *(Recommended & active by default)*.
* `banner-alt.png`: Action aesthetic theme with Sanji's Ifrit Jambe kick & centered typography **"PILA the developer"**.

To switch to the alternative banner anytime, simply update line 3 of `README.md`:
```markdown
<img src="./banner-alt.png" alt="PILA - Developer" width="100%" />
```

---

## 4. GitHub Sidebar & Bio Setup (for Backend Internships)
To complete the look matching your reference sample:

1. Go to your GitHub profile: [https://github.com/Sanji4126](https://github.com/Sanji4126)
2. Click **Edit profile** on the left sidebar:
   * **Name**: `KHORN PILA`
   * **Bio**: `Aspiring Web Backend Engineer | PHP Laravel • C# • JavaScript • MySQL • MongoDB`
   * **Pronouns**: (Optional)
   * **Location**: `Phnom Penh`
   * **Email**: `khornpila23@gmail.com`
   * **Social links / Website**: Your LinkedIn or portfolio link
3. **Pin Repositories**:
   * Scroll down to **Pinned** and click **Customize your pins**.
   * Pin 3 to 6 of your backend repositories (e.g. Laravel REST API, C# .NET microservice, etc.).
   * Ensure each pinned repo has a clear description and backend topic tags (e.g. `laravel`, `php`, `csharp`, `mysql`, `rest-api`).
