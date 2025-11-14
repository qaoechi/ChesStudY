# ChesStudY
디자인 패턴을 활용한 체스 오프닝 연구 노트

## 프로젝트 소개
ChesStudY는 체스 오프닝 연구하고 기록하는 프로그램입니다. <br>
객체 지향 개념을 이해하고, 다양한 디자인 패턴을 적용해보기 위해 체스를 주제로 개발을 하고 있습니다. 

## 배경
+ 기존 체스 플랫폼(Chess.com, lichess)은 영어로 작성된 연구가 많음
+ 연구에서 코멘트가 기보에 텍스트로 적혀있어 보기 불편함
+ 초보자가 보기에 오프닝의 흐름과 전환을 catch하기 어려움
+ stockfish가 최선 수 상위 몇 개를 보여주나, 설명이 없어 이해할 수 없음

## 목표 기능
+ 현 포지션에서 좋은 수, 나쁜 수 등을 구분하여 시각적 제공
+ 현 포지션의 전략적 의도 요약
+ 오프닝 전환 표현
+ 포지션을 Tree로 묶어 추적

## Tech
| pattern | 적용 |
| :--- | :---: |
| Decorator | 기보 |
| Object | 기물 흑백 |
| Strategy | 기물 행마법 |
| State | 기물 행동 |

[code](https://github.com/qaoechi/chess)
## 화면(예정)
<img width="4162" height="2198" alt="Image" src="https://github.com/user-attachments/assets/d3d34ccc-2698-4438-a4ae-67d5c0283eb5" />

## UML
![Image](https://github.com/user-attachments/assets/669c35b1-d0bd-4d9a-b639-7f6983581977)
