# 리눅스 명령어 정리
## top
- 시스템의 상태를 전반적으로 가장 빠르게 파악 가능
    - CPU, Memory, Process

- 옵션 없이 입력하면 interval 간격(기본 3초)으로 화면을 갱신하여 정보를 보여줌
- 실행 전 옵션
    - 순간의 정보 확인 : -b (batch 모드)
    - -n : top 실행 주기 설정

- 실행 후 명령어
    - shift + p : CPU 사용률 내림차순
    - shift + m : 메모리 사용률 내림차순
    - shift + t : 프로세스가 돌고있는 시간 순
    - k : kill(후술함) k 입력 후 PID 번호 작성
    - f : sort field 선택 화면
        - q 누르면 RES 순으로 정렬
            - RES : 프로세스가 물리적 메모리를 사용하는 크기
    - a : 메모리 사용량 순으로 정렬
    - b : Batch 모드로 작동
    - 1 : CPU Core별 사용량

## ps
- Process Status
- 현재 돌아가고 있는 프로세스 확인
    - PID, TTY(프로세스가 연결된 터미널), 총 CPU 사용 시간, 실행 명령행

- 옵션
    - -A        : 모든 프로세스 출력
    - a         : 터미널과 관련된 프로세스 출력
    - -a        : 
    - -e        :
    - -f        :
    - -l / l    :
    - -o value  :
    - -M        :
    - -m        :
    - -p        :
    - -r        :
    - u         :
    - x         :
    - -x        :


## jobs
- asdfa

## kill
- asdf
