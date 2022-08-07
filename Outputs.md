# 산출물

### 산출물 목차

1. **프로젝트 간략 조회**
2. **프로젝트 간략 조회**
3. **완료된 프로젝트의 평가 정보 조회**
4. **프로젝트 상세 조회**
5. **프로젝트 참여 모든 직원 조회**
6. **평가 정보 조회**
7. **항목 평균 조회**
8. **인사 정보 조회**
9. **부서 조회**
10. **인사 입력, 수정**
11. **로그인**
12. **인사 정보 등록 & 수정**
13. **평가 정보 입력 > 동료 평가 정보**
14. **평가 정보 수정 > 동료 평가 정보**
15. **평가 정보 입력 > 고객 평가 정보**
16. **평가 정보 수정 > 고객 평가 정보**
17. **평가 정보 입력 > PM 평가 정보**
18. **평가 정보 수정 > PM 평가 정보**
19. **프로젝트 정보 등록**
20. **프로젝트 정보 수정**

### 1. 프로젝트 간략 조회

프로젝트 간략 정보 조회가 가능하다. 프로젝트 번호, 프로젝트 이름, 프로젝트 타입, 발주처 등을 확인할 수 있다. 프로젝트는 종료 일자 순으로 오름차순으로 정렬한다.

![Untitled](Outputs/Untitled.png)

### 2. 프로젝트 간략 조회

캘린더를 통해 사용자가 기간(시작일, 종료일)을 입력하면 그 기간에 해당되는 프로젝트 간략 정보를 보여준다. 프로젝트 번호, 프로젝트 이름, 프로젝트 타입, 발주처 등을 보여준다. 프로젝트를 선택하면 해당 프로젝트의 상세 정보 보기 화면으로 이동한다.

![Untitled](Outputs/Untitled%201.png)

### 3. 완료된 프로젝트의 평가 정보 조회

프로젝트 정보 조회 시, 완료되어 평가 정보가 존재하는 프로젝트의 경우 그 프로젝트 에 존재하는 모든 평가 정보들을 조회할 수 있다. 각 평가 항목 당 평가 내용(평가 점수, 코멘트 포함)을 조회할 수 있다.

![Untitled](Outputs/Untitled%202.png)

![Untitled](Outputs/Untitled%203.png)

### 4. 프로젝트 상세 조회

프로젝트 목록을 클릭하면 프로젝트 상세 정보 보기 화면으로 전환된다. 상세 정보 보기 화면에서는 프로젝트 번호, 프로젝트명, 착수일자, 종료일자, 발주처, 프로젝트에 투입된 직원, PM에 대한 정보를 볼 수 있다. 직원별로 사번, 부서명, 직위, 직무명과 투입 기간 등을 확인할 수 있다.

![Untitled](Outputs/Untitled%204.png)

### 5. 프로젝트 참여 모든 직원 조회

프로젝트 상세조회 화면에서 팀원목록은 프로젝트에 끝까지 참여하고 있는 직원들 만을 보여주는데 조회버튼을 누르면 중간에 프로젝트 참여를 종료한 직원들까지 모두 볼 수 있다.

![Untitled](Outputs/Untitled%205.png)

조회버튼 클릭

![Untitled](Outputs/Untitled%206.png)

### 6. 평가 정보 조회

사번, 프로젝트 번호로 평가 정보를 조회할 수 있는 기능이다. 고객, PM, 동료 평가 모두 확인 가능하다. 항목 별 점수, 코멘트 데이터를 조회할 수 있다.

![Untitled](Outputs/Untitled%207.png)

### 7. 항목 평균 조회

사번을 이용하여 참여한 프로젝트의 항목별 점수가 있을 때 평가점수를 score로 평균을 조회한다. 항목별로 직원평가, PM평가, 고객평가가 존재하며 업무수행과 커뮤니케이션 능 력에 대하여 점수 평균 조회를 할 수 있다.

![Untitled](Outputs/Untitled%208.png)

### 8. 인사 정보 조회

직원 관리의 인사정보 조회를 통해 직원에 대한 정보를 검색할 수 있다.직원을 검색하면 직원에 대한 정보와 직원이 어떤 프로젝트에 참여하였는지 해당직원의 경력 정보와 기술 정보를 볼 수 있다. 검색어 옆에 사번 을 선택하고 사번을 입력하여 검색 버튼을 누르면 사번으로 조회가 가능하고 직원 이름을 선택하고 직원이름을 입력후 검색버튼을 누르면 직원이름을 조회가 가능하다.

이름으로 조회

![Untitled](Outputs/Untitled%209.png)

조회 버튼 클릭

![Untitled](Outputs/Untitled%2010.png)

사번으로 조회

![Untitled](Outputs/Untitled.jpeg)

조회 버튼 클릭

![Untitled](Outputs/Untitled%201.jpeg)

### 9. 부서 조회

부서 조회 UI를 통해 부서번호를 검색하면 해당 부서에 있는 사원들이 나오고 이 때 사원들은 직책 순에 따라 내림차순 정렬이 된 상태로 출력되도록 구현했다. 앞서 회원가입을 할 때 넣었던 이름이 확인인 사람은 IT 부서 소속이므로 캡처 사진에서 출력된 것을 확인할 수 있다.

![Untitled](Outputs/Untitled%2011.png)

![Untitled](Outputs/Untitled%2012.png)

![Untitled](Outputs/Untitled%2013.png)

### 10. 인사 입력, 수정

신입사원이 들어와 회원가입을 하면 관리자 여부, 부서 등의 정보를 입력하면 MYSQL의 기 능인 AUTO_INCREMENT를 이용하여 값이 1씩 저장한 값을 사번으로 자동으로 생성해준다.
그리고 직급 변경이나 부서이동으로 사번이 변동될 경우 수정이 가능하게 구현했다.

![Untitled](Outputs/Untitled%2014.png)

![Untitled](Outputs/Untitled%2015.png)

![Untitled](Outputs/Untitled%2016.png)

원래 사번이 74 직급이 4인 이름 확인이라는 사람의 사원번호를 888 직급을 4로 변경

![Untitled](Outputs/Untitled%2017.png)

변경된 내용을 부서 조회(IT)로 확인

![Untitled](Outputs/Untitled%2018.png)

방금 직급과 사번을 변경한 확인 이름을 가진 사람의 사번을 777 부서를 PL로 변경

![Untitled](Outputs/Untitled%2019.png)

PL 부서 조회를 통해 변경 값 확인

### 11. 로그인

방금 위에서 삽입하였던 항목으로 로그인 기능을 하는 캡처 사진이다.

아이디에 확인을 넣었고 비밀번호에 방금 삽입한 비밀번호를 삽입하여서 로그인 버튼을 누르면 main 페이지로 이동하게 구현하였다.

![Untitled](Outputs/Untitled%2020.png)

![Untitled](Outputs/Untitled%2021.png)

### 12. 인사 정보 등록 & 수정

‘인사 정보 등록’ 페이지에서 사번, 성명, 주민등록번호, 최종학력, 입사 일자, 웹 아이디, 비밀번호, 관리자인지 일반 사원인지의 정보를 등록하면 DB에 입력한 값들이 저장되어 인 사 정보 등록이 가능하다.

‘인사 정보 수정’ 페이지에서 이미 존재하는 직원의 인사 정보를 수정할 수 있다. 이 때, 사번은 변경할 수 없으며, 입력한 사번과 일치하는 직원의 인사 정보 수정이 가능하다. 항 목은 인사 정보 등록 항목과 동일하나 추가로, 퇴사 일자를 수정(등록)할 수 있다.

![Untitled](Outputs/Untitled%2022.png)

![Untitled](Outputs/Untitled%2023.png)

![Untitled](Outputs/Untitled%2024.png)

### 13. 평가 정보 입력 > 동료 평가 정보

동료 평가 정보 테이블(emp_evl, emp_p_evl)에 데이터를 삽입할 수 있는 기능이다. 현재는 모든 column을 다 입력해야 삽입이 가능하도록 구현하였다.

![Untitled](Outputs/Untitled%2025.png)

INSERT 전

employee_evl 테이블

![Untitled](Outputs/Untitled%2026.png)

employee_p_evl 테이블

![Untitled](Outputs/Untitled%2027.png)

입력 버튼 누른 후

![Untitled](Outputs/Untitled%2028.png)

Insert 결과

![Untitled](Outputs/Untitled%2029.png)

### 14. 평가 정보 수정 > 동료 평가 정보

동료 평가 정보 테이블(emp_evl, emp_p_evl)에 데이터를 수정 (update) 할 수 있는 기능이다. 현재는 모든 column을 다 입력해야 수정이 가능하도록 구현하였다.

동료 평가시 넣은 정보를 수정함.

수정 후

![Untitled](Outputs/Untitled%2030.png)

![Untitled](Outputs/Untitled%2031.png)

### 15. 평가 정보 입력 > 고객 평가 정보

고객 평가 정보 테이블(customer_evl)에 데이터를 삽입할 수 있는 기능이다. 현재는 모든 column을 다 입력해야 삽입이 가능하도록 구현하였다.

등록 전 테이블

![Untitled](Outputs/Untitled%2032.png)

등록 후

![Untitled](Outputs/Untitled%2033.png)

![Untitled](Outputs/Untitled%2034.png)

### 16. 평가 정보 수정 > 고객 평가 정보

고객 평가 정보 테이블(customer_evl)에 데이터를 수정 (update) 할 수 있는 기능이다. 현재는 모든 column을 다 입력해야 수정이 가능하도록 구현하였다.

수정 전

![Untitled](Outputs/Untitled%2035.png)

수정 후

![Untitled](Outputs/Untitled%2036.png)

### 17. 평가 정보 입력 > PM 평가 정보

PM 평가 정보 테이블(pm_evl)에 데이터를 삽입할 수 있는 기능이다. 현재는 모든 column을 다 입력해야 삽입이 가능하도록 구현하였다.

입력 전 pm_evl 테이블

![Untitled](Outputs/Untitled%2037.png)

등록

![Untitled](Outputs/Untitled%2038.png)

등록 결과

![Untitled](Outputs/Untitled%2039.png)

### 18. 평가 정보 수정 > PM 평가 정보

PM 평가 정보 테이블(pm_evl)에 데이터를 수정 (update) 할 수 있는 기능이다. 현재는 모든 column을 다 입력해야 수정이 가능하도록 구현하였다.

PM 평가 정보 등록시 사용한 데이터를 수정함.

![Untitled](Outputs/Untitled%2040.png)

수정 결과

![Untitled](Outputs/Untitled%2041.png)

### 19. 프로젝트 정보 등록

프로젝트 정보를 등록할 수 있는 기능이다. 프로젝트 번호, 프로젝트명, 착수-종료 일자 발 주처, 프로젝트 규모를 입력하고 등록을 누르면 project 테이블에 정보가 삽입된다.

등록 전 프로젝트 테이블

![Untitled](Outputs/Untitled%2042.png)

등록

![Untitled](Outputs/Untitled%2043.png)

결과

![Untitled](Outputs/Untitled%2044.png)

### 20. 프로젝트 정보 수정

프로젝트의 정보를 수정할 수 있는 기능이다. 프로젝트 정보 수정에서는 프로젝트 정보에 대한 수정, 참여 직원 추가를 할 수 있다.

프로젝트 번호로 조회하면 프로젝트에 대한 정보가 입력이 된다. 수정을 한 후에 버튼을 누르면 update 문이 실행된다.

팀원을 추가할 때는 추가할 프로젝트명을 입력하고 참여할 이름을 조회한다. 직원을 추가할 때는 참여할 사람의 직무아이디도 함께 넣어서 등록해야한다.

프로젝트 정보 수정 시에는 먼저 프로젝트 번호로 조회를 한다.

![Untitled](Outputs/Untitled%2045.png)

조회 결과가 input 안의 value로 들어간다. (프로젝트 규모, 착수 일자, 종료 일자 변경)

![Untitled](Outputs/Untitled%2046.png)

수정 후 버튼을 누른다.

![Untitled](Outputs/Untitled%2047.png)

잘못된 정보 저장 시 오류임을 안내한다.

![Untitled](Outputs/Untitled%2048.png)

Project table의 정보가 수정된 것을 볼 수 있다.

![Untitled](Outputs/Untitled%2049.png)