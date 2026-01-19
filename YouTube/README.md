# YouTube Clone

A responsive YouTube clone built with HTML and CSS, featuring a clean and modern UI that replicates the core visual design of YouTube's homepage.

## 🎯 Features

- **Responsive Header**
  - YouTube logo with hamburger menu
  - Search bar with search button
  - Voice search icon
  - Create/Upload button
  - YouTube Apps icon
  - Notifications with count badge
  - User profile picture

- **Navigation Sidebar**
  - Home
  - Explore
  - Subscriptions
  - Originals
  - YouTube Music
  - Library

- **Video Grid Layout**
  - 12 video cards with thumbnails
  - Video duration overlay
  - Channel profile pictures
  - Video titles
  - Channel names (authors)
  - View counts and upload dates

- **Interactive Elements**
  - Tooltips on hover for header icons
  - Hover effects on interactive elements

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox and grid
- **Google Fonts (Roboto)** - Typography

## 📁 Project Structure

```
YouTube/
│
├── index.html          # Main HTML file
├── README.md          # Project documentation
│
├── images/            # All image assets
│   ├── thumbnails/    # Video thumbnail images (thumbnail-1.webp to thumbnail-12.webp)
│   ├── channels/      # Channel profile pictures (channel-1.jpeg to channel-12.jpeg)
│   ├── icons/         # SVG icons (hamburger-menu, search, notifications, etc.)
│   └── profile_picture.jpg
│
└── styles/            # CSS stylesheets
    ├── general.css    # Global styles and resets
    ├── header.css     # Header component styles
    ├── main.css       # Main content and video grid styles
    └── sidebar.css    # Sidebar navigation styles
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, but recommended)

### Installation

1. Clone or download this repository
2. Open the project folder

### Running the Project

**Option 1: Direct File Opening**
- Simply open `index.html` in your web browser

**Option 2: Using a Local Server (Recommended)**

Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Using Node.js (http-server):
```bash
npx http-server
```

Then open your browser and navigate to `http://localhost:8000`

## 📝 File Descriptions

- **index.html** - Main HTML structure containing header, sidebar, and video grid
- **styles/general.css** - Base styles, resets, and global typography
- **styles/header.css** - Header layout, search bar, and navigation icons
- **styles/main.css** - Video grid layout and video card styling
- **styles/sidebar.css** - Sidebar navigation menu styles

## 🎨 Design Features

- Clean and modern UI design
- Responsive layout structure
- Hover tooltips for better user experience
- Professional typography using Roboto font
- Grid-based video layout
- Consistent spacing and alignment

## 📸 Preview

Open `index.html` in your browser to see the YouTube clone in action!

## 🔮 Future Enhancements

Potential improvements for this project:
- Add JavaScript functionality for interactivity
- Implement responsive design for mobile devices
- Add video player functionality
- Connect to YouTube API for real video data
- Add user authentication
- Implement search functionality
- Add video categories and filtering

## 📄 License

This project is for educational purposes only.

## 👤 Author

Built as a learning project to practice HTML and CSS skills.

---

**Note:** This is a front-end clone focusing on visual design and layout. It does not include backend functionality or actual video playback.

