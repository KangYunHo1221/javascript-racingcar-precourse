## 기능 요구사항 분석

- 유저로부터 차 이름 받기

  - 차 이름 ,를 기준으로 추출
  - 차 이름 input 잘못됐을 시 오류 메세지
    - 5글자 초과시 에러
    - 1개 미만 입력시 에러

- 차 생성

  - name
  - location
  - 무작위 숫자 생성
  - 무작위 숫자가 4이상이면 전진, 미만이면 멈춤

- 유저로부터 시행횟수 받기

  - 인풋 잘못 됐을 시 오류 메세지

    - 숫자가 아닐 시

  - 시행횟수만큼 차 이동 move cars trail number
  - 시행횟수 완료시 우승자 선별
    - 가장 멀리 location인 차가 우승자
    - 여러명일 시 ,로 구별

- 정답출력