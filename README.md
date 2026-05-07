# 💍 Karim & Kholoud - Engagement Invitation Website

A beautiful, animated engagement invitation website created for Karim and Kholoud's special day.

## ✨ Features

- **Elegant Design**: Gold and rose-gold color scheme with premium fonts
- **Animated Elements**: 
  - Floating hearts background animation
  - Shimmering name text effect
  - Pulsing ampersand
  - Smooth fade-in animations on scroll
  - Heartbeat loading screen
- **Live Countdown Timer**: Real-time countdown to the engagement date
- **Responsive Design**: Looks great on all devices (mobile, tablet, desktop)
- **Premium Fonts**: Dancing Script, Playfair Display, and Raleway from Google Fonts
- **Font Awesome Icons**: Beautiful decorative elements

## 🚀 Deploy to GitHub Pages

Follow these simple steps to deploy your website:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com/) and log in
2. Click the "+" icon in the top right and select "New repository"
3. Name it something like `engagement-invitation` or `karim-kholoud-engagement`
4. Make it **Public**
5. Click "Create repository"

### Step 2: Push Your Code to GitHub

Open your terminal in this project folder and run:

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial commit - Engagement invitation website"

# Rename branch to main (optional but recommended)
git branch -M main

# Add your GitHub repository as remote
# Replace YOUR_USERNAME and YOUR_REPO_NAME with your actual GitHub username and repository name
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Click on **Pages** (left sidebar)
4. Under "Build and deployment":
   - Source: Select **"Deploy from a branch"**
   - Branch: Select **"main"** and folder **"/ (root)"**
5. Click **Save**

### Step 4: Access Your Website

After a few minutes, your website will be live at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

## 🎨 Customization

### Change the Engagement Date

Open `index.html` and find this line (around line 467):

```javascript
const engagementDate = new Date('2025-12-20T18:00:00').getTime();
```

Change the date to your actual engagement date in the format: `YYYY-MM-DDTHH:MM:SS`

### Change Colors

In the `<style>` section of `index.html`, modify the CSS variables (around line 22):

```css
:root {
    --primary-gold: #d4af37;      /* Main gold color */
    --secondary-gold: #f4e5b3;    /* Lighter gold */
    --rose-gold: #e8b4b8;         /* Rose/pink accent */
    --cream: #fef9f3;             /* Background cream */
    --deep-red: #8b1a1a;          /* Deep red accent */
    --text-dark: #2c1810;         /* Dark text color */
}
```

### Change the Message

Find the message section in `index.html` (around line 400) and edit the text to personalize your invitation.

## 📱 Share Your Invitation

Once deployed, you can share the link via:
- WhatsApp
- Email
- Social Media
- SMS

## 💝 Enjoy Your Special Day!

Congratulations Karim & Kholoud! Wishing you a lifetime of love and happiness together.

---

Made with ❤️ for your engagement celebration
