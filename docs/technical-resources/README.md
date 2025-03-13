# Technical Resources

## React Native Fundamentals (2024)

### Official Resources
- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [React Native Blog](https://reactnative.dev/blog)
- [React Native New Architecture](https://reactnative.dev/docs/the-new-architecture/landing-page)
- [React Native GitHub](https://github.com/facebook/react-native)

### Core Technologies
1. **Framework Essentials**
   - [Expo SDK](https://docs.expo.dev/) - Development platform and tools
   - [Expo Router](https://docs.expo.dev/router/introduction/) - File-based routing
   - [React Navigation](https://reactnavigation.org/) - Navigation library
   - [TypeScript Guide](https://reactnative.dev/docs/typescript)

2. **UI & Design**
   - [React Native Paper](https://callstack.github.io/react-native-paper/) - Material Design
   - [NativeBase](https://nativebase.io/) - Accessible components
   - [React Native Skia](https://shopify.github.io/react-native-skia/) - 2D graphics
   - [React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/) - Animations

3. **State Management**
   - [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction) - Simple state management
   - [TanStack Query](https://tanstack.com/query/latest) - Server state management
   - [Redux Toolkit](https://redux-toolkit.js.org/) - Complex state management

## Development Setup

### Essential Tools
1. **Required Software**
   ```bash
   # Node.js (LTS version)
   # Watchman
   # Xcode (iOS)
   # Android Studio (Android)
   # VS Code
   ```

2. **VS Code Extensions**
   - [React Native Tools](https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native)
   - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
   - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
   - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

3. **Project Setup**
   ```bash
   # Create new project
   npx create-expo-app@latest my-app
   
   # Or with custom template
   npx create-expo-app@latest my-app --template with-router
   ```

### Recommended Libraries

| Category | Library | Version | Purpose |
|----------|---------|---------|----------|
| UI | react-native-paper | ^5.0.0 | Material Design |
| Navigation | @react-navigation/native | ^6.0.0 | Routing |
| State | zustand | ^4.0.0 | State management |
| Testing | jest | ^29.0.0 | Unit testing |

## Project Architecture

### Folder Structure
```bash
src/
├── components/
│   ├── atoms/        # Basic components
│   ├── molecules/    # Composite components
│   └── organisms/    # Complex components
├── features/         # Feature-based modules
├── navigation/       # Navigation setup
├── services/        # API and external services
├── hooks/           # Custom hooks
├── utils/           # Helper functions
├── theme/           # Design system
└── types/           # TypeScript definitions
```

### Best Practices
1. **Performance**
   - Use [Flipper](https://fbflipper.com/) for debugging
   - Implement [React Native Performance](https://reactnative.dev/docs/performance)
   - Monitor with [Performance Monitor](https://reactnative.dev/docs/performance#performance-monitor)

2. **Testing**
   - [Jest](https://jestjs.io/) for unit testing
   - [React Native Testing Library](https://callstack.github.io/react-native-testing-library/)
   - [Detox](https://wix.github.io/Detox/) for E2E testing

3. **Security**
   - [Security Guidelines](https://reactnative.dev/docs/security)
   - [Expo Security](https://docs.expo.dev/guides/security/)

## Latest Features (2024)

### New Architecture
- [Fabric Renderer](https://reactnative.dev/architecture/fabric-renderer)
- [TurboModules](https://reactnative.dev/docs/the-new-architecture/turbommodules)
- [Codegen](https://reactnative.dev/docs/the-new-architecture/pillars-codegen)

### Development Tools
- [Expo EAS](https://docs.expo.dev/eas/) - Build and deploy
- [Expo Updates](https://docs.expo.dev/eas-update/introduction/) - OTA updates
- [Metro Bundler](https://facebook.github.io/metro/) - JavaScript bundler

## Learning Resources

### Official Channels
- [React Native YouTube](https://www.youtube.com/@ReactNative)
- [Expo YouTube](https://www.youtube.com/@expo)
- [React Native Blog](https://reactnative.dev/blog)

### Community Resources
- [React Native Directory](https://reactnative.directory/) - Package discovery
- [React Native Community](https://github.com/react-native-community)
- [Expo Forums](https://forums.expo.dev/)

### Newsletters
- [React Native Newsletter](https://reactnativenewsletter.com/)
- [This Week In React](https://thisweekinreact.com/)

## Troubleshooting

### Common Issues
1. **Build Problems**
   - [iOS Build Issues](https://reactnative.dev/docs/troubleshooting#ios-build-errors)
   - [Android Build Issues](https://reactnative.dev/docs/troubleshooting#android-build-errors)
   - [Metro Bundler Issues](https://reactnative.dev/docs/troubleshooting#metro-bundler-issues)

2. **Development Tools**
   - [React Native Debugger](https://github.com/jhen0409/react-native-debugger)
   - [Flipper](https://fbflipper.com/)
   - [Chrome DevTools](https://reactnative.dev/docs/debugging#chrome-developer-tools)

### Support Channels
- [GitHub Issues](https://github.com/facebook/react-native/issues)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/react-native)
- [Expo Forums](https://forums.expo.dev/)

_Last updated: March 2024_