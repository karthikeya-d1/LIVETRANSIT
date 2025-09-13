# Dependencies and Package Information

## 📦 Complete Package List

### Production Dependencies

```json
{
  "@expo/vector-icons": "^14.1.0",
  "@lucide/lab": "^0.1.2", 
  "@react-navigation/bottom-tabs": "^7.2.0",
  "@react-navigation/native": "^7.0.14",
  "expo": "^53.0.0",
  "expo-blur": "~14.1.3",
  "expo-camera": "~16.1.5",
  "expo-constants": "~17.1.3",
  "expo-font": "~13.2.2",
  "expo-haptics": "~14.1.3",
  "expo-linear-gradient": "~14.1.3",
  "expo-linking": "~7.1.3",
  "expo-router": "~5.0.2",
  "expo-splash-screen": "~0.30.6",
  "expo-status-bar": "~2.2.2",
  "expo-symbols": "~0.4.3",
  "expo-system-ui": "~5.0.5",
  "expo-web-browser": "~14.1.5",
  "lucide-react-native": "^0.475.0",
  "react": "19.0.0",
  "react-dom": "19.0.0",
  "react-native": "0.79.1",
  "react-native-gesture-handler": "~2.24.0",
  "react-native-reanimated": "~3.17.4",
  "react-native-safe-area-context": "5.3.0",
  "react-native-screens": "~4.10.0",
  "react-native-svg": "15.11.2",
  "react-native-url-polyfill": "^2.0.0",
  "react-native-web": "^0.20.0",
  "react-native-webview": "13.13.5"
}
```

### Development Dependencies

```json
{
  "@babel/core": "^7.25.2",
  "@types/react": "~19.0.10",
  "typescript": "~5.8.3"
}
```

## 🔧 Installation Commands

### One-time Setup
```bash
# Install all dependencies
npm install

# Or using yarn
yarn install
```

### Individual Package Installation
If you need to install packages individually:

```bash
# Core Expo and React Native
npm install expo@^53.0.0
npm install react@19.0.0 react-dom@19.0.0
npm install react-native@0.79.1

# Navigation
npm install expo-router@~5.0.2
npm install @react-navigation/native@^7.0.14
npm install @react-navigation/bottom-tabs@^7.2.0

# UI and Icons
npm install @expo/vector-icons@^14.1.0
npm install lucide-react-native@^0.475.0
npm install @lucide/lab@^0.1.2

# Expo Modules
npm install expo-constants@~17.1.3
npm install expo-font@~13.2.2
npm install expo-linking@~7.1.3
npm install expo-splash-screen@~0.30.6
npm install expo-status-bar@~2.2.2
npm install expo-system-ui@~5.0.5
npm install expo-web-browser@~14.1.5

# React Native Core
npm install react-native-safe-area-context@5.3.0
npm install react-native-screens@~4.10.0
npm install react-native-gesture-handler@~2.24.0
npm install react-native-reanimated@~3.17.4
npm install react-native-svg@15.11.2
npm install react-native-web@^0.20.0
npm install react-native-webview@13.13.5
npm install react-native-url-polyfill@^2.0.0

# Additional Features (Optional)
npm install expo-blur@~14.1.3
npm install expo-camera@~16.1.5
npm install expo-haptics@~14.1.3
npm install expo-linear-gradient@~14.1.3
npm install expo-symbols@~0.4.3

# Development Dependencies
npm install --save-dev @babel/core@^7.25.2
npm install --save-dev @types/react@~19.0.10
npm install --save-dev typescript@~5.8.3
```

## 📋 Package Purposes

### Core Framework
- **expo**: Main Expo SDK for cross-platform development
- **react**: Core React library
- **react-native**: React Native framework
- **react-dom**: React DOM for web support

### Navigation
- **expo-router**: File-based routing system
- **@react-navigation/native**: Navigation core
- **@react-navigation/bottom-tabs**: Tab navigation

### UI Components & Icons
- **@expo/vector-icons**: Ionicons and other icon sets
- **lucide-react-native**: Modern icon library
- **@lucide/lab**: Additional Lucide icons

### Platform Integration
- **react-native-safe-area-context**: Safe area handling
- **react-native-screens**: Native screen management
- **react-native-gesture-handler**: Touch gesture handling
- **react-native-reanimated**: Smooth animations
- **react-native-svg**: SVG support
- **react-native-web**: Web platform support

### Expo Modules
- **expo-constants**: App constants and configuration
- **expo-font**: Custom font loading
- **expo-linking**: Deep linking support
- **expo-splash-screen**: Splash screen management
- **expo-status-bar**: Status bar styling
- **expo-system-ui**: System UI configuration
- **expo-web-browser**: In-app browser

### Optional Features
- **expo-blur**: Blur effects
- **expo-camera**: Camera functionality
- **expo-haptics**: Haptic feedback
- **expo-linear-gradient**: Gradient backgrounds
- **expo-symbols**: SF Symbols (iOS)

## 🔄 Version Compatibility

This project uses:
- **Expo SDK 53**: Latest stable version
- **React 19**: Latest React version
- **React Native 0.79**: Latest RN version
- **TypeScript 5.8**: Latest TypeScript

## 🚨 Important Notes

1. **Expo SDK Compatibility**: All expo packages are pinned to SDK 53 versions
2. **React Native Web**: Enables web deployment
3. **TypeScript**: Full TypeScript support included
4. **Cross-platform**: Works on iOS, Android, and Web

## 🔧 Troubleshooting

### Common Issues:

1. **Metro bundler issues**:
```bash
npx expo start --clear
```

2. **Node modules issues**:
```bash
rm -rf node_modules package-lock.json
npm install
```

3. **iOS simulator issues**:
```bash
npx expo run:ios --clear
```

4. **Android emulator issues**:
```bash
npx expo run:android --clear
```

## 📱 Platform-Specific Notes

### iOS
- Requires Xcode for iOS simulator
- Some packages need iOS 13+ minimum

### Android
- Requires Android Studio
- Minimum SDK version: 21 (Android 5.0)

### Web
- All packages are web-compatible
- Uses react-native-web for rendering

## 🚀 Performance Optimization

The dependency list is optimized for:
- Fast startup times
- Small bundle sizes
- Cross-platform compatibility
- Modern React Native features

All packages are essential for the app's functionality and have been carefully selected for optimal performance in tier-2 city environments with limited bandwidth.