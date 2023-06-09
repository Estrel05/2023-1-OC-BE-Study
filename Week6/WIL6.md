# :pushpin: __필수 정리 내용__
## __1. 추상 클래스와 인터페이스__
### __1.1. 추상 클래스__
클래스의 틀이 되는, 상속을 위한 클래스. 여러 클래스의 공통적인 메서드를 선언하여 규격화하는 역할을 한다. 추상 클래스에서 메서드는 선언만 된 상태로 이를 추상 메서드라고 하며, 구현은 각 하위 클래스에서 이뤄진다. 하위 클래스에서는 이러한 구현이 강제되고 구현이 되었을 때 비로소 객체를 만들 수 있다. 단, 추상 클래스는 추상 메서드 없이도 선언할 수 있고 추상 메서드를 하나라도 갖고 있는 클래스는 반드시 추상 클래스로 선언해야 한다.
### __1.2. 인터페이스__
추상 클래스와 비슷한 기능을 한다. 추상 메서드를 사용하여 메서드의 틀을 잡는다. 다만 상속되는 추상 클래스와 달리 공통적인 기능이 있으면 자유롭게 선언할 수 있다. 메서드로는 public 추상 메서드, 변수로는 public 정적 상수만 가질 수 있다.
### __1.3. 공통점__
추상 클래스와 인터페이스 모두 추상 메서드를 사용할 수 있고, 이를 통해 공통적인 메서드의 규격을 설정할 수 있다.
### __1.4. 차이점__
추상 클래스는 공통 메서드를 가지는 여러 클래스의 상위 클래스가 같을 때, 인터페이스는 상위 클래스가 다를 때 사용한다. 다시 말해 추상 클래스는 스스로가 상위 클래스가 되며 하위 클래스의 '특징'을 선언하는 역할을 하고 인터페이스는 상위 클래스가 다른 여러 클래스가 있을 때 이 클래스들의 공통적인 '기능'을 선언하는 역할을 하는 것이다. 또한, 인터페이스는 추상 클래스와 달리 다중 상속이 가능하다.


## __2. static과 final 그리고 불변 객체__
### __2.1. static 블록__
클래스가 static 영역에 배치될 때 실행되는 코드 블록. 생성자는 아니지만 생성자와 비슷한 역할을 한다고 보면 된다. 생성자와 다른 점은 생성자는 클래스가 생성될 때 실행되지만 static 블록은 클래스가 최초로 사용될 때 실행된다. static 블록에서는 static 멤버만 사용할 수 있고, 클래스를 사용하는 코드가 없으면 static 블록이 실행되지 않는다.
### __2.2. final__
final은 변수, 메서드, 클래스에 사용할 수 있는 키워드로 기능을 제한한다. 변수에 final을 사용할 경우 그 변수는 변경 불가능한 상수가 된다. c++의 const와 같은 역할이다. 메서드에 final을 사용할 경우 오버라이딩이 금지된다. 클래스에 사용할 경우 상속 불가능한 클래스가 된다.
### __2.3. 불변 객체__
말 그대로 변하지 않는 객체, 즉 수정 불가능한 객체를 의미한다. final 키워드를 통해 불변 객체를 만들 수 있다. 값의 수정이 불가능하기 때문에 객체를 보호할 수 있지만 새로운 값을 가지게 되었을 때 수정할 수 없기 때문에 새 객체를 만들어야 하므로 성능 저하를 부를 수 있다.