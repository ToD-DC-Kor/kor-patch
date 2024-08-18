# Tales of Destiny Director's Cut (PS2) 한국어화 패치

## 진행 상황

### 요약

시나리오와 아이템은 AI를 통한 기계 번역이 완료되어, 번역 품질에 신경쓰지 않는다면 초반 플레이는 가능하다고 생각되는 수준.

### 스크린샷

![select_story](./screenshots/select_story.png)
![main_menu](./screenshots/main_menu.png)
![scenario](./screenshots/scenario.png)
![item](./screenshots/item.png)
![weapon](./screenshots/weapon.png)
![skill](./screenshots/skill.png)

### 상세

추출된 모든 문자열에 대해서는 AI 기계 번역 완료

- 시나리오 대사
  - 추출: RSCE 100%, SLPS 90%+?, PAK 0%
  - 검수: 0%
- 전투 튜토리얼: 0%
- 스킷: 0%
- 영상 자막:
  - 추출: 99%? (불확실)
  - 검수: 0%
- 지명: 0%
- 아이템 설명
  - 추출: 99%
  - 검수: 0%
- 몬스터 도감: 0%
- UI 메뉴
  - 추출: SLPS 99%, PAK 0%
  - 검수: 0%
- 그래픽: 0%

## 배포 주기 & 다운로드

패치는 갱신이 있을 때마다 수시로 배포.

다운로드는 [Releases 페이지](https://github.com/ToD-DC-Kor/kor-patch/releases)에서 확인. XDelta를 이용하여 원본 ISO에 패치.

## 번역 기여

GitHub Issue나 Pull Request를 통해 기여할 수 있습니다. [GitHub Pull Request 도움말](https://docs.github.com/ko/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request), [GitHub Desktop 설치 도움말](https://docs.github.com/ko/desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop)

번역 작업에 대한 것은 [CONTRIBUTING.md](./CONTRIBUTING.md)을 참고하세요.

## 제보

제보는 이슈를 이용하세요.

- 버그 제보, 번역 오류 제보: <https://github.com/ToD-DC-Kor/kor-patch/issues/new/choose>

## Tools

- [Ghidra](https://ghidra-sre.org/)
- [Ghidra Emotion Engine: Reloaded](https://github.com/chaoticgd/ghidra-emotionengine-reloaded)
- [PCSX2](https://pcsx2.net/) Debugger
- [ImHex](https://github.com/WerWolv/ImHex)
- [XDelta](https://www.romhacking.net/utilities/928/)
- [Tales of Destiny Driector's Cut Tools](https://www.romhacking.net/utilities/1419/)
- forked version of [sceWork](https://github.com/lifebottle/sceWork)
- [Pakcomposer Clone](https://github.com/lifebottle/Tales-of-Destiny-DC/tree/master/pakcomposer)
- Hand-maded tools:
  - SLPS string patcher
  - SLPS string find & extractor
  - ISO Patcher
  - LLM Translator
  - Font image creator
  - Memory address converter
  - Hangul(Korean alphabet) font mapper

## Credits

- RangerRus, [Tales of Destiny Driector's Cut Tools](https://www.romhacking.net/utilities/1419/)
  - Thanks to RangerRus for creating this tool. It has become very easy to extract game data.
- Tales of Destiny DC English Translation Team(Life Bottle), [Repository](https://github.com/lifebottle/Tales-of-Destiny-DC).
  - Thanks to the Tales of Destiny DC English Translation Team(Life Bottle). The information they left in the repository has saved me a lot of time.
