# what should i eat today?

밥은 먹어야 하는데 무엇을 먹어야 할 지 고민하며 오늘 뭐 먹지?라는 생각을 해보신 적 있으신가요??

아마 대부분이 한번쯤은 해본 적 있으실 것이라고 생각합니다.

그래서 네이버 지식in에서 오늘 뭐 먹지?라고 물어 보았을 때 가장 많이 추천된 메뉴를 알아보려고 합니다.

진행 방식은 다음과 같습니다.

1.네이버 지식in에 오늘 뭐 먹지?라고 검색한 후 웹크롤링을 통해 데이터 수집

2.수집된 데이터를 konlpy를 통해 형태소 단위로 토큰화 한 후 워드 클라우드로 만들어 가장 많이 추천된 메뉴가 무엇인지 알아보기

3.word2vec를 활용하여 많이 추천된 메뉴와 유사한 단어를 알아보기


**파이썬으로 데이터 주무르기 책을 바탕으로 작성하였습니다.
