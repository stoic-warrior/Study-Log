# ■ 프로그램 실행 시 CPU burst와 I/O burst
![image](https://github.com/user-attachments/assets/d76e9f1b-3133-4613-816b-1277084ff837)
```
- 주로 사람이 상호작용 하는 프로그램이 이렇게 CPU와 I/O 버스트가 번갈아 나온다
- 어떤 프로그램은 I/O작업 없이 CPU만 오래 쓰기도 한다
- 버스트의 빈도와 기간이 프로그램의 종류마다 다르다
```
  #### CPU Burst
  - 프로그램이 CPU 연산을 집중적으로 수행하는 기간
  - 예: load, store, add, read 등과 같은 연산
  #### I/O Burst
  - 프로그램이 입출력 작업을 수행하며, CPU는 이 기간 동안 대기(wait for I/O) 상태
  - 예: 파일 읽기/쓰기와 같은 작업
## CPU burst Time의 분포
![image](https://github.com/user-attachments/assets/ccd121ae-43d2-4f74-a759-2c8774fe070e)
