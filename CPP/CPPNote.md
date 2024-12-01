### Instruction [명령어]
```txt
CPU가 수행하는 기초적인 연산들 이다.
```

### Programming Language
```txt
프로그래밍 언어는 인간과 기계 사이의 번역을 맡는 역할 이라고 생각하면 된다.
Programming Language를 통해 원하는 작업을 텍스트로 기술한 것을 source code라고 칭하고, 
파일 내에 저장된 것을 source file 라고 부르고, Compiler는 source file을 기계어로 변환하여 파일에 저장하는데, 이를 object file이라 부른다.
```

### Procedural Programming
```txt
절차적 프로그래밍은 절차를 중시하며 이러한 프로그래밍 기법이란 의미를 가진다.
```

### Object-Oriented Programming [OOP]
```txt
Procedural Programming의 문제점을 대응하기 위해 객체 지향 프로그래밍이 개발 되었다. 알고리즘 중점이 아닌 객체 지향으로 데이터를 중점으로 시작으로 문제에 필요한 데이터를 먼저 설계하는 기법이다. 데이터를 나타낼 때 사용하는 도구는 Class로 데이터 외에 데이터를 처리하는 함수가 포함된다.
```
> OOP는 데이터와 알고리즘이 분리되어 있지 않는다. 추가로 C++는 OOP 기법을 베이스로 설계되어 있다.

### Generic Programming
```txt
데이터의 타입과 무관한 일반적인 코드를 작성하는 기법이기에, 알고리즘이 타입 매개 변수를 이용하여 작성된다.
```

### Bottom-up
```txt
Low Level Class 부터 High Level Class 설계 까지 진행하는 방법을 Bottom-up 설계라고 한다.
데이터와 알고리즘을 하나의 Class로 묶어 이것을 캡슐화라고 한다. 캡슐화를 함 으로써 접근을 차단하여 데이터 보호와
각 Class들을 서로 독립적으로 작성이 가능하다. [Rust의 Shadow와 비슷하다?]
```

## ETC
* Algorithm : 문제를 해결하기 위한 일련의 정확한 단계를 의미, 계산 수행, 데이터 처리, 자동 추론 등 다양한 작업에 사용
* C++ Keywords : [CppReference](https://en.cppreference.com/w/cpp/keyword)