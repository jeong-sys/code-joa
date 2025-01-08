# 6팀 깃헙 협업 연습

## 상품 추가
- ITEM.md 추가

## **Commit Message Convention**

```
TaskNo (type) : subject
<BLANK LINE> // 구분줄
body
<BLANK LINE> // 구분줄
footer

ex)
COM-2 feat: About the team 개발
CR-18 feat: 메인페이지 개발
SR-22 fix: User 테이블 필드 수정
```

## 1. TaskNo

각 Task Card Number 를 작성한다.

## 2. Type

commit message의 의도를 다른 사람들에게 전달하기 위해 표시

| Type | Description |
| --- | --- |
| fix | 버그를 수정한 경우 |
| feat | 새로운 기능을 추가한 경우 |
| breaking change | 큰 API 변경이 있는 경우 |
| hotfix | 치명적인 버그를 급하게 수정해야 하는 경우 |
| style | 코드 포맷 변경, 세미 콜론 누락 등 코드 수정이 없는 경우 |
| refactor | 프로덕션 코드 리팩토링 |
| comment | 필요한 주석 추가 및 변경 |
| docs | 문서를 수정한 경우 |
| test | 테스트를 추가한 경우 |
| chore | 빌드 테스트 업데이트, 패키지 매니저를 설정하는 경우 |
| rename | 파일 혹은 폴더명을 수정하거나 옮기는 작업을 한 경우 |
| remove | 파일을 삭제하는 작업을 한 경우 |

**브레이크 체인지 여부**: <is breakchange>

> 브레이크 체인지란?
> 
> 
> 변경내용에 대한 설명을 body에 작성
> 

브레이크 체인지가 존재하는 커밋의 경우에는 제목 뒤에 '!' 을 추가합니다.

예시

- feat!: 랭킹 점수 계산 공식 변경 *// 변경(change)되었으니 잠깐 멈춰서(break) 이 커밋을 읽어주세요!*
- feat: 로그인 기능 구현

## 2. S**ubject**

- 제목은 티켓명과 동일하게 한다.
- 마침표를 찍지 않는다.
- 티켓이 겹칠 경우 [ *** ] (대괄호) 안에 간략히 작성한다.
    - ex ) 물품 Image 저장 Util 구현
    - ex ) 물품 Image 저장 Util 구현 [ Image Naming Policy 작성 ]

## 3. **Body**

- 본문은 한 줄 당 100자 이내로 작성한다.
- 최대한 간단하게 작성한다.
- 상세한 내용은 Notion Task Card 에 작성한다.
- '어떻게' 보단 '무엇을', '왜' 변경했는지를 설명한다.
- ‘어떻게’ 는 Task Card 에 작성한다.

## 4. F**ooter**

- 꼬리말은 작성하지 않는다.

## **5. Pull Request**

- 제목은 '[#TaskCardNo] 변경 사항' 구조로 작성할 것

예시:

- [2] 로그인 기능
- [11] 게시글 업로드 기능 구현
