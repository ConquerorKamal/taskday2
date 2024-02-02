Window object and Document object : Differences between the both.


Before jumping into the differences ,let us clearly understand what they both are, its properties and its methods.


==> what is a window object and a document object ?  

--- A window object represents a window in browser. 
     An object of window is created automatically by the browser and it is supported by all browsers.
     All global Javascript objects, functions and variables automatically become the members of window object .
     global variables are properties and global functions are methods of the window object and the window object is the object of the browser,it is not the object of Javascript.
     
--- whereas a document object is an HTML document which is loaded into a web browser.
     On the other hand , the document object is the root node of its HTML document and the owner of all the other nodes(element nodes,text nodes,attribute nodes, and comment nodes).
     similar to the window object, the document object provides properties and methods to access all node objects within Javascript.


==> Its properties : 

----> Properties of Window Object.

  1)  closed : Returns a boolean true if a window is closed.
  2)  console : Returns the Console Object for the window.
  3)  screenLeft : Returns the horizontal coordinate of the window relative to the screen.
  4)  screenTop : Returns the vertical coordinate of the window relative to the screen.
  5)  screenX : Returns the horizontal coordinate of the window relative to the screen.
  6)  screenY : Returns the vertical coordinate of the window relative to the screen.
  7)  top : Returns the topmost browser window                                                                                                               
  8)  self : Returns the current window
  9)  frames : Returns all window objects running in the window.
 

---> Properties of Document Object. 

  1) bgColor : sets background color for the document.
  2) fgColor : sets foreground(text) color for the document.
  3) title : sets the title for the document.
  4) forms : It returns forms collection.
  5) links : It returns links collection.
  6) anchors : It returns anchors collection.


==> Its methods : 

----> Methods of Window object.

  1) alert() : displays the alert box containing message with ok button.
  2) confirm() : displays the confirm dialogue box containing message with ok and cancel button.
  3) prompt() : displays a dialog box to get input from the user.
  4) open() : opens the new window.
  5) close() : closes the current window.
  6) srtTimeout() : performs action after specified time like calling function,evaluating expressions etc.


---> Methods of Document Object. 

  1) document.write() : writes or displays a line of text on the document.
  2) document.writeIn() : same as write(),but adds a newline character after each statement.
  3) getElementById() :  get the element with the specified ID [document.getElementById("id name")].
  4) getElementByClassName() : get all elements with the specified class name [var X = document.getElementById ("class name")].
  5) getElementByName() : get all elements with the specified name.


 

===> Differences between the Window object and Document object. 

  1)  Window object : it represents the browser window in which you are seeing the content.
      Document object : It represents the document loaded inside the window or browser.

  2)  Window object : It is loaded before the document because window container document.
      Document object : It is loaded after the loading window because the window contains a document.

  3)  Window object : The window is the global element for all objects, functions, etc.
      Document object : It is the root element of the document object model.

  4)  Window object : It is an object of the browser.
      Document object : It is an object of window.

  5)  Window object : The properties related to it are stored in the window object.
      Document object : The properties related to it are stored in the document object.

  6)  Window object : We can access document object properties inside the window.
      Document object : We can not access windows objects properties inside the document.

  7)  Window object : Example: window.document.title will return the title of the document.
      Document object : Example: document.title will return the title of the document


      