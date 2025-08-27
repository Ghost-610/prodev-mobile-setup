# First Expo App with Router 👋

This project was created with [Expo](https://expo.dev) using the [`create-expo-app`](https://www.npmjs.com/package/create-expo-app) command.

---

## Steps for Scaffolding

1. Navigated to the parent project directory:
   ```bash
   cd prodev-mobile-setup
2. Initialized the project with the Expo Router template:
npx create-expo-app@latest .
Modified app/(tabs)/index.tsx:
Changed the default text:
<Text>Welcome!</Text>
to
<Text> First App Created</Text>
Started the project:
npx expo start
For iOS: Scan the QR code with the Camera app.
For Android: Scan the QR code with the Expo Go app.
Verified the app showed First App Created on the screen.
Observations from npm run reset-project
When I ran:
npm run reset-project
the following happened:
Cleared the node_modules folder and caches.
Reinstalled dependencies, so the first run after reset took longer.
Moved the previous project files into a backup directory called app-example/.
This included:
app-example/app/(tabs)/index.tsx
app-example/constants/Colors.tsx
and other related files.
Created a fresh app/ folder with a clean Expo Router scaffold.
👉 Important: My modified code (First App Created) is in the new app/(tabs)/index.tsx, not inside the backup app-example folder.
