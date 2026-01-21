# EDI 발주 분석 PWA (Progressive Web App)

**설치 파일 없이** 데스크톱/모바일에 앱처럼 설치할 수 있는 웹앱입니다.

---

## 🚀 3가지 배포 방법

### 방법 1: GitHub Pages (무료, 가장 쉬움)

1. **GitHub 계정 생성**: [github.com](https://github.com) 가입
2. **새 저장소 생성**: `edi-dashboard` 이름으로 생성
3. **파일 업로드**: 이 폴더의 모든 파일 업로드
4. **GitHub Pages 활성화**:
   - Settings → Pages → Source: `main` 선택 → Save
5. **완료!** `https://사용자명.github.io/edi-dashboard` 주소로 접속

### 방법 2: Vercel (무료, 자동 배포)

1. [vercel.com](https://vercel.com) 가입
2. "Import Project" → GitHub 연결
3. 저장소 선택 → Deploy
4. **완료!** `https://프로젝트명.vercel.app` 주소 생성

### 방법 3: Netlify (무료, 드래그앤드롭)

1. [netlify.com](https://netlify.com) 가입
2. "Add new site" → "Deploy manually"
3. 이 폴더를 드래그앤드롭
4. **완료!** 자동 주소 생성

---

## 📱 앱 설치 방법

### 데스크톱 (Chrome)

1. 배포된 URL 접속
2. 주소창 오른쪽 **설치 아이콘** 클릭 또는
3. 메뉴(⋮) → "앱 설치" 또는 "바로가기 만들기"

### iPhone/iPad (Safari)

1. Safari로 URL 접속
2. 하단 **공유 버튼** (□↑) 탭
3. **"홈 화면에 추가"** 선택
4. "추가" 탭

### Android (Chrome)

1. Chrome으로 URL 접속
2. 하단에 **"홈 화면에 추가"** 배너 표시됨
3. 또는 메뉴(⋮) → "앱 설치" 또는 "홈 화면에 추가"

---

## 📁 파일 구조

```
edi-pwa/
├── index.html      # 메인 앱 (React)
├── manifest.json   # PWA 설정
├── sw.js           # 오프라인 캐시
├── icon-192.png    # 앱 아이콘 (필요)
├── icon-512.png    # 앱 아이콘 (필요)
└── README.md       # 이 파일
```

---

## 🎨 앱 아이콘 만들기

앱 아이콘이 필요합니다:

1. 512x512 PNG 이미지 준비 (회사 로고 등)
2. `icon-512.png`로 저장
3. 192x192로 리사이즈하여 `icon-192.png` 저장
4. 무료 도구: [canva.com](https://canva.com) 또는 [figma.com](https://figma.com)

---

## ✅ PWA 장점

| 기능 | 설명 |
|------|------|
| 🏠 홈 화면 설치 | 앱처럼 아이콘으로 실행 |
| 📴 오프라인 지원 | 인터넷 없이도 기본 기능 동작 |
| ⚡ 빠른 로딩 | 캐시된 리소스 사용 |
| 🔄 자동 업데이트 | 새 버전 배포 시 자동 반영 |
| 📱 크로스 플랫폼 | Windows, Mac, iOS, Android 모두 지원 |

---

## ❓ FAQ

**Q: 앱 스토어에 등록해야 하나요?**
A: 아니요! PWA는 앱 스토어 없이 바로 설치됩니다.

**Q: 업데이트는 어떻게 하나요?**
A: 서버에 파일만 업데이트하면 자동으로 반영됩니다.

**Q: HTTPS가 필요한가요?**
A: 네, PWA는 보안상 HTTPS가 필요합니다. GitHub Pages, Vercel, Netlify는 자동으로 HTTPS를 제공합니다.

---

## 📞 지원

문의: your-email@company.com
