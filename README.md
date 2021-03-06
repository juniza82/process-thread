# 1. 프로세스(process)
[프로세스(process)](https://ko.wikipedia.org/wiki/프로세스)는 **컴퓨터에서 연속적으로 실행되고 있는 컴퓨터 프로그램**을 말한다. 종종 스케줄링의 대상이 되는 작업(task)이라는 용어와 거의 같은 의미로 쓰인다. 여러 개의 프로세서를 사용하는 것을 멀티프로세싱이라고 하며 같은 시간에 여러 개의 프로그램을 띄우는 시분할 방식을 멀티태스킹이라고 한다. 프로세스 관리는 운영 체제의 중요한 부분이 되었다.

프로세스는 프로그램 실행시 Code, Data, Stack, Heap의 구조로 되어있는 독립된 메모리 영역을 할당 받습니다.

#### 멀티프로세싱(Multi-processing)
- 멀티프로세싱은 한 개 이상의 컴퓨터 프로세서들이 협력하여 프로그램들을 처리하는 것이다. 멀티프로세싱은 서로 협력하여 작업을 하고 있는 두 대 이상의 컴퓨터 중 한 대에 프로그램을 동적으로 할당하는 것을 의미하거나, 또는 같은 프로그램을 동시에 병렬로 처리하고 있는 여러 대의 컴퓨터들을 가리키는 일반적인 용어이다.

- 병렬처리의 출현과 함께, 멀티프로세싱은 __SMP__(symmetric multiprocessing:대칭형 다중처리)와 __MPP__(massively parallel processing:고도 병렬처리)로 나뉘어졌다.


# 2. 쓰레드(thread)
[스레드(thread)](https://ko.wikipedia.org/wiki/스레드_(컴퓨팅))는 **프로세스 내에서 실행되는 여러 흐름의 단위** 을 말한다.

* **장점**
  - 메모리 공유로 인한 시스템 자원 소모가 줄어 듭니다.
  - 응답시간이 단축 됩니다.
  - Context Switching 에 대한 오버헤드가 줄어 듭니다.
* **단점**
  - 서로 데이터를 사용하다가 충돌이 일어날 가능성이 있습니다.
  - 디버깅이 다소 까다로워 집니다. (버그 생성될 가능성 증가)


# 프로세스(process)와 쓰레드(thread)의 차이
