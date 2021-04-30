## About Node.js
> NodeJs Architecture
+ **싱글스레드**    
###### -프로세스: 운영체제 위에서 독립적으로 메모리에서 실행되고 있는 프로그램
###### -스레드: 프로세스 내에서 동작되는 여러 실행의 흐름(프로그램 안에서 동시에 여러개가 수행될 수 있는 작은 일꾼 단위)
###### -node js가 싱글스레드인 이유: 이벤트 루프 기반의 비동기성의 성능이 더 좋음   
+ **이벤트 루프**   
###### -callback함수의 경우: Task Queue에 쌓였다가 Call Stack이 비워지면 Call Stack으로 이동 (Event loop는 계속 순회한다)
###### -Promise: Microtask Queue에 쌓였다가 동작이 끝나면 Microtask에서 Call Stack으로 이동 (call back함수는 동작이 끝나지않아도 Call Stack에 데이터가 하나도 없을 때 Task Queue에서 Call Stack으로 이동)


