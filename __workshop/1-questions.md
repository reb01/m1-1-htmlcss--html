# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`// should end with </span></div>

b) [false] //should end with </ul> or start with <ol>

```html
<ul>
<li>one</li>
</ol>
```

c) [false] [ ] <ul></ul><img/><ol><li>one</li></ol> //  no alt in the img tag.

## Q2 - What is a screenreader and why should we care about them?

A screen reader is a software application that enables people with severe visual impairments to use a computer. Screen readers work closely with the computer’s Operating System (OS) to provide information about icons, menus, dialogue boxes, files and folders. The device provides access to the entire OS that it works with, including many common applications.
The two ways the  screen reader relays information to the user is through Speech and Braille. (Source https://www.nomensa.com/blog/2005/what-screen-reader)

Web Accessibility focuses on how a disabled person interacts with your website. 19.3% percent of people in the United States have some type of disability as of 2019. This is a huge percentage of people. (Source https://medium.com/@adhithiravi/web-accessibility-and-why-you-should-care-c8b436412ebd)

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<img src="photo" alt="text if image doesnt work"

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<a href="url">link text</a> and

Unordered list 

<ul>
    <li>Chocolate Cake</li>
    <li>Black Forest Cake</li>
    <li>Pineapple Cake</li>
</ul>

— Used to create a list of related items, in no particular order.

OR

Ordered list <ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>  

— Used to create a list of related items, in a specific order (using numbers).

c) You want to sell designer hats. You need to receive orders from the user.

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No it id not valid HTML5 according to the HTML5 Spec Document from W3C

## Q5 - What is the most generic tag you can use?

<div>	The HTML Content Division element (<div>) is the generic container for flow content. It has no effect on the content or layout until styled using CSS.

## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` represents an item in a list

e) `tr` <tr> tag defines a row in an HTML table

f) `th` <th> tag defines a header cell in an HTML table

g) `td` <td> tag defines a standard data cell in an HTML table

## Q7 - Usually, `td` elements are children of what kind of elements?

<tr> elements

## Q8 - What is the difference between td and th?

The <td> tag is used for showing the table data while the <th> element defines a header cell in a table

## Q9 - Which tag makes the text appear bigger: h1 or h3?

<h1> shows the largest text of all the Headings 1 - 6

## Q10 - In which situation can you use self closing tags?

Self-closing tags on non-void elements like <p/>, <div/> will not work at all (in HTML5). The trailing slash will be ignored, and these will be treated as opening tags. This is likely to lead to nesting problems.

This is true regardless of whether there is whitespace in front of the slash: <p /> and <div /> also won't work for the same reason.

Self-closing tags on void elements like <br/> or <img src="" alt=""/> will work, but only because the trailing slash is ignored, and in this case that happens to result in the correct behaviour.

it is possible to represent an HTML5 document as XML, and this is sometimes dubbed "XHTML 5.0". In this case the rules of XML apply and self-closing tags will always be handled. It would always need to be served with an XML mime type.


## Q11 - What is autofilling and why is it important?

 Autofilling allows the filling of form fields automatically on page load without any user interaction. This is  great feature for 
 ease of use but it is important to mention that it allows greater access to hackers and scammers if they are able to access your browser.

## Q12 - Which attributes are always present in an img element?

The <img> tag has two required attributes: src - Specifies the path to the image. alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed.

## Q13 - Which attribute is always present for an anchor tag?
The HTML <a> element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address. Content within each <a> should indicate the link's destination.