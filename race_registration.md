# Race Registration
> race_registration.html 파일에 대한 설명입니다. html로만 작성하여 만든 페이지로 이후에 기능을 추가할 예정입니다.
> Udemy Web 강의와 w3schools 사이트를 참고했습니다.

- div 요소를 사용해 적절히 내용을 나누었습니다.
- radio 속성의 value를 명시하여 정확한 값이 전달되도록 하였습니다.
- email 속성을 사용하여 email 형식으로 입력되도록 하였습니다.
- password 속성을 사용하여 입력 값이 가려지도록 하였습니다.
- select 요소와 option 요소를 사용하여 드롭다운 메뉴가 만들어지도록 하였습니다.
- 다른 사람이 보아도 이해하기 쉽도록 id, name을 적절히 작성하였습니다.

### form
form에 대한 이해가 필요합니다.
form 요소는 input 요소의 다른 타입들을 위한 컨테이너입니다. input 요소의 타입은 text fields, checkboxes, radio buttons 등이 있습니다.

form 요소의 action 속성은 form data를 서버로 보낼 때 해당 데이터가 도착할 URL을 명시합니다.
```
<form action="">
</form>
```

### input
input 요소는 type 속성을 사용해 다양한 방식으로 나타낼 수 있습니다. type 속성은 text, radio, checkbox, email, password 등이 있습니다.
이외에도 id, name, value 속성 등이 있습니다. 

특히 radio type을 사용할 때는 value 값을 반드시 지정해주는 것이 좋습니다.
```
<form>
  <input type="radio" id="java" name="fav-lang" value="java">
  <input type="radio" id="c" name="fav-lang" value="c">
  <input type="radio" id="javascript" name="fav-lang" value="javascript">
```

### label
label의 for 속성 값과 input의 id 속성 값이 같다면 해당 input의 label로 사용할 수 있습니다.
```
<form>
  <input type="radio" id="java" name="fav-lang" value="java">
  <label for="java">JAVA</label><br>
  <input type="radio" id="c" name="fav-lang" value="c">
  <label for="c">C</label><br>
  <input type="radio" id="javascript" name="fav-lang" value="javascript">
  <label for="javascript">JAVASCRIPT</label>
</form>
```
<br>

[W3SCHOOLS ABOUT HTML FORMS](https://www.w3schools.com/html/html_forms.asp)
