# 💕 Valentine's Day Interactive Experience

A fun and playful Valentine's Day themed web experience for Njoki Sites!

## 🎯 Features

- **Interactive Yes/No Game**: Playful prompts that encourage users to say "Yes"
- **Beautiful Animations**: Floating hearts, pulse effects, and smooth transitions
- **Three-Page Journey**: 
  1. Valentine's proposal with Yes/No buttons
  2. Thank you page with gift claim
  3. Subscription reveal with Instagram link
- **Contact Information**: Phone number and email with clickable links
- **Portfolio Showcase**: Three video blocks to display past completed websites
- **Fully Responsive**: Works beautifully on desktop and mobile devices
- **Single File**: Everything in one HTML file for easy deployment

## 🚀 Getting Started

### Option 1: Open Locally
1. Download `index.html`
2. Double-click the file to open in your browser
3. Enjoy!

### Option 2: Deploy to GitHub Pages
1. Fork or clone this repository
2. Go to your repository Settings
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select your main branch
5. Click "Save"
6. Your site will be live at `https://yourusername.github.io/repository-name/`

### Option 3: Deploy Anywhere
Since this is a single HTML file, you can deploy it to:
- Netlify (drag and drop)
- Vercel
- Any web hosting service
- GitHub Pages

## 🎨 Customization

### Adding Your Images
Replace the placeholder div on Page 3 with your actual image:

```html
<!-- Replace this: -->
<div class="image-placeholder">
    📸 Add your image here
</div>

<!-- With this: -->
<img src="your-image.jpg" alt="Valentine's Gift" style="width: 300px; border-radius: 20px;">
```

### Update Contact Information
Change the phone number and email in the contact section:
```html
<!-- Update phone number -->
<div class="contact-item">
    📞 <a href="tel:+YOUR_PHONE_NUMBER">+YOUR_PHONE_NUMBER</a>
</div>

<!-- Update email -->
<div class="contact-item">
    📧 <a href="mailto:YOUR_EMAIL@example.com">YOUR_EMAIL@example.com</a>
</div>
```

### Add Your Video Showcases
Replace the video placeholders with actual video embeds or links:

**Option 1: YouTube Embed**
```html
<div class="video-placeholder">
    <iframe width="100%" height="200" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
            frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope" 
            allowfullscreen style="border-radius: 15px;">
    </iframe>
</div>
```

**Option 2: Video Links**
```html
<div class="video-placeholder">
    <a href="YOUR_VIDEO_URL" target="_blank">
        <img src="thumbnail.jpg" alt="Project Preview" style="width: 100%; border-radius: 15px;">
    </a>
</div>
```

Update the video titles to match your projects:
```html
<div class="video-title">Your Actual Project Name</div>
```

### Update Instagram Link
Change the Instagram handle in the link on Page 3:
```html
<a href="https://www.instagram.com/YOUR_HANDLE" target="_blank" class="instagram-link">
    📱 Follow @YOUR_HANDLE on Instagram
</a>
```

### Color Scheme
The project uses a pink Valentine's theme. You can customize colors by editing the CSS gradient values:
- Page 1: Light pink gradient
- Page 2: Soft pink gradient
- Page 3: Hot pink gradient

## 📱 Instagram Integration

The final page includes a prominent call-to-action button linking to your Instagram profile. Make sure to update the Instagram URL with your actual handle.

## 🎭 How It Works

**Page 1 - The Proposal**
- Clicking "No" shows escalating error messages
- After 3 "No" clicks, users still need to click "Yes"
- "Yes" takes them to Page 2

**Page 2 - Thank You**
- Back button shows a warning on first click
- Second click actually goes back
- Gift button proceeds to Page 3

**Page 3 - The Reveal**
- Animated welcome message
- Subscription announcement
- Image placeholder for your content
- Contact information (phone & email)
- Three video showcase blocks for past work
- Instagram follow button

## 🛠️ Technologies

- Pure HTML5
- CSS3 (Animations & Gradients)
- Vanilla JavaScript (No dependencies!)

## 📄 License

Feel free to customize and use this for your business!

## 💝 Credits

Created with love for Njoki Sites Valentine's Day campaign 2025!

---

**Happy Valentine's Day! 💕**
