# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

## RacingGame

### 요구사항

Input
- 사용자에게 참가할 자동차의 수를 입력받는다.
- 진행될 라운드를 입력받는다.

Car 
- 자동차는 4이상의 숫자를 받아야 앞으로 갈 수 있다.
- 자동차 이름은 5자를 초과할 수 없다.

CarFactory
- 자동차를 입력받은 숫자만큼 생성한다.
    - 음수를 입력받으면 에러를 발생시킨다.

RacingGame
- Racing Game의 round는 음수가 될 수 없다. 만약 음수를 받는다면 에러를 뱉는다.
- 설정된 round 보다 더 많은 라운드를 진행할때 에러를 뱉는다.

ResultView
- 매 라운드 마다 현재 움직인 거리를 출력한다.

  
  