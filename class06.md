# Class06

# Objects 

### Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. 

- Functions become known as methods.

- Variables become known as properties.

## We can create object using literal notation like this:

### `var hote l = { name: 'Quay', rooms: 40, booked : 25, checkAvailability: function() { return this.rooms - this.booked; } };`

# DOM (Document Object Model)

### specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 

## DOM Tree

### As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes. Each node is an object with methods and properties.

### Accessing and updating the DOM tree involves two steps:


1- Locate the node that represents the element you want to work with. 

2- Use its text content, child elements, and attributes. 

## Accessing Elements

### DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes. 

### METHODS THAT RETURN A SINGLE ELEMENT NODE: 

1- `getElementByld('id')`

2- `querySel ector('css selector')`

3- `getElementsByClassName('class')`

4- `getElementsByTagName('tagName')`

5- `querySelectorAll ('css selector')`

## Traversing the DOM 

### When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM. 

## WHITESPACE NODES 

### Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements. 










