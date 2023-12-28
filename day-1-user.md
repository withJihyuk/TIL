컨트롤러 → 웹 요청 GET, POST, DELETE.. 등등 여러 요청을 받아들이고 처리하는 역할을 함 / 예: POST /api/order

서비스 → 비지니스 로직을 처리 하는 계층임. 주로 유효성 검사 등의 역할을 하며, 여러 리포지토리를 조합하여 특정 기능을 수행하는 메서드 제공 / 예: 주문 서비스, 고객 서비스

리포지토리 → 데이터베이스의 읽기 쓰기 검색 등의 기능을 주로 제공하며 ORM을 사용함 / 예: CREATE DB

도메인 → 기능 구현과 동시에 객체의 속성과 메서드를 담고 있어야함. 주로 비지니스 로직을 말하는데, 이는 비지니스의 전반적인 서비스 로직을 구현하는데 쓰기 때문. / 예: 고객, 주문, 상품

도메인 객체 / 서비스 객체 구분 → 핵심