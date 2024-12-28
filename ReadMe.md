
---

# Setting Up a React Native Project with Expo and React Navigation 2025

Follow the steps below to set up a React Native project using Expo, without TypeScript, and configure React Navigation.

---

## Step 1: Create an Expo Project (Without TypeScript)

Run the following command to create a new Expo project inside an alraedy existing empty folder/repo with Project Name:

```bash
npx create-expo-app@latest ./ --template blank
```

---

## Step 2: Install React Navigation

Add the core React Navigation package:

```bash
npm install @react-navigation/native
```

---

## Step 3: Install Required Dependencies for React Navigation

Install the required dependencies for React Navigation in an Expo-managed workflow:

```bash
npx expo install react-native-screens react-native-safe-area-context react-native-gesture-handler react-native-reanimated react-native-vector-icons
```

---

## Step 4: Install the Native Stack Navigator

Add the native stack navigator library:

```bash
npm install @react-navigation/native-stack
```

---

## Step 5: Install React Navigation Elements Library

Install the React Navigation Elements library (with legacy peer dependencies if necessary):

```bash
npm install @react-navigation/elements --legacy-peer-deps
```

---

By following these steps, your project will be set up with Expo and React Navigation. You can now start building your app! 🚀

--- 
