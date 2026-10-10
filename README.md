# Agent Browser (내 PC) — 배포 파일

AI(Claude Code · Codex · Cursor)가 내 PC의 Chrome으로 웹 작업을 하는 프로그램의 설치 파일과 업데이트가 올라오는 곳입니다. 소스 코드는 비공개 저장소에 있습니다.

## 설치

1. [최신 설치 파일 받기 (agent-browser-local.zip)](https://github.com/GNchoo/agent-browser-releases/releases/latest/download/agent-browser-local.zip)
2. 압축을 풀고 **설치.cmd** 더블클릭 (관리자 권한 필요 없음)
3. 바탕화면의 **Agent Browser (내 PC)** 아이콘으로 엽니다.

설치하면 이후 업데이트는 자동입니다.

## 업데이트의 안전성

설치된 프로그램은 `latest.json`을 확인해 새 버전을 받습니다. `latest.json`은 개발자 키로 서명되어 있고(`latest.json.sig`, Ed25519), 설치본에 들어 있는 공개키로 서명과 파일 체크섬(SHA-256)이 모두 맞을 때만 적용합니다. 이 저장소의 파일이 바뀌어도 서명이 없으면 설치본은 받아들이지 않습니다.
