# 251216

# iframe 알아보기
구글 지도, 유튜브, 웹 페이지...


# 선택자
동일한 대상이면 마지막 설정된 값으로 설정 됨 <br>
href 속성 이름 <br>

선택자 : 태그, 아이디, 클래스 <br>
		============================================ <br>
		= 전체 일치 <br>
		^= 시작하는 <br>
		$= 끝나는 <br>
		*= 일부 문자 (단어 중 일부 문자) <br>
		~= 단어 일치 <br>
		============================================ <br>
사용 예시) a[href^="https"] {background-color: purple; color:#fff;} <br>

	/* 방문하지않은 link */
		a:link{
			color:#0f0;
			text-decoration: none;
		}
		/* 방문한 link */
		a:visited{
			color: #ddd;
		}
		/* 마우스를 올려 놨을 때 */
		a:hover{
			color: #f00;
			text-decoration: underline;
		}
		/* 클릭했을 때 */
		a:active{
			color: #00f;
		}
		/* 탭키 */
		a:focus{
			background-color: #ff0;
		}
     /* 플롯 해제 할 때 주로 사용 */
  	h1::before {
			content: "이전";
			color: red;
		}
		h1::after {
			content: "이후";
			color: blue;
		}
    /* 첫번째 글자 */
    	p::first-letter {
			font-size: 2em;
			font-weight: bold;
			color: navy;
		}
    /* 첫 줄 */
		div::first-line {
			color: red;
			background-color: yellow;
		}
    /* 드래그 했을 때 */
    div::selection {
			background-color: gray;
			color: blue;
		} 
    
    






    
