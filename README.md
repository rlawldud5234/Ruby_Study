# Ruby_Study
**터미널 창에 irb 입력 후 코딩**

210720)
## 루비란?
세계 10대 프로그래밍 언어
2015년 gitHub 3위

## 루비의 자료형
<자료형이란?>
- 순수 객체지향적 언어
  원시 자료형이 사실상 존재하지 않고 모든 것은 객체인 언어
- 여러 종류의 데이터를 식별하는 분류

<다양한 데이터 종류>
Q. 여러 종류의 데이터에는 대표적으로 무엇이?
A. 숫자, 문자열, 배열(Array), 해시(Hash)

* 배열 : 번호(인덱스)와 번호에 대응하는 데이터들로 이루어진 자료 구조
* 해시 : 키를 값에 매핑할 수 있는 자료구조
        해시(Hash) = {키 => 요소}
        
## 변수와 상수
<변수의 선언>
* 상수 2를 변수 x에 대입한다
  x = 2
 변수 = 대입할 값
 
<변수의 종류>

* 지역변수
foo = 'foo in top level'

* 전역변수
$foo = 'foo in whole'

* 인스턴스 변수
@foo = 'foo in instance'

* 클래스 변수
@@foo = 'foo in class'

=> 앞에 변수형 선언이 없어도 됨

<지역변수>
자신이 선언된 스코프에서만 참조 가능하다.
hello = "World"
def call_hello #=> 메소드
  puts hello
end

call_hello  #=> ERROR!

<전역변수>
어디서 선언하던, 어느 곳에서나 불러올 수 있다.
$hello = "World"

def call_hello
  puts $hello
end

call_hello    #=> "World"

