# 🚀 HTML 게임 호스팅 & 애드센스 수익화 완전 가이드

## 📋 **1단계: 무료 호스팅 플랫폼 선택**

### 🏆 **추천 호스팅 서비스 (우선순위별)**

| 순위 | 플랫폼 | 특징 | 장점 | 단점 | 추천도 |
|------|--------|------|------|------|-------|
| 🥇 | **GitHub Pages** | 정적 사이트 전용 | • 완전 무료<br>• 커스텀 도메인 가능<br>• 빠른 속도 | • 정적 사이트만<br>• 1GB 제한 | ⭐⭐⭐⭐⭐ |
| 🥈 | **Netlify** | 정적 + 폼 기능 | • GitHub 연동 자동배포<br>• SSL 자동<br>• 폼 기능 | • 대역폭 제한 | ⭐⭐⭐⭐⭐ |
| 🥉 | **Vercel** | Next.js 최적화 | • 빌드 자동화<br>• 실시간 프리뷰 | • React 기반에 최적화 | ⭐⭐⭐⭐ |
| 4위 | **Firebase Hosting** | 구글 서비스 | • 구글 연동<br>• 안정적 | • 설정 복잡 | ⭐⭐⭐ |

---

## 🌟 **GitHub Pages 배포 방법 (추천!)**

### **Step 1: GitHub 계정 & 저장소 생성**
```bash
1. https://github.com 가입
2. "New repository" 클릭
3. Repository 이름: "brainrot-quiz-game" 
4. Public으로 설정
5. "Add a README file" 체크
6. "Create repository" 클릭
```

### **Step 2: HTML 파일 업로드**
```bash
1. 저장소 페이지에서 "Add file" → "Upload files"
2. 완성된 HTML 파일을 "index.html"로 업로드
3. Commit 메시지: "Add Italian Brainrot Quiz Game"
4. "Commit changes" 클릭
```

### **Step 3: GitHub Pages 활성화**
```bash
1. 저장소 → Settings 탭
2. 왼쪽 메뉴에서 "Pages" 클릭
3. Source: "Deploy from a branch" 선택
4. Branch: "main" 선택
5. Folder: "/ (root)" 선택
6. "Save" 클릭
```

### **Step 4: 사이트 확인**
- **URL**: `https://[사용자명].github.io/brainrot-quiz-game`
- 배포 완료까지 약 5-10분 소요

---

## 💰 **2단계: 구글 애드센스 수익화**

### **🎯 애드센스 승인 조건**

#### **필수 요구사항**
- ✅ **도메인 소유기간**: 최소 3개월 (커스텀 도메인 권장)
- ✅ **콘텐츠 품질**: 독창적이고 유익한 콘텐츠
- ✅ **페이지 수**: 최소 15-20개 페이지
- ✅ **글자 수**: 페이지당 최소 1,500-2,000자
- ✅ **사이트 완성도**: 네비게이션, 개인정보처리방침 등
- ✅ **사이트 속도**: 모바일 기준 3초 이내 로딩

#### **정책 준수사항**
- 🚫 저작권 침해 콘텐츠 금지
- 🚫 성인/도박/불법 콘텐츠 금지
- 🚫 허위/스팸 콘텐츠 금지
- ✅ 사용자 친화적 디자인
- ✅ 반응형 웹사이트 (모바일 지원)

---

### **🔧 애드센스 승인 전략**

#### **전략 1: 게임 + 블로그 하이브리드**
```html
<!-- 사이트 구조 예시 -->
/index.html (게임 메인 페이지)
/about.html (게임 소개)
/how-to-play.html (게임 방법)
/characters/ (캐릭터 소개 15-20개 페이지)
  ├── tralala.html
  ├── bombardeiro.html
  ├── patapim.html
  └── ...
/privacy-policy.html
/contact.html
```

#### **전략 2: 정적 콘텐츠 사이트로 먼저 승인**
1. **Netlify/Vercel로 정적 블로그 생성**
2. **이탈리안 브레인롯 관련 콘텐츠 20개 작성**
   - 캐릭터 상세 설명
   - 게임 공략 가이드
   - 브레인롯 문화 분석
3. **커스텀 도메인 연결** (선택사항)
4. **애드센스 신청**
5. **승인 후 도메인을 게임 사이트로 연결**

---

### **📝 애드센스 신청 과정**

#### **Step 1: 애드센스 계정 생성**
```bash
1. https://adsense.google.com 접속
2. 구글 계정으로 로그인
3. "시작하기" 클릭
4. 웹사이트 URL 입력
5. 국가/지역 선택
6. 결제 정보 입력
```

#### **Step 2: 사이트에 애드센스 코드 추가**
```html
<!-- HTML <head> 태그 안에 추가 -->
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXX" crossorigin="anonymous"></script>
```

#### **Step 3: ads.txt 파일 생성**
```txt
// public/ads.txt 파일 생성
google.com, pub-XXXXXXXX, DIRECT, f08c47fec0942fa0
```

---

### **🎮 HTML5 게임 전용 애드센스**

#### **H5 게임 광고 (베타) 활용**
```javascript
// 게임 내 광고 삽입 코드
<script>
window.adsbygoogle = window.adsbygoogle || [];
var adBreak = adConfig = function(o) {adsbygoogle.push(o);}

// 전면 광고 (게임 레벨 간)
adConfig({
  type: 'interstitial',
  timing: 'level-complete'
});

// 보상형 광고 (힌트 제공 등)
adConfig({
  type: 'rewarded',
  reward: 'hint'
});
</script>
```

---

### **💡 수익 최적화 팁**

#### **광고 배치 전략**
- 🎯 **게임 시작 전**: 전면 광고
- 🎯 **문제 간격**: 중간 배너 광고
- 🎯 **결과 화면**: 하단 배너 광고
- 🎯 **힌트 기능**: 보상형 비디오 광고

#### **예상 수익 계산**
```bash
공식: 방문자 수 × 클릭률(1-3%) × CPC(₩50-200) × 0.68(구글 수수료)

예시:
- 일 방문자: 1,000명
- 클릭률: 2% 
- CPC: ₩100
- 수익: 1,000 × 0.02 × 100 × 0.68 = ₩1,360/일
```

---

## ⚡ **빠른 시작 체크리스트**

### **1주차: 사이트 준비**
- [ ] GitHub 저장소 생성
- [ ] HTML 게임 파일 업로드
- [ ] GitHub Pages 활성화
- [ ] 기본 페이지들 생성 (about, contact 등)

### **2주차: 콘텐츠 작성**
- [ ] 캐릭터별 상세 페이지 15-20개 작성
- [ ] 게임 가이드 콘텐츠 작성
- [ ] 개인정보처리방침 작성
- [ ] 사이트맵 생성

### **3-4주차: 애드센스 신청**
- [ ] 커스텀 도메인 구매 (권장)
- [ ] 애드센스 계정 생성
- [ ] 사이트 코드 삽입
- [ ] ads.txt 파일 업로드
- [ ] 승인 대기 (2-4주)

### **승인 후: 수익화**
- [ ] 광고 단위 생성
- [ ] 게임에 광고 코드 삽입
- [ ] 수익 최적화 및 분석

---

## 🎉 **최종 추천 로드맵**

1. **GitHub Pages로 즉시 배포** (무료, 빠름)
2. **정적 콘텐츠 20개 페이지 준비**
3. **도메인 구매** (.com 도메인, 연간 $10-15)
4. **애드센스 신청** 
5. **승인 후 H5 게임 광고 베타 신청**

이 방법으로 **월 $50-200** 정도의 안정적인 수익을 기대할 수 있으며, 트래픽 증가 시 수익도 비례해서 상승합니다! 🚀