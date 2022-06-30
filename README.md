[슈퍼키 란?]

- 슈퍼키는 테이블에서 각 행을 유일하게 식별할 수 있는 하나 또는 그 이상의 속성들의 집합입니다

- 슈퍼키는 유일성만 만족하면 슈퍼키가 될 수 있습니다 (고유한 데이터 속성)

​

​

[후보키 란?]

- 후보키는 테이블에서 각 행을 유일하게 식별할 수 있는 최소한의 속성들의 집합입니다

- 후보키는 기본키가 될 수 있는 후보들이며 유일성과 최소성을 동시에 만족해야합니다

​

​

[대체키 란?]

- 대체키란 후보키가 두개 이상일 경우 그 중에서 어느 하나를 기본키로 지정하고 남은 후보키들을 대체키라합니다

- 대체키는 기본키로 선정되지 않은 후보키입니다

​

​

[기본키 란?]

- 기본키란 후보키들 중에서 하나를 선택한 키로 최소성과 유일성을 만족하는 것입니다

- 기본키는 테이블에서 기본키는 오직 1개만 지정할 수 있습니다

- 기본키는 테이블 안에서 유일하게 각 행들을 구별할 수 있도록 쓰입니다

- 기본키는 NULL 값을 절대 가질수 없고, 중복된 값을 가질 수 없습니다

​

​

[외래키 란?]

- 외래키란 테이블이 다른 테이블의 데이터를 참조하여 테이블간의 관계를 연결하는 것입니다

- 외래키는 다른 테이블의 데이터를 참조할 때 없는 값을 참조할 수 없도록 제약을 주는 것입니다

- 외래키는 외래키는 참조되는 테이블의 기본키와 동일한 키 속성을 가집니다
