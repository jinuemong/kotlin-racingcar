# kotlin-racingcar

# 미션 - 자동차 경주

## 🔍 기능 목록

- [ ] 자동차 이름 입력
    - `각 자동차에 이름을 부여할 수 있다.`
    - [x] 자동차 이름 입력 안내 문구 "경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)"를 출력한다.
    - [ ] 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.
        - [ ] 자동차 이름은 쉼표(,)를 기준으로 구분한다.
        - [ ] 자동차 이름에 공백이 없어야 한다.
        - [ ] 자동차 이름은 5자 이하만 가능하다.
        - [ ] 자동차 이름이 입력되지 않았다.
        - [ ] 자동차 이름은 중복이 불가능하다.


- [ ] 시도할 횟수 입력
    - `사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.`
    - [ ] 시도할 횟수 입력 안내 문구 "시도할 횟수는 몇 회인가요?"를 출력한다.
    - [ ] 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.
        - [ ] 시도할 횟수는 문자나 공백이 없어야한다.
        - [ ] 시도할 횟수는 1이상의 숫자여야 한다.


- [ ] 자동차 전진 판단
    - [ ] 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
    - [ ] 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.


- [ ] 각 차수별 실행 결과 출력
    - [ ] 각 차수별 실행 결과 안내 문구 "실행 결과"를 출력한다.
    - [ ] 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
    - [ ] 전진 1회당 문구 "-"를 출력한다.


- [ ] 최종 우승자 판단
    - `자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.`
    - [ ] 자동차들 중에서 가장 많이 전진한 자동차를 찾는다.


- [ ] 최종 우승자 출력
    - [ ] 최종 우승자 안내 문구 "최종 우승자 : "를 출력한다.
    - [ ] 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.
