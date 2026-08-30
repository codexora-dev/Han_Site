# Han 공식 웹사이트

이 폴더는 Han 프로그래밍 언어의 공식 정적 웹사이트 소스입니다.

## 구조

- `index.html`: 메인 홈 페이지
- `about.html`: Han 소개 페이지
- `getting-started.html`: 시작하기
- `docs.html`: 문서 페이지
- `ide.html`: IDE 소개
- `troubleshooting.html`: 오류 해결
- `download.html`: 다운로드
- `css/style.css`: 공통 스타일시트
- `js/main.js`: 공통 스크립트

## 로컬 실행

```bash
cd Han_Site
python -m http.server 8000
```

그다음 브라우저에서 http://localhost:8000 을 열면 됩니다.

## GitHub Pages 배포

GitHub 저장소의 루트에 이 폴더를 업로드하거나, Pages 설정에서 해당 폴더를 루트로 지정하면 정적으로 배포할 수 있습니다.

권장 구조:

- 저장소 루트: `Han`
- 웹사이트 루트: `Han_Site/`
- GitHub Pages: `Han_Site/` 폴더를 퍼블리싱 소스로 설정

## 참고

- 공식 GitHub: https://github.com/codexora-dev/Han
- 현재 저장소의 실제 구현 범위와 문서를 기준으로 작성했습니다.
- 실제 배포 파일이 없는 경우 "준비 중"으로 안내하고 있습니다.
