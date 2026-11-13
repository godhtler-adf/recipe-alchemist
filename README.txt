레시피 연금술사 PWA 패키지

포함 파일
- index.html: 기존 레시피 연금술사 원본에 PWA 설정을 추가한 파일
- manifest.json: 앱 이름, 아이콘, 실행 방식
- sw.js: 앱 화면 캐시 및 기본 오프라인 진입 지원
- icons/: 홈 화면 아이콘

배포
1. GitHub에서 새 Public Repository를 만듭니다.
2. 이 ZIP을 풀고, 안의 파일과 icons 폴더를 Repository 최상위에 업로드합니다.
3. Repository > Settings > Pages에서 Deploy from a branch를 선택합니다.
4. Branch는 main, 폴더는 /(root)로 지정하고 Save를 누릅니다.
5. 배포된 https://계정명.github.io/저장소명/ 주소를 Android Chrome에서 엽니다.
6. Chrome 메뉴(⋮) > 앱 설치 또는 홈 화면에 추가를 선택합니다.

주의
- AI 레시피 생성 기능은 인터넷 연결과 Gemini API 키가 필요합니다.
- API 키는 HTML 파일에 직접 적어 공개하지 마세요. 앱의 API 키 입력창에 본인 키를 입력하세요.
- 이 패키지는 앱 설치 및 기본 화면 캐시를 지원합니다. Tailwind/Lucide CDN과 Gemini/이미지 API 기능은 인터넷이 필요합니다.
