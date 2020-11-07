# Topic HTML and CSS

● Create a basic portfolio page layout using the html tags.

● Add some style to the tags using css selectors.

●We will be using a modern framework to create native mobile apps - called React Native. React Native builds on the HTML, CSS and Javascript used for the web to create modern mobile apps.

●HTML (Hypertext Markup Language) and CSS (Cascading Style Sheets).

Tag

< > open

</> close

First, we write the tag <!DOCTYPE HTML> to tell the computer that this is going to be an HTML page. This informs the browser that it is going to read an HTML page. This is a must do for all HTML pages. All our HTML content comes inside the opening <html> tag and closing </html> tag.

Inside <html> tags, we can have <head> tags and <body> tags. Inside <head> tags, we store information about the page. Inside <body> tags we write content which is displayed on the web page.

navigation menu as well which can lead to other webpages. These are called hyperlinks. We use <a> tag to create hyperlinks. Let's create two hyperlinks - Projects and About Me.

# Topic CSS and Flexbox

● Create a separate CSS style sheet for the portfolio website. 

● Use <div> blocks and flexbox to give a layout to the website. 

● Use css selectors to add style elements to the website.

the <style> tag to add styling to the document. Typically, designers/developers try to create content and styling in two different documents so that content and design are independent of each other. This creates consistent design for different pages of a website easily. It also allows for a change in the design template of a website easily without affecting the content page.

Developers need to create two different and separate styling pages to create these two different designs. We call such styling page “CSS (cascading style sheet).”

Creating a CSS is quite simple. 

1. Create an empty file in the same folder and call it style.css (or any other name. The extension .css is important) This is going to be our style sheet.
2. Copy the style content (inside style tags) to this style sheet. We are going to add more styling to our document in this and the next class. 
3. This stylesheet needs to be linked to the html file. We do it using the <link/> tag.

# Decimal Number System :

- Decimal means 10 Our number systems contains 10 different digits - 0 to 9 Also, each place value in a number is 10 raised to some power.
  - Example
    - 56 = 50 + 6 = 5 X 10^1 + 6 X 10^0=123 = 100 + 20 + 3= 1 X 10^3 + 2 X 10^1 + 3
      - Note: Any number raised to the power 0 is 1. 10^0 = 1
    - 80= 8 X 10^1+0 X 10^0
    - 25=20+5=2 X 10^1+5 X 10^0

- What if we use only 2 digits - 0 and 1. and every place value is 2 raised to some power? Our numbers will only contain 0 and 1.

  - What will 101 mean in such a number system?
    - 101 = 1 X 2^2 + 0 X 2^1 + 1 X 2^0=5
    - 1110= 1 X 2^3+1 X 2^2+ 1 X 2^1+ 0 X 2^0= 14
  - what this number system is called?
    - Binary Number System

- We have several number systems in computers based out of different number of digits used. One popular number system is called Hexadecimal number system. Hexadecimal number system is based on 16 digits !! Hex (6) + Dec (10) But we have symbols of numbers only for 10 digits - 0 to 9?

  - We use alphabets to represent numbers after 9.
    - A : 10
    -  B: 11
    -  C: 12
    -  D: 13
    -  E: 14 
    - F: 15
      - From 0 to F, we have 16 digits which can be used to represent hexadecimal number system!!
        - what would the number AD mean in hexadecimal number system?
          - AD= A X 16^1 + D X 16^0= 10 X 16^1 + 13 X 1=160+13=173
          - FE= F X 16^1+ E X 16^0= 15 X 16^1+ 14 X 16^0=240+14=254

- How would you write 255 in hexadecimal number system?

  - Divide 255 with 16
    - 255 / 16 => Quotient 15 (F) and remainder 15 (F)
      - So, the hexadecimal number is FF = 15 X 16 + 15
      - 128/16=> Quotient 8 & remainder 0
        - hexadecimal is 80

- rgb

  - r ------ 0, 255

  - b----- 0,255

  - 254 / 2 = 128

  - g----- 0,255

  - r =128 ,g =128, b=128

    

  - #808080

    - background color grey

    

