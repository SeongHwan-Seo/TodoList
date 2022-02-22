# TodoList
#UITableView
- 데이터들을 목록 형태로 보여 줄 수 있느 가장 기본적이 UI 컴포넌트
- 여러 개의 Cell을 가지고 있고 하나으 열고 여러 줄의 행을 지닐수 있으며, 수직으로만 스크롤이 가능하다.
- 섹션을 이용해 행을 그룹화하여 콘텐츠를 좀 더 쉽개 탐색하 수 있다.
- Delegate와 DataSource 프로토콜을 채택하여야 한다.

#UITableViewDataSource
- UITableViewDataSource는 테이블 뷰를 생성하고 수정하는데 필요한 정보를 테이블 뷰 객체에 제공한다.

#UITableViewDelegate
- 테이블 뷰의 시각적인 부분을 설정하고, 행으 액션 관리, 엑세서리 뷰 지원, 테이블 뷰의 개별 해 편집을 도와준다.

#UserDefaults
- UserDefaults는 App 시작시 사용자의 기본 데이터베이스를 키-값 쌍으로 지속적으로 저장하는 인터페이스이다.
런타임 시 개체를 사용하여 App이 사용자의 기본 데이터베이스에서 사용하는 기본값을 읽기 때문에 값이 필요할 때마다 데이터베이스를 열 필요가 없어진다.
