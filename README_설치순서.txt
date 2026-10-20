ARCH VISUAL 관리자형 사이트 설치 순서

1. github.com 에 가입하고 이메일 인증
2. GitHub 새 저장소(repository) 생성: 예 archvisual-website (Private 추천)
3. 이 ZIP 압축을 풀고, 내부 파일 전부를 저장소 최상위에 업로드 (숨김파일 .pages.yml 반드시 포함)
4. pagescms.org -> Sign in with GitHub -> GitHub App 승인 -> 해당 저장소 선택
5. 관리자 화면: 작품 이미지 관리 / 홈페이지 글 · 연락처
6. Cloudflare -> Workers & Pages -> Create application -> Pages -> Import an existing Git repository -> GitHub 연결 -> archvisual-website 선택
   Build command: 비워두기 / Build output directory: / 또는 . (설정 UI에 따라) / Root directory: 저장소 최상위
7. 새 pages.dev 주소에서 수정 테스트 후 기존 도메인 이전

중요: 기존 archvisual-portfolio는 Direct Upload 프로젝트입니다. Git 연동으로 바꿀 수 없어 새 Pages 프로젝트가 필요합니다. 기존 프로젝트 삭제/도메인 변경은 아직 하지 마세요.
현재 작품 이미지는 Wix의 공개 이미지 주소를 임시로 사용하며 원본 이미지의 자체 업로드가 권장됩니다.
Cloudflare 무료 호스팅 및 Pages CMS 무료 서비스 사용 조건은 각 서비스 정책과 제한을 확인하세요.
