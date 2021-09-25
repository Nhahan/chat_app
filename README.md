### SQL과 NoSQL의 장점과 단점, 차이
&nbsp;&nbsp;&nbsp;NoSql은 데이터의 중복으로 인해 insert는 느리다. 하지만 데이터 사이의 관계가 없기 때문에 select의 퍼포먼스가 RDBMS에 비해 훨씬 빠르다.<br>
&nbsp;&nbsp;&nbsp;러프하게 예를 들면 연예인(ex. IU, BTS...)이 글을 등록하면 insert는 한 번 이지만, 사람들이 연예인의 글을 조회하는건 수백만 수천만이기 때문에 이럴 경우 nosql로 설계하는 것이 성능상 이점이 될 수 있다.<br>
&nbsp;&nbsp;&nbsp;그럼에도 불구하고 NoSQL은 데이터의 중복을 허용하기 때문에 데이터의 일관성을 유지하기 힘들다는 단점이 크기 때문에 sql과 nosql 사이의 트레이드오프를 잘 생각해서 써야한다.
