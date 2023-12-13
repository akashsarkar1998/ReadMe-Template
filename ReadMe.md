# Markdown Markup Language!
<!--https://www.youtube.com/watch?v=bl0-DTgh-mw&list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-&index=12-->
<!--Mark Down is a lightweight language that you can use to add formatting to plain txt documents.--> 
<!--We can use HTML syntax in markdown!, This is how we make comments -->
Normal text it is, And New line <br/> Also we can use HTML syntax here so we can make new line like this way! or type 2 space to create a new line.

---
1. Markdown is a markup language that allows users to format plain text without using HTML tags or a formal text editor. It's a lightweight text-to-HTML conversion tool that can add formatting elements like headings, bulleted lists, and URLs. Markdown is also device agnostic, meaning it displays the writing format consistently across devices. 
2. Is Markdown the same as HTML?
Markdown is easier to write than HTML, and it's easier for most humans to read Markdown source than HTML source
3. Is Python a Markdown language?
Python-Markdown is a free and open source Python library for converting Markdown code to HTML markup. It can either accept interactive input or process a Markdown file. Python-Markdown follows the rules of the original Markdown specification as much as possible.
<!--<hr>-->
<!--<hr>for horizontal rule!-->
<!--but we will use markdown-->
<!-- with this we maed an Horizontal rule-->
---
<!-- To markdown we need to start with #, # is a heading level-->
# <h1> Heading like  <!-- Same level as <h1> is html -->
##  <h2> Heading like
### <h3> Heading like
#### <h4> and same will go on!

<p> Now I am making a paragraph. Hi my name is Akash Sarkar, I am from India. I am 25 years old. </p>

### Italic text:
<i> This is italic text wit html syntax </i><br>

_This is italic text with MarkDown syntax_  
*This is also example of Italic text*
__To make word BOLD we can use 2 underscore__
<!-- Now Strikethrough text-->

#### Strike Through
<s> Strike through </s>  
<del> Strike through </del>  
~~Strike through~~  <!--Markdown syntax it is-->  
<!--Inline Code block-->  

### `This is Inline code!` <!--HTML syntax-->  
`This is Inline codes`
<!--Multiple line code blocks-->
### `Multiple Line Code:`
Here I am adding an code in this way
where we can use inline in multiple line like this:
For example: here it's an HTML code:
```html
<html>
    <head>
        <link rel="stylesheet" href="s_button.css">
    </head>
    <body>
        <div class="item">▽ Shoes</div>
        <div class="item">▽ Hoodies</div>
        <div class="item">▽ T Shirts</div>
    </body>
</html>
```  
```python
Python programming example:
# Compound Interest:
class Bank:
    bank_name= 'SBI'
    r= 7.25   #r = Rate of Interest.
    @staticmethod
    def compund_interest(p, y):
        ci= p*(pow((1+(Bank.r/100)),y)-1)
        total_amount= ci+p
        print(f"Your Simple Interest for Principle amount {p:.2f} is: {ci:.2f}")
        print(f"Your total amount for {p:.2f} + {ci:.2f} will be: {total_amount:.2f}")
    
p=float(input('Enter Principle Amount: '))
y= int(input('enter years: '))
Bank.compund_interest(p,y)
```
```javascript
if you are writing javascript language than just write there javascript so that we can get the format or style of that programming language
```
<br>
<!--List: See in Markdown language how to make list:-->

### Ordered List
1. Ajit Ranjan Sarkar
   1. Papia Sarkar
      1. Arpan Sarkar
2. Ajay Ranjan Sarkar
   1. Suparna Sarkar
      1. Akash Sarkar
<br>

#### Unordered list:
- Item 1
  - Item 1.1
    - iTEM 1.1.1
  - Item 1.2
- Item 2
  - Item 2.1
  - Item 2.2
- Item 3
<br>

#### Task Link:
- [x] Task 1
- [x] Task 2
- [x] Task 3

<br>

#### Automatic Link:
https://github.com/akashsarkar1998


#### Disable Automatic Link:
`https://github.com/akashsarkar1998`
<!-- Link is under the title, means if we click the tile then the link will open!-->
#### Markdown Link Syntax:
[Akash's-Github-Account](https://github.com/akashsarkar1998)

#### Markdown Link Syntax(One link but use it multiple times):
[Akash's-Github-Account][website_link]
[Akash's-Linkedin-Account][Linkedin_Account]


<!--All links are here-->
[website_link]: https://github.com/akashsarkar1998
[Linkedin_Account]: https://www.linkedin.com/in/akash-sarkar59/

<br>  

#### Image Syntax:
<!--Markdown syntax:-->

![text_something...] (image_source)
<br>  

![profile](./google.png)
<!--HTML Syntax-->
<img src="./google.png" width="250" height= "100" title = "Profile image"/>  

<br>

### Emoji
🔥

### Table syntax:
| Name | Roll No | Class | Email |
|------|---------|-------|-------|
| Akash sarkar | 10 | 6 | akashsarkarcob98@gmail.com |
| Arpan sarkar | 11 | 12 | arpansarkar@email.com |
| Arnab sarkar | 12 | 1 | arnabsarkar@gmail.com |
| Ajay Ranjan sarkar | 59 | 12 | ajaysarkar@gmail.com |