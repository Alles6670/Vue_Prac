# Vue-Router
  사이트를 구성하는데 있어서 페이지를 관리하는데 필요한 기능들을 포함한 모듈
## 기능
  ##### 중첩된 라우트/뷰 맵핑
  ##### 컴포넌트 단위로 페이지 설정
  ##### 라우터 파라미터, 쿼리, 와일드카드 설정
  ##### 트랜지션 효과
  ##### active CSS클래스 자동 추가
  ##### 사용자 정의 가능한 스크롤 동작
### 기본 모드는 hash mode로 전체 URL을 분석해서 그 페이지로 URL이 변경돼도 단일페이지가 다시 새로 로드 되지 않고도 특정 페이지로 진입가능.
  history모드를 통하여 hash를 제거할 수 있다.
  #### 문제점
  SPA는 단일페이지이기 때문에 직접 특정페이지URL에 접근하면 404 오류가 발생하기 때문에, 서버에 대체경로를 추가해야 한다.
  발견되지 않는 경로는 404에러를 보고하지 않기 때문에 따로 catch-all 라우트를 통해 404페이지를 표시해야한다.
  
