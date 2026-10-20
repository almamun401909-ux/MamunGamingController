# Mamun Gaming Controller — Prototype v0.3

Android Studio project for Redmi 13. Root-free prototype for testing keyboard/mouse input and configuring a local key-mapping profile.

## Defaults
- Movement: WASD
- Fire: LEFT CLICK
- Sensitivity: 65/100
- Mouse DPI profile: 800
- Other sample mappings: Jump=SPACE, Aim=MOUSE MOVE, Reload=R, Crouch=C, Sprint=SHIFT

## Build APK
1. Extract this ZIP.
2. Open the `MamunGamingController` folder in Android Studio.
3. Install Android SDK Platform 35 if Android Studio requests it, then sync Gradle.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Install the generated debug APK on your Android phone.

## Important limitations
This app can test keyboard/mouse events while its own screen is active and save key mappings/sensitivity/DPI preferences locally. The DPI value is a profile setting only; it does not change the physical mouse's hardware DPI. This root-free prototype does not inject touch events into Free Fire or guarantee compatibility with third-party games. Use only input methods permitted by the game and Android.
