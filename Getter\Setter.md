## Getter\Setter
객체 지향 프로그래밍에서 객체의 데이터는 객체 외부에서 직접적으로 접근하는 것을 막는다. 
객체 데이터를 외부에서 읽고 변경 시 객체의 무결성이 깨질 수 있기 때문이다. <br><br>
따라서 객체 지향 프로그래밍에서는 메소드를 통해 데이터를 변경하는 방법을 선호한다.<br>
데이터는 외부에서 접근하지 않도록 막고, 메소드는 공개해서 외부에서 메소드를 통해 데이터에 접근하도록 유도한다.
(메소드는 매개값을 검증해서 유효한 값만 데이터로 저장할 수 있기 때문이다.) <br>
이러한 역할을 하는 메소드가 **Setter** 이다.
<br><br>
외부에서 객체의 데이터를 읽을 때도 메소드를 사용하는 것이 좋다. 객체 외부에서 객체 필드값을 사용하기 부적절한 경우에 메소드로 필드값을 가공 후, 외부로 전달한다.
<br>
이런 역할을 하는 메소드가 **Getter** 이다.<br>

## 메소드 선언 방식
보통 클래스의 멤버 변수는 `private`로 접근 제한자를 설정한 후 `getter`, `setter`를 통해 멤버변수의 값을 변경, 호출하게 된다.




