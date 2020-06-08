# JS Object Literals; The DOM

[Back to Home](https://rizo85.github.io/reading-notes/)

### JavaScript

##### Objects

Duckett’s JS book talks about objects on pages 100-105; Objects are virtual representations of every day physical objects, their attributes, and their behaviors.

Literal notation is the way that objects are defined: they consist of the name of the object declared, and the key-value paring making up the object. This is all defined within the culry brackets of the object declaration. 
An object once created and populated with attributes can let us use the **dot notation** to access and even update them in our created object. 
Object.property = “newPropertyValue”; Similar to **Java** and other programing languages we can use constructors to create our objects and so we can use the keyword “new” to construct an object and later on give it values.

##### DOM

The dom is outside of the JS/HTML/CSS file structure we are used to building our **aboutMe.html** page. This is because it is a tree with nodes created by the browser to model a page. 
This makes it usefull in that anything inside of this model can be used and manipulated by using the **Document Object Model.**
My favorite way to understand this is to think of the HTML doctype declaration on our html; this is the document we are targeting using the DOM, so whenever we have a **document.** operation, I already know its targeting something on the HTML.
What gets targeted, and how it gets targeted has to do with what I need to select and my methods available. If I use the **elementById**, or specify a tag. This all lets me use JavaScript to continue on down and select the attributes on the different “nodes” of my DOM.

In a DOM tree the first node is the **Document Node**

Element nodes are the structural elements of our page from head, body, html, and most important tags that define our page.

Attribute nodes are not children of, but contained within the element nodes. 

Text nodes are just the text defined in their own nodes. If there is a child node, its never a text node but an element node child element to include additional text in a paragraph but inside a span element.

DOM Tree nodes from Jon Duckett book: 
![alt text](https://www-archive.mozilla.org/docs/dom/technote/whitespace/whitespace_tree.png )

### Reading: UNDERSTANDING THE PROBLEM DOMAIN 
#####by John Sonmez

Reading this made me realize that when i see a domain i have to fix, i immediately get transfixed by the lack of context i might feel not knowing what was trying to be achieved by the person there before me.  

Sonmez makes the argument that the hardest part is just understanding the problem domain like a puzzle without the image to work upon. If i understand that and put it in to practice, i would imagine it would be like: "Well, maybe i don't know what this is supposed to be, but i can clean up the tags, organize the styling, put everything where its supposed to be..." and by slowly applying the most basic structural order i'm already improving the domain.

A lot of it is just simple efforts built upon, but in order to get a domain that's not mine, but some client, then it becomes an exercise in listening to them and building based on their needs, and focus on smaller goals rather than the outdated waterfall software development life-cycle. 

[Back to Home](https://rizo85.github.io/reading-notes/)
