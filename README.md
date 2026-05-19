# Marketeve Website

A static HTML website for Marketeve - an ecommerce business building and marketing agency.

## Project Structure

```
marketeve/
├── index.html          # Main homepage
├── about.html          # About us page
├── projects.html       # Projects showcase page
├── thankyou.html       # Thank you page (form submission)
├── asset/              # Images and media files
├── css/                # Stylesheets
│   └── style.css
├── js/                 # JavaScript files
│   └── index.js
├── vercel.json         # Vercel deployment configuration
├── package.json        # Project metadata
└── .gitignore          # Git ignore rules
```

## Local Development

To run this project locally:

1. Install dependencies:
```bash
npm install
```

2. Start a local server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:3000`

## Deployment to Vercel

This project is configured for Vercel deployment with the included `vercel.json` file.

### Deploy via Vercel CLI:

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

### Deploy via Vercel Dashboard:

1. Push your code to GitHub
2. Import the project in Vercel dashboard
3. Vercel will automatically detect the static site configuration from `vercel.json`
4. Deploy!

## Configuration Files

- **vercel.json**: Configures Vercel to serve this as a static site
- **package.json**: Contains project metadata and local development scripts
- **.gitignore**: Excludes node_modules and other unnecessary files from git

## Features

- Responsive design
- Smooth animations (AOS library)
- Contact form with Web3Forms integration
- Calendly booking integration
- Client testimonials slider
- Project showcase gallery
- Services and pricing sections

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- AOS (Animate On Scroll)
- Font Awesome icons
- Calendly widget
- Web3Forms (contact form handling)

## License

© 2025 Marketeve. All rights reserved.
