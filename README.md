# HTML and CSS
## WEEK 1

# Unit 1: Introduction 
- The web or browser programming consists of three parts (HTML, CSS, and JavaScrript), this combination allows the web or browser programming to be resilient to changes in technology. HTML stands for HyperText Markup Language. It is used to structure our webpage. It uses the opening and closing tags (less-than, and greater-than symbols). So far we have introduced some different tags including; p for writing paragraphs, em, i, b, and strong; these tags are used to emphasize or stress some information. We have also covered the tags for making heading h, the heading is named from \<h1, h2, h3, h4, h5, and h6>. Each headline \<h1, h2, h3, h4, h5, and h6> has a distinct visual effect. The h1 element is the largest and most prominent, while h6 is the smallest and least attention-grabbing. We have also covered the HTML list. 

- There are three types of lists in HTML
  
1. ordered list \<ol>
   - The ordered list is used to represent data in a list for which the order of items has significance.
2. unordered list \<ul>
   - The unordered list is used to represent data in a list for which the order of items does not matter.
4. definition list \<dl>
   - The HTML description list is used to represent data in the name-value form.
   
- HTML Date and Time
   HTML elements can have extra information provided to them via HTML attributes. Here, we can provide the date or time in a manner that computers can comprehend by using the datetime attribute.
   For example, \<time datetime="2025-05-08"> May 8, 2025 \</time> is how we express it. The complete date does not need to be written out on the webpage. While time stamps on webpages sometimes utilize terms like 
  "five hours ago" or "ten days ago," the property actually uses the correct machine-readable version in the background. Highly uniform formats are preferred by machines, and the time element can also be used to 
  denote times. Numbers in the 24-hour clock format are preferred in the machine-readable version, and we have the option of include seconds and fractions of a second.
 -HTML Qoutes
  To attributes the qoute we use tag \<cite> element, and to add distinguish from the sourounding text, we can wrap the whole thing in a blockqoute tag element

# Unit 2: HTML fommating
- HTML formatting can be quite handly for structuring content. \<pre> is used for preformatted text, maintaining whitespaces and line break exactly as they are written in HTMLcode. \<br> is a linebreak tag, used 
 to create a line break un the content. There is no opening or closing tag on the \<br> element, making it a simple tag. It only specifies where a line break should occur; it has nothing inside it. \<Pre> and \<code> elements are often combined to display a code block with proper indentation.

- HTML Superscripts, Subscripts and Small Text
  The  Superscripts, Subscripts and Small Text are used to mark the certain bits of content as having different meaning that than the rest.
  The \<sub> tag is used for subscript, making text appear slightly below the normal line, while the \<sup> tag is used for superscript, positioning text slightly above the normal line. These tags are 
  employed to format text in a way that is either lower or higher than the regular text line, useful for applications such as chemical formulas or mathematical expressions. The \<small> tag in HTML is used to 
 define smaller text, reducing font size. It decreases the font size by one size (from medium to small, from x-large to large). It has a display property of inline. The \<small> tag also supports the Global 
 Attributes and Event Attributes in HTML. This tag is not deprecated, but it is possible to achieve better results or nearly the same effect with CSS.

# Unit 3: HTML Capabilities
  
- Inspector
  
    We can view the HTML and CSS of the webpage  with the Inspector tool, by right clicking the web page and select Inspect. We use it to see what CSS has been applied to each page element. Additionally, we may 
    preview updates to the HTML and CSS instantly, as they are mirrored in real time in the browser. When you reload the browser window, these modifications are reversed and become temporary. This is because HTML 
  alone only provides the editing functionality; the back-end developers need to create a system for capturing and saving the new content. The process of saving content varies across different websites and is 
  typically implemented in JavaScript. We can also use the HTML Inspector in the dev tools to debug mistakes.
 - HTML id Attribute:
     The id attribute is a unique identifier that is used to specify the document. It is used by CSS and JavaScript to perform a certain task for a unique element. In CSS, the id attribute is written using the # 
     symbol followed by id.

- HTML class Attribute:
  
     The class attribute is used to specify one or more class names for an HTML element. The class attribute can be used on any HTML element. The class name can be used by CSS and JavaScript to perform certain 
     tasks for elements with the specified class name. The class name in CSS stylesheet using “.” symbol
  
    These kinds of characteristics are common and give JavaScript browser APIs. we can use a short language code to define the language of the content with the "lang" the attribute. The direction of text flow is 
 clearly indicated by the "dir" element, which uses "LTR" for scripts that flow from left to right and "RTL" for scripts that flow from left to left. "lang" and "dir," two elements that are regarded as global 
 attributes, can be applied to any HTML element.

- Arial role
  
  ARIA Roles are similar to additional properties that we can apply to HTML components to enhance their meaning and facilitate browser comprehension. The intention is to avoid using ARIA Roles and instead rely on 
  appropriate HTML elements to communicate the intended meaning of the content. But aspirations and reality don't always coincide, so occasionally the code needs to be modified to accommodate compromises. If these 
  concessions make it difficult or impossible for persons with disabilities to utilize a website, then it becomes a serious issue. In fact, having a website that is inaccessible to those with impairments is illegal 
  in many places.

  The accessibility tree functions similarly to a companion document (DOM) tree that the browser constructs from the content of the page. The accessibility tree is essential for assistive devices like screen 
  readers, even though the DOM tree depicts the HTML structure. It enables them to give users an improved experience. It is evident from the accessibility tree that the content is treated as distinct text 
  containers. But this can lead to a bad experience—for example, hearing the letter "hello" repeated out one by one. We can make this better by using ARIA.

    The text that the screen reader will read is specified by an ARIA label that you add to the HTML. Put the ARIA label in this instance to "hello world." Furthermore, conceal. According to programmers, they 
  enhance 
    code readability by adding comments that explain its purpose. In HTML, comments are inserted by typing "\<!--" at the start and "\-->" at the end.According to programmers, they enhance code readability by adding 
   comments that explain its purpose. In HTML, comments are inserted by typing "\<!--" at the start and "\-->" at the end.

- Void element
   Are self-clossing tags including image, break element.

   One thing worth mentioning is the non-breaking space, which has a unique role. Usually, spaces in the text allow lines to break and words to remain intact. However, when there isn't enough space for a full 
 sentence, the browser searches for a suitable spot to wrap the text. It looks for any regular space where words have a gap between them. Instead of using a regular space, we can use a special kind of space called 
 a non-breaking space in HTML. This tells the browser not to break the line between two words. For instance, let's say we want to keep the first name "Lebron" and the last name "James" together in a sentence. We 
 can use the code "&nbsp;" to insert a non-breaking space between the two names, ensuring they stay on the same line. 

  Another use of non-breaking spaces is to create multiple spaces between words. Normally, if you add multiple spaces in your HTML, the browser will only recognize the first one. But non-breaking spaces are not 
 ignored by the browser, so if you include one, you can have two spaces between each sentence, for example. HTML character entities, including non-breaking spaces, provide a way to make sure the browser displays 
 the specific characters you want on your webpage.

# Unit 4: HTML Navigation and Linking

- HTML Link
  
   When we want to create a link, we use the A element, which stands for anchor. To do this, we need to add a href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href 
  stands for Hypertext Reference, a nerdy phrase from the past. Between the opening and closing A tags, we can place text or images, or both, to make them clickable. For example, we can turn the phrase "this is a 
  link" into an actual link that takes us to example.com when clicked. By default, the A element is inline and can be placed within a paragraph or any other text. In the example, there is a paragraph with a link 
  wrapped around specific words. However, links are not limited to just text; we can also wrap them around images or even more complex elements like teaser cards. This allows us to create a group of linked 
  elements.

  While the simple HTTPS://example.com has been commonly used, URLs can be much more versatile. When linking to another website or a specific page on the web, you can include the entire URL. It does not matter if 
 it has a trailing slash or not. These types of URLs are called absolute URLs because they point to a precise location on the web. In an absolute URL, the HTTP or HTTPS port must be included which stands for 
 Hypertext Transport Protocol. This protocol defines the rules for communication on the web and is crucial for linking. The difference between HTTP and HTTPS. The "S" in HTTPS stands for Secure. In the past, all 
 web addresses used to start with HTTP, but nowadays, experts recommend using HTTPS for enhanced security. When example.com is typed in a modern browser, it automatically adds the HTTPS:// part.


# Unit 5: HTML Working with Graphics and Images
- Image tag is a void element, meaning it does not require the classing tag, they are normally known as self-closing tag.
- Each image should include four essential attributes. Initially, there's the source attribute (SRC), indicating the image file to load. Following that is the alt attribute (ALT), supplying a textual depiction of the image. Lastly, the width and height attributes define the image's dimensions. Therefore, every image must incorporate these four attributes.

Referring to Figure 51: Working with an image element, the image's URL is inserted into the source attribute, as illustrated in the example, initiating the image loading process. However, the process isn't complete. Adding an ALT attribute is essential, serving as a substitute for the image in situations where it's not visible. For instance, individuals with visual impairments may utilize a screen reader that vocalizes the ALT text to them. t does not matter whether the height or the width is specified first. In HTML, the order of attributes within an element can be whatever you prefer.


# Unit 6: Working With Media
- Audio
 The audio element has an opening tag and a closing tag, which sets it apart from the image element. This increases its strength and flexibility and gives it a more modern look.
   We supply the audio file's URL using a source attribute, just like we do with the image element. You may be wondering why the audio element has an opening and closing tag. That's because, like the picture element, the source element can be used to provide numerous audio files. Furthermore, it is possible to provide fallback text within the audio element, which will only be displayed if the browser does not understand the audio element at all. This demonstrates the resilience of HTML, where a single set of code can cater to a wide variety of browsers and provide a suitable user experience. The audio element is an excellent tool for embedding audio files and a player on a webpage.

- Working With Video
   the video element has an opening and closing tag. To display a video, use the source attribute to specify the video file. And if the controls attribute is added, the browser will automatically create a video player. Sounds simple right? But there are a couple of issues that need to be addressed. The first problem has to do with video encoding. Modern browsers support MP3s by default, although OGG had some benefits but never really took off. Though it's not yet generally accessible, a new format that resembles the AV1 video file format might be on the future. Because of this, there isn't currently a second audio format that is advised. Nevertheless, as it was vital in the past and will probably be again soon, it is critical to comprehend the syntax for supporting numerous formats.


- Working With Captions and Subtitles
   To display these captions on the video, insert a track element within the video element. Similar to the source element, it is one of the options the browser uses to render the video player. On the track element, use the source attribute to specify the file, the kind attribute to indicate that it contains captions, and a label attribute to display the caption option as "English" in the player. Additionally, use the source lang attribute to indicate the language and add a default attribute to make this track the default choice when captions are enabled.  


# Unit 7: HTML Generic Element
- Different HTML components have as of now been secured for diverse purposes but what approximately those occurrences when an component is required that does not exist? Now and then we basically require a strategy to bunch components or highlight a express. Other times, we got to target a particular portion of the DOM with CSS or Javascript, indeed on the off chance that there's no genuine meaning behind it. In such cases, we have two trusty components at our transfer:
div and span. If you've got worked as a developer writing HTML, chances are you have got come over these components some time recently Before 2010, when HTML5 came along side its supportive semantic components, we depended intensely on divs for all sorts of purposes. Divs were utilized to make segments, sidebars, and everything in between. Individuals still tend to utilize divs and ranges too much in HTML, without much else. This course points the esteem of semantic HTML. Div is a block-level element, while span is an inline element. They essentially do nothing until CSS or Javascript is applied to them.

- Example: Span Element

\<!DOCTYPE html>

\<html>

\<body>

\<h1>The span element</h1>

\<p>My mother has \<span style="color:blue;font-weight:bold">blue\</span> eyes and my father has \<span style="color:darkolivegreen;font-weight:bold">dark green\</span> eyes.\</p>

\</body>

\</html>

- Example: Div Element
  
 \<!DOCTYPE html>
 
 \<html>
  
\<head>
  
\<style>

.myDiv {

  border: 5px outset red;
  
  background-color: lightblue; 
  
  text-align: center;
}


\</style>

\</head>

\<body>

\<h1>The div element\</h1>

\<div class="myDiv">
  \<h2>This is a heading in a div element\</h2>
  \<p>This is some text in a div element.\</p>
\</div>

\<p>This is some text outside the div element.\</p>

\</body>
\</html>

# Unit 8: HTML Integration

We've studied HTML and all the components, attributes, functions, and resources needed to mark up content on webpages and web applications. Although it is not the only explanation, HTML is crucial in defining these terms. The web cannot function without HTML files.

Once the HTML file is built, there are a few crucial parts that every web page needs. 

Firstly, the file should begin with a doctype statement, which indicates the era of this HTML file. In the past, there were different doctype declarations for older HTML versions. By including this one, we are saying, "Hey, this is a modern web page, so follow modern best practices and treat it accordingly." 
Next, we enclose everything else on the page within an HTML element, which means an element named HTML. It tells us that all the content within it is HTML. Place the opening HTML tag at the top and the closing HTML tag at the bottom. 
At the beginning, specify a few things about the web page. Declare the language being used and the content flow direction. This code is for a website using US-based English that reads from left to right. 

Inside the HTML element, there are two main parts where everything goes: the head and the body. Create them using the head and body elements. The head contains all the metadata that the browser needs to know but will not display on the page. The body, on the other hand, is for all the content and is composed of various elements already discussed in this course. The body is where most of the action happens. 

The doctype declaration, HTML head, and body elements are the essential building blocks of every web page.

The character set is not something you want your users to see, it is intended for the browser. To convey this, use the meta element. Ensure that meta elements are only placed inside the head as they provide metadata about the page. 
![image](https://github.com/216037150/Introduction-to-HTML-CSS/assets/52372746/e4a8cc6c-cf74-41c2-b5cd-f79d57d39914)

- Perpose of Meta data: To inform the browser that the layout has been adjasted to fit small screens, making it responsive website.
      2. It is use to assign a name the wabpage, when saved to the hme screen and to specify a tile image and background and color.

The link element is a crucial component used extensively within the head section. It serves to connect various assets that should load, such as CSS files, fonts, and favicons. To inform the browser about the type of asset, utilize the rel attribute.

Additionally, the href attribute is employed to specify the URL for the asset.

\<link rel ="tree" href="the treewabpage"> : The rel stands for relation, it shows the rel;ationship  between a tag and hyper text reference.

 Furthermore, you can also include a link to preload a font file. It is important to consider that the browser will load the files in the order they are listed. You are advised to place the items that need to load first at the top, while less crucial or delayed-use items can be positioned further down.

 The HTML head serves as a central hub for connecting and setting up various components, ensuring that all assets are loaded and sharing page information with other sites and platforms. In a way, it is like the headquarters for getting the page off to a good start.

 The structure of HTML inside the body

 Main - The main element is used once per webpage and tells the browser where the main content is located.
 Header- The header and footer elements mark the header and footer areas on the page. Do not confuse header with head though. Head is where the file's metadata lives and is not displayed to users. Header is used for site 
         headers, article headers, and headers within the content. A header is usually found at the top of most web pages and may include a logo, site name, and navigation.

footer - The footer signifies that there are extra things to convey, regardless of its position on the page.       

Article -  An article often starts with a title, subtitle, author's name, and publication date, which can also be considered a header. Many web pages end with a footer at the bottom, containing links, copyright 
            information, and additional details about the company. However, footers can also appear elsewhere. Some articles begin with metadata like hashtags or share buttons, which are suitable for a footer element. 
             The article element wraps around any type of content unit, whether it is a long written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content.


 
section -  The section element is used to mark sections of content. For example, in a long essay with subheadings, each segment can be wrapped in a section element. It is also useful for dividing different topic zones on 
         a website. Each section typically starts with its own headline.

Aside -  Lastly, the aside element is for content that is off to the side, like sidebar information or additional details that
          accompany an article but are not part of its main flow. Advertisements can also be marked as 
         an aside. Although the position on the page does not matter, the semantic meaning of these elements is crucial.
         The visual layout often conveys meaning, and these HTML elements help transfer that meaning from 
         the design to the content.       


# Unit 9: Working with Forms and Interactive Elements
- Form Fundamental
   Forms are crucial components of web development, facilitating tasks like logging in, making purchases, and more. Using semantic form elements in HTML is preferred over divs and spans for efficiency and compatibility 
  across devices. To create a simple newsletter signup form, start with the form element and add fields for name and email using input elements, along with corresponding label elements. Ensure functionality by adding a 
   button element for submission and specifying action and method attributes. Include "name" attributes in input fields to capture data. For accessibility, connect label and input elements using either the "for" 
 attribute 
   or by wrapping the input with the label. Test functionality by clicking on labels to verify input focus.

To enhance the form for newsletter sign-up, specify input types for name and email fields using the "type" attribute. Use "text" for the name field and "email" for the email field to prompt browser validation for email format. Make the email field required by adding the "required" attribute, ensuring users fill it before submission. Include a placeholder attribute to suggest content for the email field, which disappears when clicked, aiding user comprehension without manual erasure. For pre-populating fields, utilize the "value" attribute, but note that data from the placeholder won't be submitted. Value is beneficial for auto-completion scenarios like user details or shipping addresses. By leveraging HTML's capabilities, forms can be optimized for clarity and usability, ensuring seamless interaction for all users.

To enhance the form for newsletter sign-up, specify input types for the name and email fields using the "type" attribute. For the name field, indicate "type=text" to collect text, which is the default behavior if the type is omitted. For the email field, specify "type=email" to prompt browser validation for email format. Make the email field required by adding the "required" attribute, ensuring users fill it before submission. Include a placeholder attribute to suggest content for the email field, which disappears when clicked, aiding user comprehension without manual erasure.For pre-populating fields, utilize the "value" attribute, but note that data from the placeholder won't be submitted. Value is beneficial for auto-completion scenarios like user details or shipping addresses. By leveraging HTML's capabilities, forms can be optimized for clarity and usability, ensuring seamless interaction for all users.

![image](https://github.com/216037150/Introduction-to-HTML-CSS/assets/52372746/ae17881a-3122-4e80-b201-699380371668)



. Proper semantic HTML elements can be used in forms to style them, creating a custom look and feel. 


<form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required placeholder="Enter your name">

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required placeholder="Enter your email">

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required placeholder="Enter your password">

    <label for="search">Search:</label>
    <input type="search" id="search" name="search" placeholder="Search here">

    <label for="phone">Phone Number:</label>
    <input type="tel" id="phone" name="phone" placeholder="Enter your phone number">

    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" cols="50" placeholder="Enter your message"></textarea>

    <label for="birthdate">Birthdate:</label>
    <input type="date" id="birthdate" name="birthdate" required>

    <label for="color">Favorite Color:</label>
    <input type="color" id="color" name="color">

    <label for="file">Upload Image:</label>
    <input type="file" id="file" name="file" accept="image/*" multiple>
    <p>Yes, allow multiple files.</p>

    <button type="submit">Submit</button>
</form>

# Unit: 10 Organizing Tabular Information in HTML


** We start with a table element to mark the beginning of the table and close it at the end. This table has six rows, five rows about five different birds, and a top row which contains the header for each column. In the HTML we use the TR element to markup each row. Six pairs of TR opening and closing tags make six rows. Then put the content inside of each row. Start with the American goldfinch. 

Use the TD element to wrap a cell of content, American goldfinch, yellow, eats mostly seeds, and the image with an image element. You can put any HTML markup inside of these cells e.g. paragraphs, videos and headlines. There are four columns in this table, which means four cells of data in each row. Fill in all the rest of the birds. 

Include a bit of styling and CSS to make the table look more like a table of your choice instead of the default styling that a browser uses. But what about that header? Well, we put the content for the header in the first row, wrapping each one in a TH element instead of a TD element. TD stands for table data, while TH stands for table header. Bird, color, diet, photo**



![image](https://github.com/216037150/Introduction-to-HTML-CSS/assets/52372746/2de46e68-90c8-428d-8c69-ae0b1353490d)


\<table class="styled"> 

\<tr> 

\<th> Name \</th> 

\<th> Phone \</th>

\</tr>

\<tr> 

  \<td> Bill LaVarre \</td>
  
  \<td> 555-2987 \</td>
  
\</tr>

\<tr>

  \<td> Waymon LaVarre \</td>
  
  \<td> 555-4673 \</td>
  
\</tr>

\</table>


# Week 5: Understanding Types in CSS

Generally speaking, non-designers divide typefaces into two categories: 
1. Sans serif 
2.  serif. 

Small lines known as serifs are found at the extremities of the letters in serif fonts. In the past, printed products with lengthy text blocks were composed using serif typefaces. Letters were never precisely aligned when they were manually positioned on a printing press. The text was simpler to read because of the serifs that connected the letters. Sans serif typefaces, on the other hand, lack serifs and seem more contemporary. Sans serif fonts are primarily utilized on the web for longer text when computer typesetting because they have a clean, readable appearance. What typeface is therefore the standard web font? Well, it is usually Times New Roman, but not always. 


- Two types of sizing

There are two kinds of sizing in web design: absolute and relative. Points and pixels are examples of absolute sizes that don't change with screen size. Conversely, relative units like R-E-M (pronounced "rem") or percentages can change according on the size of the page. The font sizes that use relative units scale proportionately with the rest of the page when I zoom in. For greater flexibility, web designers so frequently favor the use of relative units.



# Introduction to JavaScript: 
##  WEEK 1: Basic Syntax


In computer science, data is anything that is meaningful to the computer. JavaScript provides eight different data types which are undefined, null, boolean, string, symbol, bigint, number, and object.

For example, computers distinguish between numbers, such as the number 12, and strings, such as "12", "dog", or "123 cats", which are collections of characters. Computers can perform mathematical operations on a number, but not on a string.

Variables allow computers to store and manipulate data in a dynamic fashion. They do this by using a "label" to point to the data rather than using the data itself. Any of the eight data types may be stored in a variable.

Variables are similar to the x and y variables you use in mathematics, which means they're a simple name to represent the data we want to refer to. Computer variables differ from mathematical variables in that they can store different values at different times.

We tell JavaScript to create or declare a variable by putting the keyword var in front of it, like so:
Storing a value in a variable is called variable initialization.
 
## WEEK 2:  Web Design

Most of the time, operators and functions automatically convert the values given to them to the right type.  For example, alert automatically converts any value to a string to show it. Mathematical operations convert values to numbers. There are also cases when we need to explicitly convert a value to the expected type.  
String Conversion

String conversion happens when we need the string form of a value.  

For example, alert(value) does it to show the value.  

We can also call the String(value) function to convert a value to a string: 

let value = true; 

alert(typeof value); // boolean  

value = String(value); // now value is a string "true"  

alert(typeof value); // string  


String conversion is mostly obvious. A false becomes "false", null becomes "null", etc. 
Numeric Conversion  

Numeric conversion happens in mathematical functions and expressions automatically.  

### JavaScript Number Format: Summary  

    JavaScript number format can be changed through various methods into multiple different values.  
    Most popular methods are Number(), parseInt(), and parseFloat().  
    If you want JavaScript to convert to an integer, you should use parseInt() method.  
    Each time JavaScript converts to integer, it returns a new value instead of rewriting the old one. 


### DOM

The Document Object Model and JavaScript Syntax

The Document Object Model is an Application Programming Interface (API) for HTML and XML documents. It does two things for web developers: 

        Provides a structural representation of the document
        Defines the way that that structure is to be accessed from script

This allows you to get at the web page as a structured group of nodes. Essentially, it connects web pages to scripts or programming languages.

The JavaScript syntax has to do with objects. To access an object, property, or method, its reference must include every object that contains it, separated by a dot. This is called the "dot syntax".

Let us define the terms introduced above:

    Object 

a JavaScript object is any scriptable HTML element, that is, any HTML element within a document that may be accessed through the JavaScript language. Although the browser window is not an HTML element, it too is a scriptable object.

Outside the context of a web page are core objects. These objects are not associated with HTML elements, but with the language itself. Then there are the homemade objects. Core objects and Home made objects are both associated with the JavaScript Object Model. 

The following are some of the JavaScript objects:

                window
                document
                form
                image
        Property
        Objects have properties, which you can think of as characteristics of an object. A JavaScript property has a similar relationship to the object it belongs to that an HTML tag attribute has to the tag that contains it. For example, the     JavaScript "value" property is to a text field object as the HTML "width" attribute is to a table tag.

There is one major exception: JavaScript properties can also be objects. In that case, the object-property relationship is more like the relationship an <option> tag has to the <select> tag that contains it. But in JavaScript, there is no difference in how you refer to a plain old property and a property that is also an object. 

A document, although contained by the window and therefore a property of the window object, is also considered an object. The same is true for a form and an image - they are properties of the document object but also objects themselves. The rule for the dual identities is this: a property is also an object if that property has its own properties and methods. It is best to think of objects which are also properties as objects - that way it is clear what you may and may not do with them.

        Method
        Methods are actions that can be applied directly to objects. Within a web page, methods cause a boring old HTML document to react to the end user. This results in a meaningful experience for the end user which would otherwise be completely one-sided.

Method Parameters

Syntactically speaking, methods are signified by parenthesis immediately following their name, e.g. "alert()". These parenthesis sometimes hold values called parameters, which are required by some methods. 

A parameter is simply information needed by a method in order to accomplish its task. For instance, the alert() method pops up an alert box. Without a parameter, the alert method will generate a dialog box (using Internet Explorer) alert() which is meaningless. But with a parameter, the alert method will generate a dialog box alert("Hello World") which communicates a message to the end user. 

Here are a Few JavaScript Methods:

        alert() causes an alert dialog box to appear over the page that launched it
        write() writes content to a page
        focus() causes the mouse cursor to be inserted into a form element

Notice the parenthesis following the above methods? That is how you distinguish a method from a property or object

NB: Please note that these definitions are given in the context of Web programming. They may also be loosely be used to define the terms in Java as well.
Core APIs in the DOM

document and window objects are the objects whose interfaces you generally use most often in DOM programming. In simple terms, the window object represents something like the browser, and the document object is the root of the document itself. Element inherits from the generic Node interface, and together these two interfaces provide many of the methods and properties you use on individual elements. 

The following is a brief list of common APIs in web and XML page scripting using the DOM.

        document.getElementById(id)
        document.getElementsByTagName(name)
        document.createElement(name)
        parentNode.appendChild(node)
        element.innerHTML
        element.style.left
        element.setAttribute
        element.getAttribute
        element.addEventListener
        window._content
        window.onload
        window.dump()
        window.scrollTo()

    Let us look at the window object for example. Since most of the objects belonging to a web page are contained by the document object, 
    path references almost always include the document object. But since the document is contained by the window object, why is the window reference left off in     JavaScript code? 


  The window reference is the only exception to the complete object containment hierarchy reference rule. Since the window object is 
    at the top of the object hierarchy, it is assumed. In the case where a method is shared by the window object and another object,
      omitting it asserts the assumption that it is beinginvoked on the window object. 

  Most of the time, the containment structure is obvious. 

Now let's  take a look at the DOM structure

## Function:

  -  A function is a subprogram designed to perform a particular task. A function will only execute if and only when 
      it has been called (invoking a function). Values can be passed into functions and used within that function as well. 
      All functions have a return value, otherwise they become undefined (value is unknown). Most importantly, you must 
    know that a function is an object (an HTML element, with properties and methods.

# The Focus Event (onfocus)

  The focus event occurs when the user gives focus to an element on a web page. You can handle the focus event with the onfocus event handler. 
  The following example will highlight the background of text input in yellow color when it receives the focus.

  ![image](https://github.com/216037150/Introduction-to-HTML-CSS/assets/52372746/63d1603f-7460-40c8-946d-e893ef791655)

# Unit 4: HTML Navigation and Linking

- HTML Link
  
   When we want to create a link, we use the A element, which stands for anchor. To do this, we need to add a href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href 
  stands for Hypertext Reference, a nerdy phrase from the past. Between the opening and closing A tags, we can place text or images, or both, to make them clickable. For example, we can turn the phrase "this is a 
  link" into an actual link that takes us to example.com when clicked. By default, the A element is inline and can be placed within a paragraph or any other text. In the example, there is a paragraph with a link 
  wrapped around specific words. However, links are not limited to just text; we can also wrap them around images or even more complex elements like teaser cards. This allows us to create a group of linked 
  elements


# HTML and CSS
## WEEK 
