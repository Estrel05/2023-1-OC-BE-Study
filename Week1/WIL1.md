# __:pushpin: �ʼ� ���� ����__
##  __1. MVC(Model, View, Controller)����__
������Ʈ ���� ��Ҹ� Model, View, Controoller�� �и��� ������ ����Ͻ� ������ ȭ�� �۾��� ���� ó���Ͽ� ȿ�����̴�. ���ſ��� View�� Controller�� �и��Ǿ� ���� ���� Model1 ����� ����ߴ�.
* Model, Controller: ����Ͻ� �����̳� ���� �۾� ó��
* View: ȭ�� ��°� ���� �۾� ó��<br/><br/>

## __2. API(Application Programming Interface)�� ����__
���ø����̼� ����Ʈ��� �����ϰ� �����ϱ� ���� �������̽��̴�. ���α׷����� ���� ��ȣ�ۿ��� �� �ֵ��� ���� ������ �Ѵ�.
* API�� ����
  * ������ �����ͺ��̽��� __���Ա�__
  * ���ø����̼ǰ� ��� ������ ��Ȱ�� ��� ����
  * ��� ���� __ǥ��ȭ__<br/><br/>

## __3. RESTful(Representational State Transfer-ful)__
### __3.1. REST__
�ڿ��� ǥ���� ���� ���� ������ ���Ѵ�. ��Ű��ó ��Ÿ�Ϸμ� API�� ����� �� �������̶�� �����ϸ� �ȴ�.
* REST�� ���� ���
  * �ڿ�(Resources): URL
  * �޼���(Method): HTTP �޼���
  * �޽���(Message): HTTP header, body, status code, etc.<br/><br>

### __3.2. RESTful API__
REST ���� ��Ģ�� �� ���� ����� API�� ���Ѵ�. ������ �ǹ̿ʹ� �ٸ��� �Ϲ������� REST ��Ű��ó�� �����ϴ� �����񽺸� ǥ���ϴ� ���� ���δ�. RESTful�ϰ� ����� API�� ��û�� ������ �ּҸ� ���� � ��û�� �ϴ��� �� �� �ִٰ� �Ѵ�.<br/><br/>

# __:pushpin: WIL__
## __1. Java ���� ȯ�� ����__
* Java��ġ
* intellij ��ġ<br/><br/>

## __2. ��������Ʈ ����__
1. spring initializr ����
2. Project - Gradle ����
3. Language - Java ����
4. Spring Boot - ���� ���� �� ���� �ֽ� �������� ����
5. Group - ��Ű���� �Է�
6. Artifact - ���ø����̼Ǹ� �Է�
7. Name - Artifact�� ����
8. Description - ���� �Է�
9. Package name - Gruop.Artifact
10. Packaging - Jar ����
11. Java - Java ���� ����
12. Dependencies - spring web, thymeleaf ����
13. generate ���� ��ġ �� ����Ǯ��<br/><br/>

## __3. ������Ʈ ����__
1. intellij ����
2. open ����
3. ������ Ǭ ���� ���� build.gradle���� ����
4. open as project ����<br/><br/>

## __4. ���������� �����__
1. src\main\resources\static������ index.html���� �ۼ�
2. main ����
3. localhost:8080 �����Ͽ� Ȯ��<br/><br/>

## __5. ����� ����__
1. �͹̳� ����
2. ������Ʈ ���� ���� build\libs������ �̵�
3. ./gradlew build �Է�
4. java -jar "Package name"-0.0.1-SNAPSHOT.jar�Է�
5. localhost:8080 �����Ͽ� Ȯ��