# 📱 Mobile Development Environment Setup

## 🎯 Objective

Set up and test a mobile development environment using **React Native**, **TypeScript**, **NativeWindCSS**, and the **Expo Framework**. This setup ensures efficient, cross-platform development with real-device testing using Expo Go.

---

## 🛠️ Tools Required

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Node.js     | JavaScript runtime               |
| VS Code     | Recommended code editor          |
| Expo CLI    | Manage and run React Native apps |
| Expo Go     | Test apps on physical device     |
| Mobile OS   | Android or iOS                   |

---

## 🔧 Setup Steps

### ✅ 1. Install Node.js and VS Code

- [Download Node.js LTS](https://nodejs.org/)
- [Download VS Code](https://code.visualstudio.com/)

### ✅ 2. Install Expo CLI

```bash
npm install -g expo-cli
```

### ✅ 3. Create a New Expo App with TypeScript

```bash
npx create-expo-app test-app --template expo-template-blank-typescript
cd test-app
```

### ✅ 4. Start the Development Server

```bash
npx expo start
```

- This opens Expo Dev Tools and displays a QR code.

### ✅ 5. Install Expo Go on Your Device

- Go to [https://expo.dev/go](https://expo.dev/go)
- Download Expo Go from:
  - **Google Play Store** (Android)
  - **Apple App Store** (iOS)
- Open Expo Go and **log in** or **create an account**

### ✅ 6. Test the App on Your Device

- Open **Expo Go**
- Scan the QR code from the terminal or browser
- The test app should open on your mobile device

---

## ✅ Results

- Environment is set up correctly.
- App loads and runs successfully on a physical Android device.
- Ready for further development with NativeWindCSS and additional screens.

---

## ⚠️ Challenges Faced

- None. Setup completed successfully without any issues.

---

## 📌 Next Steps

- Configure NativeWindCSS
- Set up project structure for screen components
- Implement UI from mockups
- Start building features

---

> 💡 Expo Go simplifies real-device testing and helps skip emulator setup, making it ideal for mobile development using React Native.
