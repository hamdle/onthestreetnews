# OTSN Landing Page - Build Plan

## Project Overview
Single-page landing site for onthestreetnews.com
- Purpose: Central link hub for all social media platforms
- Hosting: GitHub Pages
- Tech: HTML + CSS (no JavaScript required)

## Design Concept
Clean, minimal link-in-bio style page with OTSN branding
- Mobile-first responsive design
- Bold red and white color scheme
- Centered vertical layout
- Social media link buttons

## Color Palette
- **Primary Red**: #ED1C24 (extracted from logo)
- **White**: #FFFFFF
- **Background**: White
- **Accents**: Red for buttons and highlights

## Content Structure

### 1. Header Section
- OTSN logo (square, centered)
- Logo size: 200px × 200px on desktop, 150px × 150px on mobile

### 2. Tagline Section
- Text: "Real streets, 8 bits of truth."
- Subtext: "New episodes monthly."
- Typography: Bold, clean sans-serif
- Color: Dark gray/black on white background

### 3. Social Links Section
Three buttons linking to:
- **YouTube** - [Placeholder URL]
- **TikTok** - [Placeholder URL]
- **Instagram** - [Placeholder URL]

Button style:
- White background with red border
- Red text
- Hover state: Red background with white text
- Rounded corners (8px)
- Icon + platform name

## File Structure
```
website/
├── index.html           # Main landing page
├── style.css            # Stylesheet
├── images/
│   └── logo.png        # Copy of logo_square_full_solid_v01.png
└── WEBSITE_PLAN.md     # This file
```

## Typography
- **Primary Font**: System font stack (Arial, Helvetica, sans-serif)
- **Heading Size**: 24px - 32px
- **Body Size**: 16px - 18px
- **Button Text**: 18px - 20px, bold

## Layout Specifications

### Desktop (>768px)
- Max width: 600px
- Centered container
- Logo: 200px
- Button width: 400px
- Vertical spacing: 40px between sections

### Mobile (<768px)
- Full width with 20px padding
- Logo: 150px
- Button width: 100% (max 350px)
- Vertical spacing: 30px between sections

## Button Specifications
- Height: 60px
- Border: 2px solid red
- Border radius: 8px
- Font weight: Bold
- Transition: 0.3s ease for hover effects
- Margin: 12px between buttons

## Implementation Notes
1. Copy logo from `/home/otsn/Production/branding/final/logo_square_full_solid_v01.png` to `website/images/logo.png`
2. Use semantic HTML5 elements
3. Mobile-responsive using CSS media queries
4. Accessible markup (alt text, ARIA labels where needed)
5. Fast loading (minimal assets, optimized images)

## Social Media Placeholders
Update these URLs in index.html when ready:
- YouTube: `https://youtube.com/@CHANNEL_NAME`
- TikTok: `https://tiktok.com/@CHANNEL_NAME`
- Instagram: `https://instagram.com/CHANNEL_NAME`

## Future Enhancements (Optional)
- Add favicon (use logo)
- Add meta tags for social sharing (Open Graph)
- Add simple footer with copyright
- Consider adding email signup form
- Add analytics tracking code

## Testing Checklist
- [ ] Renders correctly on mobile (iOS Safari, Android Chrome)
- [ ] Renders correctly on desktop (Chrome, Firefox, Safari, Edge)
- [ ] All links work and open in new tabs
- [ ] Logo displays correctly
- [ ] Hover states work on buttons
- [ ] Page loads quickly
- [ ] Works on GitHub Pages deployment
