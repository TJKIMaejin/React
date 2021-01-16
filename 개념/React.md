# React


## props

사용자가 component를 사용 할 때 중요함

## state

component를 구현하는 동작을 바꿀 때 사용함


### **props 와 state는 분리해야한다.**


##   constructor(props)

가장 먼저 실행하는 함수


## key

React에서 key는 컴포넌트 배열을 렌더링했을 때 원소에 변동이 있는지 알아내려고 사용한다.
예를 들어 유동적인 데이터를 다룰 때는 원소를 새로 생성, 제거, 수정 할 수 있다.
DOM을 비교하는 과정에서 리스트는 순차적으로 비교하면서 변화를 감지한다.
하지만 key가 있다면 이 값을 사용하여 어떤 변화가 일어났는지 빠르게 찾아 낸다.


## render

props,state의 값이 바뀌면  render 함수가 다시 호출 
render 함수 하위에 있는 componenet들이 다시 호출


##  e.preventDefault();

debugger 사용시 방해
