#Assignments Questions

* What is React?
Ans : React is Javascript library which help us to build reusable component that use in make UIs.
***

* Who made React?
Ans : Facebook make React .
***

* What is Babel?
Ans :Babel is a translator that translate JSX into plane Old javascript language .

***

* How does Babel convert html code in React into valid code?
Ans Follow this steps :
    Step 1: Add Babel package : "https://unpkg.com/@babel/standalone/babel.min.js"
    Step 2 : Add the script type as <mark> text/babel

    Step 3 : Write Html code in script .

***

* What is ReactDOM used for? Write an example?
Ans : It defines a location that where are React codes will be attached .It is like a bridge between Creating React elements and converting the react element into ReactDOM and displayed it in browser.

eg: 
```
ReactDOM.createRoot('document.getElmentbyID('root')');
```
In this example ReactDOM create root node where our react code will be live and furder converted in React Dom and displayed in browser by help of ReactDOM's render method.
***

*  How do you add react to a web application?
Ans : Adding react to a web application required :
 1 . First Creating a React element by React.createElement .
 2 . Second It required a location that where it should be attached .
 3 . third  It must be converted into ReactDom by ReactDOM' render method and then it add to a web application.

 ***
* What is React.createElement?
Ans : It is a method of creating React element in object form .

***

* What are the three properties that createElement accept?
Ans : 
1. Type of element (eg:"div")
2. Element attrubutes and properties(eg:"id")
3. Children "text"(eg:children:"hello react")

***

* What is the meaning of render and root?
Ans : 
1.Root is a main div or element where our whole DOM tree will be start. It is like a root of a tree which holds all the branches of tree .
2.Render is a method that take react element and convert it into reactDOM and displayed it over browser.

    
    
