# Android-Development

## step-by-step guide to setting up and building your Expo React Native app for Android.  

---

## **1️⃣ Required Documentation & Links**
- **Expo Build Setup**: [Expo Build Setup Docs](https://docs.expo.dev/build/setup/)  
- **Your Expo Project**: [Expo ControlHub](https://expo.dev/accounts/hackbugs/projects/controlhub)  
- **React Native Setup**: [React Native Environment Setup](https://reactnative.dev/docs/environment-setup)  

---

## **2️⃣ Install Required Software**
### **Download and Install Android Development Tools**
1. **Android Command Line Tools** – [Download](https://dl.google.com/android/repository/commandlinetools-win-11076708_latest.zip)  
2. **Android Platform Tools** – [Download](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)  
3. **Android Studio** – [Download](https://r1---sn-qxaeenl6.gvt1.com/edgedl/android/studio/install/2024.2.2.14/android-studio-2024.2.2.14-windows.exe?cms_redirect=yes&met=1739991946,&mh=E3&mip=103.225.188.31&mm=28&mn=sn-qxaeenl6&ms=nvh&mt=1739991615&mv=m&mvi=1&pl=24&rms=nvh,nvh&shardbypass=sd&smhost=r1---sn-qxaeenlk.gvt1.com)  

---

## **3️⃣ Set Up Expo & Create the Project**
### **Install Expo & EAS CLI**
```sh
npm install --global eas-cli
```

### **Create a New Expo Project**
```sh
npx create-expo-app controlhub
cd controlhub
```

### **Initialize EAS in the Project**
```sh
eas init --id cc6a227a-bb1b-4818-8f4a-d5ff9e008edd
```

---

## **4️⃣ Set Up EAS Again (If Needed)**
If EAS setup was not successful, re-run:
```sh
npm install --global eas-cli
eas init --id cc6a227a-bb1b-4818-8f4a-d5ff9e008edd
```

---

## **5️⃣ Start Development Server**
To start the project:
```sh
expo start
```

To build the Android app:
```sh
eas build --platform android
```

---
