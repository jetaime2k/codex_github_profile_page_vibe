# 설계자 포트폴리오 (GitHub Pages)

정적 HTML/CSS/JS 기반 단일 페이지 포트폴리오입니다.

## 구조

- `index.html`: 단일 진입 페이지
- `assets/css/styles.css`: 디자인 시스템 및 반응형 스타일
- `assets/js/main.js`: 모바일 메뉴 토글, 푸터 연도 자동 표시
- `assets/images/`: 이미지 에셋 폴더

## GitHub Pages 배포

1. 이 폴더를 GitHub 저장소에 푸시합니다.
2. 저장소에서 `Settings > Pages`로 이동합니다.
3. `Build and deployment`에서 Source를 `Deploy from a branch`로 선택합니다.
4. Branch를 `main`, 폴더는 `/ (root)`로 설정 후 저장합니다.
5. 배포 URL 확인:
   - 유저/조직 사이트: `https://<username>.github.io`
   - 프로젝트 사이트: `https://<username>.github.io/<repo>`

## 커스터마이징 포인트

- `index.html` 내 이름/소개/프로젝트/연락처 링크를 본인 정보로 교체
- 강조색 변경: `assets/css/styles.css`의 `--color-accent`, `--color-accent-strong`
- 프로젝트 카드 추가/삭제: `#projects` 섹션의 `article.project-card` 블록 편집
