# pomodoro

A new Flutter project.

## Summary
뽀모도로 생산성 앱을 플러터로 구현했습니다.

## Key Functions

-	재생 버튼 클릭 시 설정된 25분을 기준으로 1초씩 차감되는 Timer 기능 구현
-	일시정지 기능 구현 및 타이머 동작 시 기존 재생버튼 위치에 일시정지 버튼 노출
-	일시정지 상태에서 리셋 버튼 클릭 시 타이머 시간 원래의 25분으로 복구되는 기능 구현 
-	모든 시간이 경과한 경우 최하단의 Pomodoros 부분의 숫자가 1씩 증가하는 기능 구현

## Learned

-	StatefuleWidget에서 버튼 동작 시 SetState를 통해 변경된 상태(재생,리셋 등) 반영하기.
-	Duration 클래스 활용해 int 값을 시,분,초 Format으로 변경하기.
-	Timer 클래스의 periodic 메소드를 통해 특정 주기마다 실행될 함수 지정하기.


## Screenshots

<img width="138" alt="image" src="https://user-images.githubusercontent.com/77106988/236773055-2d86e575-3b57-47bd-b06e-98819f916bec.png">
<img width="134" alt="image" src="https://user-images.githubusercontent.com/77106988/236773076-5a62a519-b40c-4964-8de0-380a657ff900.png">
<img width="141" alt="image" src="https://user-images.githubusercontent.com/77106988/236773091-cce83e28-4f76-47ab-bb4d-441b3cafe817.png">

