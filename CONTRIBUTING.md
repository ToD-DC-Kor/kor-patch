# 프로젝트에 기여하기

다음과 같은 방법으로 프로젝트에 기여할 수 있습니다.

- 게임 플레이 후 화면에 잘못 표기되는 번역 문자열 [이슈](https://github.com/ToD-DC-Kor/kor-patch/issues/new/choose) 제보
- 번역 오류/교정 Pull Request(PR) 작성
- 그 외 기여

## 번역 교정

### RSCE 번역 수정에 대해 Pull Request(PR) 작성하기

1. GitHub Desktop 등을 사용하여 저장소를 로컬에 내려 받습니다.
[GitHub Desktop 설치 도움말](https://docs.github.com/ko/desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop).
2. [VS Code](https://code.visualstudio.com/download) 등의 도구를 사용하여 RSCE 파일을 수정합니다. (메모장을 사용하지 마세요)
3. 수정이 완료되면 GitHub Desktop 등을 사용하여 변경사항을 Commit으로 만들고 Push합니다.
4. GitHub 웹에서 Pull Request(PR)를 생성합니다. [GitHub Pull Request 도움말](https://docs.github.com/ko/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

### RSCE 원문과 번역 비교하기

원문의 확인이 필요할 경우, Git 저장소의 Commit history를 통해 확인할 수 있습니다.

#### Git에 익숙하지 않은 경우

- [GitHub File Diff](https://chromewebstore.google.com/detail/github-file-diff/lmhbkinmjbfihpkihjdhcagnigpklinh?pli=1) Chome 확장 프로그램을 설치합니다.
  - FireFox 용: <https://addons.mozilla.org/en-US/firefox/addon/github-file-diff/>  

확인을 원하는 파일을 GitHub 웹에서 찾아 선택합니다. 오른쪽 위의 `History` 버튼을 클릭합니다.

![step1](./guide/step1.png)

클릭하면 해당 파일이 속한 Commits 목록이 나타납니다. 가장 하단에 있는 것이 원문이 포함된 Commit입니다. 해당 커밋 바로 다음 Commit의 ID를 클릭합니다.

![step2](./guide/step2.png)

클릭하면 미리 설치한 확장 프로그램에 의해서 선택한 파일에 대한 변경 사항만 보여줍니다. 이를 통해 원문과 번역을 비교할 수 있습니다.

![step3](./guide/step3.png)

#### Git에 익숙한 경우

`./translations/RSCE/` 디렉토리의 최초 커밋에 원본 파일이 포함되어 있습니다. 최초 커밋을 참조하여 원문과 번역을 비교하고 수정하면 됩니다.

## 그 외 기여

Issues에서 [🐤 good first issue](https://github.com/ToD-DC-Kor/kor-patch/issues?q=is%3Aissue+is%3Aopen+label%3A%22%F0%9F%90%A4+good+first+issue%22) Label이 달린 항목을 클릭하여 도움이 필요한 이슈를 확인하고 기여해보세요.
