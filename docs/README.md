### ✨ 구현할 기능 목록

<b>1. 1에서 9까지의 서로 다른 수로 이루어진 3자리의 수를 pickNumberInRange()를 활용해 구현</b>

    - 3자리 자연수
    - 각 자리 숫자는 중복되지 않는다
<b>2. 게임 플레이어 입력 기능 readLine()를 활용해 구현</b>

    - 예외사항 3자리의 자연수가 아닌 경우
    - 1부터 9까지의 숫자가 아닌 경우
    - 각 자릿수의 숫자 중 중복된 값이 있는 경우
    - 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException 발생시킨 후 애플리케이션 종료
<b>3. 플레이어 입력과 컴퓨터의 숫자와 비교</b>

    - 같은 수가 다른 자리에 있으면 볼
    - 같은 수가 전혀 없으면 낫싱
    - 같은 수가 같은 자리에 있으면 스트라이크
<b>4. 비교 결과</b>

    - 볼, 스트라이크 카운팅 후 출력
    - 스트라이크가 3이 아닌 경우 사용자 입력 전환
    - 스트라이크가 3인 경우 게임 종료 문구 출력
    - 출력 예시 : (x)볼, (y) 스트라이크
<b>5. 종료 조건</b>

    - 1 입력 시 재시작 후 숫자 랜덤 생성으로 전환
    - 2 입력 시 게임 종료
    - 예외사항 1과 2가 아닌 숫자를 입력 시 IllegalArgumentException 발생