# 미술수업 스튜디오 · GitHub Pages 게시 안내

수업 모형 탐색, 질문 아카이브, 교육과정 선택, 지도안 작성·인쇄를 제공하는 웹앱입니다.
ChatGPT 로그인, 별도 서버, API 키, 빌드 작업이 필요하지 않습니다.

## 1. ZIP 압축 풀기

압축을 풀면 index.html, app.js, curriculum.js, curriculum-picker.js, style.css,
readability.css, StudioNarrow-Bold.otf 등의 파일이 보입니다.
ZIP 파일 자체를 GitHub에 올리지 말고, 압축을 푼 파일들을 올려 주세요.

## 2. GitHub 저장소 만들기

GitHub에서 New repository를 눌러 저장소 이름을 art-lesson-studio 등으로 정합니다.
일반적인 무료 GitHub 계정에서는 Public 저장소로 만드세요.
비공개 저장소의 Pages 지원 여부는 이용 중인 요금제에 따라 다릅니다.

## 3. 파일 올리기

저장소에서 Add file → Upload files를 선택합니다.
압축을 푼 폴더 안의 파일들을 모두 끌어 놓고 Commit changes를 누릅니다.
저장소 첫 화면에 index.html이 바로 보여야 합니다.
하위 폴더 안에 index.html을 넣으면 아래 설정으로 첫 화면이 열리지 않습니다.

## 4. Pages 설정

저장소의 Settings → Pages로 이동해 다음처럼 선택합니다.

- Build and deployment → Source: Deploy from a branch
- Branch: main (실제 업로드한 브랜치 이름)
- Folder: / (root)
- Save

몇 분 후 같은 Pages 화면에 게시된 사이트 주소가 표시됩니다.
주소는 https://본인아이디.github.io/저장소이름/ 형식입니다.
위 예시 주소를 그대로 쓰지 말고 Pages 화면에 표시된 실제 주소를 공유하세요.
저장소 이름이 본인아이디.github.io인 경우에는 주소 형식이 다릅니다.

## 5. 게시 확인

1. 사이트 주소를 열어 모형 카드 선택과 질문 검색을 확인합니다.
2. 지도안 만들기 → 02 목표와 탐구 질문에서 교육과정을 선택합니다.
3. 성취기준과 핵심 아이디어를 골라 작성란에 반영되는지 확인합니다.
4. 05 지도안 미리보기에서 인쇄 / PDF 저장을 확인합니다.

## 사용·저장 방식

- 방문자는 GitHub나 ChatGPT 로그인 없이 사용할 수 있습니다.
- 작성 내용은 각 방문자의 브라우저 저장소에 보관됩니다.
- 다른 기기에서 이어 쓰려면 JSON 파일 저장 후 그 기기에서 파일을 다시 여세요.
- 브라우저 데이터를 삭제하면 저장한 내용도 사라질 수 있습니다.
- 기존 ChatGPT Sites 주소의 브라우저 저장 내용은 새 GitHub Pages 주소로 자동 이전되지 않습니다.
  기존 사이트에서 JSON 파일로 저장한 뒤 새 사이트에서 불러오세요.
- 다른 사람의 작성 내용을 수집하거나 공유하는 서버 기능은 없습니다.

## 수정·업데이트

내용을 수정한 파일을 같은 저장소의 같은 위치에 업로드하고 Commit changes를 누릅니다.
Pages 배포가 끝나면 같은 주소에서 수정본이 표시됩니다.
앱 파일 경로가 상대 경로여서 일반 저장소의 하위 주소에서도 사용할 수 있습니다.

## 포함 자료와 서체

- 교육과정: 교육부 고시 제2022-33호 [별책 13] 미술과 교육과정의 성취기준 및 핵심 아이디어.
- 수업 모형: 제공된 강의 자료를 바탕으로 구성한 단계와 설계 예시.
- StudioNarrow-Bold.otf: NimbusSansNarrow-Bold 서체를 파일명만 바꾼 것으로,
  저작권 및 이용 조건은 FONT-LICENSE.txt에 수록했습니다.
- 한글은 사용자의 기기에 설치된 고딕체로 표시됩니다.

GitHub 공식 안내:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
