자료구조란?
=======================
자료구조는 데이터를 저장하고 조직화하는데 쓰이는 저장 형태를 의미한다. 달리 말해, 컴퓨터가 효율적으로 데이터에 접근하고 업데이트 하기 위해 데이터를 저장하는 방법이다.

자료구조는 데이터를 조직화하는데 사용될 뿐만 아니라 데이터를 처리, 검색, 저장하는 역할도 한다. 기초적이고, 개발된 거의 모든 프로그램이나 소프트웨어 시스템에는 다양한 기본적인 그리고 발전된 형태의 데이터 구조가 사용된다. 그러므로 우리는 자료구조에 대한 공부를 꾸준히 해야 한다.

__자료구조__ 는 메모리에 데이터를 배열하는데 사용되는 컴퓨터의 필수적인 부분이다. 자료구조는 데이터를 효율적으로 구성, 처리, 접근 및 저장하는데 필수적이다. 다양한 형태의 자료구조에는 저마다의 특성, 기능, 활용 그리고 장점 및 단점이 존재한다.

##자료구조분류:
자료구조는 일상 생활에서 다양한 용도로 사용된다. 자료구조를 이용하면 짧은 시간에 많은 데이터를 정리하고 처리할 수 있다. 다양한 문제를 해결할 때, 그 문제에 적합한 자료구조를 활용하는 것이 중요하다. 

![자료구조분류](https://media.geeksforgeeks.org/wp-content/uploads/20220520182504/ClassificationofDataStructure-660x347.jpg)\

* __선형 자료구조__: 데이터 요소가 순차적 또는 선형으로 배열되고 각 요소가 이전 및 다음 요소에 배열되는 자료구조를 선형 자료구로라고 한다.
ex) 배열, 스택, 큐, 연결 리스트(linked list)
  * __정적 자료구조__: 정적 자료구조는 메모리 크기가 고정돼있으며, 각 요소에 접근하는 것이 더 쉽다.
    ex) 배열
  * __동적 자료구조__: 동적 자료구조는 크기를 런타임 중에 무작위로 업데이트 할 수 있으며, 이는 메모리(공간) 복잡성과 관련하여 효율적이다.
    ex) 큐, 스택

* __비선형 자료구조__: 데이터의 요소가 순차적 또는 선형으로 배치되지 않은 모든 자료구조를 비선형 자료구조라고 한다. 비선형 자료구조에서는 단일 실행만으로는 모든 요소를 탐색할 수 없다.

* * *

# 자료구조의 필요성:
자료구조의 정의에서 알 수 있듯 데이터를 효율적으로 관리 저장하고, 메모리를절약, 실행시간을 단축시키는데 그 목적이 있다고 할 수 있다.  그리고 자료구조와 알고리즘은 서로 연관이 깊다. 알고리즘은 자료구조에 저장된 데이터를 활용해서 문제를 해결하기 위한 방법들의 모임이라고 정리할 수 있다. ( [참고링크](https://re-code-cord.tistory.com/entry/%EC%9E%90%EB%A3%8C%EA%B5%AC%EC%A1%B0-%EC%9E%90%EB%A3%8C%EA%B5%AC%EC%A1%B0-%EC%99%9C-%EA%B7%B8%EB%A0%87%EA%B2%8C-%EC%A4%91%EC%9A%94%ED%95%A0%EA%B9%8C#:~:text=%EC%9E%90%EB%A3%8C%EA%B5%AC%EC%A1%B0%EB%8A%94%20%EC%BB%B4%ED%93%A8%ED%84%B0%EA%B3%BC%ED%95%99%EC%97%90%EC%84%9C%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%EA%B3%BC%20%ED%95%A8%EA%BB%98%20%EA%B0%80%EC%9E%A5%20%EC%A4%91%EC%9A%94%ED%95%9C%20%EA%B8%B0%EC%B4%88%EC%9D%B4%EB%A1%A0%EC%9D%B4%EB%8B%A4.%20%EC%99%9C,%EC%A0%88%EC%95%BD%ED%95%98%EA%B1%B0%EB%82%98%20%EC%8B%A4%ED%96%89%EC%8B%9C%EA%B0%84%EC%9D%84%20%EB%8B%A8%EC%B6%95%EC%8B%9C%ED%82%A4%EB%8A%94%20%EB%93%B1%EC%97%90%20%EB%AA%A9%EC%A0%81%EC%9D%84%20%EB%91%90%EA%B3%A0%20%EC%9E%88%EB%8B%A4%EB%8A%94%20%EA%B2%83%EC%9D%B4%EB%8B%A4.) ) 

* * *
# Array(배열) 
* 배열은 선형 자료구조의 일종
* 같은 타입의 여러 데이터들이 서로 인접한 메모리 공간에 저장
* 위의 특성으로 비교적 짧은 시간에 많은 양의 데이터 처리 가능
* 배열에는 검색, 정렬, 삽입, 탐색, 반전, 삭제와 같은 다양한 작업을 수행할 수 있음

![배열](https://media.geeksforgeeks.org/wp-content/uploads/Arrays-1.png)
