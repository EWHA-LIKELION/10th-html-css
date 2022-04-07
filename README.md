# 10th-html-css
#### 멋사 1회차 세션 과제
> ##### HTML/CSS로 자기소개 페이지 만들기


## HTML

   
1. **[ABOUT ME]** _section_
  - p 태그 : 자기소개글(텍스트)   
  - img 태그 : 대표사진
  
  ```html
        <p class="about-me-text"></p>
        <img src="image.jpg" />
  ```
  
2. **[EDUCATION]** _section_
  - div 태그 : float wrap을 위해 사용
  - p 태그 : 학교 이름, 세부 정보(텍스트)
  
  ```html
        <div class="float-wrap">
          <p class="title-text"></p>
          <p class="year-text"></p>
        </div>
        <p class="desc-text"></p>
        <p class="desc-subtext"></p>
  ```
  
 3. **[CONTACT]** _section_
  - div 태그 : float wrap을 위해 사용
  - ul, li 태그 : 이메일, 전화번호를 리스트로 나열
  
  ```html
        <div class="float-wrap">
          <ul>
            <li>
              <p class="desc-contact"></p>
            </li>
            <li>
              <p class="desc-contact"></p>
            </li>
          </ul>
        </div>
  ```
  
  4. **SNS** _section_
   - div 태그 : float wrap을 위해 사용
   - a 태그 : img 태그에 링크를 연결
   
   ```html
      <div class="sns-wrap">
        <a href="https:// 링크 ~ "><img class="sns-img" src="image.jpg"/></a>
      </div>
   ```
   
   ***
   
   ## CSS
   
   - **웹폰트 적용**   
     웹폰트 코드 복사 후 전체 선택자로 적용
   ```html
    @font-face {
    font-family: "GmarketSansMedium";
    src: url("https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2001@1.1/GmarketSansMedium.woff")
    format("woff");
    font-weight: normal;
    font-style: normal;
    }

    * {
    font-family: "GmarketSansMedium";
    }
   ```

- **태그 선택자, 클래스 선택자 사용**   
```html
   .mainbox {
   width: 610px;
   padding: 30px;
   margin: 30px;
   margin-right: auto;
   margin-left: auto;
   border: 1px solid #ebebeb;
   box-shadow: 0 1px 20px 0 rgba(0, 0, 0, 0.1);
   }
```
