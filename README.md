# 🌊 TM Travel - Flotilla Sailing Website

A premium travel website showcasing flotilla sailing holidays in the Greek Islands, featuring stunning Iceland-themed imagery and modern responsive design.

## 🌐 Live Demo

**🚀 Live Website:** [https://tm-travel-website.vercel.app](https://tm-travel-website.vercel.app)

---

## ✨ Features

- **Single-Page Application** with smooth navigation
- **Fully Responsive Design** - optimized for mobile, tablet, and desktop
- **High-Quality Images** - 19 professional Iceland landscape photos
- **Modern UI/UX** with elegant animations and transitions
- **Multiple Sections:**
  - Hero landing page with call-to-action
  - Destination showcases (Lefkada, Kefalonia, Ithaca, Meganisi, Kalamos)
  - Customer testimonials
  - Sailing holiday details
  - About Us / CSR section
  - Blog article
  - FAQ section
  - Contact form

---

## 🎨 Design Highlights

- **Color Palette:** Navy blue, gold accents, elegant typography
- **Fonts:** 
  - Cormorant Garamond (headings)
  - Jost (body text)
- **Layout:** CSS Grid & Flexbox
- **Animations:** Smooth fade-in effects, hover transitions
- **Navigation:** Fixed top navbar with mobile hamburger menu

---

## 📁 Project Structure

```
TravelWebsite/
├── index.html              # Main website file
├── TM-Travel.html          # Original source file
├── images/                 # All website images (19 files)
│   ├── hero-bg.jpg
│   ├── lefkada.jpg
│   ├── kefalonia.jpg
│   ├── ithaca.jpg
│   ├── meganisi.jpg
│   ├── kalamos.jpg
│   ├── intro-couple.jpg
│   ├── products-hero.jpg
│   ├── about-hero.jpg
│   ├── blog-hero.jpg
│   ├── faq-hero.jpg
│   ├── contact-hero.jpg
│   ├── gallery-1.jpg
│   ├── gallery-2.jpg
│   ├── gallery-3.jpg
│   ├── csr-1.jpg
│   ├── csr-2.jpg
│   ├── blog-1.jpg
│   └── blog-2.jpg
├── vercel.json             # Vercel deployment config
├── .gitignore              # Git ignore rules
└── README.md               # This file
```

---

## 🚀 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties (CSS variables)
- **JavaScript** - Vanilla JS for navigation and interactions
- **Vercel** - Deployment platform
- **Git** - Version control

---

## 🛠️ Local Development

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Git installed on your machine

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Mehedi259/TravelWebsite.git
   cd TravelWebsite
   ```

2. **Open in browser:**
   Simply double-click `index.html` or use a local server:
   
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **View in browser:**
   Open `http://localhost:8000` in your browser

---

## 📦 Deployment

This project is deployed on **Vercel** for instant global CDN delivery.

### Deploy to Vercel

1. **Install Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Deploy:**
   ```bash
   vercel --prod
   ```

3. **Or use Vercel Dashboard:**
   - Go to [vercel.com/new](https://vercel.com/new)
   - Import this repository
   - Click Deploy

---

## 📱 Responsive Breakpoints

- **Mobile:** < 600px
- **Tablet:** 600px - 900px
- **Desktop:** > 900px

---

## 🖼️ Image Credits

All images sourced from [Unsplash](https://unsplash.com) - high-quality, royalty-free Iceland landscapes.

### Featured Destinations (Iceland Theme):
- **Lefkada** - Dramatic Iceland landscape
- **Kefalonia** - Iceland waterfall scenery
- **Ithaca** - Iceland mountain views
- **Meganisi** - Iceland glacier lagoon
- **Kalamos** - Iceland northern lights

---

## 🎯 Key Sections

### 1. Home Page
- Hero section with compelling copy
- Feature highlights (Small groups, Expert crew, Sustainable sailing, Authentic experience)
- Company introduction
- Destination grid showcase
- Customer testimonials

### 2. Sailing Holidays
- Detailed holiday information
- Image gallery
- Booking sidebar with key features

### 3. About Us
- Company mission and values
- CSR initiatives (4Ps framework: People, Planet, Profit, Purpose)
- Community impact images

### 4. Blog
- Featured article: "Finding Peace Between Greek Islands"
- Storytelling approach to travel experiences
- SEO-optimized content with keywords

### 5. FAQ
- Common questions answered
- Expandable accordion design
- Live chat/contact options

### 6. Contact
- Contact form with validation-ready inputs
- Business details (phone, email, address)
- Direct booking call-to-action

---

## 🔧 Customization

### Changing Colors
Edit CSS variables in the `:root` selector:
```css
:root {
  --navy: #0d1f3c;
  --gold: #c9a84c;
  --white: #ffffff;
  /* ... other colors */
}
```

### Adding New Pages
1. Create a new `<div id="page-name" class="page">` section
2. Add navigation link with `onclick="showPage('page-name')"`
3. Style as needed

### Updating Images
Replace images in the `/images` folder and update the `src` attributes in HTML.

---

## 📈 Performance

- ✅ Optimized images (compressed JPEGs)
- ✅ Minimal JavaScript (vanilla, no frameworks)
- ✅ CSS Grid for efficient layouts
- ✅ Lazy loading ready
- ✅ Mobile-first responsive design

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Mehedi259**
- GitHub: [@Mehedi259](https://github.com/Mehedi259)
- Project Link: [https://github.com/Mehedi259/TravelWebsite](https://github.com/Mehedi259/TravelWebsite)

---

## 🙏 Acknowledgments

- [Unsplash](https://unsplash.com) for beautiful free images
- [Google Fonts](https://fonts.google.com) for Cormorant Garamond & Jost typefaces
- [Vercel](https://vercel.com) for seamless deployment
- Iceland photographers for stunning landscape imagery

---

## 📞 Support

For support, email: [Your Email] or open an issue in the repository.

---

## 🌟 Show Your Support

Give a ⭐️ if you like this project!

---

**Built with ❤️ for travel enthusiasts**
