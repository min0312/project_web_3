폭탄게임💣
https://min0312.github.io/project_3_boom/





--------
+ 삼향연산자 => 조건식 ? 참 : 거짓
+ parseInt : 문자를 숫자로 변환
+ !isNaN : 문자열이 아닌 것



입력
1. 폭탄 섞기 버튼 입력
2. 숫자 박스 클릭 입력
처리
1-1. 폭탄 섞기 처리
- 폭탄 위치를 배열로 처리
  [0,0,0,0,0,0,0,0,1] => 셔플

2-1. 숫자 박스 클릭 처리
- 폭탄이 있는 위치가 셔플이 되었는지 확인
- 셔플이 되었으면 현재 눌러진 슷자 박스에 그림 표시
  폭탄 위치 배열의 숫자값으로 그림 구분
- 클릭된 번호를 배열에 저장
- 하트 그림이 나오면 카운트 증가
  카운트 값이 8이면 폭탄 위치에 하트를 넣고 종료
- 폭탄 그림이 나오면 다시 눌러지지 않도록

