1. 운영체제란?
- 하드웨어 바로 윗단에서 실행되는 SW
- 좁은 의미 = 운영체제의 가장 핵심적인 부분 : 커널
  - 부팅 시 항상 메모리에 올라가 있음.
- 넓은 의미 = 각종 주변 시스템 유틸리티를 포함한 개념
2. 운영체제의 목적 
- 여러 사용자/프로그램들이 컴퓨터를 편리하게 사용할 수 있게 인터페이스를 제공한다.
- 자원을 효율적으로 관리
  - 자원 : CPU / Hardware / Software
  - 주어진 자원을 통해 최대한의 성능(효율성)을 내는 것이 목적
  - 한정된 메모리 공간에 여러 프로그램들이 동시에 올라가기 때문에 프로그램마다 메모리를 나눠줘야함.
3. 운영 체제 분류
- 동시 작업 가능 여부
  - 단일 작업 (Single Tasking) : 초창기의 운영체제는 단일 작업만 가능 
  - 다중 작업 (Multi Tasking) : 현대 운영체제는 다중작업이 가능
- 사용자의 수
  - 단일 사용자 : 스마트폰, Windows와 같은 경우 혼자만 사용이 가능
  - 멀티 사용자 : Unix, Linux와 같은 경우에는 여러명의 사용자가  동시접속, 사용 가능
- 처리 방식
    - 일괄처리 (Batch Processing)
        - 현대 운영체제와는 다른 내용(현재 키보드가 입력되는대로 화면에 바로바로 확인이가능)
        - 일정량의 작업 요청을 모아 한번에 처리
    - 시분할 (Time Sharing)
        - 범용 시스템, 범용 운영체제에서 사용
        - 일정 시간 단위로 분할하여 사용 > 일괄처리에 비해 짧은 응답시간
        - Interactive 방식
    - 실시간 (Realtime OS)
        - 시간의 제약조건, DeadLine이 있음.
        - 일반적으로 사용하는 운영체제에서는 Deadline 없음.
        - 원자로, 미사일 등 치명적인 시스템에서 사용
        - Hard Realtime vs. Soft Realtime
4. 몇가지 용어
- Multi Tasking
- Multi Programming : 메모리 측면을 강조. 메모리에 여러 프로그램이 동시에 올라가있는 상황을 의미
- Time Sharing : CPU를 강조, CPU의 시간을 분할하여 나누어 쓴다.
- Multiprocess : 하나의 컴퓨터에 여러개의 CPU(Processor)가 있음.
5. 운영체제의 예
- UNIX
    - Server 운영체제
    - 하드웨어를 다루는 부분도 C언어로 대부분 작성되어있음.
    - 커널이 최소한의 구조이기 때문에 효율성 및 확장이 용이.
- MS-DOS 
    - 개인용 컴퓨터
    - 단일 사용자, 단일 프로그램 
- MS WIndows
    - 다중 작업이 가능한 GUI 기반 운영체제
