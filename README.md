# college-CAS
Improving the CAS system of MGM

BASICS OF HTML
1) Structure of HTML
<!DOCTYPE html>
   <html>
    <head>
        <meta charset="utf-8">
        <title>MGM LOGIN</title>
    </head>
    
    <body>
        <p>Welcome to MGM NANDED!</p>
    </body>
    
</html>

2) Headings
 - from h1 to h6
 - There is a default line break above and below the heading tags.
<h1>Heading 1</h1>
<h6>Heading 6</h6>

3) Paragraphs
 - There is a default line break above and below the heading tags.

4) links
  - <a href="www.engineersplot.blogspot.in"></a> 
  - <a href="#id"></a> - to go to a particular section in the page.
  - <a href="/README.md"></a> - to go to a particular page from another page.

5) images
<img src="Enter file name" width="100px" height="120px" alt="Picture">

We write alt, so that in case the browser doesnot show the image, it will atleast display the name of the image.

6) Inline and Block Elements

Inline - If there is no default break statements. eg: links, images
Block - If there are break line statements. Eg: <p></p>, <h1></h1>

7) iframes - embed html elements into another html pages.

syntax: 
  -  <iframe scr="Page" width="" height="" frameborder="1"></iframe>
  - <iframe name="myiframe"></iframe>
  <p><a href="engineersplot.blogspot.com" target="myframe">link</a></p>
  
  - We can also embed a youtube video.
  
8) Unordered list:
  <ul> - unordered list
      <li> - list item
          This is a list of bullet points.
      </li>
  </ul>
  
9) Ordered list
  - List of numbers
  
  <ol type="1">
      <li>
          Hello
      </li>
  </ol>
  
10) Description Lists
<dt>HTML</dt> - description item
<dd> - Hypertext Markup Language</dd> - description

11) Tables
<table>
    <tr><th>Heading1</th><th>Heading2</th></tr>
    <tr><td>Data1</td><td>Data2</td></tr>
    <tr><td>Data3</td><td>Data4</td></tr>
</table>

12) Entities

There are few words reserved for by the HTML editor which cannot be used... 
For eg:
 When we want to use space, use write: &nbsp; to get the space. 
 
Similarily, to get some other entitiles, go to Google and type "HTML Entities", and go to w3.org website/






