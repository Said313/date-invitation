# Date Invitation 💕

A beautiful, romantic date invitation webpage with lovely animations and transitions. Perfect for inviting your special someone on a date!

## ✨ Features

- **Beautiful Design**: Gradient backgrounds, floating hearts, and sparkles
- **Responsive**: Optimized for iPhone 15 and MacBook 14-16" screens
- **Interactive**: Yes/No buttons with delightful responses
- **Animations**: Smooth transitions, confetti celebration, and dynamic effects
- **Russian Language**: Fully translated to Russian
- **Analytics**: Button clicks logged to Google Sheets

## 🚀 Live Demo

Visit: [Your Custom Domain] (after setup)

## 📁 Project Structure

```
date-invitation/
├── index.html          # Main webpage
├── styles.css          # All styles and animations
└── README.md           # This file
```

## 🛠️ Setup Instructions

### 1. GitHub Pages Setup

1. **Push to GitHub**: Upload this project to a GitHub repository
2. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
   - Click Save

### 2. Custom Domain Setup (Namecheap)

#### Step 1: Configure GitHub Repository
1. In your repository Settings → Pages
2. Add your custom domain in "Custom domain" field
3. Check "Enforce HTTPS" (recommended)
4. Save the changes

#### Step 2: Configure Namecheap DNS
1. **Log into Namecheap** and go to Domain List
2. **Click "Manage"** next to your domain
3. **Go to "Advanced DNS"** tab
4. **Add these DNS records**:

```
Type: A Record
Host: @
Value: 185.199.108.153
TTL: Automatic

Type: A Record  
Host: @
Value: 185.199.109.153
TTL: Automatic

Type: A Record
Host: @
Value: 185.199.110.153
TTL: Automatic

Type: A Record
Host: @
Value: 185.199.111.153
TTL: Automatic

Type: CNAME Record
Host: www
Value: yourusername.github.io
TTL: Automatic
```

#### Step 3: Wait for Propagation
- DNS changes can take 24-48 hours to propagate
- You can check propagation using: https://www.whatsmydns.net/

#### Step 4: Verify Setup
- Visit your custom domain
- Check that HTTPS works (if enabled)
- Verify all features work correctly

## 🎨 Customization

### Changing Text
Edit the Russian text in `index.html`:
- Main title and message
- Button responses
- Celebration messages

### Styling
Modify `styles.css` to:
- Change colors and gradients
- Adjust animations
- Modify responsive breakpoints

### Google Sheets Integration
Update the `scriptURL` in `index.html` with your own Google Apps Script URL.

## 📱 Browser Support

- ✅ Chrome
- ✅ Safari  
- ✅ Firefox
- ✅ Edge
- ✅ Mobile browsers

## 🔧 Technical Details

- **HTML5** with semantic markup
- **CSS3** with modern features (Grid, Flexbox, Animations)
- **Vanilla JavaScript** for interactivity
- **Google Sheets API** for analytics
- **Responsive design** with mobile-first approach

## 📊 Analytics

Button clicks are logged to Google Sheets with:
- Timestamp
- Button clicked (Yes/No)
- Device information
- Browser details
- Screen dimensions

## 🤝 Contributing

Feel free to fork and customize for your own romantic invitations!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with 💕 for special moments
