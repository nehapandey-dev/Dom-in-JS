# Dom Manipulation Assignment 💻
![Cover](./thumbnail.png)

There are 20 Dom Manipulation Assignments given below along with my solution.

1. Webiste Name: [Dev To](https://dev.to/)

### Topics

    - Query Selctory, Inner HTML

### Tasks

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion

## My Output

### Target the Top description div

let mainDiv = document.querySelector(".authentication-feed__title").innerHTML
console.log(mainDiv)

### change the DEV Community
let newDiv = document.querySelector(".authentication-feed__title").innerHTML='INeuron'
console.log(newDiv)

### change description
let newDec = document.querySelector(".authentication-feed__description").innerHTML='I write Code'
console.log(newDec)

![My Output](./My%20output-images/output1.png)


2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

### Fetch all the product name and store in an array

### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

## My Output

let productsName = [];

### Fetch all the product name

let getArr = document.querySelectorAll(".as-imagegrid-item-title");

### store in an array

getArr.forEach(function (item){productsName.push(item.innerText);
});

console.log(productsName.replace("\nSupport", ""))

![My Output](./My%20output-images/output2.png)

3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)

### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child

### Tasks

     Add another FAQ 'My New FAQ' to the list

### My Output

var nav = document.getElementsByClassName("accordion-homepage");

var addSection = document.createElement("New Section")

addSection.className = "parent"

var heading = document.createElement("h3")

### Add another FAQ 'My New FAQ'

heading.textContent = "My New FAQ"
addSection.appendChild(heading)

nav.appendChild(addSection)


![My Output](./My%20output-images/Output3.png)

4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText

### Tasks

      Change the contact number

### My Output

document.querySelector(".service-number").innerText 

### Change the contact number

document.querySelector(".service-number").innerText = ("9643634963")

![My Output](./My%20output-images/Output4.png)

5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Tasks

     Target the main div of card and change the Button text to Check out

### My Output
### Target the main div of card and
document.querySelector(".mytabs").innerText

### change the Button text to Check out
document.querySelector(".diwali-deals-product-sale-btn").innerText = "Check now"

![My Output](./My%20output-images/Output5.png)

6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Tasks

     Target the search box and on hover change thebackground color to red.

### My Output

### Target the search box
var search = document.querySelector(".searchinput___19uW0")

### change thebackground color to red

search.addEventListener("mouseover", red);

function red(){
document.body.style.backgroundColor = "red";
console.log(document.body.style.backgroundColor);
};

![My Output](./My%20output-images/Output6.png)

7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

### My Output

let value = document.querySelector("#top-nav-search-input").value = "css selector";

let submit = document.querySelector("#top-nav-search-form").submit();

console.log(submit);

![My Output](./My%20output-images/Output7.png)

8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Tasks

     Remove alternate languages from the home page languages listed

###  My solution for assignment 8 is pending.


9. Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.

### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.

### My Output

#### changed the text color
document.querySelector(".
display-heading-1").style.color = "brown"

#### Changed the font family of the text
document.querySelector(".display-heading-1").style.fontFamily = "monospace"

#### added background color
document.querySelector(".display-heading-1").style.backgroundColor = "#242B2E"

![My Output](./My%20output-images/Output9.png)

10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Tasks

    Target the button and change background colour on mouseover

### My Output

### Target the button 
search = document.querySelector("a.btn-cta-big.btn-block.signup-btn.btn-cta.btn.btn-default").innerText

### change background colour on mouseover
search.addEventListener("mouseover", red);

function red(){
document.body.style.backgroundColor = "red";
console.log(document.body.style.backgroundColor);
};

![My Output](./My%20output-images/Output10.png)

11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Tasks

    change the realme logo to ineuron logo

### My Output

#### change the realme logo to ineuron logo

document.querySelector("span.icon.icon-logo.in").style.backgroundImage = "url('https://ineuron.ai/images/ineuron-logo.png')"

![My Output](./My%20output-images/Output11.png)

12. Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Tasks

     change the background colour of the button to blue.

## My Output

document.querySelector(".d-xl-flex .btn-sm").innerText

#### Changed the background colour of the button to blue.
document.querySelector(".d-xl-flex .btn-sm").style.backgroundColor = "green"

![My Output](./My%20output-images/Output12.png)

13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

## My Output

document.querySelector(".fl-heading").innerHTML = "JSBOOTCAMP"

![My Output](./My%20output-images/Output13.png)


14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Tasks

       change the fontsize of “Hot Deals” to 80px

## My Output

document.querySelector(".HotDealsAll__Heading__2fIbe").innerHTML

#### changed the fontsize of “Hot Deals” to 80px
document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize = "80px"

![My Output](./My%20output-images/Output14.png)

15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign


### Tasks

       Convert the text “G15 Gaming Laptop” from left to right

## My Output

document.querySelector("#d560823win9b .ps-title").style.textAlign = "right"

![My Output](./My%20output-images/Output15.png)

16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

## My OutPut

document.querySelector(".section-title_title__VEDfK").innerHTML

#### change the heading “Start with the developer” to “Start with Scratch”
document.querySelector(".section-title_title__VEDfK").innerHTML = "Start with Scratch"

![My Output](./My%20output-images/Output16.png)

17. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Tasks

     change the button text To current Date.

## My Output

var date = new Date();

document.querySelector(".btn-container .btn.btn-large.btn-block.buy.buy-button.retailer_btn-align").innerHTML = date;

![My Output](./My%20output-images/Output17.png)

18. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Tasks

    change the background colour blue to orange

## My OutPut

let newBgc = document.querySelector(".p-footer").style.backgroundColor = "orange";
console.log(newBgc);

![Output](./My%20output-images/Output18.png)

19. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src


### Tasks

    extract the canon logo


## My Output

document.querySelector(".logo").src

![MyOutput](./My%20output-images/Output19.png)

20. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Tasks

      Change the description colour black to orange

## My Output

document.querySelector("h3.desc").style.color = "orange"

![My Output](./My%20output-images/Output20.png)
