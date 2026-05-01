# MsLeonuh – Link-in-Bio

A link-in-bio page for affiliate marketing, hosted on GitHub Pages.

## 🚀 How to Deploy (Free with GitHub Pages)

### Step 1 – Create a GitHub account
Go to [github.com](https://github.com) and sign up (free).

### Step 2 – Create a new repository
1. Click the **+** button → **New repository**
2. Name it exactly: `msleonuh` (or your username)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 – Upload your file
1. Click **Add file** → **Upload files**
2. Drag and drop `index.html` into the box
3. Click **Commit changes**

### Step 4 – Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose **main** branch → **/ (root)** → click **Save**
4. Wait ~60 seconds, then visit:
   `https://YOUR-GITHUB-USERNAME.github.io/msleonuh/`

---

## ✏️ How to Update Your Links

Open `index.html` in any text editor (Notepad, TextEdit, VS Code) and find the link cards. Replace the `href="#"` placeholders with your real affiliate links:

```html
<!-- Example: replace # with your real link -->
<a href="https://amzn.to/your-link" class="link-card">
```

### Pinterest link is already set:
```html
href="https://ca.pinterest.com/MsLeonuh/"
```

---

## 📋 Affiliate Disclosure

The footer already includes an affiliate disclosure statement. This is **required by law** (FTC guidelines in the US/Canada). Keep it visible.

---

## 🎨 Customization Tips

- **Change your bio:** Find `<p class="bio">` and edit the text
- **Add/remove link cards:** Copy a `<div class="link-card">` block and paste it
- **Change the avatar emoji:** Find `<div class="avatar-inner">💋</div>` and swap the emoji
- **Update your name/handle:** Find `<h1>` and `<p class="handle">`
