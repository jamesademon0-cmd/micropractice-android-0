# Build APK

## Local

```bash
gradle --no-daemon :app:assembleDebug
```

APK output:
`app/build/outputs/apk/debug/app-debug.apk`

The project uses Kotlin + Jetpack Compose + Material 3. Current module settings are compatible with JDK 17 and Android SDK 35.
