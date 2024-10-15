# java-calculator-precourse

### 🔻기능 목록

1. **기본 구분자 지원**
   - 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 처리한다.
   - 입력된 문자열에서 숫자를 추출하여 더한다.
   - 빈문자열이 입력된 경우 0을 출력한다.
   - 예: 
     - "" => 0
     - "1,2" => 3
     - "1,2,3" => 6
     - "1,2:3" => 6

2. **커스텀 구분자 지원**
   - 사용자 정의 구분자를 지원한다.
   - 커스텀 구분자는 문자열의 시작 부분에 "//"와 "\n" 사이에 위치하는 문자로 정의한다.
   - 예: 
     - "//;\n1;2;3" => 6 (세미콜론(;)을 구분자로 사용)

3. **예외 처리**
   - 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생시킨다.
   - 예외 발생 후 애플리케이션은 종료된다.
