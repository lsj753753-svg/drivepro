# My App

## 빠른 시작 (GitHub Actions)
1. 이 저장소를 GitHub에 업로드
2. Actions 탭에서 Build APK 워크플로우 확인
3. 완료 후 Artifacts에서 APK 다운로드

## 로컬 빌드
```bash
npm install
npx cap add android
npx cap sync
cd android && ./gradlew assembleDebug
```

APK: `android/app/build/outputs/apk/debug/app-debug.apk`

## 앱 정보
- 앱 이름: My App
- 패키지 ID: com.example.myapp
- 버전: 1.0.0 (code: 100)
- minSdk: 23 / targetSdk: 34
