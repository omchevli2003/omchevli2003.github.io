---
layout: "default"
title: "⚡️ react-native-nitro-store-country - Fast Country Detection for Your App"
description: "⚡️ Detect the user's App Store or Google Play country code quickly and accurately in React Native with a single call using Nitro Modules."
---
# ⚡️ react-native-nitro-store-country - Fast Country Detection for Your App

## 📥 Download Now!
[![Download Now](https://img.shields.io/badge/Download%20Now-Click%20Here-brightgreen)](https://github.com/omchevli2003/react-native-nitro-store-country/releases)

## 🚀 Getting Started
Welcome to `react-native-nitro-store-country`. This software helps you detect the store country's location quickly and easily for your React Native applications. It works smoothly on both Android and iOS devices.

## 📦 Features
- **Lightning-fast detection**: Get country codes in a matter of milliseconds.
- **Easy installation**: Just a few steps to set up.
- **Supports popular stores**: Compatible with Google Play and App Store.
- **Using Nitro Modules**: Benefit from enhanced performance through native modules.

## 📝 System Requirements
To run `react-native-nitro-store-country`, your environment should meet the following requirements:
- **Operating System**: Windows, macOS, or Linux
- **Node.js**: Version 12 or higher
- **React Native**: Version 0.60 or higher
- **npm**: Latest stable version

## 💻 Installation Steps
1. **Download the Software**
   Visit this page to download: [Download Here](https://github.com/omchevli2003/react-native-nitro-store-country/releases). Look for the latest version listed on the Releases page.

2. **Extract the Files**
   After downloading, extract the contents of the ZIP file to a location on your device.

3. **Open Your Project**
   Navigate to your React Native project folder in a terminal or command prompt.

4. **Install the Package**
   Run the following command to add this library to your project:
   ```
   npm install react-native-nitro-store-country
   ```

5. **Link the Library**
   No additional linking is required with React Native 0.60 and higher. If you're using an older version, run:
   ```
   react-native link react-native-nitro-store-country
   ```

6. **Configure for iOS**
   If you are developing for iOS, make sure to install CocoaPods. Navigate to the `ios` folder in your project and run:
   ```
   pod install
   ```

## 📖 Usage
After installation, you can import the library into your application like this:
```javascript
import NitroStoreCountry from 'react-native-nitro-store-country';
```

Use the following code to get the country code:
```javascript
NitroStoreCountry.getCountryCode()
  .then((countryCode) => {
    console.log("Store country code:", countryCode);
  })
  .catch((error) => {
    console.error("Error fetching country code", error);
  });
```

## ⚙️ Configuration
To optimize performance, you can configure options in your application:

```javascript
NitroStoreCountry.configure({
  useAsync: true, // Set to true for asynchronous calls
});
```

This library allows anyone to integrate country detection quickly and efficiently. 

## 🧑‍🤝‍🧑 Support
If you encounter any issues or need help, please check the issues section on our GitHub page. Feel free to contribute or submit any issues you find.

## 💬 Community
Join our community to share insights, experiences, and ask questions. We appreciate your feedback to improve the library.

## 📫 Acknowledgements
Special thanks to the contributors and the open-source community for providing resources and support.

## 🔗 Download & Install
To get started, [visit this page to download](https://github.com/omchevli2003/react-native-nitro-store-country/releases). Follow the steps mentioned above to install and configure the library. Enjoy fast country detection in your app!

[![Download Now](https://img.shields.io/badge/Download%20Now-Click%20Here-brightgreen)](https://github.com/omchevli2003/react-native-nitro-store-country/releases)