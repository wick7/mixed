# Mixed

## Getting Started

### Installation

To install the required dependencies for this project, run:

```bash
npm install
```

### Running the Application

To start the development server, run:

```bash
npm run dev
```

This will launch the application in development mode. A local development URL will be provided in the terminal output, which you'll need for testing with the Lynx Explorer.

## Setting Up Lynx Explorer with iOS Simulator

To test the application on iOS simulator with Lynx Explorer, follow these steps:

1. **Install Xcode**: Download and install Xcode from the App Store if you don't already have it installed.

2. **Download Lynx Explorer**: Download the Lynx Explorer app from the [official guide](https://lynxjs.org/guide/start/quick-start.html#ios-simulator-platform=macos-arm64,explorer-platform=ios-simulator).

3. **Extract the Lynx Explorer**: Extract the downloaded file as instructed in the guide.

4. **Launch iOS Simulator**: Open Xcode and launch the iOS simulator by navigating to Xcode > Open Developer Tool > Simulator (or press Cmd + Space and search for "Simulator").

5. **Install Lynx Explorer on Simulator**: Drag and drop the extracted Lynx Explorer app into the iOS simulator window. This will install the app on the simulated device.

6. **Open and Connect**: 
   - Open the Lynx Explorer app on the simulator
   - Copy the local development URL provided after running `npm run dev`
   - Paste this URL into the Lynx Explorer app

The application should now load in the Lynx Explorer, allowing you to test your project in an iOS environment.

## Additional Resources

- [Lynx JS Documentation](https://lynxjs.org/)
- [iOS Simulator Guide](https://developer.apple.com/documentation/xcode/running-your-app-in-simulator-or-on-a-device)