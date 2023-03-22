# 모달 구현
potal을 이용한 모달 구현
https://velog.io/@toyo8/Portals%EB%9E%80

# 고민
1. overlay가 부모닌깐 부모에다가 onclick넣어 주면 되는데 바탕이랑 박스랑 분리한 이유는
부모에다가 onclick을 주면 자식인 박스를 클릭해도 부모의 onclick발생. 버블링 때문.
2. CSSTransition 말고 모달을 켜고 끌때 애니메이션을 넣을수 없을까
css만으로 가능

# 알게된점
## padding blokc, padding inline
https://velog.io/@toyo8/padding-block-inline-%EC%9D%B4%EB%9E%80
