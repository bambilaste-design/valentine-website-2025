# 💝 Valentine's Day Website 2026 💝

[![Stars](https://img.shields.io/github/stars/End2EndAI/valentine-website-2025?style=social)](https://github.com/End2EndAI/valentine-website-2025/stargazers)
[![Fork](https://img.shields.io/github/forks/End2EndAI/valentine-website-2025?style=social)](https://github.com/End2EndAI/valentine-website-2025/fork)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Support me](https://img.shields.io/badge/Support-Stripe-blue)](https://buy.stripe.com/bJefZa8Le7fvgDe3ric7u00)

A beautiful, interactive Valentine's Day website generator to ask your special someone to be your Valentine! Create your own personalized version in minutes. Perfect for Valentine's Day 2026! 💝
Follow below the tutorial how to custom the website and get your custom URL and access your website on the internet from everywhere !

🌟 **[Live Demo](https://end2endai.github.io/valentine-website-2025)** | 🚀 **[Quick Start](#-quick-start-guide)** | 🌐 **[Deploy Your Website](#4-make-it-live-get-your-online-website-url)**

## 🌟 Share The Love

If you liked it, please :
- ⭐ Star this repository if you like it
- 🔄 Fork it to create your own version
- 🔥 Like and follow on instagram for more websites : [Instagram](https://www.instagram.com/reel/DFh3ZaxtrYX/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==)

## ✨ Features
- 💖 Floating hearts and bears
- 🎵 Custom music
- 📏 Love meter that goes beyond 100%
- 🏃‍♂️ Playful buttons that run away
- 🎁 Hidden answer for the first question, "Do you like me?"
- 🎉 Grand celebration when they say yes!

## 🚀 Quick Start Guide

### 1. Get Your Own Copy
1. Click the "Fork" button at the top right of this page or [click here](https://github.com/End2EndAI/valentine-website-2025/fork)
2. Wait a few seconds while GitHub creates your copy
3. You now have your own version of the code!

Note: Make sure you're logged into your GitHub account. If you don't have one, you can [create a free account here](https://github.com/signup).

### 2. Customize for Your Valentine

#### Easy Way (Recommended)
1. In your new repository, click on `config.js`
2. Click the pencil icon (✏️) to edit
3. Change the values to personalize your website
4. Click "Commit changes" at the bottom

Here's what you can customize in `config.js`:
```javascript
// Basic Information
valentineName: "Irene"                    // Your Valentine's name
pageTitle: "i love you. 🤍" // Browser tab title

// Floating Background Elements
floatingEmojis: {
    hearts: ['❤️', '💖', '💝', '💗', '💓'],  // Heart emojis in background
    bears: ['🧸', '🐻']                       // Bear emojis in background
}

// Questions and Buttons
questions: {
    first: {
        text: "Do you like me?",                   // First question
        yesBtn: "Yes",                             // Yes button text
        noBtn: "No",                               // No button text
        secretAnswer: "I don't like you, I love you! ❤️"  // Hidden message
    },
    second: {
        text: "How much do you love me?",          // Second question
        startText: "This much!",                   // Text before percentage
        nextBtn: "Next ❤️"                         // Next button text
    },
    third: {
        text: "be mine forever my beautiful angel irene.",      // Final question
        yesBtn: "Yes!",                            // Yes button text
        noBtn: "No"                                // No button text
    }
}

// Love Meter Messages
loveMessages: {
    extreme: "you really love me that much huuh? i love you alot more though.",  // Shows above 5000%
    high: "youre so sweet loving me that much heh.",              // Shows above 1000%
    normal: "i beliebe you love me more than that."                           // Shows above 100%
}

// Final Celebration
celebration: {
    title: "i mus treally be the luckiest boy in the world habing you.",     // Celebration title
    message: "hi my sweetheart, i know these days have been hard for you but i want you to remember im always here for you. you might feel shitty ans selfish for not giving me as much love or focusing on me these days but trust me, im fine with it im used to it anyway, i understand that youre struggling nowadays and i want you to know that youre not alone in this, im here for you my beautiful princess. evem whwn things get hard for me as well, i want to take care of you first, making sure youre okay before me, and why you may think? because i love you more than myself, i dont want myself well first i want you to heal faster than me, thats why i want you to communicate with me and tell whatever happens to you oksy my sweetie? i hope you get a charger soon so we can talk more ans what happened these days, i love you so so much my cutest irene, youre the best thing thst could ever happen to me trust me ans you deserve my love so much. you genuinely deserve all the love in the world, you have went through so so much these months i genuinely wish i could just, stop it somehow because jesus you deserbe the whole world and ill make sure tou get all that love. youre genuinely my entire universe my darling and i love you so much
",          // Celebration message
    emojis: "🤍🎶🩷🖤🌸🥀"                        // Celebration emojis
}

// Website Colors
colors: {
    backgroundStart: "#ffafbd",      // Background gradient start
    backgroundEnd: "#ffc3a0",        // Background gradient end
    buttonBackground: "#ff6b6b",     // Button color
    buttonHover: "#ff8787",          // Button hover color
    textColor: "#ff4757"            // Text color
}

// Animation Settings
animations: {
    floatDuration: "15s",           // How long hearts float (10-20s)
    floatDistance: "50px",          // Sideways movement (30-70px)
    bounceSpeed: "0.5s",            // Bounce animation speed (0.3-0.7s)
    heartExplosionSize: 1.5         // Final heart explosion size (1.2-2.0)
}

// Music Settings
music: {
    enabled: true, // Music feature is enabled
    autoplay: true, // Try to autoplay (note: some browsers may block this)
    musicUrl: "YOUR_CLOUDINARY_URL_HERE", // Paste your music URL here
    startText: "🎵 Play Music", // Button text to start music
    stopText: "🔇 Stop Music", // Button text to stop music
    volume: 0.5 // Volume level (0.0 to 1.0)
}
```

### 3. Adding Your Own Background Music 🎵

Want to make it extra special with your own romantic song? Follow these steps to add background music:

1. **Get a Cloudinary Account (Free):**
   - Go to [Cloudinary.com](https://cloudinary.com) and sign up for a free account

2. **Upload Your Music:**
   - Log in to your Cloudinary dashboard
   - Click on the "Upload" button in the top right
   - Select "Upload" from the dropdown menu
   - Choose your MP3 file (keep it under 10MB for better loading)
   - Wait for the upload to complete

3. **Get Your Music URL:**
   - After upload, find your music file in the Media Library
   - Click the "..." (more options) button on your music file
   - Click "Copy URL"
   - Select "Copy Original URL with options"
   - The URL should look like: `https://res.cloudinary.com/your-cloud-name/video/upload/v1234567890/your-file-name.mp3`

4. **Add to Your Website:**
   - Open `config.js`
   - Find the `music` section
   - Replace the `musicUrl` value with your Cloudinary URL

```javascript
music: {
    enabled: true,
    autoplay: true,
    musicUrl: "YOUR_CLOUDINARY_URL_HERE", // [https://player.cloudinary.com/embed/?cloud_name=dwtcbjwlo&public_id=KARMA_Alien_Stage_mf1a39]
    startText: "🎵 Play Music",
    stopText: "🔇 Stop Music",
    volume: 0.5
}
```

### 4. Make It Live! (Get your online website URL)

#### Using GitHub Pages (Free)
1. Go to your repository's "Settings"
2. Click "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait a few minutes
6. Your site will be live at: `https://your-username.github.io/repository-name`

#### Using Netlify (Free, Recommended, Custom URL)
1. Go to [Netlify](https://www.netlify.com/)
2. Sign up for a free account
3. Click "Add new site" → "Import an existing project"
4. Choose your GitHub repository
5. Click "Deploy site"
6. Once deployed, click "Domain settings"
7. Choose a custom domain (e.g., `my-valentine-2025.netlify.app`)

## 💡 Tips
- Test the website before sending it to your Valentine
- Try all the buttons and interactions
- Check how it looks on mobile phones

## 🎨 Want Different Colors?
Use these tools to find beautiful colors:
- [Coolors](https://coolors.co/) - Color palette generator
- [ColorHunt](https://colorhunt.co/) - Color palettes

## 🔍 Need More Emojis?
Find more emojis at:
- [EmojiKeyboard](https://emojikeyboard.top/fr/)
- [Emojipedia](https://emojipedia.org/)

## 💖 Credits
Created with love for Valentine's Day 2026.
Feel free to use and modify for your special someone!

\- Louis Fontaine -

## ❤️ Support this project

This Valentine website template is completely **free and open-source**.

If it helped you create something special, you can support the project with a small donation:

👉 [Tip](https://buy.stripe.com/bJefZa8Le7fvgDe3ric7u00)

Thank you for keeping it alive!

## 📜 License
MIT License - Feel free to use this for your Valentine! 
