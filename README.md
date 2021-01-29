# Java Syntax Training
자바문법 연습

---
# 📑 공부일지
# 2021년 1월29일
## 내부 클래스
> **클래스 내부에 선언된 클래스**, 클래스에 다른 클래스를 선언하는 이유는 두 클래스가 서로 밀접한 관계에 있기 때문이다. 
> [출처](https://doublesprogramming.tistory.com/158)
### 내부 클래스의 종류
* 인스턴스 내부 클래스(inner class)
* 정적 중첩 클래스(static inner class)
* 익명 내부 클래스(anonymous class) +함수형 인터페이스, 람다
* 지역 내부 클래스(local inner class)
### 장점 
1. 서로 연관성있는 클래스를 내부에 포함시킴으로써 내부 클래스에서 외부로 접근할 수 있다.
2. 연관된 클래스가 내부에 있기 때문에, 읽기 쉬우며 내부코드의 복잡성을 줄일 수 있다.

[예제코드](https://github.com/sinwoo1225/java-syntax-training/tree/master/src/innerclass)