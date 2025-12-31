# 선(한) 결제 - 랜딩 페이지

투명하고 따뜻한 선결제 기부 문화를 만들어갑니다.

## 소개

이 레포지토리는 **선(한) 결제** 서비스의 공식 랜딩 페이지입니다. Jekyll을 사용하여 GitHub Pages로 배포됩니다.

## 로컬 개발

### 요구사항

- Ruby 3.0+
- Bundler

### 설치 및 실행

```bash
# 의존성 설치
bundle install

# 로컬 서버 실행
bundle exec jekyll serve
```

브라우저에서 `http://localhost:4000/prepaid-landing/` 접속

## 배포

`main` 브랜치에 푸시하면 GitHub Actions를 통해 자동으로 GitHub Pages에 배포됩니다.

## 구조

```
├── _config.yml          # Jekyll 설정
├── _layouts/
│   └── default.html     # 기본 레이아웃
├── index.md             # 메인 페이지
├── privacy-policy.md    # 개인정보처리방침
├── terms-of-service.md  # 이용약관
└── images/              # 스크린샷 이미지
```

## 라이선스

© 2025 공명. All rights reserved.
