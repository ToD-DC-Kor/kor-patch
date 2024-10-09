# 프로젝트에 기여하기

다음과 같은 방법으로 프로젝트에 기여하여 패치 제작에 참여할 수 있습니다.

- 도움 이슈에 기여하기
- 게임 플레이 후 화면에 잘못 표기되는 번역 문자열 [이슈](https://github.com/ToD-DC-Kor/kor-patch/issues/new/choose) 제보
- 번역 오류/교정 제보 또는 Pull Request(PR) 작성

## 도움 이슈에 기여하기

Issues에서 [🐤 help wanted](https://github.com/ToD-DC-Kor/kor-patch/issues?q=sort%3Aupdated-desc+is%3Aissue+is%3Aopen+label%3A%22%F0%9F%90%A4+help+wanted%22) Label이 달린 항목을 클릭하여 도움이 필요한 이슈를 확인하고 기여해보세요.

## 번역 교정

### 검수 Pull Request(PR)에 참여하기

[Pull requests](https://github.com/ToD-DC-Kor/kor-patch/pulls) 메뉴에 들어갑니다. 참여를 원하는 항목을 선택합니다.

선택한 페이지에서 상단의 `Files changed`를 누르면 변경된 항목을 볼 수 있습니다.

![image](https://github.com/user-attachments/assets/f0632985-04ab-45a4-9e6c-15ab6dede028)

파일이 접혀 있는 경우 "Load diff`를 누르면 펼쳐집니다.

![image](https://github.com/user-attachments/assets/fc738c9b-aacc-44d1-a5a9-e416fc1b3d52)

줄 번호를 눌러서 댓글을 달 수 있습니다. 검수 중 이상한 부분이나 의견이 필요한 부분에 달아주세요!

![image](https://github.com/user-attachments/assets/850043c1-15db-45dc-8f67-417c27c25de6)
(마우스를 올리면 버튼이 보입니다)

자세한 설명은 [#72](https://github.com/ToD-DC-Kor/kor-patch/issues/72) 이슈를 참고해 주세요.

### (고급) RSCE 번역 수정에 대해 Pull Request(PR) 작성하기

1. GitHub Desktop 등을 사용하여 저장소를 로컬에 내려 받습니다.
[GitHub Desktop 설치 도움말](https://docs.github.com/ko/desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop).
2. [VS Code](https://code.visualstudio.com/download) 등의 도구를 사용하여 RSCE 파일을 수정합니다. (메모장을 사용하지 마세요)
3. 수정이 완료되면 GitHub Desktop 등을 사용하여 변경사항을 Commit으로 만들고 Push합니다.
4. GitHub 웹에서 Pull Request(PR)를 생성합니다. [GitHub Pull Request 도움말](https://docs.github.com/ko/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

## 텍스트 오류 제보

플레이 중 번역 오류, 글자 깨짐, 줄바꿈 이상, 글자 넘침 등을 발견하면 [이슈](https://github.com/ToD-DC-Kor/kor-patch/issues/new/choose)로 제보해주세요.

제보 방법은 다음과 같습니다.

1. [VS Code](https://code.visualstudio.com/download)를 다운받아 설치합니다.

2. <https://github.com/ToD-DC-Kor/kor-patch>에서 저장소의 최신 버전을 다운로드 받습니다.

   ![download repo](./guide/download_repo.png)

3. 다운받은 저장소의 압축을 풀고, VS Code로 해당 폴더를 엽니다.

4. 검색 메뉴를 통해, 번역 오류의 위치를 찾습니다. 근처에 같이 출력되는 정상 문자열을 검색합니다.

   ![search text](./guide/search_text.png)
   (예시: `13721_77.txt` 파일의 `805` 줄 번역 오류)

5. [이슈](https://github.com/ToD-DC-Kor/kor-patch/issues/new/choose)로 문제가 발생한 스크린샷 또는 번역 오류의 위치(파일명, 줄 번호)를 제보합니다.
