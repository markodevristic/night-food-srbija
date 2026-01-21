# Step by Step – Pretvori u mobilnu aplikaciju

1. Provjeri da frontend radi na localhost:3000
2. Dodaj manifest.json
3. Instaliraj next-pwa
4. Build frontend
5. Instaliraj Capacitor:
   npm install @capacitor/core @capacitor/cli
   npx cap init
6. Dodaj platforme:
   Android: npx cap add android
   iOS: npx cap add ios
7. Kopiraj build u Capacitor: npx cap copy
8. Otvori Android Studio / Xcode: npx cap open android / ios
9. Build APK / IPA
10. Testiraj na uređaju
11. Upload na Play Store / App Store
