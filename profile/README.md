# O-BAB 서비스 소개

O-BAB은 오늘의 식사 메뉴를 추천해주고, 필요한 레시피를 검색할 수 있는 플랫폼입니다. 사용자는 날씨와 기분에 따라 식사 메뉴를 추천받고, 좋아하거나 자주 먹는 음식을 즐겨찾기에 추가할 수 있습니다. 또한, 냉장고에 남아 있는 재료를 이용한 레시피 검색, 편의점 꿀조합 레시피, 방송에서 핫한 레시피, 음식 양념 레시피 등 다양한 기능을 제공합니다.

<br/>

## 📌 기능

- OPENAI를 이용하여 날씨 및 그날 기분에 따른 식사 메뉴 추천
- 즐겨찾기 기능을 통해 자주 먹는 음식 관리
- 음식점 위치 확인 및 리뷰 확인 기능
- 냉장고에 남은 재료를 활용한 레시피 검색
- 편의점 꿀조합 레시피 보기
- 방송에서 인기 있는 레시피 보기
- 다양한 음식 양념 레시피 제공

<br/>

## 사용 기술 스택

| **분야**        | **기술 스택**                                                                                   |
|-----------------|-------------------------------------------------------------------------------------------------|
| **프론트엔드**  | JavaScript, React, Recoil, React-Query, HTML, CSS, TailwindCSS, Material UI                     |
| **백엔드**      | Python 3.11.6, Django 5.0.3, DRF 3.14.0                                                         |
| **DB**          | PostgreSQL                                                                                      |
| **Infra**       | AWS (계획 중), Route 53, SSL                                                                    |
| **API**         | Kakao API, Google API, Naver API, OPENAI API                                                    |
| **기타**        | SSE, Web Socket, SEO                                                                            |

<br/>

## 프로젝트 구성도

```
O-BAB/
├── obab-client/      # JavaScript, React 기반 화면단 구축
└── obab-server/      # Python, Django로 서버 및 DB 구축
```

<br/>

## Getting Started

프로젝트의 각 부분에 대한 자세한 설명은 해당 디렉토리의 README.md 파일을 참조하십시오.

- [Front-End 리포지토리](https://github.com/O-BAB/obab-client)
- [Back-End 리포지토리](https://github.com/O-BAB/obab-server)
