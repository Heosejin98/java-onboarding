## 기능목록

### 변경 1
22.10.27 DTO가 아닌데 getter를 사용하여 클래스를 없애고 함수로 구현하도록 바꿈


~~1. 사용자의 펼친 페이지 자릿수 따로 저장한다.~~

~~2. 저장된 페이지의 수를 왼쪽, 오른쪽을 모두 더하고 곱하여 가장 큰수를 반환한다~~


1. 사용자의 펼친 왼쪽페이지 자릿수를 곱하고 더 하여 MAX 값을 찾아낸다 (변경 1)
2. 오른쪽 페이지의 MAX 갑솨 비교하여 더 큰 MAX 값을 저장한다. (변경 1)
3. 사용자들의 점수를 비교하여 더 큰 사람이 따라 결과를 리턴한다.
4. 예외인 경우를 처리한다.
## 예외 목록
1. 펼친 페이지의 숫자가 1 ~ 400사이의 숫자가 아닐경우
2. 펼친 페이지의 번호가 2개가 아닐 경우
3. 펼친 페이지의 번호 차이가 1이상일 경우