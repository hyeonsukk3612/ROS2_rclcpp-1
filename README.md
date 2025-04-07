과제1번

 예제1번을 수정하여 문자열 대신에 정수값을 0으로 초기화하고 1씩 증가 시키면서 퍼블리시 하는 패키지 pub1-1를 작성하시오.

 토픽 메시지 인터페이스는 std_msgs/msg/Int32을 사용할 것

 소스파일 작성시 헤더 파일명과 클래스 명을 수정해야함 (15페이지참고)

 예제 1번과 같이 ROS2 명령어로 실행 결과를 확인하라.

 완료 후 강사에게 확인 받을 것

 패키지 소스 코드를 깃허브에 업로드 할 것


과제2번

 예제 1번을 수정하여 키보드로부터 실수값 3개를 입력받아 퍼블리시 하는 패키지 pub1-2를 작성하시오.

 토픽 메시지 인터페이스는 geometry_msgs/msg/Vector3을 사용

 패키지 생성시 의존패키지에서 std_msgs->geometry_msgs으로 수정해야함

 소스 파일 작성시 헤더 파일명과 클래스 명을 수정해야함 (15페이지참고)

 CMakeLists.txt의 add_executables 명령에서 의존 패키지를 std_msgs-> geometry_msgs으로 수정해야함

 예제1번과 같이ROS2명령어로실행결과를확인하라.

 완료후강사에게확인받을것

 패키지소스코드를깃허브에업로드할것


과제3번

 Turtlesim 패키지의 teleop_turtle 노드를 대신하는 패키지 pub1-3를 작
성하라.

 키보드입력시/turtle1/cmd_vel 토픽을 발행하도록 할 것
 
 f-> 전진, b->후진, l->좌회전, r->우회전

 메시지인터페이스는geometry_msgs/msg/Twist를 사용할 것

 패키지생성시의존패키지에서std_msgs-> geometry_msgs으로 변경

 소스파일작성시헤더파일명과클래스명을수정해야함(15페이지참고)

 CMakeLists.txt의 add_executables 명령에서 의존 패키지를 std_msgs에서 geometry_msgs으로 변경

 turtlesim(subscriber 역할수행) 노드를 실행하고 테스트 할 것

 완료후강사에게확인받을것

 패키지소스코드를깃허브에업로드할것

