## Use Case

| Actor              | Actor’s Goal                                  | Use Case Name                |
| ------------------ | --------------------------------------------- | ---------------------------- |
| 구매자             | 올바른 사용자인지 인증 하는 것                | UC-1: User Authentication    |
| 구매자             | 원하는 메뉴를 선택하여 주문을 하는 것         | UC-2: Order, UC-9: Show Menu |
| 구매자             | 충전해둔 금액을 이용하여 결제하는 것          | UC-2                         |
| 구매자             | 자신이 먹은 음식에 대한 평점을 남기는 것      | UC-3: Add Review             |
| 판매자             | 아이디와 비밀번호를 입력하여 로그인하는 것    | UC-4                         |
| 판매자             | 메뉴와 정보를 변경하는 것                     | UC-5: Modify Menu            |
| 판매자             | 주문을 수락, 거절 하는 것                     | UC-7: Take Order             |
| 판매자             | 완료된 음식을 표시하는 것                     | UC-7: Notify Cooked          |
| Online Server      | 사용자의 주문 내역을 기록한다.                | UC-7                         |
| Recommender System | 사용자별 기록을 토대로 추천순위를 제공하는 것 | UC-9: Show Menu              |
| Alarm System       | 주문의 현황을 알려준다                        | UC-2, UC-7                   |
