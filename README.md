# java-lotto-precourse

## 🚀 기능 목록

### 🎰 Application

- [x] 구매 금액을 입력 받는다.
  - [x] 구매 금액 입력 힌트를 출력한다.
- [x] 금액 유효성을 검사한다.
  - [x] 숫자인지 검사한다.
    - [x] 숫자가 아니라면 `IllegalArgumentException`을 발생시킨다.
  - [x] 금액이 1000원 단위인지 검사한다.
    - [x] 금액이 1000원 단위가 아니라면 `IllegalArgumentException`을 발생시킨다.
- [x] 로또 번호를 생성한다.
  - [x] 금액을 1000으로 나누어 로또 개수를 구한다.
  - [x] 로또 개수 만큼 랜덤 번호를 생성한다.
    - [x] 생성된 랜덤 번호로 Lotto 인스턴스를 생성한다.
  - [x] 생성된 로또 번호를 출력한다.
- [x] 로또 당첨 번호를 입력받는다.
  - [x] 로또 당첨 번호 입력 힌트를 출력한다.
  - [x] 당첨 번호 유효성을 검사한다.
    - [x] 숫자인지 검사한다.
      - [x] 숫자가 아니라면 `IllegalArgumentException`을 발생시킨다.
    - [x] 당첨 번호가 6개인지 검사한다.
      - [x] 당첨 번호가 6개가 아니라면 `IllegalArgumentException`을 발생시킨다.
    - [x] 로또 당첨 번호가 1~45 사이의 숫자인지 검사한다.
      - [x] 로또 당첨 번호가 1~45 사이의 숫자가 아니라면 `IllegalArgumentException`을 발생시킨다.
- [x] 보너스 볼을 입력받는다.
  - [x] 로또 당첨 번호 입력 힌트를 출력한다.
- [ ] 당첨 여부를 통계를 확인한다.
  - [ ] 각 Lotto 인스턴스에 로또 당첨 번호를 비교한다.
  - [ ] 당첨 통계 배열에 0번 인덱스부터 3개 일치하는 로또의 수를 저장한다.
- [ ] 당첨 통계를 출력한다.
- [ ] 총 수익률을 계산한다.
  - [ ] 수익률을 출력한다.

### 🎟️ Lotto

- [ ] 당첨 번호와 보너스 번호를 입력받아 비교하여 일치하는 수를 반환한다.
