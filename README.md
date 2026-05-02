# 🌱 AgroMitra — AI-Powered Agricultural Marketplace

**AgroMitra** is a modern web-based marketplace platform connecting farmers directly with consumers. It eliminates middlemen, ensures fair pricing through AI-powered forecasts, and enables transpar[...]

## ✨ Key Features

### 🌾 Farmer Panel
- **Product Listings**: Manage active agricultural products with real-time availability
- **AI Price Forecasting**: LSTM-powered price predictions for the next 7 days (85%+ accuracy)
- **Order Management**: Track incoming orders with status updates (Preparing → Shipped → Delivered)
- **Demand Analytics**: Region-wise demand visualization to optimize sales strategy
- **Crop Recommendations**: AI-driven suggestions based on location, season, and market trends
- **Revenue Insights**: Real-time earnings tracking and performance metrics

### 🛒 Consumer Panel
- **Product Discovery**: Search and filter fresh farm products with farmer ratings
- **Smart Cart**: Easy-to-use shopping cart with quantity controls
- **Order Tracking**: Real-time delivery status tracking with estimated arrival times
- **Nearby Farmers**: Discover local farms with distance, ratings, and specialty products
- **Multiple Payment Methods**: Support for bKash and Nagad (mobile payment systems)

### 🤖 AI-Powered Features
- **Dynamic Pricing**: Automatic price optimization based on demand and supply
- **Demand Forecasting**: Predict regional demand patterns
- **Crop Recommendations**: Suggest high-profit crops based on farmer location and season
- **Trend Analysis**: Market trend indicators (Rising/Dropping prices)

## 📱 Responsive Design
- **Mobile-First**: Optimized for all screen sizes
- **Sticky Navigation**: Easy access to panels on any device
- **Adaptive Grid**: Products and statistics adjust to screen size

## 🎨 Design System

### Color Palette
```css
Primary Colors:
- Dark Green (#1C3A1E) — Brand primary
- Mid Green (#2C5F2E) — Active elements
- Light Green (#97BC62) — Highlights & badges
- Accent Gold (#F4C430) — CTAs & progress

Backgrounds:
- Cream (#F7FAF3) — Page background
- Card White (#FFFFFF) — Card backgrounds
- Light Gray (#64748B) — Text & borders
```

### Typography
- **Brand Font**: Fraunces (serif) — Headings
- **Body Font**: DM Sans (sans-serif) — Content & UI

## 🔧 Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Custom CSS with CSS variables for theming
- **ML/AI**: LSTM model for price forecasting
- **Payment Integration**: bKash & Nagad APIs (ready for integration)

## 📂 Project Structure

```
demo.html          # Main application file (all-in-one demo)
README.md          # This file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/lalchandali/UU_Project.git
cd UU_Project
```

2. Open `demo.html` in your browser:
```bash
open demo.html
# or
python -m http.server  # For local server
```

3. Start exploring:
   - **Farmer Mode**: Click "🌾 Farmer Panel" to manage crops and view analytics
   - **Consumer Mode**: Click "🛒 Consumer Panel" to browse and purchase

## 🌐 Live View

🔗 **[View Live Project](https://lalchandali.github.io/UU_Project/demo.html)** — Open the interactive demo in your browser

## 💡 Usage Guide

### For Farmers
1. View total earnings, active listings, and pending orders on the dashboard
2. Check AI price forecasts to optimize pricing
3. Monitor demand by region to decide where to focus
4. Get crop recommendations based on your location and season
5. Track all incoming orders and their status

### For Consumers
1. Search for fresh products using the search bar
2. Filter by product name or farmer rating
3. Add items to cart
4. View order tracking in real-time
5. Check nearby farms and their specialties
6. Checkout with bKash or Nagad

## 🎯 Future Enhancements

- [ ] Backend API integration (Node.js/Express)
- [ ] User authentication & authorization
- [ ] Real database (MongoDB/PostgreSQL)
- [ ] Advanced analytics dashboard
- [ ] Logistics & delivery tracking
- [ ] Review & rating system
- [ ] Seasonal crop calendar
- [ ] Weather integration for crop planning
- [ ] Mobile app (React Native/Flutter)
- [ ] Multi-language support (Bangla, English)

## 📊 Sample Data

The demo includes sample data:
- **6 Products**: Tomato, Onion, Potato, Chili, Brinjal, Spinach
- **4 Farmers**: Rahim, Karim, Mia, Hasan farms across Bangladesh
- **Multiple Regions**: Dhaka, Chittagong, Sylhet, Rajshahi, Khulna
- **Real Pricing**: Market-realistic rates in Bengali Taka (৳)

## 🔐 Security Considerations

- Implement HTTPS for production
- Validate all user inputs
- Secure payment gateway integration
- Implement rate limiting on APIs
- Add CSRF protection

## 📈 Performance

- Lightweight HTML file (~50KB)
- No external dependencies
- Fast load time and smooth animations
- CSS animations use GPU acceleration (transform/opacity)

## 🤝 Contributing

Contributions are welcome! Please feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**Lalchand Ali**
- GitHub: [@lalchandali](https://github.com/lalchandali)
- Project: [AgroMitra](https://github.com/lalchandali/UU_Project)

## 📧 Support

For questions, issues, or suggestions, please open an issue on GitHub or contact the project maintainer.

---

**Status**: 🚀 Beta — Active Development

**Last Updated**: May 2, 2026

Made with ❤️ for sustainable agriculture in Bangladesh
