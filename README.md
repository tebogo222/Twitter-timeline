# 𝕏 Timeline - Twitter UI Clone

<div align="center">

![Twitter](https://img.shields.io/badge/Twitter-Clone-1DA1F2?style=flat&logo=twitter&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

A modern, responsive Twitter-like social media timeline interface built with HTML5 and CSS3. This project replicates the core UI/UX of Twitter (X), featuring a clean three-column layout with a sidebar, main feed, and trending section.

[View Demo](#-features) • [Get Started](#-quick-start) • [Project Structure](#-project-structure)

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎨 **Modern UI Design**
- Clean, minimalist interface inspired by Twitter's design system
- Responsive three-column layout
- Smooth hover effects and transitions
- Professional color scheme with Twitter's signature blue

</td>
<td width="50%">

### 📱 **Responsive Layout**
- Sticky navigation sidebar
- Fixed header with home indicator
- Adaptive trending section
- Mobile-friendly structure

</td>
</tr>
<tr>
<td width="50%">

### 🚀 **Interactive Elements**
- Tweet compose area with textarea
- Tweet action buttons (comment, retweet, like, share)
- Trends section with dynamic content
- "Who to Follow" recommendations

</td>
<td width="50%">

### 🎯 **User Experience**
- Intuitive navigation with Font Awesome icons
- Search functionality
- Smooth visual feedback on interactions
- Professional styling throughout

</td>
</tr>
</table>

---

## 🎯 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required!

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/tebogo222/Twitter-timeline.git
cd Twitter-timeline
```

2. **Add your assets**
Create an `assets/` folder and add your profile images:
```
assets/
├── istockphoto-1318858332-612x612.jpeg
├── istockphoto-1338134336-612x612.jpeg
├── istockphoto-1407759041-612x612.jpeg
├── istockphoto-1471845315-612x612.jpeg
└── istockphoto-1437816897-612x612.webp
```

3. **Open in browser**
Simply open `index.html` in your favorite web browser!

---

## 📁 Project Structure

```
Twitter-timeline/
│
├── 📄 index.html          # Main HTML structure
├── 🎨 styles.css          # Styling and layout
├── 📸 assets/             # Profile images
│   ├── istockphoto-*.jpeg
│   └── istockphoto-*.webp
│
└── 📖 README.md           # This file
```

### File Descriptions

| File | Purpose |
|------|---------|
| `index.html` | Contains the semantic HTML structure with three main columns: sidebar, feed, and trends |
| `styles.css` | Complete styling with flexbox layout, color scheme, and responsive design |
| `assets/` | Directory for storing profile pictures and media files |

---

## 🏗️ Layout Overview

The application uses a three-column layout:

```
┌─────────────────────────────────────────────────┐
│  SIDEBAR    │    MAIN FEED    │   TRENDING      │
│  • Home     │  • Compose      │   • Search      │
│  • Explore  │  • Tweets       │   • Trends      │
│  • Notify   │  • Actions      │   • Follow      │
│  • Messages │                 │                 │
│  • Bookmark │                 │                 │
│  • Lists    │                 │                 │
│  • Profile  │                 │                 │
│  • More     │                 │                 │
│  • Tweet    │                 │                 │
└─────────────────────────────────────────────────┘
```

---

## 🎨 Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Twitter Blue | `#1DA1F2` | Primary brand color, links, buttons |
| Dark Gray | `#0F1419` | Text and primary content |
| Light Gray | `#E1E8ED` | Borders and dividers |
| White | `#FFFFFF` | Background |
| Light Blue | `#E8F5FE` | Hover states |

---

## 🚀 Features in Detail

### Sidebar Navigation
- Quick access to all major sections
- Sticky positioning for easy navigation
- Prominent "Tweet" button for composing new posts
- Font Awesome icons for visual clarity

### Main Feed
- **Tweet Compose**: Input area for creating new tweets
- **Tweet Display**: Individual tweet cards with:
  - User profile picture
  - Username and handle
  - Tweet content with hashtags
  - Tweet preview image
  - Action buttons (comment, retweet, like, share)

### Trending Section
- **Search Bar**: Quick search functionality
- **Trending Topics**: Shows trending hashtags with post counts
- **Who to Follow**: Suggested users with follow buttons
- **Show More**: Expandable content

---

## 💻 Customization

### Edit Tweets
Modify the tweet content in `index.html`:
```html
<span><strong>Your Name</strong>@YourHandle</span>
<span>Your tweet content goes here!</span>
<span>#yourhashtag</span>
```

### Change Colors
Update the color scheme in `styles.css`:
```css
/* Primary brand color */
--primary-color: #1DA1F2;

/* Text color */
--text-color: #0F1419;
```

### Add More Tweets
Duplicate the `.tweet` div and customize with your content!

---

## 🔧 Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with Flexbox layout
- **Font Awesome 5.0** - Comprehensive icon library
- **Responsive Design** - Mobile-friendly approach

---

## 📸 Screenshots

The UI includes:
- ✅ Responsive header with home indicator
- ✅ Composable tweet section
- ✅ Tweet feed with engagement metrics
- ✅ Trending topics sidebar
- ✅ User recommendations panel
- ✅ Professional color scheme

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👨‍💻 Author

**Tebogo Musi**
- GitHub: [@tebogo222](https://github.com/tebogo222)


---

## 🙏 Acknowledgments

- Inspired by Twitter/X's elegant design philosophy
- Icons from [Font Awesome](https://fontawesome.com/)
- Modern web design best practices

---

<div align="center">

### ⭐ If you like this project, please consider giving it a star!

**Made with ❤️ by Tebogo Musi**

</div>