# Java

---

### 박싱boxing, 언박싱unboxing, 오토박싱autoboxing
- 자바에는 기본형(byte, int, char)와 참조형(Byte, Integer, List)이 있다.

- 박싱: 기본형 -> 참조형 변환
- 언박싱: 참조형 -> 기본형 변환
- 오토박싱: 자바에서는 박싱과 언박싱을 자동으로 해준다. 

``` java
int num = 123
List<Integer> list = new ArrayList<>();
list.add(i); // int -> Integer

```
---
### 시그니처 Signature
- 메서드명과 파라미터 순서, 타입, 개수를 의미

```java
public String someMethod(String str) {}
public String someMethod(String str, int num) {}
// someMethod의 두 메서드는 서로 다른 시그니처다.
```
