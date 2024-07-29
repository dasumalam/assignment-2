**Q-1 What are the benefits of using CSS?**
**Ans:**
CSS (Cascading Style Sheets) is used to style and layout web pages.

- **benefites:**
- Consistency
- Faster Loading Times
- Responsive Design
- Ease of Maintenance
- Accessibility
- Print-Friendly Pages
- Global Styling

---

**Q-2What are the disadvantages of CSS?**
**Ans:**
This can create confusion for non-developers and beginners. Lack of security is one of the major disadvantages of the Cascading style sheet.

- **disadvantages:**

- Learning Curve,
- Lack of Security,
- Limited Layout Control,
- Performance Impact,
- Overriding Styles,
- Maintenance Challenges.

---

**Q-3 What is the difference between CSS2 and CSS3?**
**Ans:**

- **CSS2:**
  CSS2 introduced a new box model which included padding, borders, and margins.

**Example:-**

```html
<html>
  <head>
    <title>web page</title>
    <style>
      .box1 {
        height: 200px;
        width: 200px;
        margin: 10% 40%;
        border: 3px solid black;
        background-image: url(https://play-lh.googleusercontent.com/l_Lm4yidvp_sfTkoDRdkF0lODJu72jkP4RfPqfPBlrk2X7b2qb0q88BUwt_7QzKSaLY);
        object-fit: cover;
        background-position: top;
      }
    </style>
  </head>
  <body>
    <div class="box1"></div>
  </body>
</html>
```

- **CSS3:**
  CSS3 introduced the flexible box layout module, which allows for more flexible layouts.

- **Example:-**

```html
<html>
  <head>
    <title>web page</title>
    <style>
      .boxs {
        height: 500px;
        width: 500px;
        display: flex;
        gap: 40px;
      }
      .box1 {
        height: 200px;
        width: 200px;
        border: 2px solid black;
        background-image: url(https://play-lh.googleusercontent.com/l_Lm4yidvp_sfTkoDRdkF0lODJu72jkP4RfPqfPBlrk2X7b2qb0q88BUwt_7QzKSaLY);
        object-fit: cover;
        background-position: top;
      }
      .box2 {
        height: 200px;
        width: 200px;
        border: 2px solid black;
        background-image: url(https://play-lh.googleusercontent.com/l_Lm4yidvp_sfTkoDRdkF0lODJu72jkP4RfPqfPBlrk2X7b2qb0q88BUwt_7QzKSaLY);
        object-fit: cover;
        background-position: center;
      }
    </style>
  </head>
  <body>
    <div class="boxs">
      <div class="box1"></div>
      <div class="box2"></div>
    </div>
  </body>
</html>
```

---

**Q-4 Name a few CSS style components?**
**Ans:**
  The components of a CSS (Cascading Style Sheets) style are:

* `Selector:` This is the HTML element or elements that the style will be applied to. 
* **Examples:** include h1, p, .class-name, or #id-name.
* `Property:` The specific aspect of the element that you want to style.
* **Example:** color, font-size, background-color, etc.
`Value:` The value assigned to the property.
 * **Example:** red, 16px, or #ffffff.

**Q-5 What do you understand by CSS opacity?**
**Ans:**
The opacity CSS property sets the opacity of an element. Opacity is the degree to which content behind an element is hidden, and is the opposite of transparency.

- **Example:**

```html
<html>
  <head>
    <title>opacity</title>
    <style>
      h2 {
        opacity: 1;
      }
      h1 {
        opacity: 0.55;
      }
    </style>
  </head>
  <body>
    <h5>Normal</h5>
    <h2>Hello Word</h2>
    <h5>opacity</h5>
    <h1>Hello Word</h1>
  </body>
</html>
```

---

**Q-6 How can the background color of an element be changed?**
**Ans:**
Use the CSS background-color property to add a background color to HTML. Put it into a style attribute and change the value to the desired color name or code. Then include this style attribute in an HTML element, such as a heading, span tag, table, or div.

- **Example:**

```html
<html>
  <head>
    <title>color</title>
    <style>
      * {
        margin: 0;
        box-sizing: border-box;
      }
      .boxs {
        margin: 100px auto;
        height: 300px;
        width: 300px;
        background-color: burlywood;
      }
      .box1 {
        height: 100px;
        width: 100px;
        background-color: brown;
      }
      .box2 {
        width: 100px;
        height: 100px;
        background-color: cadetblue;
      }
    </style>
  </head>
  <body>
    <div class="boxs">
      <div class="box1"></div>
      <div class="box2"></div>
    </div>
  </body>
</html>
```

---

**Q-7 How can image repetition of the backup be controlled?**
**Ans:**
The background-repeat property in CSS is used to repeat the background image both horizontally and vertically. It also decides whether the background image will be repeated or not.

- **Example**

```html
<html>
  <head>
    <title>web page</title>
    <style>
      .box {
        height: 300px;
        width: 300px;
        border: 1px solid black;
        border-radius: 12px;
        background-image: url(https://as1.ftcdn.net/jpg/07/14/32/64/220_F_714326459_HQC7IAgU5Dm6esO3LbNbhs9XehOaF0gQ.jpg);
        background-repeat: no-repeat;
      }
      .box1 {
        height: 300px;
        width: 300px;
        border: 1px solid black;
        border-radius: 12px;
        background-image: url(https://as1.ftcdn.net/jpg/07/14/32/64/220_F_714326459_HQC7IAgU5Dm6esO3LbNbhs9XehOaF0gQ.jpg);
      }
    </style>
  </head>
  <body>
    <div class="box"></div>
    <div class="box1"></div>
  </body>
</html>
```

---

**Q-8 What is the use of the background-position property?**
**Ans:**
he background-position property in CSS allows you to move a background image around within its container.

- **Example:**

```html
<html>
  <head>
    <title>web page</title>
    <style>
      .boxs {
        display: flex;
        gap: 20px;
      }
      .box {
        height: 400px;
        width: 400px;
        border: 1px solid black;
        background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Fronalpstock_big.jpg/1200px-Fronalpstock_big.jpg);
        background-position: top;
        object-fit: cover;
      }
      .box1 {
        height: 400px;
        width: 400px;
        border: 1px solid black;
        background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Fronalpstock_big.jpg/1200px-Fronalpstock_big.jpg);
        background-position: bottom left;
        object-fit: cover;
      }
    </style>
  </head>
  <body>
    <div class="boxs">
      <div class="box"></div>
      <div class="box1"></div>
    </div>
  </body>
</html>
```

---

**Q-9 Which property controls the image scroll in the background?**
**Ans:**
The background-attachment property in CSS is used to specify the kind of attachment of the background image with respect to its container. It can be set to scroll or make it remain fixed. It can be applied to all HTML elements.

- **Example:**

```html
<html>
  <head>
    <title>web page</title>
    <style>
        p {
          height: 300px;
        width: 30%;
        margin: 100px auto;
        background: scroll;
        background-attachment: local;
        overflow-y: scroll;
        background-image: url(https://thumbs.dreamstime.com/b/purple-flower-2212075.jpg);
      }
    </style>
  </head>
  <body>
    <p>
      “Nature has given us all the pieces required to achievexceptional wellness
      and health, ut has left it to us to put these pieces together.” —Diane
      McLaren Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam
      nobis, doloribus similique odio voluptatibus odit laborum tempora repellat
      illum fugit tenetur corporis doloremque blanditiis animi sit. Optio sint
      quas rem! Lorem ipsum dolor, sit amet consectetur adipisicing elit.
      Voluptatem iure nesciunt eius natus qui, laboriosam quisquam deserunt
      corporis necessitatibus fugit dolores et earum ut, possimus perferendis,
      in animi ducimus quo? Dolores culpa expedita itaque, quidem porro impedit
      architecto, totam mollitia, tempore tenetur ipsa modi magni distinctio
      cumque facilis quia voluptatibus.
      Nature has given us all the pieces required to achievexceptional wellness
      and health, ut has left it to us to put these pieces together.” —Diane
      McLaren Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam
      nobis, doloribus similique odio voluptatibus odit laborum tempora repellat
      illum fugit tenetur corporis doloremque blanditiis animi sit. Optio sint
      quas rem! Lorem ipsum dolor, sit amet consectetur adipisicing elit.
      Voluptatem iure nesciunt eius natus qui, laboriosam quisquam deserunt
      corporis necessitatibus fugit dolores et earum ut, possimus perferendis,
      in animi ducimus quo? Dolores culpa expedita itaque, quidem porro impedit
      architecto, totam mollitia, tempore tenetur ipsa modi magni distinctio
      cumque facilis quia voluptatibus.
    </p>
 </body>
</html>


```

---

**Q-10 Why should background and color be used as separate properties?**
**Ans:**
While background and color are often used together for elements, they serve different purposes. "Color" sets the text color, while "background" defines the background color or image. Separating them allows for more flexibility in styling, as background properties can include images, gradients, and positioning.

- **Example:**

  ```html
  <html>
    <head>
      <title>web page</title>
      <style>
        .box {
          height: 400px;
          width: 400px;
          border: 1px solid black;
          background-image: linear-gradient(pink, skyblue);
        }
        h1 {
          color: brown;
          border: 1px solid black;
          width: fit-content;
        }
      </style>
    </head>
    <body>
      <div class="box"></div>
      <h1>Hello Word</h1>
    </body>
  </html>

  ```
---

**Q-11 How to center block elements using CSS1?**
**Ans:**
To centrally align the block elements, we can simply make use of the `<center>` tag. All the elements within the `<center>` tag will be centrally aligned

- **Example:**

```html
<html>
  <head>
    <title></title>
    <style>
      .box {
        display: flex;
        height: 200px;
        width: 200px;
        border: 1px solid black;
        border-radius: 17px;
        align-items: center;
        justify-content: center;
      }
    </style>
  </head>
  <body>
    <div class="box">Hello Word</div>
  </body>
</html>
```

---

**Q-12 How to maintain the CSS specifications?**
**Ans:**

The components of a CSS (Cascading Style Sheets) style are:

* **Selector:** 
This is the HTML element or elements that the style will be applied to. Examples include h1, p, .class-name, or #id-name.
* **Property:**
 The specific aspect of the element that you want to style, such as color, font-size, background-color, etc.
* **Value:** 
The value assigned to the property, such as red, 16px, or #ffffff.

- **Example:**

```html
h1 { 
  color: blue; 
  font-size: 24px; 
  font-weight: bold; 
} 
 
.my-class { 
  background-color: #f2f2f2; 
  padding: 10px; 
  margin-bottom: 20px; 
} 
 
#my-id { 
  text-align: center; 
  font-family: Arial, sans-serif; 
} 
```

---

**Q-13 What are the ways to integrate CSS as a web page?**
**Ans:**
There are three primary methods to use CSS into your HTML documents: external, internal, and inline.

* **Inline CSS:**
 CSS styles are applied directly to HTML elements using the style attribute. This method is generally discouraged for larger projects as it makes the code less maintainable.

* **Internal CSS:**
For Internal CSS, a style tag is used in which all the styles related to the webpage are added. This style tag is added in the head tag of the page so that the styles are added even before the HTML document is rendered.

* **External CSS:**
In external CSS we use a separate file with a .css extension where we write all our styles. This CSS file can be used by multiple webpages by using a link tag which is added under the head tag.

  **Example:**
  ```html
  <html>
    <head>
      <title>Web page</title>
    </head>
    <style>
      .box {
        border: 1px solid black;
        height: 200px;
        width: 200px;
        color: brown;
        background-color: burlywood;
      }
    </style>
    <body>
      <div class="box">
        <ul>
          <li>tea</li>
          <li style="color: cyan;">pizzaa</li>
          <li style="font-size: 20px;">coffee</li>
        </ul>
      </div>
    </body>
  </html>
  ```

---

**Q-14 What is embedded style sheets?**
**Ans:**
Internal or embedded CSS requires you to add a `<style>` tag in the `<head>` section of your HTML document. This CSS style is an effective method of styling a single page.

- **Example:**
  ```html
  <html>
    <head>
      <title>web page</title>
      <style>
        .boxs {
          height: 500px;
          width: 500px;
          border: 1px solid black;
          border-radius: 12px;
          background-color: rgb(87, 62, 29);
          margin: 0px auto;
        }
        .box1 {
          margin: 10px 10px;
          height: 100px;
          width: 100px;
          border: 1px solid black;
          background-color: rgb(14, 70, 70);
        }
        .box2 {
          margin: 50px 150px;
          height: 100px;
          width: 100px;
          border: 1px solid black;
          background-color: rgb(14, 70, 70);
        }
        .box3 {
          margin: 100px 300px;
          height: 100px;
          width: 100px;
          border: 1px solid black;
          background-color: rgb(14, 70, 70);
        }
      </style>
    </head>
    <body>
      <div class="boxs">
        <div class="box1"></div>
        <div class="box2"></div>
        <div class="box3"></div>
      </div>
    </body>
  </html>
  ```
---

**Q-15 What are the external style sheets?**
**Ans:**
An external style sheet is a separate CSS file that can be accessed by creating a link within the head section of the webpage. Multiple webpages can use the same link to access the stylesheet.

- **Example**

```html
<html>
  <head>
    <title>web page</title>
    <link rel="stylesheet" href="D:\assignment\external.css" />
  </head>
  <body>
    <div class="box">
      <ul>
        <li>html</li>
        <li>java</li>
        <li>css</li>
      </ul>
    </div>
  </body>
</html>
```
---

**Q-16 What are the advantages and disadvantages of using external style sheets?**
**Ans:**
`The main advantages of using an external style sheet are:`

* **Separation of Concerns:** 
          Keeping the HTML and CSS separate makes the code more maintainable and easier to update.
* **Caching and Performance:**
         The external CSS file can be cached by the browser, reducing download times on subsequent page loads. This improves overall website performance.       
*  **Faster Development:**
          Developers can work on the HTML and CSS concurrently, as the CSS can be developed and tested independently of the HTML.

 `The main disadvantages of using an external style sheet include:`

* **Additional HTTP Request:**
       Loading an external CSS file requires an additional HTTP request, which can slightly increase the initial page load time, especially on slower connections.
* **Increased Complexity:**
 Managing a separate CSS file can add a bit of complexity to the development process, especially for small websites with limited styling needs.





---

**Q-17What is the meaning of the CSS selector?**
**Ans:**
The CSS selectors module defines the patterns to select elements to which a set of CSS rules are then applied along with their specificity

<b>There are several different types of selectors in CSS.</b>

- CSS Element Selector.
- CSS Id Selector.
- CSS Class Selector.
- CSS Universal Selector.
- CSS Group Selector.

---

**Q-18 What are the media types allowed by CSS?**
**Ans:**
* `all`: Suitable for all devices.
* `print`: Intended for paged material and documents viewed on a screen in print preview mode.
* `screen`: Intended primarily for color computer screens, including tablets, smartphones, etc.

---
**Q-19 What is the rule set?**
**Ans:**
* **Selector:** 
Identifies the HTML element(s) to which the rules apply.

* **Properties:** 
Define the visual styling and layout attributes, such as color, font-size, margin, padding, etc.

* **Values:**
 Specify the values for the properties, such as color: red; or font-size: 18px;

* **Declaration block:** 
The set of properties and values enclosed in curly braces ({}) that apply to the selected element(s).

---
**Q-20 Create Layouts**
**Ans:**  
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        
         .cards{
            display: flex;
             gap:30px;
             width: 1300px;
             margin: 30px auto;
             flex-wrap: wrap;
        } 
       .cards .card{
            height: 300px;
            width: 400px;
            border-radius: 15px;
            border: 1px solid black;
            background-color: rgb(236, 235, 233);
        }
        .card:hover{
            background-color: rgb(240, 236, 230);
            color: brown;
            box-shadow:10px 10px 5px rgb(225, 227, 228);
        }
     
        .card img{
            height: 60%;
            width: 100%;
            object-fit: cover;
            border-radius: 15px 15px 0px 0px;
        }
       .cards .card p{
            font-family:cursive;
            font-size: 14px;
            padding: 15px 20px;
        }
       .cards .card .btns{
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0px 10px;
        }
      .cards .card .btns .btn a {
           text-decoration: none;
            border-radius: 10px;         
            font-size: 13px;
            padding: 2px;
            font-family: cursive;
            border: 1px solid black;
            color: black;
        }
        a:hover{
            transition: all 3.5s ease-in;
            background-image: linear-gradient(rgb(204, 154, 189),rgb(248, 202, 141));
        }
       .card h5{
        font-family: cursive;
       }
    </style>
</head>
<body>
    <div class="cards">
        <div class="card">
            <img src="https://images.herzindagi.info/image/2024/Jul/season-3-mirzapur-location.jpg" alt="">
            <p>The series is produced by Ritesh Sidhwani and Farhan Akhtar of Excel Entertainment.
             The story follows Akhandanand Tripathi also known as Kaleen Bhaiya.
            </p>
            <div class="btns">
                <div class="btn">
           <a href="#">view</a>
           <a href="#">Edit</a>
        </div>
        <div class="btn">
            <h5>5 hours ago</h5>
        </div>
        </div>
        </div>
        <div class="card">
            <img src="https://assets-in.bmscdn.com/iedb/movies/images/mobile/listing/medium/kalki-2898-ad-et00352941-1718275859.jpg" alt="">
            <p>He is described as a Brahmin warrior in the Puranas. 
                It is mentioned in the Puranas that the immortal Chiranjivis will assist him in various stages of his life.
           </p>
           <div class="btns">
            <div class="btn">
       <a href="#">view</a>
       <a href="#">Edit</a>
    </div>
    <div class="btn">
        <h5>5 hours ago</h5>
    </div>
    </div>
        </div>
        <div class="card">
            <img src="https://images.indianexpress.com/2024/02/Fighter.jpg" alt="">
            <p>Shamsher Pathania fulfills his lifelong dream and becomes a member of the Indian air force. 
                As he faces rigorous challenges, Patty must rise above.
               </p>
               <div class="btns">
                <div class="btn">
           <a href="#">view</a>
           <a href="#">Edit</a>
        </div>
        <div class="btn">
            <h5>5 hours ago</h5>
        </div>
        </div>
     </div>
        <div class="card">
            <img src="https://images.herzindagi.info/image/2022/May/bhool-bhulaiyaa-2-cast-fees-Main.jpg" alt="">
            <p>arents need to know that Bhool Bhulaiyaa 2 is an Indian horror-comedy standalone sequel with plenty of 
                jump scares and some gruesome imagery. 
             </p>
             <div class="btns">
                <div class="btn">
           <a href="#">view</a>
           <a href="#">Edit</a>
        </div>
        <div class="btn">
            <h5>5 hours ago</h5>
        </div>
        </div>
    </div>
        <div class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-xXoURX1t5LEN565Cxl5f4J_hpsfDvQdj1Q&s" alt="">
            <p>The Avengers are a team of fictional superheroes and the protagonists of the Marvel Cinematic Universe
              media franchise,based on the Marvel Comics team of 
            </p>
            <div class="btns">
                <div class="btn">
           <a href="#">view</a>
           <a href="#">Edit</a>
        </div>
        <div class="btn">
            <h5>5 hours ago</h5>
        </div>
        </div>
     </div>
        <div class="card">
            <img src="https://i.ytimg.com/vi/CJuSuyGu-bU/maxresdefault.jpg" alt="">
            <p>"Yodha is a completely fictitious story. We have created a new task force-Yodha. So when you create something from zero, 
                 We have done many variations </p>
                 <div class="btns">
                   <div class="btn">
               <a href="#">view</a>
               <a href="#">Edit</a>
                </div>
            <div class="btn">
                <h5>5 hours ago</h5>
            </div>
            </div>
     </div>
    </div>
</body>
</html>
```
