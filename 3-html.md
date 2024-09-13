# 3-html

## Intoroduction
HTML (мова розмітки гіпертексту) служить основою для веб-сторінок, структуруючи вміст, як-от текст, зображення та відео. HTML утворює основу кожної веб-сторінки, визначаючи її структуру, вміст і взаємодію. Його незмінна актуальність полягає в його універсальному застосуванні у веб-розробці, що гарантує, що незалежно від використовуваного фреймворку чи мови вміст остаточно відтворюється в HTML.

Для початку роботи на компютері потрібно створити файл GitHub-HTML.html

Наша ціль зробити все те ж що й у уроці 2 але використовуючи значно сильніший синтаксис ніж Markdown

Писати ми будемо в файл і відкривати цей файл прямо у браузері

## Basic Syntax
Нижче приведені типові тектсові елементи що можуть бути використані у файлах формату .html

### Заголовки і текст:

<h1>GeeksforGeeks</h1>
<h2>GeeksforGeeks</h2>
<h3>GeeksforGeeks</h3>
<h4>GeeksforGeeks</h4>
<h5>GeeksforGeeks</h5>
<h6>GeeksforGeeks</h6>

<p>Звичайний текст</p>

<p>Звичайний текст <span>В який додано окремий текст, наприклад для подальшого виділення кольором</span></p>

<div>Блок із довільними даними</div>

<p>
    Посилання
    <!-- anchor tag starts -->
    <a href="https://www.geeksforgeeks.org">
        Текст посилання
    </a>
    <!-- anchor tag ends -->
</p>

### Стилі тексту:

<!-- emphasis -->
<div><em>Emphasized text</em></div>
<!-- strong -->
<div><strong>Important text!</strong></div>
<!-- subscript -->
<div>GFG<sub>subscript text</sub></div>
<!-- superscript -->
<div>GFG<sup>Superscript text</sup></div>
<!-- abbreviation -->
<div><abbr>Abbreviation</abbr></div>
<!-- mark -->
<div><mark>Highlighted text</mark></div>
<!-- cite -->
<div><cite>Title of creative work</cite></div>
<!-- time -->
<div>Time<time>9:00 am</time>
    to <time>7:00 pm</time>
</div>

### Списки:
<!-- Unordered List -->
<ul>
    <li>Data Structures & Algorithm</li>
    <li>Web Technology</li>
    <li>Aptitude & Logical Reasoning</li>
</ul>
<!-- Ordered List -->
<ol>
    <li>Array</li>
    <li>Linked List</li>
    <li>Stacks</li>
</ol>
<!-- Description List -->
<dl>
    <dt>Courses:</dt>
    <dd>100 </dd>
    <dt> Quizes:</dt>
    <dd> 500 </dd>
    <dt> Interview Experiences:</dt>
    <dd>1000 </dd>
</dl>

### Таблиці:
<!-- table starts here -->
<table>
    <!-- Table Caption -->
    <caption>Geeks For Geeks Learning</caption>
    <!-- Table row starts -->
    <tr>
        <!--Headers -->
        <th>Programming Languages</th>
        <th>Development</th>
    </tr>
    <!-- Table row ends -->
    <tr>
        <!-- Table data -->
        <td>C programming </td>
        <td>Full stack development</td>
    </tr>
    <tr>
        <td>Java programming</td>
        <td>Backend development</td>
    </tr>
    <tr>
        <td>Angular </td>
        <td>Frontend Development</td>
    </tr>
    <!-- Table Footer starts here -->
    <tfoot>
        <tr>
            <td>Footer content</td>
        </tr>
    </tfoot>
    <!-- Table footer ends here -->
</table>

### Медіа:

<p>image here</p>
<!-- image tag starts here-->
<img src=
"https://media.geeksforgeeks.org/wp-content/uploads/geeksforgeeks-13.png" 
     width="420" height="100" alt="Geeksforgeeks.org">
<!-- image tag ends here-->
<p> Audio Sample</p>
<!-- audio tag starts here -->
<audio controls>
    <source src="test.mp3" type="audio/mp3">
    <source src="test.ogg" type="audio/ogg">
</audio>
<!-- audio tag ends here -->
<p> Video sample</p>
<!-- Video tag starts here -->
<video width="400" height="350" controls>
    <source src="myvid.mp4" type="video/mp4">
    <source src="myvid.ogg" type="video/ogg">
</video>
<!-- Video tag ends here -->
<p> HTML Figure here</p>
<!--HTML figure tag starts here-->
<figure>
    <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/geeks-25.png" 
         width="304" height="228" alt="The Pulpit Rock">
    <figcaption>Figure Caption goes here </figcaption>
</figure>
<!--HTML figure tag ends here-->
<p> HTML Object here</p>
<!--HTML object tag starts here-->
<object data=
"https://media.geeksforgeeks.org/wp-content/cdn-uploads/Geek_logi_-low_res.png"
        width="550px" height="150px">
    GeeksforGeeks
    <!--HTML object tag ends here-->
</object>

### Форми:

<form>
  <fieldset>
      <legend>Personal Details</legend>
      <p>
      <p>select used here:</p>
      <!-- label starts -->
      <label>
          Salutation
          <br />
          <!-- select starts -->
          <select name="salutation">
              <option>--None--</option>
              <option>Mr.</option>
              <option>Ms.</option>
              <option>Mrs.</option>
          </select>
          <!-- select ends -->
      </label>
      <!-- label ends -->
      </p>
      <p>
          <label>First name: 
            <input name="firstName" placeholder="input element used here" />
          </label>
      </p>
      <p>
          <label>Last name: <input name="lastName" /></label>
      </p>
      <p>
          Gender :
          <label>
            <input type="radio" name="gender" value="male" /> Male
          </label>
          <label>
            <input type="radio" name="gender" value="female" /> Female
          </label>
      </p>
      <label Language preferred: </label>
          <input list="lang" placeholder="datalist used here">
          <!--datalist Tag starts here -->
          <datalist id="lang">
              <option value="java"></option>
              <option value="reactjs"></option>
              <option value="php"></option>
              <option value="python"></option>
          </datalist>
          <!--datalist Tag ends here -->
          <p>
              <label>Email:
                 <input type="email" name="email" />
              </label>
          </p>
          <p>
              <label>Date of Birth:
                 <input type="date" name="birthDate"/>
              </label>
          </p>
          <p>
              <!-- HTML address tag -->
              <label>
                  Address :
                  <br />
                  <!--Textarea  -->
                  <textarea name="address" 
                            placeholder="Textarea used here">
                  </textarea>
              </label>
          </p>
          <p>
              <button type="submit">Submit</button>
          </p>
          <p>Progress tag used here:</p>
          Downloading progress for your profile:
          <!--HTML progress tag starts here-->
          <progress value="57" max="100" placeholder="progress tag used here">
          </progress>
          <!--HTML progress tag ends here-->
  </fieldset>
</form>



