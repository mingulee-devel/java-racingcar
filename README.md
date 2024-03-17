# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

## 구현기능 (3단계)
- `Race` 클래스는 게임 설정을 위한 사용자 입력을 처리합니다.
- [대상] 지정된 수의 `Car` 객체를 `cars` 목록을 초기화 합니다.
- [정책] 무작위 숫자를 기반으로 차가 전진할지를 결정합니다. 무작위 숫자(0-9)가 4 이상이면 차의 위치가 증가합니다.
- [조건] 주어진 시도 횟수에 대한 경주를 진행합니다. 각 시도에서 각 차는 이동할 기회가 있습니다. 각 시도 후에 경주 진행 상황이 표시됩니다.
- [결과] 주어진 차의 현재 위치를 차의 위치에 해당하는 대시 라인으로 표시하여 출력합니다.
