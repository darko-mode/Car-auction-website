# AutoBid - Car Auction Website

A modern, responsive car auction website built with HTML, Tailwind CSS, and minimal JavaScript. Perfect for hosting on Netlify or any static hosting platform.

## 🚗 Features

- **Homepage** - Hero section, featured auctions, and call-to-action
- **Auction Listings** - Grid view with filters (make, model, year, price)
- **Auction Detail** - Image gallery, car specs, bidding interface, comments
- **Login/Register** - Toggle forms with social login options
- **Sell Your Car** - Comprehensive listing form
- **User Dashboard** - Manage listings, bids, and watchlist
- **About/Contact** - Company info and contact form

## 🎨 Design

- **Framework**: Tailwind CSS via CDN
- **Font**: Inter (Google Fonts)
- **Colors**: Blue primary theme with clean grays
- **Layout**: Fully responsive, mobile-first design
- **Images**: Unsplash placeholder images

## 📁 File Structure

```
/
├── index.html          # Homepage
├── auctions.html       # All auctions listing
├── auction-detail.html # Single auction page
├── login.html          # Login/Register forms
├── sell.html           # Post a car form
├── dashboard.html      # User dashboard
├── about.html          # About & contact page
├── assets/
│   ├── images/         # Image assets
│   ├── js/             # JavaScript files
│   └── css/            # Additional CSS
└── README.md
```

## 🚀 Deployment

### Netlify (Recommended)
1. Drag and drop the entire folder to Netlify
2. Your site will be live instantly

### Other Static Hosts
- GitHub Pages
- Vercel
- Firebase Hosting
- AWS S3 + CloudFront

## 🛠️ Customization

### Colors
Edit the Tailwind config in each HTML file to change the color scheme:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                'primary': '#your-color'
            }
        }
    }
}
```

### Images
Replace Unsplash URLs with your own images:
- Car photos: 400x250px for cards, 800x500px for detail view
- Thumbnails: 200x150px for gallery

### Content
- Update company name, contact info, and descriptions
- Modify car listings with real data
- Customize form fields as needed

## 📱 Mobile Responsive

All pages are fully responsive with:
- Mobile-first design approach
- Touch-friendly buttons and forms
- Optimized image sizes
- Collapsible navigation

## ⚡ Performance

- Lightweight HTML/CSS only
- CDN-hosted Tailwind CSS
- Optimized images via Unsplash
- Minimal JavaScript for interactions

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the MIT License.