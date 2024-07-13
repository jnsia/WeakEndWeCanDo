# Weak? End. We Can Do!

## 릴리즈 노트

- v 1.0.1 (2024.07.12)
  - GitHub Actions - Firebase CI/CD 자동화
  - 스타일 일부 수정

- v 1.0.0 (2024.06.15)
  - (new) 릴리즈 노트 작성

## 프로젝트 URL

**https://weak-end.web.app**

Firebase Hosting을 통해 배포하였습니다.

## 기획의도

대학교 시험 기간 중 힘들어하는 친구들을 응원하고 싶었으며,
작은 글귀를 모아둔 책자를 웹 사이트로 구현해보고 싶었습니다.

## 프로젝트 기간
2022.10 ~ 2022.10 (1주)

## 개발 환경

- Firebase v9
    - Firebase Hosting
    - Firebase Realtime Database
- React 18.2.0
- NodeJS 18.12.1

## 프로젝트하며 느낀 점

프로젝트를 완성한 지 1년 반? 정도 후에 작성하는 README이지만,
첫 프로젝트였기 때문에 아무래도 기억이 많이 남습니다.
또한 그 당시에 적은 글도 있으니 아래 링크에서 확인해보셔도 좋습니다.

[Weak? End. We Can Do! 프로젝트 회고](https://blog.naver.com/kia546/222902760512)

그리고 프로젝트를 진행하며 알게 된 점은 아래 4가지였습니다.

### ⭐ 기획 및 디자인 단계의 중요성

개발을 시작하기 전에 피그마에 그려놓은 UI를 기반으로 직접 화면을 구현하면서 깨달은 점이 여럿 있었습니다.

기획과 디자인 단계에서 디테일한 부분까지 확실히 정해두어야 프론트엔드 개발 시에 횡설수설하는 느낌이 없어질 것 같았습니다.

UI 디자인과 적절한 이미지를 찾거나 만드는 일은 아직 감이 잡히지 않았지만, 다음부터는 컴포넌트가 어떻게 나뉘어지는지 생각한 후에 피그마에서 프레임 단위로 화면을 구현해야 겠다고 생각했습니다.

### ⭐ 반응형 웹을 위한 CSS

당시 숙련도가 부족하여 bootstrap과 같은 UI 라이브러리는 사용하지 못했습니다.
또한 `%`, `vw`, `vh`, `rem` 등 반응형 css에 대한 이해도가 낮았기 때문에 반응형 css 중에서는 %를 가장 많이 사용했던 것 같습니다. (폰트 크기는 rem)

반응형 웹 UI를 위해 css와 UI 관련 라이브러리에 대한 학습이 필요하다는 것을 느꼈습니다.

### ⭐ 서버리스에 대한 개념 이해

Firebase는 대표적인 서버리스 서비스이지만, 당시에는 개념 자체가 낯설고 서버에 대한 이해도 온전하지 못했습니다.

그래서 저는 Node.js express로 server를 구현하려고 노력하였으며, express를 통해 로컬에서 서버를 가동시키면 firebase 클라우드에서 작동하는 것으로 착각하였습니다. 당연히 그렇게 작동하지 않았고 서버리스 서비스에 대한 학습을 하게 되었습니다.

또한 최신 버전인 Firebase v9 관련 자료는 v8에 비해 적었고 개발자 공식문서를 읽는 습관이 아직 체화되지 않았었기에 firebase를 어느정도 이해하고 사용하는 데에 조금 어려움이 있었습니다. 이러한 계기로 공식문서를 읽고 이해하는 것이 개발 속도에 도움이 많이 된다는 것을 알게 되었습니다.

**서버리스**: 개발자가 서버를 관리할 필요 없이 애플리케이션을 빌드하고 실행할 수 있도록 하는 클라우드 네이티브 개발 모델
