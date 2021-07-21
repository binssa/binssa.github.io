# 1. 컴퓨터 시스템 구조
- 내부 
    * CPU 
    * Memory : 디바이스기 때문에 Memory Controller 가 붙어있음.
- 외부
    * 여러 I/O Device
        * Device Controller : I/O Device 마다 Device 컨트롤러가 붙어있음.(디바이스를 관리하는 작은 CPU라고 생각하면됨)
        * Local Buffer : Device Controller 별로 작업 공간(Memory)을 가지고 있음
# 2. Mode Bit
- 사용자 프로그램의 잘못된 수행으로 운영체제 및 다른 프로그램에 피해가 가지 않도록 하기 위한 보호 역할 수행
- 2가지 모드 지원
    > <span style="color:red">사용자 모드 (1)</span> : 운영체제가 CPU를 사용자 프로그램에게 넘길 경우<br>
    > <span style="color:blue">모니터 모드 (0)</span> : 운영체제가 CPU를 실행 중일 경우
  - 위험한 기계어 = 특권명령은 Mode Bit이 0일때만 실행이 가능하도록함.
  - Interrupt / Exception을 통해서 User Mode(1) -> Monitor Mode(0)