# Paulina Youn - Portfolio

개인 포트폴리오 메인 페이지입니다.

## 🌟 Features

- 모던하고 깔끔한 디자인
- 반응형 레이아웃 (모바일/태블릿/데스크톱)
- 프로젝트 카드 레이아웃
- GitHub Pages 최적화

## 🚀 GitHub Pages 배포 방법

### 1. GitHub 저장소 생성
```bash
# Git 초기화
git init

# 파일 추가
git add .

# 커밋
git commit -m "Initial commit: Portfolio main page"

# GitHub에 원격 저장소 추가
git remote add origin https://github.com/paulinayoun/paulinayoun.github.io.git

# 푸시
git push -u origin main
```

### 2. GitHub Pages 설정
1. GitHub 저장소로 이동
2. `Settings` > `Pages` 메뉴 선택
3. Source를 `main` 브랜치로 설정
4. 저장 후 몇 분 기다리면 `https://paulinayoun.github.io`로 접속 가능

### 3. 서브 프로젝트 연결
서브 프로젝트들은 별도의 저장소로 관리하고 GitHub Pages로 배포하세요:

- **Todo 앱**: `paulinayoun/todo` 저장소 생성 후 `https://paulinayoun.github.io/todo`로 접근
- **Season Pick**: `paulinayoun/seasonpick` 저장소 생성 후 `https://paulinayoun.github.io/seasonpick`로 접근

각 서브 프로젝트 저장소의 Settings > Pages에서 배포 설정을 하면 자동으로 서브 도메인에 연결됩니다.

## 📁 프로젝트 구조

```
paulinayoun.github.io/
├── index.html          # 메인 HTML 파일
├── style.css           # 스타일시트
└── README.md          # 문서
```

## 🎨 커스터마이징

### 개인 정보 수정
`index.html` 파일에서 다음 항목들을 수정하세요:
- 이름과 타이틀
- 소개 문구
- 프로젝트 설명
- 연락처 정보 (GitHub, Email)

### 스타일 변경
`style.css` 파일의 `:root` 섹션에서 색상 테마를 변경할 수 있습니다:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* ... */
}
```

## 📝 License

MIT License - 자유롭게 사용하세요!
