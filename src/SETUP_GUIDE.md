# VIVEK.PORTFOLIO - React Portfolio Setup Guide

## Project Structure

This project has been converted to a modern React + TypeScript + Tailwind CSS portfolio.

### Folder Structure
```
VIVEK.PORTFOLIO/
├── src/
│   ├── components/
│   │   ├── Navigation.tsx
│   │   ├── Hero.tsx
│   │   ├── About.tsx
│   │   ├── Projects.tsx
│   │   ├── Skills.tsx
│   │   ├── Contact.tsx
│   │   └── Footer.tsx
│   ├── data/
│   │   └── portfolio.ts
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── public/
├── index.html
├── vite.config.ts
├── tailwind.config.ts
├── postcss.config.js
├── tsconfig.json
├── package.json
└── README.md
```

## Files Needed to Create

### 1. Component Files (src/components/)
- Navigation.tsx
- Hero.tsx
- About.tsx
- Projects.tsx
- Skills.tsx
- Contact.tsx
- Footer.tsx

### 2. Data Files (src/data/)
- portfolio.ts (contains all portfolio data)

### 3. Core Files (src/)
- main.tsx (React entry point)
- index.css (global styles)

### 4. Configuration Files (root)
- vite.config.ts
- tailwind.config.ts
- postcss.config.js
- tsconfig.json
- tsconfig.app.json
- tsconfig.node.json
- index.html

## Installation Steps

1. Clone the repository
2. Install dependencies: `npm install` or `yarn install` or `bun install`
3. Run development server: `npm run dev`
4. Build for production: `npm run build`

## Technology Stack

- React 18.2.0
- TypeScript 5.0
- Vite 4.3.0
- Tailwind CSS 3.3.0
- Lucide React Icons 0.263.1

## Design System

- **Color Scheme**: Dark theme with amber/gold accents
  - Primary: Black (#000000)
  - Accent: Amber (#FFC107)
  - Text: White & Gray
  
- **Typography**:
  - Headings: Serif font (font-serif)
  - Body: Sans-serif (default)
  
- **Components**:
  - Navigation: Fixed header with smooth scroll detection
  - Hero: Large intro section with CTAs
  - About: Bio with highlights
  - Projects: Grid layout with project cards
  - Skills: Badge-style skill tags
  - Contact: Form and contact info
  - Footer: Links and social media

## Customization

Edit `src/data/portfolio.ts` to update:
- Personal information
- Project details
- Skills list
- Contact information
- Social links

## Next Steps

All component files and configuration files need to be created as per the structure above. 
Refer to the demox11 repository for reference implementations.
