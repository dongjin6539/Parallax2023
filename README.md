# Parallax2023
패럴렉스 효과를 사용해서 사용자가 웹 페이지를 스크롤할 때 애니메이션 효과가 나타나도록 구성했습니다.

javascript를 사용해서 window.pageYOffset, window.scrollY, document.documentElement.scrollTop 메서드를 사용해서 scroll 할 때의 값을 구했습니다.

**parallaxEffect01** : https://dongjin6539.github.io/web2023/javascript/parallax/parallaxEffect01.html <br>
- scroll 할 때의 값을 구하고 각 section 태그의 offesct 값을 구했습니다.
- 각 section 태그의 구역에 scroll 위치가 맞으면 menu바에 active 효과를 줍니다.

**parallaxEffect02** : https://dongjin6539.github.io/web2023/javascript/parallax/parallaxEffect02.html <br>
- 각 section 태그의 구역에 scroll 위치가 맞으면 side menu바에 active 효과를 줍니다.

**parallaxEffect03** : https://dongjin6539.github.io/web2023/javascript/parallax/parallaxEffect03.html <br> 
- menu바가 scroll의 값이 일정 값보다 커지면 remove 메서드로 class를 사라지게 해주고 일정 값으로 도달하게 되면 add 메서드로 class를 붙여줍니다.
- footer 구역에 scroll의 값이 일정 값에 도달하면 top버튼이 add메서드를 사용해서 나타나게 해주고 일정값보다 작으면 remove 메서드로 사라지게 해줍니다.

**parallaxEffect04** : https://dongjin6539.github.io/web2023/javascript/parallax/parallaxEffect04.html <br> 
- 이번 웹 페이지에서는 css로 transform을 사용해서 animation 효과를 주고 transition을 사용해서 나타나는 효과를 적용했습니다.
- javascript를 사용해서 forEach를 사용해서 각 item의 scroll 값이 보여지는 화면에서 절반이 되었을 때 add 메서드를 사용해서 class를 붙여줍니다.

**parallaxEffect05** : https://dongjin6539.github.io/web2023/javascript/parallax/parallaxEffect05.html <br> 
- gsap(https://greensock.com/gsap/) 라이브러리를 사용했습니다.
- script src 태그를 사용해서 https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/gsap.min.js 의 cdn 링크를 가져왔습니다.
- gsap.to 메서드를 사용해서 scroll할 때 생기는 이질감 효과를 적용했습니다.

**parallaxEffect06** : https://dongjin6539.github.io/web2023/javascript/parallax/parallaxEffect06.html <br> 
- gsap(https://greensock.com/gsap/) 라이브러리를 사용했습니다.
- script src 태그를 사용해서 https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/gsap.min.js 의 cdn 링크를 가져왔습니다.
- split 메서드를 사용해서 해당 text를 span 태그로 감싸줍니다.
- span 태그를 css로 기존의 적용된 효과를 줍니다.
- gsap.to 메서드를 사용해서 scroll할 때 나타나도록 적용했습니다.

**parallaxEffect07** : https://dongjin6539.github.io/web2023/javascript/parallax/parallaxEffect07.html <br> 
- reveal 효과로 스크롤을 하면서 숨겨진 요소들이 나타나는 효과를 나타냈습니다.

**parallaxEffect08** : https://dongjin6539.github.io/web2023/javascript/parallax/parallaxEffect08.html <br> 
- gsap(https://greensock.com/gsap/) 라이브러리를 사용했습니다.
- script src 태그를 사용해서 https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/gsap.min.js 의 cdn 링크를 가져왔습니다.
- css로 flex 효과를 줘서 section 태그들이 가로로 나열되게 했습니다.
- gsap.to 메서드를 사용해서 scroll할 때 왼쪽으로 이동하게 적용했습니다.

**parallaxEffect09** : https://dongjin6539.github.io/web2023/javascript/parallax/parallaxEffect09.html <br> 
- gsap(https://greensock.com/gsap/) 라이브러리를 사용했습니다.
- script src 태그를 사용해서 https://cdn.jsdelivr.net/npm/gsap@3.12.2/dist/gsap.min.js 의 cdn 링크를 가져왔습니다.
- html 코드를 css로 flex 효과를 줘서 세로 모드와 가로 모드를 만들었습니다.
- gsap.to 메서드를 사용해서 scroll할 때 해당하는 scroll의 값이 일정 값에 오게 되면 왼쪽으로 이동하게 적용하고 그 section 태그가 끝나면 세로로 이동하게 됩니다.







