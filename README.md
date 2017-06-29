# ![SkyEngine Logo](https://raw.githubusercontent.com/Hanul/SkyEngine/master/logo.png)
SkyEngine은 [UPPERCASE](http://uppercase.io) 기반 2D 게임 엔진입니다.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## 특징
* HTML5 Canvas 기반 게임 엔진입니다.
* 모든 게임 오브젝트는 [노드](DOC/Node.md) 트리로 이루어져 있습니다.
* 웹 페이지 전체 화면을 게임 화면으로 사용합니다.
* 화면의 가운데가 0, 0 좌표 입니다.

## 다른 게임 엔진과의 차이점
* 이벤트 기반으로 게임이 동작합니다. 즉 일반적인 게임 엔진 에서의 `step`, `update` 등의 함수를 작성하지 않습니다.
* 텍스쳐를 더 이상 생각하지 않아도 됩니다.

## 모듈 시스템
SkyEngine은 기본적으로 스프라이트 기반 2D 게임 개발에 적합합니다. 아래 모듈을 사용하여 추가적인 기능 확장을 할 수 있습니다. 또한 직접 모듈을 만들어 사용하는 것도 가능합니다.
- 물리엔진 모듈
- Spine 모듈

## 설치하기
프로젝트의 `DEPENDENCY` 파일에 `Hanul/SkyEngine`를 추가합니다.

## 구성 요소
SkyEngine은 다음과 같은 것들로 구성되어 있습니다.

### [노드](DOC/Node.md)
SkyEngine의 모든 구성요소는 노드를 확장합니다.

### [스크린 노드](DOC/Screen.md)
게임 화면 전체를 다루는 오브젝트입니다. 모든 노드는 스크린 노드 하위 노드로 구성됩니다.

### 도형 노드
* 직선 노드
* 사각형 노드
* 원형 노드
* 폴리곤 노드

### 이미지 노드
* 이미지 노드
* 스프라이트 애니메이션 노드
* 실루엣 노드
* 배경 노드

### 상태 세트 노드

### DOM 노드

### 타일 시스템 노드
* 타일 노드
* 충돌 타일 노드
* 타일맵 노드
* 아이소메트릭 타일맵 노드
* 헥사곤 타일맵 노드

### 파티클 노드
파티클 노드는 개발중입니다.

## 기타 문서
* [튜토리얼](DOC/Tutorial.md)
* [API 문서](API/README.md)

## TODO
https://trello.com/b/S3rayJx2/skyengine

## 라이센스
[MIT](LICENSE)

## 작성자
[Young Jae Sim](https://github.com/Hanul)