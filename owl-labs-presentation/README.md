# Owl Labs Presentation Style Guide

A professional presentation template built with [Reveal.js](https://revealjs.com/) for creating engaging Owl Labs presentations.

## 🦉 About

This project provides a customized Reveal.js presentation framework with Owl Labs branding, including:
- Custom color palette (Purple, Teal, Orange)
- Typography guidelines
- Flexible layout options
- Smooth transitions and animations
- Responsive design

## 🚀 Getting Started

### Prerequisites
- Node.js and npm installed
- A modern web browser
- VS Code (recommended)

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the local development server:
```bash
npm start
```

3. Open your browser to `http://localhost:8000`

## 📁 Project Structure

```
owl-labs-presentation/
├── index.html          # Main presentation file
├── css/
│   └── custom.css      # Owl Labs custom styles
├── js/
│   └── main.js         # Reveal.js configuration
├── package.json        # Project dependencies
└── README.md          # This file
```

## 🎨 Customization

### Brand Colors
The style guide uses these Owl Labs brand colors:
- **Owl Navy**: `#212c65`
- **Owl Blue**: `#1b92c8`
- **Owl Lime**: `#b4d04c`

### Adding New Slides
Edit `index.html` and add new sections within the `<div class="slides">` container:

```html
<section>
    <h2>Your Slide Title</h2>
    <p>Your content here</p>
</section>
```

### Slide Layouts
- **Title Slide**: Main heading with subtitle
- **Content Slide**: Standard text and lists
- **Two-Column**: Side-by-side content
- **Background Color**: Full-screen colored backgrounds
- **Fragments**: Progressive content reveal

## ⌨️ Keyboard Shortcuts

- **Arrow Keys / Space**: Navigate slides
- **F**: Fullscreen mode
- **S**: Speaker notes
- **O / ESC**: Overview mode
- **B**: Blank screen (pause)

## 🛠️ Development

### Local Server
The presentation uses a local HTTP server to properly load resources. You can use:

```bash
npm start
```

Or with Python:
```bash
python -m http.server 8000
```

Or with VS Code's Live Server extension.

## 📝 Tips

1. Keep slides simple and focused
2. Use high-quality images
3. Limit text per slide (max 6 bullet points)
4. Use fragments for progressive disclosure
5. Test on multiple screen sizes

## 📦 Dependencies

- [Reveal.js 5.0.4](https://revealjs.com/) - Loaded via CDN

## 🤝 Contributing

This is an internal Owl Labs style guide. For updates or suggestions, contact the design team.

## 📄 License

Internal use only - Owl Labs © 2025
