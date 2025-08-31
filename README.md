# SoanAI - 6 AI Tools Lifetime Deal Landing Page

A modern, responsive landing page for SoanAI's lifetime deal offering featuring 6 AI-powered tools.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Live Countdown Timer**: 12-minute countdown to create urgency
- **Modern UI**: Clean, professional design with smooth animations
- **6 AI Tools Showcase**: 
  - AI Domain Checker
  - Gmail Cleaner
  - PDF Converter
  - Instagram Tool
  - Baby Budget Lite
  - Credit / Loan Checker

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)
- SVG Icons

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. The landing page will load automatically

### Running Locally

Simply double-click the `index.html` file or open it in your preferred web browser.

For development, you can also use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Project Structure

```
landing-page/
├── index.html          # Main landing page
├── README.md           # Project documentation
└── .gitignore          # Git ignore file
```

## Customization

### Colors
The color scheme is defined using CSS custom properties in the `:root` selector:

```css
:root {
    --bg-gradient-start: #E6F0FF;
    --bg-gradient-end: #F8FAFD;
    --blue-cta: #4285F4;
    --blue-cta-hover: #357ae8;
    /* ... other colors */
}
```

### Timer Duration
To change the countdown duration, modify the `timeInSeconds` variable in the JavaScript section:

```javascript
let timeInSeconds = 12 * 60; // Change 12 to your desired minutes
```

### Content
Update the tool cards, headlines, and descriptions in the HTML to match your specific offerings.

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License

This project is proprietary to SoanAI.

## Contact

For questions or support, please contact the SoanAI team.

---

Built with ❤️ by SoanAI 