

# Welcome to my Loveable Project

## Project info

**URL**: https://lovable.dev/projects/cf516961-303d-481b-b621-61bab01570c3

## How can you edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/cf516961-303d-481b-b621-61bab01570c3) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

## Running on a mobile device

To run this app on a physical Android device or emulator:

1. Make sure you have the latest Node.js installed
2. Install Android Studio and set up the Android SDK
3. Enable USB debugging on your Android device
4. Run these commands:

```sh
# Install dependencies
npm install

# Build the web app
npm run build

# Add Android platform (if not already added)
npx cap add android

# Sync web code to Android project
npx cap sync android

# Open in Android Studio
npx cap open android
```

From Android Studio, you can run the app on your connected device or emulator.

## Building an APK without Android Studio

If you want to build an APK directly without opening Android Studio (for low-resource computers):

1. Make sure you have the Android SDK command line tools installed and ANDROID_SDK_ROOT environment variable set
2. Run the following commands:

```sh
# Build the web app
npm run build

# Sync with Android
npx cap sync android

# Navigate to Android project directory
cd android

# Build debug APK using Gradle
./gradlew assembleDebug

# OR build release APK (requires signing configuration in build.gradle)
# ./gradlew assembleRelease
```

The debug APK will be available at: `android/app/build/outputs/apk/debug/app-debug.apk`

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
- Capacitor for mobile capabilities

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/cf516961-303d-481b-b621-61bab01570c3) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/tips-tricks/custom-domain#step-by-step-guide)

