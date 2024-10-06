# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)



### 기능 목록

#### UI
- [x] ~~자동차 대수 입력~~
- [x] 이동 횟수 입력
- [ ] 자동차 이름 부여, 자동차 이름은 쉼표(,)를 기준으로 구분
- [x] 자동차 상태 출력
- [ ] 자동차 상태 출력 시 이름 함께 출력 (ex) name : -
- [ ] 자동차 게임 완료 후 우승자 출력 (1명 이상)

#### 자동차
- [x] 0 ~ 9 사이의 랜덤값 생성
- [x] 랜덤값이 4 이상인지 체크
- [x] 자동차 전진 또는 멈춤
- [ ] 자동차의 이름은 5자를 초과할 수 없다.

#### 경기
- [x] 자동차 대수만큼 생성 
- [x] 라운드 진행

* [x] 테스트 코드 작성