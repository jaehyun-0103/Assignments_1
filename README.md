# 1학년 1학기 과제
---

# 목차
1. 프로그래밍기초

    1.1. [과제1](#과제1)
    
    1.2. [과제2](#과제2)
    
    1.3. [과제3](#과제3)
    
2. 전산학기초

    2.1. [자판기](#자판기)

---

# 1. 프로그래밍기초

# 과제1

클래스 상속을 이용하여 학생 5명의 자료를 임의로 입력하시오.

## 조건
    1. python 과목의 평균을 계산한다.
    2. python 과목의 점수가 평균 이상인 학생의 이름을 출력한다.
## 클래스
    1. Person class
        • name: 문자열로 이름 표현
        • id: 정수형 주민번호
    2. Student class
        • classes: 수강 과목을 dictionary를 사용하여 {과목 : 점수}로 표현
        • 과목 종류는 kor, math, python
    
---
    
# 과제2

은행 계좌를 개설하는 프로그램을 만드시오.

## 조건
    1. saving account 5명 개설
    2. checking account 5명 개설
    3. saving account 총액 계산
    4. checking account 총액 계산
    5. 최고액의 잔액 보유자 이름 출력
    
---
    
# 과제3

은행 계좌를 개설하는 프로그램을 만드시오.

## 조건
    1. 과제2에서 balance 변수를 private 변수로 수정

     
---
---

# 2. 전산학기초

# 자판기

아래 이미지를 참고하여 자판기 프로그램을 만드시오.
![IMG_6364](https://user-images.githubusercontent.com/80446951/187058489-44368217-663f-404d-a897-5fe9e4b33f65.JPG)

## 조건
    1. 1000원짜리 지폐를 받을 수 있고, 100원짜리와 500원짜리도 받을 수 있다.
    2. 지불한 돈만큼 자판기 내부의 잔돈의 개수 증가한다.
    3. 사용된 거스름돈의 개수만큼 잔돈의 개수 감소한다.
    4. 사용자가 낸 돈이 부족하다면 돈을 돌려주고 돈을 지불하던 때로 돌아간다.
    5. 주인이 비밀번호를 3번 넘게 틀리면 강제 종료한다.
    6. 손님이 선택한 음료의 재고가 없다면 다시 고르게 한다.
    7. 결제 수단에 따라 적절한 과정을 거친다.
    8. 주인모드와 손님모드가 존재있다.

## 변수 설명

### 음료수
    water = 0 / daily = 4 / corn = 8 / cantata = 3 / trevi = 3 / milkis = 9 / pepsi = 10 /
    hotsix = 1 / cider = 8 / mango = 4 / lipton = 7 / apple = 4 / grape = 6 / gana = 5 /
    be = 0 / latte = 3 / cafe = 2 / gatorade = 4 / coco = 4 / rice = 10

### 답변
    · answer1: 1. 주인 2. 고객 중 하나를 골라 저장한다.
    
    · answer2: 입력한 암호를 저장한다.
    
    · answer3: 1. 음료를 고른다 2. 음료를 고르지 않는다 중 하나를 골라 저장한다.
    
    · answer4: 1. 현금 2. 카드 중 하나를 골라 저장한다.
    
    · answer5: 1. 잔돈 확인 2. 재고 확인 중 하나를 골라 저장한다.
    
    · answer6: 추가할 음료 번호를 저장한다.
    
    · answer7: 추가할 음료 개수를 저장한다.
    
    · answer8: 추가 잔돈 종류를 저장한다.
    
    · answer9: 추가 잔돈 개수를 저장한다.
    
    · answer10: 잔돈 추가 선택를 할지 말지 골라 저장한다.
    
    · answer11: 재고 추가 선택을 할지 말지 골라 저장한다.

### 돈
    · coin10000: 지불한 만원짜리 돈의 개수이다.
    
    · coin1000: 지불한 천원짜리 돈의 개수이다.
    
    · coin500: 지불한 오백원짜리 돈의 개수이다.
    
    · coin100: 지불한 백원짜리 돈의 개수이다.
    
    · _ coin10000: 사용자에게 줄 만원짜리 거스름돈의 개수이다.
    
    · _ coin1000: 사용자에게 줄 천원짜리 거스름돈의 개수이다.
    
    · _ coin500: 사용자에게 줄 오백원짜리 거스름돈의 개수이다.
    
    · _ coin100: 사용자에게 줄 백원짜리 거스름돈의 개수이다.
    
    · coin10000_m: 자판기 내부에 있는 만원짜리 거스름돈의 개수이다.
    
    · coin1000_m: 자판기 내부에 있는 천원짜리 거스름돈의 개수이다.
    
    · coin500_m: 자판기 내부에 있는 오백원짜리 거스름돈의 개수이다.
    
    · coin100_m: 자판기 내부에 있는 백원짜리 거스름돈의 개수이다.

### 기타
    · money: 사용자가 지불한 돈의 총합이다.
    
    · menu: 사용자가 고른 음료이다.
    
    · charge: 사용자에게 줄 거스름돈의 총합이다.
    
    · select: 사용자가 선택한 음료 번호이다.
    
    · list_2000: 2000원짜리 음료를 모아 리스트에 저장한다.
    
    · list_1500: 1500원짜리 음료를 모아 리스트에 저장한다.
    
    · list_1300: 1300원짜리 음료를 모아 리스트에 저장한다.
    
    · list_1000: 1000원짜리 음료를 모아 리스트에 저장한다.
    
    · list_800: 800원짜리 음료를 모아 리스트에 저장한다.
    
    · list_600: 600원짜리 음료를 모아 리스트에 저장한다.

---
