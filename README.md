# Total Compensation Calculator

A static web application to compare job offers with all compensation dimensions including base salary, stocks, bonuses, benefits, and more.

## Features

- 💰 **Comprehensive Compensation Analysis**: Track base salary, stock grants, signing bonuses, annual bonuses, medical benefits, other benefits, and relocation assistance
- 📊 **Side-by-Side Comparison**: Compare multiple job offers in an easy-to-read comparison table
- 🏆 **Best Offer Highlighting**: Automatically highlights the best values in green with a "BEST" badge
- 📱 **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- 🎨 **Modern UI**: Clean, professional interface with gradient backgrounds and smooth animations
- 💾 **No Backend Required**: Fully static page - no server or database needed

## How to Use

1. **Open the Application**: Simply open `index.html` in any modern web browser
2. **Add Offers**: Click "+ Add Job Offer" to create comparison cards for each job offer
3. **Enter Details**: Fill in all compensation components:
   - Company name and position
   - Base salary (annual or monthly)
   - Stock value (total grant amount)
   - Vesting period (how many years stocks vest over)
   - Signing bonus (one-time)
   - Annual bonus (yearly)
   - Medical benefits (annual, e.g., health, dental, vision insurance)
   - Other benefits (annual, e.g., 401k match, gym, commuter)
   - Relocation bonus (one-time)
4. **Calculate**: Click "Calculate" to update the totals
5. **Compare**: View the comparison table to see all offers side-by-side
6. **Remove**: Click "Remove" to delete offers you don't need

## Compensation Breakdown

The calculator shows two key metrics:

- **First Year Total**: Includes all one-time bonuses (signing + relocation) plus annual compensation
- **Ongoing Annual (Year 2+)**: Shows recurring annual compensation without one-time bonuses

## Live Demo

Simply open `index.html` in your browser or host it on any static web hosting service like:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Or any web server

## Technical Details

- Pure HTML, CSS, and JavaScript
- No dependencies or frameworks required
- All calculations happen in the browser
- Responsive grid layout using CSS Grid
- Modern styling with CSS gradients and transitions

## Browser Compatibility

Works with all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

Open source - feel free to use and modify as needed.