# 🍎 iOS 개념 시각화 LAB

13가지 핵심 iOS/Swift 개념을 눈으로 보고, 직접 조작하며 배우는 인터랙티브 학습 도구

🔗 **[지금 바로 체험하기 → https://m1zz.github.io/ios-concept-lab/](https://m1zz.github.io/ios-concept-lab/)**

> **빌드 없음 · npm 없음 · 파일 2개**

---

## 🚀 배포 (딱 한 번만)

### 1단계 — GitHub 저장소 만들기

[github.com/new](https://github.com/new) 에서 새 repository 생성  
(Public, README 추가 X)

### 2단계 — 코드 push

```bash
git init
git add .
git commit -m "🍎 iOS 개념 시각화 LAB"
git branch -M main
git remote add origin https://github.com/[본인계정]/[저장소이름].git
git push -u origin main
```

### 3단계 — GitHub Pages 활성화 (최초 1회)

저장소 → **Settings → Pages**  
Source: **GitHub Actions** 선택 → Save

**끝.** 이후 `main` 브랜치에 push할 때마다 자동 배포됩니다.

🔗 배포 주소: https://m1zz.github.io/ios-concept-lab/

---

## 📚 수록 개념 (25가지)

| 카테고리 | 개념 |
|----------|------|
| Swift 기초 | 📦 Call by Value / Ref · 📭 Optional / nil · 🪤 Closure Capture · 🏷 Enum & Associated Values · 🧬 Generics · 🔐 Access Control |
| 상태 & 데이터 | 🎯 Source of Truth · 🔄 @State / @Binding / @ObservedObject / @EnvironmentObject · 🎁 Property Wrappers · 📋 Codable |
| 동시성 | 🧵 Main vs Background Thread · ⏳ async/await · 🚦 GCD & DispatchQueue · 🛡 Actor & Sendable |
| 메모리 | ♻️ ARC (Retain Count 시각화) · 🐄 Copy on Write |
| 에러 & 클로저 | 🚨 Error Handling (do-try-catch & Result) · 🏃 @escaping Closure |
| 패턴 & 구조 | 🔔 Delegate · 📱 View Lifecycle · 🏗 MVC vs MVVM · 📢 NotificationCenter · 🔒 Protocol & DI |
| 앱 & UIKit | 🔁 App Lifecycle · 👆 Responder Chain |

---

## 📁 파일 구조

```
/
├── index.html                   ← 앱 전체 (빌드 불필요)
├── .github/
│   └── workflows/
│       └── deploy.yml           ← 자동 배포 워크플로우
└── README.md
```

---

Made with ❤️ by [개발자리](https://www.youtube.com/@개발자리)
