# PARK HYUN YOUNG 포트폴리오

블랙 배경, 형광 연두·오렌지 포인트를 사용한 반응형 포트폴리오입니다.
HTML·CSS·JavaScript는 index.html 한 파일에 포함되어 있습니다.

## 포함 파일

| 파일 | 용도 |
| --- | --- |
| index.html | 실제 홈페이지. 파일 이름을 그대로 유지하세요. |
| .nojekyll | Jekyll 처리를 생략하고 정적 파일을 그대로 배포합니다. 빈 파일이 정상입니다. |
| README.md | 이 업로드 및 운영 안내입니다. |

별도 설치, 빌드 명령, package.json, GitHub Actions 설정 파일은 필요하지 않습니다.

## GitHub 웹사이트에서 업로드하기

1. ZIP을 컴퓨터에서 압축 해제합니다. ZIP 자체를 저장소에 업로드하지 마세요.
2. GitHub에 로그인한 뒤 새 저장소(New repository)를 만듭니다.
3. Repository name은 예를 들어 `portfolio`로 입력합니다. 실제 주소에는 본인이 정한 저장소 이름이 사용됩니다.
4. GitHub Free 계정으로 무료 Pages를 사용하려면 Public 저장소를 선택합니다. 공개하면 페이지의 이메일과 콘텐츠도 인터넷에서 볼 수 있습니다.
5. Create repository를 누릅니다.
6. 새 저장소의 `uploading an existing file` 링크 또는 `Add file → Upload files`를 선택합니다.
7. 압축 해제 폴더 자체가 아니라 **폴더 안의 파일**을 업로드합니다. 저장소 최상위에 index.html이 바로 있어야 합니다.
8. index.html, README.md, .nojekyll을 선택하고 `Commit changes`를 누릅니다. 일반적으로 첫 브랜치 이름은 main입니다.
9. .nojekyll이 컴퓨터에서 보이지 않으면 숨김 파일 표시를 켭니다. 웹에서 직접 만들려면 `Add file → Create new file`을 선택하고 파일명을 `.nojekyll`로 입력한 다음 빈 줄을 넣고 커밋해도 됩니다.

## GitHub Pages 켜기

1. 저장소의 `Settings → Pages`로 이동합니다.
2. `Build and deployment → Source`에서 **Deploy from a branch**를 선택합니다.
3. `Branch`는 **main**, 폴더는 **/(root)**로 선택합니다. 실제 브랜치가 main이 아니면 파일을 올린 브랜치를 선택합니다.
4. `Save`를 누릅니다.
5. 배포가 끝나면 같은 Pages 화면에 표시되는 `Visit site` 링크로 접속합니다. 업로드 직후에는 잠시 기다려야 할 수 있습니다.
6. HTTPS 설정이 제공되면 `Enforce HTTPS`를 켭니다.

일반 저장소의 주소 형식: `https://GITHUB_ID.github.io/REPOSITORY/`
예시: 저장소 이름이 portfolio이면 `https://GITHUB_ID.github.io/portfolio/`
여기서 GITHUB_ID는 본인 계정명이며, 위 주소는 예시입니다.
저장소 이름을 정확히 `GITHUB_ID.github.io`로 만들면 기본 주소는 `https://GITHUB_ID.github.io/`가 됩니다.

## 나중에 내용 수정하기

- 저장소의 index.html을 수정하고 커밋하면 Pages가 다시 배포합니다.
- 이름은 PARK HYUN YOUNG으로 반영되어 있습니다.
- 기존 디자인, 내용, 링크 및 회색 사진 자리를 그대로 유지했습니다.
- Pretendard는 외부 CDN에서 불러옵니다. 인터넷 연결이 없으면 시스템 글꼴로 표시됩니다.
- 사진을 넣으려면 사진 파일을 저장소의 images 폴더 등에 올리고, 해당 회색 자리 요소를 `<img src="./images/photo.jpg" alt="사진 설명">` 형태로 교체하세요. 실제 파일명과 대소문자가 일치해야 합니다. 현재 패키지에는 사진 파일이 없습니다.
- 노션의 내용을 수정해도 이 정적 HTML에 자동 반영되지는 않습니다.

## 문제 해결

- 404가 보이면 Pages 설정의 브랜치와 /(root), 저장소 최상위의 index.html 이름을 확인합니다.
- 페이지 대신 저장소 파일 목록이 보이면 github.com 주소가 아닌 Pages의 Visit site 주소를 엽니다.
- 변경 내용이 바로 안 보이면 배포 완료를 확인한 뒤 Ctrl+F5로 새로고침합니다.
- Pages 배포 실패는 저장소 Actions 탭에서 확인할 수 있습니다.

## 공식 안내

- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
