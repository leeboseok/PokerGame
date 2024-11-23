# PokerGame
This project marks my first attempt at OOP.

## 개발 환경
- Java 8

## 카드 게임 규칙
- **플레이어 수**: 1명에서 4명까지 가능합니다.
- **승리 조건**:
  - 승리자가 한 명도 없을 경우, 모든 플레이어가 승리로 처리됩니다.
  - 두 명 이상의 플레이어의 카드 랭크가 동일할 때, 더 높은 카드 랭크를 가진 플레이어가 없으면, 동일한 랭크를 가진 모든 플레이어가 승리합니다.

## 요구 사항
        1. 게임 당 한벌의 카드만 사용. 카드 한벌은 서로 다른 52장의 카드로 구성.
        2. 카드게임은 최대 4명의 플레이어가 참가 가능
        3. 각 플레이어에게는 게임머니 10000원이 제공된다.
        4. 각 플레이어는 자신만의 고유한 nickname을 기지며 nickname의 길이는 20자를 넘지못한다.
        5. 딜러는 플레이어에게 서로 다른 5장의 카드를 나눠준다.
        6. 딜러는 플레이어의 카드를 평가하고 결과를 점수로 반환한다.(점수가 높을 수록 좋음)
        7. 카드의 평가는 일반적인 포커의 랭크를 참고하여 높은 랭크에게 더 높은 점수를 준다.
        8. 매 게임마다 딜러는 각 플레이어의 카드를 평가하여 결과를 출력한다.
        9. 게임에서 승리한 플레이어는 상금 100원과 1승이 추가되고 나머지 플레이어는 상금 0원과 1패가 추가된다.
        10. 100번의 게임을 자동적으로 반복해서 실행하여 최종 결과를 승리의 수가 많은 플레이어부터 내림차순으로 정렬하여 화면에 출력한다.

## 향후 지속적인 개선 사항
  - 동일한 랭크가 나왔을 때의 승리자 처리 로직 추가
  - 예외 처리 기능 구현
  - 닉네임 중복 확인 기능 추가
  - 람다식을 사용하여 코드 작성
  - 객체지향 원칙에 따라 개발
  - 테스트 코드를 작성하여 게임 로직 테스트

## 계획
- 위의 보완 사항들을 구현하여 게임의 안정성과 사용자 경험을 향상시킬 예정입니다.

## 설치 및 실행
1. 이 레포지토리를 클론합니다.
   ```bash
   git clone https://github.com/leeboseok/KDT_DBE2_Java-OOP_Assignment.git
