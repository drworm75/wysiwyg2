
![Title Banner](https://raw.githubusercontent.com/drworm75/wysiwyg2/master/images/wysiwyg2-readme%20.png) 
 
### Specifications:  
 
* Create an array of objects that represents famous people. 
 
* Create a text input in your DOM. 
 
* Create a container, block element in your DOM. 
 
* Create a DOM element for each of the objects inside the container.  
 
* For every even numbered element, have a light yellow background. 
 
* For every odd numbered element, have a light blue background. 
 
* When you click on one of the person elements, a dotted border should appear around it. 
 
* When you click on one of the person elements, the text input should immediately gain focus so that you can start typing. 
 
* When there is a highlighted person element, and you begin typing in the input box, the person's biography should be immediately bound to what you are typing, letter by letter. 
 
* When you press the enter/return key when typing in the input field, then the content of the input field should immediately be blank. 
 
* Update with Jquery 
 
### Final Result: 
> Click on a card, and the input field becomes focused.  Hit the enter key, and the field becomes blank, and the card is deselected.  If a selected card is clicked again, it becomes deselected.   
 
 
![Page Screenshot](https://raw.githubusercontent.com/drworm75/wysiwyg2/master/images/wysiwyg2-ss.png) 
 
### Takehome Lesson: 
 
> Navigating in Jquery for the first time was a little more difficult then the JavaScript that I was familar with. The first breakthough was finding the `.each()` method to loop though the array of objects, then start pulling the correct value for each key 
 
> Building the `<person>` element was different.  When the element was appended to the parent, it build the entire element.  I was able to use `nth-of-type` to insert the elements with information into each `<person>` element.  
 
### How to run (Node must be installed on your machine): 
``` 
git clone https://github.com/drworm75/wysiwyg2.git
cd wysiwyg2.git 
npm install http-server -g 
http-server -p 8080 
``` 
 
This will show in your browser at: 
`http://localhost:8080` 
 
### Contributors: 
[Dwayne Pate](https://github.com/drworm75)
 