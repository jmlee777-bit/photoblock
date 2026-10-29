포토블록 (PhotoBlock) 배포 폴더

- index.html          네온 버전(메인)
- classic/index.html  기본 버전 (주소 뒤에 /classic/)
- dense/index.html    벽돌 1,080개 촘촘한 테스트 버전 (주소 뒤에 /dense/)
- shoot/index.html    위 촘촘 버전 + 카메라 플래시 연사 아이템 (주소 뒤에 /shoot/)
- shooter/index.html  공 없이 패들(카메라)이 플래시만 쏘는 슈팅 전용 버전 (주소 뒤에 /shooter/)
- shooter6000/index.html  이벤트 없이 쏘기만, 벽돌 약 6,000개 (주소 뒤에 /shooter6000/)
- shooter-events/index.html  6,000개 + 사진 속 ×3/×2/×1 블록 + 발사음 (주소 뒤에 /shooter-events/)
- manifest.webmanifest, icon-192.png, icon-512.png  홈 화면 설치용

[Vercel에 올리는 방법 1: 터미널]
1) 이 폴더에서 터미널을 열고  npx vercel  실행 (처음이면 로그인)
2) 질문에는 모두 Enter. 프레임워크는 Other, 빌드 명령과 출력 폴더는 비워 둡니다.
3) 확인되면  npx vercel --prod  로 정식 주소를 만듭니다.

[Vercel에 올리는 방법 2: GitHub]
1) 새 저장소를 만들고 이 폴더 안의 파일을 그대로 올립니다.
2) Vercel > Add New > Project 에서 저장소를 가져옵니다.
3) Framework Preset은 Other, Build Command와 Output Directory는 비워 두고 Deploy.

[폰에서 앱처럼 쓰기]
크롬에서 주소를 열고 메뉴(점 3개) > 홈 화면에 추가 (또는 앱 설치).

- shooter-click/index.html  클릭하면 발사, ×2/×3 블록은 숨김 (주소 뒤에 /shooter-click/)
- shooter-rank/index.html  클릭 발사 + 랭크(브론즈~다이아) (주소 뒤에 /shooter-rank/)
- v2/index.html  새 디자인(뷰파인더) + 랭크 + 클릭 발사 (주소 뒤에 /v2/)
- v2-clip/index.html  1.1 시험판: 클리어 후 3~5초 하이라이트 클립 만들기/공유 (주소 뒤에 /v2-clip/)
- v3/index.html  기본 사진 18장(동물·음식·로봇 등 새 캐릭터 13장 추가) + 클립 (주소 뒤에 /v3/)
