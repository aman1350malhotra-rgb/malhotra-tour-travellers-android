# Malhotra Tour & Travellers — Android APK project

Ye Android app aapki existing live website ko app ke andar kholti hai:

https://malhotra-tours-travels.netlify.app/

## App mein kya kaam karega
- Existing website ka home page aur sections
- Website ke call links
- WhatsApp booking links (phone mein WhatsApp installed ho to usmein khulenge)
- Android back button se previous page

## APK banane ka free tareeqa (GitHub Actions)
1. GitHub par login karke ek naya **public ya private repository** banayein.
2. Is ZIP ko extract karke iske andar ki saari files repository mein upload karein.
3. Repository ka naam, example: `malhotra-tour-travellers-android`.
4. Files `main` branch mein commit karein.
5. GitHub repository mein **Actions** tab kholein. `Build Android APK` workflow run hoga.
6. Build successful hone par workflow run ke neeche **Artifacts** mein `Malhotra-Tour-Travellers-APK` download karein.
7. ZIP extract karein. `app-debug.apk` Android phone mein bhej kar install karein. Phone par prompt aaye to browser/file manager ke liye “Install unknown apps” allow karein.

## Important
- Ye abhi **debug APK** hai, Play Store release ke liye signed release build alag se banana hoga.
- APK internet connection ke saath live website load karti hai. Website par future changes app mein bhi dikh jayenge.
- Website hosting aur GitHub Actions ke free limits apply ho sakte hain.
- Android Studio se bhi project open karke `app > Tasks > build > assembleDebug` run kar sakte hain.

## App identity
- App name: Malhotra Tour & Travellers
- Package: `com.malhotra.tourstravels`
- Version: 1.0
- Minimum Android: Android 6.0 (API 23)
