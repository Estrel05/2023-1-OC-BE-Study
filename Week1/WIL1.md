# __1. �ʼ� ���� ����__
##  __1.1. MVC(Model, View, Controller)����__
������Ʈ ���� ��Ҹ� Model, View, Controoller�� �и��� ������ ����Ͻ� ������ ȭ�� �۾��� ���� ó���Ͽ� ȿ�����̴�. ���ſ��� View�� Controller�� �и��Ǿ� ���� ���� Model1 ����� ����ߴ�.
* Model, Controller: ����Ͻ� �����̳� ���� �۾� ó��
* View: ȭ�� ��°� ���� �۾� ó��<br/><br/>

## __1.2. API(Application Programming Interface)�� ����__
���ø����̼� ����Ʈ��� �����ϰ� �����ϱ� ���� �������̽��̴�. ���α׷����� ���� ��ȣ�ۿ��� �� �ֵ��� ���� ������ �Ѵ�.
* API�� ����
  * ������ �����ͺ��̽��� __���Ա�__
  * ���ø����̼ǰ� ��� ������ ��Ȱ�� ��� ����
  * ��� ���� __ǥ��ȭ__<br/><br/>

## __1.3. RESTful(Representational State Transfer-ful)__
### __1.3.1. REST__
�ڿ��� ǥ���� ���� ���� ������ ���Ѵ�. ��Ű��ó ��Ÿ�Ϸμ� API�� ����� �� �������̶�� �����ϸ� �ȴ�.
* REST�� ���� ���
  * �ڿ�(Resources): URL
  * �޼���(Method): HTTP �޼���
  * �޽���(Message): HTTP header, body, status code, etc.<br/><br>

### __1.3.2. RESTful API__
REST ���� ��Ģ�� �� ���� ����� API�� ���Ѵ�. ������ �ǹ̿ʹ� �ٸ��� �Ϲ������� REST ��Ű��ó�� �����ϴ� �����񽺸� ǥ���ϴ� ���� ���δ�. RESTful�ϰ� ����� API�� ��û�� ������ �ּҸ� ���� � ��û�� �ϴ��� �� �� �ִٰ� �Ѵ�.<br/><br/>

# __2. WIL1__
## __2.1. Java ���� ȯ�� ����__
* Java��ġ
* intellij ��ġ<br/><br/>

## __2.2. ��������Ʈ ����__
* spring initializr ����
  * Project - Gradle ����
  * Language - Java ����
  * Spring Boot - ���� ���� �� ���� �ֽ� �������� ����
  * Group - ��Ű���� �Է�
  * Artifact - ���ø����̼Ǹ� �Է�
  * Name - Artifact�� ����
  * Description - ���� �Է�
  * Package name - Gruop.Artifact
  * Packaging - Jar ����
  * Java - Java ���� ����
  * Dependencies - spring web, thymeleaf ����
  * generate ���� ��ġ �� ����Ǯ��<br/><br/>

## __2.3. ������Ʈ ����__
1. intellij ����
2. open ����
3. ������ Ǭ ���� ���� build.gradle���� ����
4. open as project ����<br/><br/>

## __2.4. ���������� �����__
1. src\main\resources\static������ index.html���� �ۼ�
2. main ����
3. localhost:8080 �����Ͽ� Ȯ��<br/><br/>

## __2.5. ����� ����__
1. �͹̳� ����
2. ������Ʈ ���� ���� build\libs������ �̵�
3. ./gradlew build �Է�
4. java -jar "Package name"-0.0.1-SNAPSHOT.jar�Է�
5. localhost:8080 �����Ͽ� Ȯ��