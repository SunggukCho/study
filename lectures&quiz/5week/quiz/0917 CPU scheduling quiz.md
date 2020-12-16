# 0917 CPU scheduling quiz

### 1. CPU 스케쥴링 정의

```text
(__a__)에서, (__b__)에게 들어오는 여러가지 처리 요청들을 어떤 순서대로 처리할 지 결정하는 프로그램
```

a: (주체) 

b: (대상) 

### 2. T/F

- Ready Queue는 메인 메모리에서 CPU서비스를 받기 위해 대기하는 공간으로 CPU스케쥴링을 담당하고, Short-term 스케쥴러라고도 한다. (답:   )
- Job Queue는 메인 메모리에서 하드디스크로 데이터를 내려보낼 때 대기하는 공간으로 job 스케쥴링을 담당하고 CPU에 비해 긴 시간에 걸쳐 일어나기 때문에 long term 스케쥴러라고도 불린다. (답:   )
- PCB에는 스케줄링 정보가 포함되어 있어서 이전과 다음 프로세스로 어떤 것이 올지 알고 있다. 또한 우선순위(priority) 정보도 담고 있다. (답:   ) 



### 3. 다음중 스케쥴링 척도가 아닌 것은?

1. CPU utilization
2. Throughout
3. Waiting Time
4. Response Time
5. Turnaround Time



### 4. 스케쥴링 알고리즘

- 다음과 같은 Process들이 CPU를 기다리고 있다. 각각 FCFS, Priority 방식으로 했을 때의 AWT를 구하여라.

| Process | Arrival Time | Burst Time | Priority |
| :-----: | :----------: | :--------: | :------: |
|    A    |      0       |     9      |    2     |
|    B    |      3       |     5      |    3     |
|    C    |      5       |     3      |    4     |
|    D    |      8       |     7      |    1     |

- FCFS AWT

  ```text
  
  ```

- Priority AWT

  ```text
  
  ```