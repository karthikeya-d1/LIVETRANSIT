# BusTracker - Real-time Public Transport Tracking

A comprehensive mobile application for real-time bus tracking in tier-2 cities, built with React Native and Expo.

## 🚌 Features

- **Real-time GPS Tracking**: Live bus locations with estimated arrival times
- **Route Information**: Detailed route maps with all stops
- **Nearby Stops**: Find bus stops within walking distance
- **Low Bandwidth Optimized**: Designed for tier-2 cities with limited connectivity
- **User Profiles**: Track travel statistics and preferences
- **Offline Support**: Core features work with minimal connectivity

## 🎯 Problem Statement

In small cities and tier-2 towns, public transport systems lack real-time tracking, causing inconvenience to commuters who face unpredictable bus schedules. This leads to overcrowding, wasted time, and reduced reliance on public transport.

## 📊 Impact

- Over 60% of commuters in small cities face delays due to lack of real-time information
- Reduces public transport usage and increases private vehicle dependency
- Worsens traffic congestion and pollution

## 🛠️ Technology Stack

- **Framework**: React Native with Expo
- **Navigation**: Expo Router
- **Icons**: Lucide React Native & Ionicons
- **Styling**: StyleSheet (React Native)
- **Platform**: Cross-platform (iOS, Android, Web)

## 📱 Screenshots

The app features a clean, professional interface with:
- Live bus tracking map
- Route information with stop details
- Nearby bus stops with walking directions
- User profile and statistics

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Expo CLI
- iOS Simulator (for iOS development)
- Android Studio (for Android development)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/bus-tracking.git
cd bus-tracking
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open the app:
   - Press `i` for iOS simulator
   - Press `a` for Android emulator
   - Press `w` for web browser
   - Scan QR code with Expo Go app on your device

### Building for Production

#### Web Build
```bash
npm run build:web
```

#### Mobile Build (requires Expo account)
```bash
# iOS
expo build:ios

# Android
expo build:android
```

## 📁 Project Structure

```
bus-tracking/
├── app/                    # App screens and navigation
│   ├── (tabs)/            # Tab-based navigation
│   │   ├── index.tsx      # Live Map screen
│   │   ├── routes.tsx     # Routes screen
│   │   ├── stops.tsx      # Nearby stops screen
│   │   └── profile.tsx    # Profile screen
│   ├── _layout.tsx        # Root layout
│   └── +not-found.tsx     # 404 screen
├── hooks/                 # Custom React hooks
├── assets/                # Images and static assets
├── package.json           # Dependencies and scripts
├── app.json              # Expo configuration
└── tsconfig.json         # TypeScript configuration
```

## 🎨 Design System

### Colors
- **Primary**: #2563EB (Blue)
- **Success**: #059669 (Green)
- **Warning**: #EA580C (Orange)
- **Error**: #DC2626 (Red)
- **Gray Scale**: #111827 to #F8FAFC

### Typography
- **Headers**: 18-24px, weight 600-700
- **Body**: 14-16px, weight 400-500
- **Captions**: 12px, weight 400

## 🔧 Configuration

### Environment Setup

The app is configured for development out of the box. For production deployment:

1. Update `app.json` with your app details
2. Configure push notifications (if needed)
3. Set up analytics (if needed)
4. Configure app store metadata

### Customization

- **Routes**: Modify route data in `app/(tabs)/routes.tsx`
- **Bus Stops**: Update stop information in `app/(tabs)/stops.tsx`
- **Styling**: Customize colors and styles in individual component files
- **Icons**: Replace with your preferred icon library

## 📊 Data Integration

Currently uses simulated data for demonstration. To integrate with real bus tracking systems:

1. Replace mock data with API calls
2. Implement WebSocket connections for real-time updates
3. Add GPS integration for user location
4. Connect to municipal transport databases

## 🌐 Deployment

### Web Deployment
- Build: `npm run build:web`
- Deploy to Netlify, Vercel, or similar platforms

### Mobile App Stores
- Use Expo Application Services (EAS) for building
- Submit to Apple App Store and Google Play Store

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Stakeholders

- **Commuters**: Primary users benefiting from real-time information
- **Local Transport Authorities**: Improved service management
- **Municipal Corporations**: Better urban mobility planning

## 📈 Future Enhancements

- Integration with payment systems
- Route optimization algorithms
- Crowd-sourced delay reporting
- Multi-language support
- Accessibility features
- Analytics dashboard for authorities

## 📞 Support

For support and questions:
- Create an issue in this repository
- Contact: [your-email@example.com]

## 🏆 Hackathon Ready

This prototype is designed for university hackathons and demonstrations, featuring:
- Complete working application
- Professional UI/UX design
- Simulated real-time data
- Cross-platform compatibility
- Easy setup and deployment

---

Built with ❤️ for better public transportation in tier-2 cities.