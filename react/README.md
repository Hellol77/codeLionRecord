# react

## Babel

jsx -> js 로 변환하는 역활을 한다.

jsx는 선언형 : 결과물을 선언

js는 명령형 : 어떻게 만들지 방법을 명령

---

## jsx 문법 파헤치기

- ### Fragment 태그

  컴포넌트에서 Fragment 태그 내부만 들어가게 하도록

<></>로 축약해서 쓸 수 있다.

- ### 자바스크립트 표현식의 사용

  {} 를 사용한다.

- ### 조건부 렌더링

  1. return 문 밖에서 if문 사용
  2. && 와 || 이용하기
  3. case문 사용하기
  4. 삼항연산자

- ### 컴포넌트

  1. 클래스형
  2. 함수형

- ### props
  defaultProps : 기본값 설정
  부모 컴포넌트로부터 자녀 컴포넌트에 데이터 등을 전달
- ### state

  useState라는 함수를 통해 해당 컴포넌트 내부에서 데이터 전달

  변경 가능

  배열의 첫 번째 원소에는 현재 상태 저장 배열의 두번째 원소에는 상태를 바꿔주는 setter 함수

- ### MPA(Multiple Page Application)
  단점 : 상태 유지의 어려움, 불필요한 로딩
- ### SPA(Single Page Application) - React

  기존 페이지를 수정 , 한개의 페이지로 구성

  다른 주소의 다른 화면을 보여주는 것 : 라우팅

- ### map함수

- ### route
  <Route path="주소규칙" element={보여줄 컴포넌트}/>
- ### useLocation() 

- ### useNavigate()

- ### useEffect()
    리액트 컴포넌트가 렌더링 될 때마다 특정 잡업을 실행할 수 있도록 하는 Hook
    
    가장 처음 렌더링 될 때 한 번만 실행 - 빈 배열 넣기 useEffect(function,[])
    
    특정 props나 state가 바뀔 때 실행 - 특정 값 넣기 useEffect(function,[바뀌는 값])
- ### 페이지 주소 정의
  - URL 파라미터 예시 : /movies/1
    - 특정아이디, 이름을 사용하여 조회할 때 사용
  - 쿼리스트링 예시 : /movies/1?detail=true
    - 키워드 검색, 페이지네이션, 옵션 전달

- ### useMemo()
  성능 최적화를 위해 연산된 값을 재사용하게 해주는 Hook
  
  useMemo(function,deps)
   - function :  어떤 연산을 할 지 정의하는 함수
   - deps : 검사하고자 하는 값 또는 배열, 배열 형태이다.
   
- ### 제어 컴포넌트(Controlled Component)

- ### virtual DOM

- ### useRef

- ### useCallback
useCallback을 통해 함수를 memorize

- ### React.memo
Props가 안 바뀌어도 setState로 변화가 안 일어나도 상위 컴포넌트가 re-render되면 re-render

컴포넌트를 memorize 해놨다가 정말 필요한 상황에서만 re-render하자

- ### axios


   

