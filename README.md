# 문자열 덧셈 계산기 

## 기능 요구 사항
- 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 분리한 각 숫자의 합을 반환한다. 
  - 쉼표 또는 콜론으로 문자열을 분리한다.
  - 분리된 문자열에 숫자가 아닌 문자가 존재할 경우 IllegalArgumentException 예외를 발생시키고 프로그램을 종료한다.
  - 분리된 숫자(들)의 합을 반환한다.
- 앞의 기본 구분자(쉼표,콜론) 외에 커스텀 구분자를 지정할 수 있다. ✅
  - 문자열에 커스텀 구분자가 존재하는 지 판단한다. ✅
    - 커스텀 구분자가 존재한다면 커스텀 구분자를 반환한다(커스텀 구분자는 `// 와 \n` 사이에 위치) ✅
- 입력과 출력이 예상과 동일하게 동작한다.
  - 정상 동작을 판단하기 위해 테스트 코드를 통해 확인한다.
  
