---
title: 히즈넷 원클릭 민원 자동검색기!
---

## 국가근로장학생의 편하게 살려는 발버둥!!
  
해야하는 일 중에 원클릭 민원에 해당기관에 들어온 민원이 있는지 확인해야 하는 일이 있다.

자동으로 들어가서 해당사항이 있으면 알려주도록 하는 프로그램을 만들어본다.

## 개발일지 :
### 4.17 금요일 - NoSuchElementException
  frameset이 있다는 부분을 잘 몰랐다.
  아무리 find_element_by_css_selector를 써도 분명히 있는데 잡아오질 못해서 보니,
  frameset이 되있으면 switch_to.frame("name")을 써야한다.
  그거 쓰니까 해결 됨!
  
  이제 로그인이 아주 잘된다.
  다음에 키워드에 반응하도록 개발해보자!