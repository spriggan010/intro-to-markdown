# INTRODUCTION TO MARKDOWN

<!--HEADING-->
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

##### Heading 6

---

<!-- Italics -->

_This is going to be a paragraph that is using italic styling_

*This is going to be a paragraph that is using italic styling*

---

<!-- Strong -->

This is an example of **strong text** , anything between the two opening asterisk and two closing asterisk will be displayed as **strong text**

This is another example of a way to have __strongtext__ in our document. Anything between the two double opening underscore and closing underscore will bed displayed as __strong text__.

<!-- Strike Trough -->

This is an example of a ~~strikethrough~~ text, anything in between the double tilde opening characters and closing doulbe tilde characters will be displayed as ~~strike through~~ text.

---
<!-- Horizontal Rule -->

We can add triple hypens to be able to create a horizontal rule for separating content.

Another way to add __HORIZONTAL RULES__ in our document markdown is by using three underscores.
___

<!-- Escape Character Rule using Backslash -->

This is an example of a *text with an asterisk*. When we don't want i t to be italicized. We want to use the backslash to escape the rule of using an opening \*asterisk* and closing \*asterisk* to enclose the text contents.

---

<!-- Blockquote Rule -->

>We use the greater than symbol to display a block of text as a quote with a background and line on the left side.

> *"You don't have to be great to start, but you need to start to be great."* - __Unknwon Author__

---

<!-- Link Rule -->

**NOTE**: We would want to put the link description inside of square brackets and the link to the resource inside of two open and close parenthesis.
[JRacca pexels collection profile](https://images.pexels.com/photos/10499104/pexels-photo-10499104.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

__NOTE__: We can add a baloon title description to our lin k by using double quotes after the link to the resource.
[JRacca pexels collection profile](https://images.pexels.com/photos/10499104/pexels-photo-10499104.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1/ "JRACCA pexel photo")

---

<!-- List Item Rules -->

<!-- Unordered Lists -->

* Item 1 - This is going to be our list item 1
  *  This is our list item 1 child item 1
  *  This is our list item 2 child item 2
* Item 2 - This is going to be our list item 2
  *  This is our list itme 2 child item 1
  *  This is our list itme 2 child item 2
* Item 3 - This is going to be our list item 3
  *  This is our list itme 3 child item 1
  *  This is our list itme 3 child item 2 
* Item 4 - This is going to be our list item 4
  *  This is our list itme 4 child item 1
  *  This is our list itme 4 child item 2 
* Item 5 - This is going to be our list item 5
  *  This is our list itme 5 child item 1 
  *  This is our list itme 5 child item 2 

<!-- Ordered List -->

1. Item 1 - This is going to be our list item 1

      1.  This is our list item 1 child item 1

      3.  This is our list item 2 child item 2

2. Item 2 - This is going to be our list item 2

      1.  This is our list itme 2 child item 1

      3.  This is our list itme 2 child item 2

3. Item 3 - This is going to be our list item 3

      1.  This is our list itme 3 child item 1

      3.  This is our list itme 3 child item 2 

4. Item 4 - This is going to be our list item 4

      1.  This is our list itme 4 child item 1

      3.  This is our list itme 4 child item 2 

5. Item 5 - This is going to be our list item 5

      1.  This is our list itme 5 child item 1 

      3.  This is our list itme 5 child item 2 
      
      
---

<!--Code Block Inline Example-->

**NOTE**: *__Backtics__ will allow us to show the code block or the paragraph tags in this example. It is located below the tilde character and on top of the tab key*

`<p> This is a paragraph tag with an inline codee block example opening ang closing tags </p>`


---

<!-- Image Rule -->

![This is an image](https://images.pexels.com/photos/1404819/pexels-photo-1404819.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1 "Link to a cat image")

---

<!-- GITHUB FLAVOR SET OF CODE BLOCK -->

<!-- CODE BLOCKS FOR GITHUB DOCUMENTATION -->

```install npm
npm install

npm start
```

**NOTE**: You can specify some syntax code blocks for different languages

```javascript
  function jsadd (num1,num2){
    return num1 + num2;
}
```

```python
  def pythonAdd(um1,num2):
    return num1 + num2;
```

```C#
  public static int Sum(int num1, int num2)
    {
      int total;
      total = num1 + num2;
      return total;
    }
```

---

<!-- Table Rules -->

| Name | Nickname | Email               |
|------|----------|-------              |
|John  |Jo        |john@gmail.com       |
|Jason |J         |spriggan010@yahoo.com|
|Bart  |CoolKid   |testbart@gmail.com   |
