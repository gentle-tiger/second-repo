# HTML(생활코딩)

과목: HTML
날짜: 2023년 3월 11일 → 2023년 3월 13일
진행상황: Not started
체크박스: No
현재 진행중인 강의: 100

- **기술소개**
    
    ![Untitled](HTML(%E1%84%89%E1%85%A2%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B5%E1%86%BC)%20a14997571ceb40f787ff45562dbbc7d7/Untitled.png)
    
    **HyperText** : 하이퍼텍스트를 가장 중요한 특징으로 하는 
    
    **Markup** : 마크업이라는 형식을 가진 
    
    **Language** : 컴퓨터 프로그래밍 언어 
    
    - 사람과 컴퓨터가 소통할 수 있도록 하는 것이 컴퓨터 프로그램밍 언어이다 .
    - 사람과 웹 브라우저 사이에서 서로가 이해할 수 있도록 하는 **약속**이다.
    
- **기본문법**
    - 태그
        
        ```php
        <h1>생활코딩의 어록</h1>
        우리 모두는 <strong>자신의 힘</strong>으로 발견한 내용을 가장 쉽게 익힌다. (도널드 커누스)
        ```
        
- **하이퍼텍스트와 속성**
    
    ```php
    <a herf="https://www.youtube.com/watch?v=AE7foaifXMU&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=5" target="_blank" title="생활코딩은 전설이다.">
    블링크는 새로운 탭이 열리는 속성이다.</a>
    ```
    
    ![Untitled](HTML(%E1%84%89%E1%85%A2%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B5%E1%86%BC)%20a14997571ceb40f787ff45562dbbc7d7/Untitled%201.png)
    
- **태그의 중첩과 목록**
    
    ```php
    <ol> // ordered list 순서가 있는 리스트
      <li>기술소개</li>
      <li>기본문법</li>
      <li>하이퍼텍스트와 속성</li>
      <li>리스트와 태그의 중첩</li>
    </ol>
    <ul>  // unordered list
      <li>최진혁</li>
      <li>최유빈</li>
      <li>한이람</li>
      <li>한이은</li>
    </ul>
    ```
    
- **문서의 구조**
    
    ```php
    html>
    <head>
      <title>HTML - 수업소개</title>
      <meta charset="utf-8">
    </head>
    ------------------------↑ 본문이 아닌 태그, 문서 자체를 꾸며주는 역할 head
    ------------------------↓ 본문인 태그 body
    <body>
    <h1>HTML</h1>
    <ol>
      <li>기술소개</li>
      <li>기본문법</li>
      <li>하이퍼텍스트와 속성</li>
      <li>리스트와 태그의 중첩</li>
    </ol>
     
    <h2>선행학습</h2>
     
    본 수업을 효과적으로 수행하기 위해서는 웹애플리케이션에 대한 전반적인 이해가 필요합니다. 이를 위해서 준비된 수업은 아래 링크를 통해서 접근하실 수 있습니다. 
    </body>
    </html>
    ```
    
- **DOCTYPE html**
    - 우리가 만든 코드가 어떤 표준을 따르고 있는 코드인지 알려준다.
    - HTML의 버전마다 다르지만 HTML5의 DOCTYPE의 경우
    
    <aside>
    💡 In other words, `<!DOCTYPE html>`, case-insensitively
    
    NOT case sensitive.
    
    `<!DOCTYPE html>`
    
    `<!DocType html>`
    
    `<!Doctype html>`
    
    `<!doctype html>`
    
    </aside>
    
- **웹사이트 만들기**
    
    ```php
    <h1><a href="index.html">HTML</a></h1>
    <ol>
    	<li><a href="1.html">기술소개</a></li>
      <li><a href="2.html">기본문법<a/></li>
      <li><a href="3.html">하이퍼텍스트와 속성</a></li>
      <li><a href="4.html">리스트와 태그의 중첩</a></li>
    </ol>
    ```
    
- **개발도구**
    
    atom
    
    subline text
    
    bracket
    
- **HTML의 변천사와 통계**
    
    [http://www.martinrinehart.com/frontend-engineering/engineers/html/html-tag-history.html](http://www.martinrinehart.com/frontend-engineering/engineers/html/html-tag-history.html)
    
    [HTML Study | Advanced Web Ranking](https://www.advancedwebranking.com/seo/html-study/)
    
- **주요태그**
    - 단락 - <p>
        
        ```php
        <body>
        	<p>HyperText Markup Language,  rather than a programming language.</p>
        	<p>HTML elements form the building blocks of all websites.</p>
        	<p>The language is written in the form of HTML elements consisting of tags enclosed in angle brackets .</p>
        </body>
        ```
        
    - 줄바꿈 - <br> / p태그를 더 많이 쓴다.
        
        ```php
        HTML elements form the building blocks of all websites. HTML allows images and objects to be embedded and can be used to create interactive forms.<br><br><br>
        The language is written in the form of HTML elements consisting of tags enclosed in angle brackets.<br><br><br>
        ```
        
    - 이미지 -<img>
        
        ```php
        <body>
            <img src="img.jpg" height="300" alt="산 이미지" title="산 이미지">
        </body>
        ```
        
    - 표 -table
        
        ```php
        <table border="2">
            <tr>
                <td>이름</td>     <td>성별</td>   <td>주소</td>
            </tr>
            <tr>
                <td>최진혁</td>  <td>남</td>      <td rowspan="2">청주</td>
            </tr>
            <tr>
                <td colspan="3">최유빈</td>  <td>여</td>      <td>청주</td>
            </tr>
        </table>
        
        (table>thrad>tr>td*3)*3
        ```
        
    - 입력양식 - <from>
        
        ```php
        <body>
        <form action="http://localhost/login.php">
            <p>아이디 : <input type="text" name="id"></p>
            <p>비밀번호 : <input type="password" name="pwd"></p>
            <p>주소 : <input type="text" name="address"></p>
            <input type="submit">
        </form>
        </body>
        ```
        
        - 텍스트 입력
        
        ```php
        <p>textarea :
                    <textarea cols="50" rows="2">default value</textarea>
        ```
        
    - **form 태그** - Dropdown list
        - select
            
            ```html
            <form action="http://localhost/color.php">
                        <h1>색상</h1>
                        <select name="color">
                            <option value="red">붉은색</option>
                            <option value="black">검은색</option>
                            <option value="blue">파란색</option>
                        </select>
                        <h1>색상2 (다중선택)</h1>
                        <select name="color2" multiple>
                            <option value="red">붉은색</option>
                            <option value="black">검은색</option>
                            <option value="blue">파란색</option>
                        </select>
                        <input type="submit">
                    </form>
            ```
            
        - checkbox, radio
            
            ```html
            <html>
                <head>
                    <meta charset="utf-8">
                </head>
                <body>
                  <form action="http://localhost/order.php">
                   <p>
                    <h1>색상(단일선택)</h1> // 같은 name으로 묶여주면 단일선택이 가능함.
                     붉은색 : <input type="radio" name="color" value="red">
                     검은색 : <input type="radio" name="color" value="black" checked>
                     파란색 : <input type="radio" name="color" value="blue">
                   </p>
            //radio는 name 값이 같은 것끼리 그룹핑되는 것이다. 
                    <p>
                     <h1>사이즈(다중선택)</h1>
                       95 : <input type="checkbox" name="size" value="95">
                      100 : <input type="checkbox" name="size" value="100" checked>
                      105 : <input type="checkbox" name="size" value="105" checked>
                    </p>
                     <input type="submit">
                  </form>
                </body>
            </html>
            ```
            
        - 버튼
            
            ```html
            <html>
            <head><meta charset="utf-8"></head>
            <body>
                <form action="http://localhost/form.php">
                    <input type="text">
                    <input type="submit" value="전송">  
                    <input type="button" value="버튼" onclick="alert('hello world')">
                     // button은 onclick 속성을 사용할 때 주로 사용함.
                    <input type="reset"> // 재설정 
                </form>
            </body>
            </html>
            ```
            
        - 데이터 전송 - hidden
            
            ```html
            // ui가 없지만 서버로 어떠한 값을 전송하고 싶을 때 사용하는 것
            <html>
                <head>
                    <meta charset="utf-8">
                </head>
                <body>
                    <form action="http://localhost/hidden.php"> // 데이터 전송 위치
                        <input type="text" name="id"> 
                        <input type="hidden" name="hide" value="egoing">
                        <input type="submit">
                    </form>
                </body>
            </html>
            텍스트에 hello를 쳤을 때 데이터 전송은 
            http://localhost/hidden.php?id=hello가 된다. 
            
            hidden 이라는 값은 egoing이라는 값이 된다. 
            ```
            
            ![Untitled](HTML(%E1%84%89%E1%85%A2%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B5%E1%86%BC)%20a14997571ceb40f787ff45562dbbc7d7/Untitled%202.png)
            
        - 컨트롤의 제목 - lable // 제목이라는 의미를 가지는 정보
            - 동일한 결과의 다른 방식을 표현한 것이다. for와 id의 값을 동일하게 묶어 좀 더 정보로서의 역할을 한다.
            
            ```html
            <p>
            <label>
                <input type="checkbox" name="color" value="red">붉은색    
            </label>
            
            <label for="color_blue">
                <input id="color_blue" type="eheckbox" name="color" value="blue">파란색
            </label> //for와 id의 값을 동일하게 묶어 좀 더 정보로서의 역할을 한다.
            </p>
            ```
            
        - method // 서버 지식 필요
            - get 방식이 아닌 post 방식. 서버쪽의 내용일 수 있다.
            
            <aside>
            💡 전송되는 방식이 url 방식으로 가게 되면 보안에 문제가 생긴다. post는 전송 방식이다. 기본값은 get이다. 
            **url을 통해서 전송하는 것이 get 방식**이다. 
            **form으로 데이터를 전송한다고 한다면 거의 대부분 post방식**으로 한다.
            
            </aside>
            
            ```html
            <html>
                <head>
                    <meta charset="utf-8">
                </head>
                <body>
                    <form action="http://localhost/method.php" method="post">
                        <input type="text" name="id">
                        <input type="password" name="pwd">
                        <input type="submit">
                    </form>
                </body>
            </html>
            ```
            
        - 파일 업로드 upload // 서버 지식 필요
            
            파일을 업로드 하는 기능이 있다면 `method="post" enctype="multipart/form-data"` 로 해야한다. 
            
            ```html
            <html>
                <head>
                    <meta charset="utf-8">
                </head>
                <body>
                    <form action="http://localhost/upload.php" method="post" enctype="multipart/form-data">
            
                        <input type="file" name="profile"> //사용자가 파일은 전송할 수 있다. 
                        <input type="submit"> // 서버로 전송
                    </form>
                </body>
            </html>
            
            ```
            
    - 웹개발자도구
        - [크롬 개발자 도구](https://www.notion.so/23c36ca295ab467392f71f8ea8cfb167)
    - 모바일 지원 (viewport)
        
        ```html
        <!DOCTYPE html>
        <html>
        <head>
          <title>HTML - 수업소개</title>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
        </head>
        <body>
        <h1><a href="index.html">HTML</a></h1>
        <ol>
          <li><a href="1.html">기술소개</a></li>
          <li><a href="2.html">기본문법<a/></li>
          <li><a href="3.html">하이퍼텍스트와 속성</a></li>
          <li><a href="4.html">리스트와 태그의 중첩</a></li>
        </ol>
         
        <h2>선행학습</h2>
         
        본 수업을 효과적으로 수행하기 위해서는 웹애플리케이션에 대한 전반적인 이해가 필요합니다. 이를 위해서 준비된 수업은 아래 링크를 통해서 접근하실 수 있습니다.
        </body>
        </html>
        ```
        
    - 외부문서삽입 - iframe
        
        <aside>
        💡 웹페이지에 다른 웹페이지를 삽입하는 방법인 아이프래임은 참 편리하면서도 위험한 방법입니다. 왜냐면 신뢰할 수 없는 사이트에서 악성코드 같은 것을 포함하고 있다면 삽입된 외부소스에서 악성코드가 실행될 수 있기 때문이죠. 이런 문제를 해소하기 위해서 HTML의 최신 버전인 HTML5에서는 샌드박스라는 것을 도입했습니다. 아이프래임으로 삽입된 웹페이지에서 자바스크립트 등이 실행되지 않도록 하는 방법인데요. 아이패래임이 무엇인지, 사용법, 그리고 보안을 개선할 수 있는 새로운 방법을 소개합니다.
        
        </aside>
        
- **정보로서의 HTML**
    - font (왜 퇴출되었는가?)
        
        ```ebnf
        <font="5" color="red">hello</font>world
        hello world의 내용에서 font의 의미는 무엇인가? ? ? ? ? ? 
        ```
        
    - meta 태그(의미론적 태그)
        
        문서의 정보를 보다 잘 표현하기 위해서는 의미에 맞는 태그를 잘 사용해야 합니다. 특히 HTML5에서는 웹페이지에서 통상 많이 사용하는 구조에 의미를 분명히 부여하기 위해서 의미론적 태그(semantic element)를 새롭게 정의해서 제공하고 있습니다. 그 목록은 아래와 같습니다.
        
        ![Untitled](HTML(%E1%84%89%E1%85%A2%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B5%E1%86%BC)%20a14997571ceb40f787ff45562dbbc7d7/Untitled%203.png)
        
    - **검색엔진 최적화**
        - 구글에서 공개한 검색엔진 최적화
        
        [검색엔진 최적화 개선 문서 | Google 검색 센터  |  Google Developers](https://developers.google.com/search/docs?hl=ko)
        
        ## **웹 페이지를 만드는데 가장 기본이 되는 가이드이다.**
        
        [SEO 기본 가이드: 기본사항 | Google 검색 센터  |  문서  |  Google Developers](https://developers.google.com/search/docs/fundamentals/seo-starter-guide?hl=ko)
        
        ![Untitled](HTML(%E1%84%89%E1%85%A2%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B5%E1%86%BC)%20a14997571ceb40f787ff45562dbbc7d7/Untitled%204.png)
        
        ![Untitled](HTML(%E1%84%89%E1%85%A2%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B5%E1%86%BC)%20a14997571ceb40f787ff45562dbbc7d7/Untitled%205.png)
        
        [자바스크립트 검색엔진 최적화의 기본사항 이해하기 | Google 검색 센터  |  문서  |  Google Developers](https://developers.google.com/search/docs/crawling-indexing/javascript/javascript-seo-basics?hl=ko)
        
        /robots.txt 
        
- **웹개발자 도구**
    - [크롬 개발자 도구](https://www.notion.so/23c36ca295ab467392f71f8ea8cfb167)
    
    [둘러보기 - 크롬 개발자 도구](https://opentutorials.org/module/306/2865)
    
- **모바일 지원 (viewport)**
    
      **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**
    
    ```ebnf
    <!DOCTYPE html>
    <html>
    <head>
      <title>HTML - 수업소개</title>
      <meta charset="utf-8">
      **<meta name="viewport" content="width=device-width, initial-scale=1.0">**
    </head>
    <body>
    <h1><a href="index.html">HTML</a></h1>
    <ol>
      <li><a href="1.html">기술소개</a></li>
      <li><a href="2.html">기본문법<a/></li>
      <li><a href="3.html">하이퍼텍스트와 속성</a></li>
      <li><a href="4.html">리스트와 태그의 중첩</a></li>
    </ol>
     
    <h2>선행학습</h2>
     
    본 수업을 효과적으로 수행하기 위해서는 웹애플리케이션에 대한 전반적인 이해가 필요합니다. 이를 위해서 준비된 수업은 아래 링크를 통해서 접근하실 수 있습니다.
    </body>
    </html>
    ```
    
- **부문서삽입 - iframe**
    
    ![Untitled](HTML(%E1%84%89%E1%85%A2%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B5%E1%86%BC)%20a14997571ceb40f787ff45562dbbc7d7/Untitled%206.png)
    
    ![Untitled](HTML(%E1%84%89%E1%85%A2%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B5%E1%86%BC)%20a14997571ceb40f787ff45562dbbc7d7/Untitled%207.png)
    
    ```html
    <body>
        <iframe src="https://opentutorials.org/module/1892/10951" frameborder="0" width="500" height="500" sandbox></iframe>
       // <iframe src="iframe_source.html" frameborder="0" width="500" height="500"></iframe>
    </body>
    sandbox를 통해서 보안을 막아준다. 
    ```
    
    <aside>
    💡 웹페이지에 다른 웹페이지를 삽입하는 방법인 아이프래임은 참 편리하면서도 위험한 방법입니다. 왜냐면 신뢰할 수 없는 사이트에서 악성코드 같은 것을 포함하고 있다면 삽입된 외부소스에서 악성코드가 실행될 수 있기 때문이죠. 이런 문제를 해소하기 위해서 HTML의 최신 버전인 HTML5에서는 샌드박스라는 것을 도입했습니다. 아이프래임으로 삽입된 웹페이지에서 자바스크립트 등이 실행되지 않도록 하는 방법인데요. 아이패래임이 무엇인지, 사용법, 그리고 보안을 개선할 수 있는 새로운 방법을 소개합니다.
    
    </aside>
    
- **HTML5**
    - 비디어 - video
    - can i use
    
    [Can I use... Support tables for HTML5, CSS3, etc](https://caniuse.com/)
    
- **HTML5의 입력방식**
    - **input types**
        - color : 색상
        - date : 날짜
        - datetime : 국제표준시
        - datetime-local : 현재살고 있는 지역
        - email : 이메일을 쉽게 입력
        - month : 연과 월을 지정
        - number : 숫자만 입력할 수 있게 한다.
        - range : 슬라이드를 움직일 수 있게?
        - search : 검색하는 입력창
        - tel : 전화번호
        - time : 시간
        - url : rul
        - week : 줄
    - **HTML5 입력양식의 속성들**
        
        `autocomplete="on"` 자동완성기능 on
        
         `autocomplete="off"` 자동완성기능 off
        
        `autofocus` 사이트에 도착하자마다 자동으로 포커싱된다. 
        
        ```html
        <!DOCTYPE html>
        <html>
            <head>
                <meta charset="utf-8">
            </head>
            <body>
                <form action="login.php" autocomplete="on">
                    <input type="text" name="id" placeholder="id를 입력해주세요." autofocus>
                    <input type="password" name="password" autocomplete="off" placeholder="비밀번호를 입력해주세요.">
                    <input type="submit">
                </form>
            </body>
        </html>
        ```
        
    - **HTML5 입력 값 체크**
        
        `required` 굳이 입력하지 않아도 되는 내용 
        
        `pattern="[a-zA-Z].+[0-9]"` 입력 양식 패턴을 만들고 싶다면 **정규표현식**
        
        ```html
        <!DOCTYPE html>
        <html>
            <head>
                <meta charset="utf-8">
            </head>
            <body>
                <form action="register.php">
                    <input type="text" name="id" placeholder="아이디를 입력" required pattern="[a-zA-Z].+[0-9]">
                    <input type="email" name="email" placeholder="이메일 입력">
                    <input type="submit">
                </form>
            </body>
        </html>
        ```