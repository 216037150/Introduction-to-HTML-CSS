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
    preview updates to the HTML and CSS instantly, as they are mirrored in real time in the browser. When you reload the browser window, these modifications are reversed and become temporary. This is because HTML alone only provides the editing functionality; the back-end developers need to create a system for capturing and saving the new content. The process of saving content varies across different websites and is typically implemented in JavaScript. We can also use the HTML Inspector in the dev tools to debug mistakes.
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
  
ARIA Roles are similar to additional properties that we can apply to HTML components to enhance their meaning and facilitate browser comprehension. The intention is to avoid using ARIA Roles and instead rely on appropriate HTML elements to communicate the intended meaning of the content. But aspirations and reality don't always coincide, so occasionally the code needs to be modified to accommodate compromises. If these concessions make it difficult or impossible for persons with disabilities to utilize a website, then it becomes a serious issue. In fact, having a website that is inaccessible to those with impairments is illegal in many places.

The accessibility tree functions similarly to a companion document (DOM) tree that the browser constructs from the content of the page. The accessibility tree is essential for assistive devices like screen readers, even though the DOM tree depicts the HTML structure. It enables them to give users an improved experience. It is evident from the accessibility tree that the content is treated as distinct text containers. But this can lead to a bad experience—for example, hearing the letter "hello" repeated out one by one. We can make this better by using ARIA.

The text that the screen reader will read is specified by an ARIA label that you add to the HTML. Put the ARIA label in this instance to "hello world." Furthermore, conceal. According to programmers, they enhance code readability by adding comments that explain its purpose. In HTML, comments are inserted by typing "\<!--" at the start and "\-->" at the end.According to programmers, they enhance code readability by adding comments that explain its purpose. In HTML, comments are inserted by typing "\<!--" at the start and "\-->" at the end.

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







  


