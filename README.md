# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## 🚀 Features

1. Expo SDK 50 (or latest)

2. NativeWind (Tailwind CSS for React Native)

3. Expo Router (File-based routing)

4. TypeScript support

5. Pre-configured styling system

## 🛠️ Setup

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## 🗂 Project Structure

/
├── app/
│ ├── \_layout.tsx # Root layout
│ ├── global.css # Tailwind imports
│ └── index.tsx # Home screen
├── components/ # Shared components
├── assets/ # Static assets
├── tailwind.config.js # Tailwind configuration
├── babel.config.js # Babel configuration
├── metro.config.js # Metro bundler config
└── nativewind-env.d.ts # TypeScript support

## ⚙️ Configuration Files

1. tailwind.config.js - Configure your design system

2. babel.config.js - Set up JSX transform for NativeWin

3. metro.config.js - Enable NativeWind with Metro bundler

## 🔄 Clearing Cache

```sh

npm start -- --clear
# or
yarn start --clear

```

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

📄 License

- [MIT] (https://choosealicense.com/licenses/mit/)
