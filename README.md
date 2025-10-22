# RetreatsBooking.com - Landing Page

A modern, high-conversion landing page for a retreat booking platform that connects retreat seekers with retreat providers.

## Overview

This landing page is designed to attract and convert two key user groups:
1. **Retreat Seekers** - People looking to find and book transformational retreat experiences
2. **Retreat Providers** - Organizations and individuals offering retreat programs

## Features

### Design & User Experience
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Modern Aesthetic**: Clean, trustworthy design inspired by Booking.com
- **Indigo Brand Identity**: Primary color scheme using #4f46e5 (Indigo)
- **Smooth Interactions**: Animated elements and smooth scrolling navigation

### Sections

1. **Header & Navigation**
   - Fixed header with smooth scrolling navigation
   - Mobile-responsive hamburger menu
   - Brand logo and quick access to all sections

2. **Hero Section**
   - Compelling headline: "Find Your Perfect Retreat"
   - Dual CTAs: "Browse Retreats" and "List Your Retreat"
   - Eye-catching gradient background with imagery

3. **For Retreat Seekers**
   - Highlights platform benefits for users
   - Features: Search & Compare, Verified Reviews, Secure Booking
   - Visual representation with relevant imagery

4. **For Retreat Providers**
   - Showcases business growth opportunities
   - Benefits: Targeted Audience, Easy Management, Business Growth
   - Clear call-to-action for listing retreats

5. **The Power of Retreats**
   - Educational section with 4 key benefits:
     - Reconnect with Yourself
     - Join a Like-Minded Community
     - Deepen Your Practice
     - Digital Detox
   - Gradient purple background for visual impact

6. **Community Sign-up**
   - Email capture form for newsletter/updates
   - Form validation (checks for empty field and valid email format)
   - Success/error messaging
   - JavaScript alert on successful submission

7. **Footer**
   - Company information
   - Navigation links
   - Copyright notice

### Technical Implementation

- **Single HTML File**: All code (HTML, CSS, JavaScript) in one file
- **No Dependencies**: Pure vanilla JavaScript, no frameworks required
- **Semantic HTML5**: Proper use of semantic elements for accessibility
- **CSS Variables**: Easy color scheme customization
- **Mobile-First Approach**: Responsive breakpoints at 768px and 480px

### Interactivity

1. **Smooth Scrolling**: Navigation links scroll smoothly to sections
2. **Mobile Menu**: Toggle navigation menu on mobile devices
3. **Form Validation**:
   - Checks for non-empty email field
   - Validates email format (contains @ and proper structure)
   - Displays success/error messages
   - Shows browser alert on successful submission
4. **Hover Effects**: Interactive buttons and cards with transitions
5. **Scroll Effects**: Header shadow appears on scroll

## Usage

Simply open `index.html` in any modern web browser. No build process or server required.

### Viewing the Page

```bash
# Option 1: Direct file open
open index.html

# Option 2: Simple HTTP server (Python 3)
python -m http.server 8000

# Option 3: Simple HTTP server (Node.js)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Colors
Edit CSS variables in the `:root` selector (line 55-63):
```css
:root {
    --primary-indigo: #4f46e5;
    --primary-indigo-dark: #4338ca;
    --primary-indigo-light: #6366f1;
    /* ... other variables ... */
}
```

### Images
Replace placeholder images from picsum.photos with your own:
- Hero background: Line 223
- Seeker section: Line 480
- Provider section: Line 502

### Content
All text content is easily editable within the HTML structure. Search for section IDs:
- `#home` - Hero section
- `#seekers` - For Seekers section
- `#providers` - For Providers section
- `#benefits` - Benefits section
- `#community` - Community sign-up section

## Future Enhancements

- Backend integration for email sign-ups
- Actual retreat search and booking functionality
- User authentication system
- Provider dashboard for managing listings
- Advanced filtering and search capabilities
- Multi-language support
- Integration with payment gateways

## License

Copyright © 2025 RetreatsBooking.com. All rights reserved.

## Contact

For questions or feedback about this landing page, please contact the development team.
