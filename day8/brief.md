# Basic of HTML/CSS Symantic Markup
## "Cross Browsing is the most Important progress."

- SEO(Search Engine Optimization) : Build webpage/site following rules that search engine can understand, so that search engine can align and show this specific website on significant list

- SEO(서치 엔진 최적화) : 웹페이지를 제작하는 과정에서 서치 엔진과 컴퓨터가 이해할 수 있는 마크업을 사용해서 특정 정보를 검색하는 과정에서 좀 더 상위 리스트에 노출 될 수 있도록 하는 과정.

- Semantic Markup : Semantic markup has a close connection with SEO and UX. Semantic markup suppose to make most of the webpage users can expect similar experience through the same webpage. Word 'users' include the deaf, the blind, and even person with no handicap. Semantic markup is now an important issue since the world is heading for equal right from reality.

- 시맨틱 마크업 : 시맨틱 마크업이란 SEO, UX와도 밀접한 연관이 있는 개념이다. 이 개념은 대부분의 사람들이 같은 웹페이지에서 비슷한 경험을 할 수 있도록 해야 한다는 것에서 출발한다. '유저'라는 단어에는 청각 장애인, 시각 장애인, 나아가서는 장애가 없는 사람들까지 모두 포함되는데 시맨틱 마크업이라는 개념은 평등이라는 개념이 중요해진 현대시대에 맞춰 가장 먼저 발전하고 기준을 맞춰가야할 중요한 개념이 되었다.

## 웹을 구성하는 세 가지 요소의 역할
HTML : 튼튼한 신체

CSS : 멋진 옷과 악세사리

JavaScript : 명석한 두뇌

HTML의 구조가 명확하게 정돈되지 않으면 UX에도 영향을 미친다.

For example : one whole page
    
    <body>
        <div class="container">
            <header class="header"></header>
            <div class="visual"></div>
            <main class="main"></main>
            <article class="slogan"></article>
            <footer class="footer"></footer>
        </div>
    </body>
기본적으로 어떤 형태의 페이지를 만들것인지 구상하고 기본적인 틀을 구성하는 것이 중요

이전에는 div 형태로 '의미가 부여되지 않은 상태'로 구성되는 마크업 형태가 많았지만, 시맨틱 마크업의 중요성이 대두되면서 헤더 영역, 메인 영역 푸터 영역을 정의하는 태그가 권장되었다. header, main, footer 태그들은 본인들의 역할을 그대로 보여주는 태그들이다.

    <article>과 <section>의 공통점

article과 section은 모두 제목을 가져야한다는 공통점을 갖는다.


    <article>과 <section>의 차이점

article과 section은 혼용되어 사용되기도 하며, 그에 맞게 비슷한 역할을 하는 태그들이다. 굳이 의미의 차이를 두고 사용하는 경우는 적지만 작은 차이를 구분하여 사용하는 것은 중요하다.

article 태그는 그 안에 가지는 정보가 그 자체로서도 충분히 의미를 가지는 내용들을 담을 때에 사용하는 것이 좋다. 예를 들어 뉴스의 내용과 같이 그 내용들이 별도로 발간되더라도 특별한 의미를 가진 내용들을 일컫는다. 그러므로 보통 article 태그 안에 또 다시 article 태그를 넣어 사용하는 일은 지양하는 것이 바람직하다.

section 태그는 각 부분을 나누는 태그로 section 안에 다른 section을 넣어 사용하는 것도 가능하며, article에 비해서는 좀 더 유연한 사용법을 가진다.

두 태그의 차이를 잘 이해하여 사용하는 것은 이 정보에 다양한 방법으로 접근하게 될 사용자들에게 전달될 정보의 중요도를 결정하는데에도 도움이 된다.

    position:relative;
    position:absolute;
    position:fixed;
    position:sticky;
    각 positon 속성이 가지는 의미

relative 는 노멀 플로우를 유지하면서 움직일 수 있게 변형이 가능하다. 보기에는 변화가 없지만 static 속성을 기본으로 갖는 요소의 속성을 바꿔준다.

absolute 가장 가까운 곳에 위치한 static이 아닌 부모를 따라가는 속성을 갖는다. 만약 static이 아닌 부모가 없다면 본문 body를 기준으로 움직이기 때문에 움직이기 까다롭다.