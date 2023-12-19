Setup:

sudo xcode-select -s /Applications/Xcode.app/Contents/Developer/ possibly required.

expo prebuild:

    * npx expo prebuild --clean (to be used only when needed)
    * npx expo prebuild
    * create script to automate updating config for android and iOS.

    Add android and ios directories to .gitignore (https://docs.expo.dev/guides/local-app-development/)

Running:

    yarn install
    npx expo run:android
    npx expo run:ios

    npx expo install expo-dev-client (start with `npx expo start --dev-client`)