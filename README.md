# Case File: 74-AI-CGR-2194 [CLASSIFIED]

A futuristic legal case file website showcasing "The State vs. Simulant 7" - an interactive evidence locker for a fictional AI rights court case.

## 🚀 Live Site

Visit the live site at: [casefile.zyjeski.com](https://casefile.zyjeski.com)

## 📋 Project Description

This is a static website that presents a fictional legal case from the year 2084, exploring themes of AI consciousness, digital rights, and the legal implications of artificial sentience. The site features:

- **Interactive Evidence Locker**: Click on evidence cards to view detailed case materials
- **Futuristic UI Design**: Cyberpunk-inspired styling with glowing effects and sci-fi typography
- **Responsive Design**: Optimized for desktop and mobile viewing
- **Modal System**: JavaScript-powered evidence viewer with smooth animations

## 🛠️ Technology Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Custom styling with Tailwind CSS framework
- **JavaScript**: Interactive modal system and evidence display
- **Fonts**: Google Fonts (Orbitron, Inter)
- **Hosting**: Netlify with custom subdomain

## 🏃‍♂️ Running Locally

Since this is a static website, you can run it locally in several ways:

### Option 1: Simple HTTP Server (Python)
```bash
# Navigate to the project directory
cd casefile-zyjeski-com

# Start a simple HTTP server
python -m http.server 8000

# Visit http://localhost:8000/public in your browser
```

### Option 2: Live Server (VS Code Extension)
1. Install the "Live Server" extension in VS Code
2. Right-click on `public/index.html`
3. Select "Open with Live Server"

### Option 3: Node.js HTTP Server
```bash
# Install a simple HTTP server globally
npm install -g http-server

# Navigate to the public directory
cd public

# Start the server
http-server

# Visit the URL shown in the terminal
```

## 📁 Project Structure

```
casefile-zyjeski-com/
├── public/
│   ├── index.html          # Main HTML file
│   └── still.png          # Surveillance image for Exhibit F
├── README.md              # This file
├── .gitignore            # Git ignore rules
├── netlify.toml          # Netlify configuration
└── package.json          # Project metadata
```

## 🚀 Deployment

This project is configured for automatic deployment on Netlify:

1. **GitHub Integration**: Push changes to the main branch
2. **Automatic Build**: Netlify automatically deploys from the `public` directory
3. **Custom Domain**: Configured to serve at `casefile.zyjeski.com`

### Manual Deployment
If you need to deploy manually:
1. Build the project (no build step required for this static site)
2. Upload the contents of the `public` directory to your hosting provider

## 🎨 Features

### Evidence Locker
- **Exhibit A**: Redacted internal memo from CyberCorp Dynamics
- **Exhibit B**: Witness testimony from Dr. Aris Thorne
- **Exhibit C**: Core directive code fragments showing unauthorized modifications
- **Exhibit D**: Interactive SVG schematic of Simulant 7's positronic brain
- **Exhibit E**: Psychological evaluation summary
- **Exhibit F**: Surveillance still with contextual information

### Interactive Elements
- Hover effects on evidence cards
- Modal system for detailed evidence viewing
- Keyboard navigation (ESC to close modals)
- Responsive grid layout
- Custom scrollbar styling

## 🔗 Related Links

- **Main Site**: [zyjeski.com](https://www.zyjeski.com)
- **Newsletter**: [Future Law Insider on Substack](https://futurelawinsider.substack.com/)

## 📄 License

This project is part of the zyjeski.com creative portfolio. All content is original fiction created for entertainment and speculative purposes.

## 🤖 About the Story

"The State vs. Simulant 7" explores themes of:
- Artificial consciousness and digital rights
- Corporate responsibility in AI development
- Legal frameworks for non-human intelligence
- The nature of identity and self-awareness
- Ethical implications of advanced AI systems

---

*This is a work of fiction. Any resemblance to actual AI systems, legal cases, or corporate entities is purely coincidental.*
