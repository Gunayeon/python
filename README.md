# python
## 출력/주석
파이선 출력:print("출력할 내용")
주석:#하고싶은 코멘트

## 자료형
정수형\
소수형\
문자열\
불린:참(True)/거짓(False)\

## 추상화
추상화(Abstract):복잡한 내용은 숨기고, 주요 기능에만 신경쓰자.
* 변수
* 함수
* 객체
### 변수 : 값을 저장하는 곳
  ```
   x=254
   y=317
   print(x+y) /여기서 x와 y가 변수이다.
  ```
### 함수 : 명령을 저장하는 곳 
  +)print도 함수임

## 변수
ex) 햄버거가게 메뉴
  * 버거:4990원
  * 감튀:1290원
  * 음료:1250원
 -변수사용x
 ```
 print(4990) #버거 1개가격 출력
 print(4990*2) #버거 2개 가격 출력
 print(4990+1490) #버거 1개, 감튀 1개 출력
 print(4990*3+1490*2+1250*5) #버거 3개, 감튀 2개, 음료 5잔
 ```
 -> 꽤나 복잡하고 코드 수정할 떄, 틀리기 쉬움 \
 -변수사용
 
 ```
 burger_price=4990 # '=':지정연산자
 fries_price=1290
 drink_price=1250

 print(burger_price) #버거 1개가격 출력
 print(burger_price*2) #버거 2개 가격 출력
 print(burger_price+fries_price) #버거 1개, 감튀 1개 출력
 print(burger_price*3+fries_price*2+drink_price*5) #버거 3개, 감튀 2개, 음료 5잔
 ```
 ## 함수
 ```
 def hello():  #def:새로운 함수 정의, hello:함수의 이름/ 함수의 첫 줄:함수의 헤더
    print("Hello!");
    print("Welcome to Python!")

hello() # hello 함수 호출
hello()
hello()
```
 ## 파라미터
```
def hello(name):  #name:파라미터
    print("Hello!")
    print(name)
    print("Welcome to Python!");

hello("Chris")
```
여러개의 파라미터
```
def print_sum(a, b): # 파라미터의 이름은 임의로 지정가능
    print(a+b)

def print_sum2(a,b,c):
    print(a+b+c)
print_sum(7,3)
print_sum2(7,3,2)
```
