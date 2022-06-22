# StripeDemo

Commands to follow after cloning this repo for setup.
- yarn install / npm install
- cd ios
- pod install

To run a project in iOS
- npm start -- --reset-cache 
- react-native run-ios

It will successfully compile and run.

Build failed when we compie and run once we add "arm64" to Excluded Architectures in Xcode.

Steps to reproduce error.
- Xcode > Project > Build Settings > Architectures > Excluded Architectures > Add "arm64"
- Xcode > Targets > Build Settings > Architectures > Excluded Architectures > Add "arm64"
- Xcode > Pods > Build Settings > Architectures > Excluded Architectures > Add "arm64"


