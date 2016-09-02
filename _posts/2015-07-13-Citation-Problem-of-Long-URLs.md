---
layout: post
title: 웹 문서 인용과 주소의 문제
feature-img: "img/post_feature_img_05.jpg"
---

얼마 전에 ["빅데이터 인문학"][book]이라는 책을 읽었다. 내용도 매우 재미있는 책이지만, 특이한 점 한 가지가 무척 인상적이었다. 그것은 책에서 참고하는 인터넷 문서의 주소가 모두 ["goo.gl"][gurl]로 시작하는 단축 주소로 적혀 있었다는 점이다. 갈수록 인터넷 문서를 인용하는 경우가 늘어나는데, 인터넷 문서의 고유주소는 길고 복잡해서 불편한 점이 많다. 그래서 이런 단축 주소를 사용하는 것이 적절한 대안이 될 수 있겠다는 생각이 들었다.

그래도 최근에는 잘 정의된 [고유주소(Permalink)][permalink]를 사용하는 경우가 많아서 그나마 사정이 낫지만[^1], 검색결과나 댓글의 댓글처럼 어쩔 수 없이 주소가 복잡해질 수밖에 없는 상황이 존재하고[^2], 이런 것을 인용하려고 하면 길고 복잡한 인터넷 주소를 정확히 입력하기가 난감한 때가 많다. 왜냐하면, 인터넷 주소는 띄어쓰기할 수가 없기 때문이다.

[^1]: ISBN이나 DOI 번호가 좋은 예시가 될 수 있다. 최근에는 JSTOR도 "Stable" 링크라는 이름으로 비교적 짧은 고유주소를 제공하고 있고, 다른 저널 공급자들도 비슷한 서비스가 있다. 그러나 이것은 공식적인 발행자가 존재하는 문서에나 해당할 뿐이다. 인터넷에서 벌어진 논쟁처럼 비공식적인 공간에서 공표된 내용을 인용하는 것은 여전히 간단하지 않다.

[^2]: 어떤 인터넷 주소는 그 길이가 심각하게 길어질 수 있다. 예를 들어, [이런 링크][longlink]는 일반적인 A4 문서 기준으로 주소만 5줄을 차지한다. 그리고 저 자료에 나라를 계속 추가하면 주소의 길이는 얼마든지 더 길어질 수 있다. 정확한 인용을 위해 저런 주소를 모두 적는 것은 매우 번거로운 일이다.

따라서 위의 사례처럼 주소의 길이를 줄여주는 단축 주소 서비스를 사용하는 것이 문제의 해결책이 될 수 있다. 그러나 주소를 단축해주는 서비스는 여러 종류가 있고, 그런 서비스가 언제까지 제공될 수 있을지는 아무도 알 수 없다. "빅데이터 인문학"은 책의 내용이 [Ngram][ngram]이라는 구글의 서비스를 활용한 결과를 다루고 있기에 구글의 단축 서비스를 사용하는 것이 당연한 것처럼 보일 수 있다. 그러나 세계 최고의 인터넷 기업인 구글조차도 지금까지 [수많은 서비스를 종결][killed]시켜 버렸다. 그래서 특정 기업이 제공하는 주소 단축 서비스가 앞으로도 오랫동안 유효하게 작동하리라고 장담하기 어렵다.

공식적인 학술저널이라면 이런 점은 특히 더 중요하다. 그래서 민간 기업의 서비스에 의존하는 것보다는 학술저널만을 위한 공식적인 인터넷 주소 단축 서비스가 있었으면 좋겠다는 생각이 들었다. 그리고 그 서비스가 충족해야 할 사항들로 이런 것을 생각할 수 있다.

- 작성자가 원주소와 단축 주소를 등록하고, 누구나 쉽게 검색할 수 있어야 한다.
- 단축 주소는 최대한 짧아야 한다.
- 똑같은 인터넷 문서를 반복적으로 등록할 필요 없이, 한번 생성된 인터넷 문서의 단축 주소는 다른 사람들이 편리하게 재사용할 수 있어야 한다.
- 등록된 인터넷 문서를 인용한 논문들을 확인할 수 있는 역링크를 제공하면 좋겠다.
- 처음 인용할 때의 인터넷 문서는 이후에 변경되거나 삭제될 수 있으니 등록할 때 스크린샷도 함께 등록해야 한다.

위 내용은 그저 내 상상일 뿐이다. 솔직히 저런 서비스가 만들어질 것이라고 기대하진 않는다. 그래서 현실적으로는 각자 알아서 잘하는 수밖에 없다. 개인적으로 [bit.ly][bitly]를 가장 선호하긴 하지만, 그렇다고 이런 단축 주소를 공식적으로 사용해도 되는지는 잘 모르겠다. 누가 이에 대한 지침이나 모범사례를 만들어주면 좋겠다.

[book]: http://www.aladin.co.kr/shop/wproduct.aspx?ISBN=8958288159
[gurl]: https://goo.gl/
[permalink]: https://en.wikipedia.org/wiki/Permalink
[longlink]: http://www.google.com/publicdata/explore?ds=d5bncppjof8f9_&ctype=l&met_y=it_net_user_p2#!ctype=l&strail=false&bcs=d&nselm=h&met_y=sp_pop_scie_rd_p6&scale_y=lin&ind_y=false&rdim=country&idim=country:GRC:NLD:NOR:KOR:NZL:DNK:LUX:DEU:BEL:USA:CHE:SWE:ESP:SVK:SVN:IRL:ISL:EST:AUS:GBR:ISR:AUT:ITA:JPN:CZE:CAN:CHL:PRT:POL:FRA:FIN&ifdim=country:income_level:OEC&tstart=837183600000&tend=1342105200000&hl=ko&dl=ko&ind=false
[ngram]: https://books.google.com/ngrams
[killed]: https://en.wikipedia.org/wiki/List_of_Google_products#Discontinued_products_and_services
[bitly]: https://bitly.com/