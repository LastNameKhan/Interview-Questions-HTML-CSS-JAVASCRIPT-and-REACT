# HTML
Q.Differnce Between HTML and HTML5
Ans:- HTML              |             HTML5
1. Html works with all old browsers.
Html5 works with all new browsers like firefox,Mozilla,Chrome,Safari etc...
2. Does not allow Javascript to run in browser.
It allows Javascript to run in bacjground.This is possible due to JS Web worker API in HTML5.
3. Older version of HTML are less mobile-friendly.
HTML5 language is more mobile-friendly.
4. Character encoding is long and complicated.
Character encoding is simple and easy.
5. Elements like nav,header were not present.
New elements for web structure like nav,header,footer etc...
6. It didn't support audio and video without the use of flash player support.
It supports audio and video controls with the use of <audio> and <video> tags.

Q.Difference between Inline and Block Line elements in HTML?
Ans:- Inline elements are those which only occupy the space bounded by the tags defining the elements, instead of breaking the flow of the element.
For eg:- <span>Hello World!</span>

Browser typically display the block-level elemet with a newline both before and after the element. You can visusalize them as a stack of boxes.
For eg:- <div>This is me Block level element</div>

.highlight {
    background-color: #ee3
}

Inline:
<div>The following span in an <span class="highlight">Inline element</span>; its background has been colored to display both the beginning and end of the inline element's influence. </div>

The div is block level element contains some text.
Span element is an inline element.

Output: The following span is an INLINE ELEMENT its background color has been colored to display both the beginning and end of the inline element's influence.

Block-Level:
Now let's change that <span> into a block-level element, such as <p>:
<div>The following paragraph is a <p class="highlight">Block-level element</p> its background color has been colored to display both the beginning and end of the Block-level element's influence.</div>

Output:
The following paragraph is a 
Block-level Element;
its background has been colored to display both the beginning ans end of the block-level element's influence.

You can change the elements visual presentation of an element using CSS display property to inline or block.

Q. Difference between Physical tag and Logical Tag?
Ans:- Physical tags are used to indicate that how specific characters are to be formatted or indicated using HTML tags.
Physical tags are used to highlight importanbt sentences.
Here are some examples of Physical Tags:
<sup> Superscript is usually used for showing elemetns above base-line.
<sub> The subscript is used for alternate baseline.
<i> An Italic tag is used to define a text with a special meaning.
<b> Bold increases the importance of the text because bold tag convert the text into bold size.
<u> It is used to underline the text.

Logical Tag:
Logical tags are used to tell browser what kind of text is written inside the tags.Logical tags are also known as structural tags because they specify the structure of the document.

Eg:- 
<strong> Defines the sample output text from a computer program.
<var> Defines the cariable in a mathermatical equation or in the comupter program.

Q. What is the differnce between a semantic and non semnatic elements?
Ans:- A semantic element clearly describes its meaning to both browser and the developer.
eg:- <form>,<table>,<article>

Non semantic elements they don't have any meaning.They don't tell anything about the content they contain.
eg:- <div>,<span>

Q.What is Anchor tag?
Ans:- The anchor tag in HTML is used to create a hyperlink on the webpage.

Q.What is differnce between bold and strong tag?
Ans:- The strong tag is semantic tag which also highlights the importance of that word or section of text.if you want to highlighta text section as important in terms of content, you should always use strong.

Where in case of writing the bold text you should use <bold>

Q. What are the different browsers that support HTML5?
Ans:- HTML5 is compatible with all popular brwoser(Chrome,FireFox,Safari,IE9 and Opera) and with the DOCTYPE it is even possible to have few HTML features in older versions of internet Explorer too.

Q. Can we change inline elements into block-level elements?
Ans:- Yes we can change an inline element to block level element using CSS display property.

Q. Explain the structure of the HTML webpage?
Ans:- <!DOCTYPE html> - This tag specifies the language you will write on the page.In this case, the language is HTML 5.
<html> - This tag signals that from here on we are going to write in HTML code.
<head> - This is where all the metadata for the page goes - stuff mostly meant for search engines and other computer programs.
<body> - This is where content of the page goes.

This is how your average HTML page is structured visually

<html>
<head>
<tilte></title>
</head>
<body>
<h1></h1>
<p></p>
</body>
</html>

Q. Why Meta tags are used in HTML?
Ans:- The <meta> tag defines metadata about an HTML document. Metadata is information about the data, <meta> tags always go inside the <head> element, and are typically used to specify characters set, page description, keywords, author of the document, and viewport settings.

Q. Explain list elements in HTML?
Ans:- The <li> element is used to represent an item in a list. It must be contained in a parent element: an ordered list (<ol>), an unordered list(<ul>), or a menu (<menu>). In menus and unordered lists, list items are ususally displayed using bullet points.

Q. Define iframe in HTML?
Ans:- The HTML <iframe> tag specifies an inline frame.
An inline frame is used to embed another document within the current HTML document.
<iframe src="url" title="description"></iframe>

Q. Define forms in HTML?
Ans:- An HTML form is used to collect user input. The user input is most often sent to a server for processing.

Q. How can we create a hyperlink in HTML?
Ans:- Use the <a> element to define a link.
Use the href attribute to define the link address.
Use the target attribute to define where to open the linked document.
Use the <img> element (inside <a> ) to use an image as a link.

Q. Differentiate between HTML and XHTML?
Ans:- HTML is the standard markup language for creating web pages, while XHTML is a stricter and more standardized version of HTML. Both HTML and XHTML include a wide range of features, such as support for multimedia, styling, and scripting.

Q. What is the SVG element?
Ans:- The svg element is a container that defines a new coordinate system and viewport. It is used as the outermost element of SVG documents, but it can also be used to embed an SVG fragment inside an SVG or HTML document. Note: The xmlns attribute is only required on the outermost svg element of SVG documents.

Q. Explain about Canvas?
Ans:- A canvas is a rectangular area on an HTML page. By default, a canvas has no border and no content. Note: Always specify an id attribute (to be referred to in a script), and a width and height attribute to define the size of the canvas. To add a border, use the style attribute.

# CSS

Q. All css Position?
Ans:- Absolute - An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).
However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.
Note: Absolute positioned elements are removed from the normal flow, and can overlap elements.

Realtive - An element with position: relative; is positioned relative to its normal position.
Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

Fixed - An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.
A fixed element does not leave a gap in the page where it would normally have been located.

Sticky - An element with position: sticky; is positioned based on the user's scroll position.
A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).

Static - An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:

Q. Difference between all positions in CSS?  
Ans:-

Q. Explain flexbox?
Ans:- 

Q. Explain CSS grid?
Ans:-

Q. Difference between CSS grid and Flexbox?
Ans:-

Q. What is box Model in CSS?
Ans:- Content:  Actual Content of the box where the text or image is placed.
Padding: Area surrounding the content (Space between the border and content). Border: Area surrounding the padding. Area surrounding the border.


Q. Which CSS properties are a part of boxModel?
Ans:-

Q. What are the advantages of using CSS?
Ans:- 

Q. What are the limitations of CSS?
Ans:-

Q. How to include CSS in the webpage?
Ans:-

Q. What are the different types of Selectors in CSS?
Ans:-

Q. What is VH/VW (viewport height/ viewport width) in CSS?
Ans:-

Q. What is the difference between inline, inline-block, and block?
Ans:-

Q. What are Pseudo elements and Pseudo classes?
Ans:-

Q. How do you specify units in the CSS?
Ans:-

Q. What are the different ways to do it?
Ans:-

Q. What are the differences between adaptive design and responsive design?
Ans:-

Q. How is border-box different from content-box?
Ans:-

Q. How is opacity specified in CSS3?
Ans:-

Q. Why should we use float property in CSS?
Ans:-

Q. What is a z-index?
Ans:- Z-index doesn't work only in static position.

Q. What are the properties of flexbox?
Ans:-

Q. What is cascading in CSS?
Ans:-

Q. Different Box Sizing Property?
Ans:- 

Q. What is the grid system?
Ans:-

# Javascript
Q. Javascript explain and how Javascript Engine works?
Ans:- JavaScript is a scripting or programming language that allows you to implement complex features on web pages.
Javascript engine works on the javascript source code and puts it and then executes the compilation to binary instructions that are easily understandable by the CPU.

Q. Explain all Javascript array methods?
Ans:- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array

Q. All Object Methods in Javascript?
Ans:- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object

Q. All String Methods in Javascript?
Ans:-https://www.w3schools.com/js/js_string_methods.asp

Q. What is hoisting with example and why cant we host let?
Ans:- Javascript Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables or classes to the top of their scope, prior to execution of the code.

Hoisting is often considered a feature of var declarations as well, although in a differnet way. Hoisting can be defined as:-

1. Being able to use a variable's value in its scope before the line it is declared.
2. Being able to reference a variable in its scope before the line it is declared, without throwing a ReferenceError, bt the value is always undefined.
3. The declaration of hte varibale causes behaviour changes in its scope before the line in which it is declared.

Let,const and class are non-hoisted, because of the temperal dead zone strictly forbids any use of the variable before its declaration.

const x = 1;
{
    console.log(x);//Reference Error
    const x = 2;
}

{
    var x = 1;
}
console.log(x)//1 Access to the value because var declaration are not scoped to blocks.

Q. What is TDZ(Temperal Dead Zone)?
Ans:-
A TDZ is the area of a block where a variable is inaccesible until the moment the computer completely intializes it with a value.

a. A block is a pair of braces({...}) used to group multiple statements.
b. intialization occurs when you assign an initial value to a variable.

A block's TDZ starts at the beginning of the block's local scope. It ends when the computer fully intializes your variable with a value. eg:-

console.log(bestFood)// Reference Error
let bestFood ="Vegetable Fried Rice" //bestFood tdz ends here

Q. What is Closure with example?
Ans:- A closure is the combination of a function bundled together (enclosed) with refernce to its surrounding state (the lexical environment). In other words, a closure gives you access to an outer function's scope from an inner function.In Javascript, closures are created every time a function is created, at function creation time.

Q. Why do we use promise?
Ans:-Promises are used to handle asynchronous operations in JavaScript. They are easy to manage when dealing with multiple asynchronous operations where callbacks can create callback hell leading to unmanageable code.

fulfilled: Action related to the promise succeeded
rejected: Action related to the promise failed
pending: Promise is still pending i.e. not fulfilled or rejected yet
settled: Promise has fulfilled or rejected

Q.What is Async and Await?
Ans:-The async function declaration declares an async function where the await keyword is permitted within the function body. The async and await keywords enable asynchronous, promise-based behavior to be written in a cleaner style, avoiding the need to explicitly configure promise chains.

Q.What is let,var ans const?
Ans:- The scope of a var variable is functional scope. The scope of a let variable is block scope. The scope of a const variable is block scope. It can be updated and re-declared into the scope. It can be updated but cannot be re-declared into the scope.

Q. What is currying in javascript?
Ans:- In the curried function, we simply wrap a function inside a function. It means the return of a function is processed by the above function to obtain this kind of translation. The parent function takes the first provided argument that returns the function taking the next argument. This keeps on repeating until the number of arguments ends. Hopefully, the function that receives the last argument returns the expected result.

function curriedFunction(param1) {
   return function (param2) {
      return function (param3) {
      }
   }
}

Q. What is Immedialtely invoked functions?
Ans:- An IIFE (Immediately Invoked Function Expression) is a JavaScript function that runs as soon as it is defined.

Q. What is HOF(Higher Order Function)?
Ans:- Higher-Order Functions(HoF): A function that takes another function(s) as an argument(s) and/or returns a function as a value. Callback Functions(CB): A function that is passed to another function.

Q. What is spread operator?
Ans:- Spread operator allows an iterable to expand in places where 0+ arguments are expected. It is mostly used in the variable array where there is more than 1 values are expected. It allows us the privilege to obtain a list of parameters from an array.

Q. What is Rest Operator?
Ans:- The rest operator (…) allows us to call a function with any number of arguments and then access those excess arguments as an array.

Q.What are Arrow Functions?
Ans:- An arrow function expression is a compact alternative to a traditional function expression, with some semantic differences and deliberate limitations in usage: Arrow functions don't have their own bindings to this , arguments , or super , and should not be used as methods.

Q. What is function?
Ans:- A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.

Q. What is date and time in Javascript?
Ans:- Date Objects, JavaScript new Date() 
new Date(year,month,day,hours,minutes,seconds,ms)

Q. What are number methods?
Ans:- toString()	Returns a number as a string
toExponential()	Returns a number written in exponential notation
toFixed()	Returns a number written with a number of decimals
toPrecision()	Returns a number written with a specified length
ValueOf()	Returns a number as a number

Q. What is lexical scope?
Ans:- While in ES5 'this' referred to the parent of the function, in ES6, arrow functions use lexical scoping — 'this' refers to it's current surrounding scope and no further. Thus the inner function knew to bind to the inner function only, and not to the object's method or the object itself.

Q. What is map and filter?
Ans:- The main difference between a map and a filter is the return of values. A map will always have a representation for elements in the list. The filter will filter out the only elements that will meet the conditions in the function.

Q. How to convert Object to Array?
Ans:- To convert an object to an array you use one of three methods: Object.keys() , Object.values() , and Object.entries() . Note that the Object.keys() method has been available since ECMAScript 2015 or ES6, and the Object.values() and Object.entries() have been available since ECMAScript 2017.

Q. How to convert Array to Object?
Ans:- To convert an array to an object, use the reduce() method to iterate over the array, passing it an object as the initial value. On each iteration, assign a new key-value pair to the accumulated object and return the result.

Q.Is javascript asynchronous?
Ans:- Javascript is the synchronous single-threaded language but with the help of event-loop and promises, JavaScript is used to do asynchronous programming.

Q. What is fetch?
Ans:- The fetch() method in JavaScript is used to request data from a server. The request can be of any type of API that return the data in JSON or XML. The fetch() method requires one parameter, the URL to request, and returns a promise.

Q. What is BOM(Browser Object Model)?
Ans:- 
The Browser Object Model (BOM) is a browser-specific convention referring to all the objects exposed by the web browser. The BOM allows JavaScript to “interact with” the browser.

# ReactJs
Q. What is JSX?
Ans:- JSX stands for JavaScript XML. JSX allows us to write HTML in React. JSX makes it easier to write and add HTML in React.

Q. What is Component?
Ans:- Components in React basically return a piece of JSX code that tells what should be rendered on the screen. In React, we mainly have two types of components: Functional Components: Functional components are simply javascript functions. We can create a functional component in React by writing a javascript function.

Q. What are props?
Ans:- Props are arguments passed into React components. Props are passed to components via HTML attributes. props stands for properties.

Q. What is State?
Ans:- What Is 'State' in ReactJS? The state is a built-in React object that is used to contain data or information about the component. A component's state can change over time; whenever it changes, the component re-renders.

Q. Props method data pass with example?
Ans:- From Parent to Child Using Props
From Child to Parent Using Callbacks

class Parent extends React.Component {
state = { message: "" }
callbackFunction = (childData) => {
      this.setState({message: childData})
},


 render() {
        return (
            <div>
                 <Child1 parentCallback = {this.callbackFunction}/>
                 <p> {this.state.message} </p>
            </div>
        );
}
}
javascript
Pass your data using this.props.callback(dataToParent) in the child1.js.
class Child1 extends React.Component{sendData = () => {
         this.props.parentCallback("Hey Popsie, How’s it going?");
    },

render() { 
//Any time you wish to send data from child to parent component, call the sendData function.
    }
};

Q. Lifecycle method in fuctional Component?
Ans:- const App = () => {
  useEffect(() => {
    console.log(
      "This only happens ONCE. 
       Anything in here is fired on component MOUNT."
    );
    return () => {
      console.log(
        "This only happens ONCE. 
         Anything in here is fired on component UNMOUNT."
      );
    }
  }, []);
};

const Button = React.memo((props) => {
  // your component
});

Q. Lifecycle method in Class based Component?
Ans:- Mounting:

There are four built-in lifecycle methods that are called in the following order when a component is mounted:
constructor( ) - This is called before anything else. We can set the initial state of the component inside this method. The constructor method is used to set the initial state and bind methods to the component.
getDerivedStateFromProps( ) - This is called before rendering the elements in the DOM.
In this method, we can set the state of the component based on the props we received. This method is used very rarely.
render( ) - This is the only required method in the class component. This method returns the HTML elements which are going to be rendered inside the DOM.
componentDidMount( ) - It is called right after the component is rendered inside the DOM. All the statements which require the DOM nodes can be executed in this method. Network requests from a remote end-point can also be instantiated in this method.

Updating:

Updates in react are caused by changes in state or props. Update leads to re-rendering of the component. The following methods are called when a component is re-rendered:
getDerivedStateFromProps( ) - This method is called again when a component is being re-rendered.
shouldComponentUpdate( ) - This method is called before rendering the component when new props are received. It lets React know if the component’s output is affected by the newly received props or by the state change. By default, it returns true.
render( ) - To re-render the HTML inside the DOM, the render( ) method gets called again.
getSnapshotBeforeUpdate( ) - This method is called just before the newly rendered HTML gets committed to the DOM. It stores the previous state of the component so that React has an idea of what parts of the DOM needs to be updated.
componentDidUpdate( ) - It is called after the component gets re-rendered. This method works just like the componentDidMount( ) method, the difference is that this method does not get called on initial render.

Unmounting:

componentWillUnmount( ) - This method is called just before the component gets destroyed. Any clean up statements should be executed inside this method.

Q. What is Ref?
Ans:- Refs are a function provided by React to access the DOM element and the React element that you might have created on your own. They are used in cases where we want to change the value of a child component, without making use of props and all to avoid re-render.

Q. What is Forward Ref?
Ans:- The forwardRef method in React allows parent components to move down (or “forward”) refs to their children. ForwardRef gives a child component a reference to a DOM entity created by its parent component in React. This helps the child to read and modify the element from any location where it is used.

Q. What is useRef?
Ans:- The useRef Hook allows you to persist values between renders. It can be used to store a mutable value that does not cause a re-render when updated. It can be used to access a DOM element directly.

Q. What is Pure Component with example?
Ans:-In simple words, If the previous value of state or props and the new value of state or props is the same, the component will not re-render itself. Since Pure Components restricts the re-rendering when there is no use of re-rendering of the component. Pure Components are Class Components which extends React.PureComponent.

import React from ‘react’;
  
export default class Test extends React.PureComponent{
   render(){
      return <h1>Welcome to GeeksforGeeks</h1>;
   }
}

Q. What is UseMemo?
Ans:- useMemo is a React Hook that lets you cache the result of a calculation between re-renders. const cachedValue = useMemo(calculateValue, dependencies) Usage. Skipping expensive recalculations. Skipping re-rendering of components.

Q.What is Memo?
Ans:- React.memo is a higher order component. If your component renders the same result given the same props, you can wrap it in a call to React.memo for a performance boost in some cases by memoizing the result. This means that React will skip rendering the component, and reuse the last rendered result.

Q. What is browser Router with example?
Ans:- BrowserRouter: BrowserRouter is a router implementation that uses the HTML5 history API (pushstate, replacestate, and popstate events) to keep your UI in sync with the URL. It is the parent component used to store all other components. Route: This is a new component introduced in v6 and an upgrade of the component.

Q. What is a portal?
Ans:- Portals provide a first-class way to render children into a DOM node that exists outside the DOM hierarchy of the parent component. ReactDOM. createPortal(child, container) The first argument ( child ) is any renderable React child, such as an element, string, or fragment.

Q. What is lazy loader?
Ans:- Lazy loading is a strategy to identify resources as non-blocking (non-critical) and load these only when needed. It's a way to shorten the length of the critical rendering path, which translates into reduced page load times.

Lazy loading can occur on different moments in the application, but it typically happens on some user interactions such as scrolling and navigation.

Q. What is useState?
Ans:- The useState() is a Hook that allows you to have state variables in functional components . so basically useState is the ability to encapsulate local state in a functional component.

Q. What is useReducer?
Ans:- The useReducer is a hook I use sometimes to manage the state of the application. It is very similar to the useState hook, just more complex. It acts as an alternate hook to the useState hook to manage complex state in your application.

Q. What is useCallback?
Ans:- useCallback is a hook that will return a memoized version of the callback function that only changes if one of the dependencies has changed.

Q. What is a Custom Hook?
Ans:- A custom hook is a special JavaScript function whose name starts with 'use' and can be used to call other hooks.

Q. What is Context API?
Ans:- Context is a built-in API introduced in ​​React 16.3. It makes it possible to pass data from parent to children nested deep down the component tree directly, instead of passing it down through a chain of props.

Q. What is MUI and its properties?
Ans:- MUI System is a set of CSS utilities to help you build custom designs more efficiently when working with MUI component libraries like Material UI, Joy UI, and MUI Base. The System gives you a set of flexible, generic wrapper components like Box and Container that can be quickly customized using the sx prop.

Q. What is Regex?
Ans:- Regex can be used to add, remove, isolate, and manipulate all kinds of text and data. It could be used as a simple text editor command, e.g., search and replace, or as it's own powerful text-processing language

Q. What are Higher Order Component?
Ans:- A higher-order component (HOC) is an advanced technique in React for reusing component logic. HOCs are not part of the React API, per se. They are a pattern that emerges from React's compositional nature. Concretely, a higher-order component is a function that takes a component and returns a new component.

Q. What is useLocation?
Ans:-  This hook returns the location object used by the react-router. This object represents the current URL and is immutable. Whenever the URL changes, the useLocation() hook returns a newly updated location object.

Q. What is useNavigate?
Ans:- useNavigation is a hook which gives access to navigation object. It's useful when you cannot pass the navigation prop into the component directly, or don't want to pass it in case of a deeply nested child. useNavigation() returns the navigation prop of the screen it's inside.

Q. What is useParams?
Ans:- The useParams hook returns an object of key/value pairs of the dynamic params from the current URL that were matched by the <Route path> . Child routes inherit all params from their parent routes.

Q. What is Redux?
Ans:- Redux is a predictable state container for JavaScript apps.

Q. Redux with an Example?
Ans:-  Redux is a predictable state container designed to help you write JavaScript apps that behave consistently across client, server, and native environments, and are easy to test. 

Q. What is Navigation?
Ans:- React Navigation is a standalone library that enables you to implement navigation functionality in a React Native application. 

Q. What is key?
Ans:- A “key” is a special string attribute you need to include when creating lists of elements in React. Keys are used in React to identify which items in the list are changed, updated, or deleted. In other words, we can say that keys are used to give an identity to the elements in the lists.

Q. What is Error Handling?
Ans:- Error boundaries were introduced in React 16 as a way to catch and handle JavaScript errors that occur in the UI parts of our component. So error boundaries only catch errors that occur in a lifecycle method, render method, and inside Hooks like useEffect .

Q. What is Error Boundaries?
Ans:- Error boundaries are React components that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI instead of the component tree that crashed. Error boundaries catch errors during rendering, in lifecycle methods, and in constructors of the whole tree below them.

Q. Data Passed from child to parent?
Ans:- While there is no direct way to pass data from the child to the parent component, there are workarounds. The most common one is to pass a handler function from the parent to the child component that accepts an argument which is the data from the child component.

Q. Data passed from Parent to child with example?
Ans:-

Q. What is Controlled and unControlled Component?
Ans:- Controlled component is component that get the changed value from the callback function 
Uncontrolled component is component that have the one from the DOM.
When input value is changed,we can use onChange function in Controlled Component and also we can get the value using DOM like ref.

Q. Form Validation with an Example?
Ans:- You should always check the data in the backend. So, while providing frontend validation is nice in concerns of usability, it's totally not neccessary. Backend validation on the other hand is and it's the only way to have sane data.

Q. What is ternary Operator with an example?
Ans:- condition ? value_if_true : value_if_false

Q. What is Props Drilling?
Ans:- Prop drilling is a situation where data is passed from one component through multiple interdependent components until you get to the component where the data is needed.

Q. Validation is better on OnChange or OnFocusOut or Onclick
Ans:-

Q. What are OOPS concept used in Javascript?
Ans:-

Q. What is Render Props?
Ans:- The term “render prop” refers to a technique for sharing code between React components using a prop whose value is a function. In simple words, render props are simply props of a component where you can pass functions. These functions need to return elements, which will be used in rendering the components.

Q. What is Debugger?
Ans:- Debugging is one of the most useful skills a developer can possess. It allows you to properly navigate and spot errors in your code quickly and efficiently. In the modern web, this is made possible by leveraging various tools and techniques. React is one of the fastest-growing front-end frameworks.

Q. What are Controlled and UnControlled Inputs?
Ans:- Controlled component is component that get the changed value from the callback function and uncontrolled component is component that have the one from the DOM. For example, When input value is changed,we can use onChange function in Controlled Component and also we can get the value using DOM like ref.

Q. Const or let which is better and why do we use it?
Ans:- Use const more often. Use let when you need to reassign another value to a variable.

Q. What is Lifting state up?
Ans:- We lift the state up to make the parent state a single shared state and a sole "source of truth" and pass the parent's data to its children. This concept is called lifting state up. It is of great use to maintain data consistency in our react applications.

Q. Differnce betweem Splice, Slice and Split?
Ans:- splice is destructive — meaning it alters the contents of the array. Splice can remove, replace existing elements, or add new elements to an array. Splice alters the existing array, but it will return the removed items in an array.

Slice() is used to extract elements from an array and return a new array, and it would not modify the origin array.

Split() is used to convert the input string into an array by the separator, and since string is immutable, it would not modify the origin string.

Q.Why do we use Strict Mode in React?
Ans:- StrictMode is a React Developer Tool that is primarily used to identify potential issues in a web application. For its descendant components, it activates additional deprecation checks and warnings.

Q.What is ReactMemo?
Ans:- React.memo is a higher order component. If your component renders the same result given the same props, you can wrap it in a call to React.memo for a performance boost in some cases by memoizing the result. This means that React will skip rendering the component, and reuse the last rendered result.

Q.Difference between UseCallback, UseMemo and UseEffect?
Ans:- The main difference between useMemo and useCallback hook is, useMemo returns memoized value and useCallback returns memoised function.

Q. Which is better if and else, Switch Case and UseReducer?
Ans:- UseReducer

Q. ES6 Features and when was let, var and const introduced?
Ans:-

Q. Normal and Arrow function differnce?
Ans:- In regular JavaScript functions, arguments keywords can be used to access the passed arguments when the function is invoked. But, arrow functions do not have their own arguments and it uses the arguments from the outer function.

Q. Why do we use React?
Ans:- It's used for building interactive user interfaces and web applications quickly and efficiently with significantly less code than you would with vanilla JavaScript. In React, you develop your applications by creating reusable components that you can think of as independent Lego blocks.

Q. What are features of React?
Ans:- Easy creation of dynamic applications: React makes it easier to create dynamic web applications because it requires less coding and offers more functionality, as opposed to JavaScript, where coding often gets complex very quickly. Improved performance: React uses Virtual DOM, thereby creating web applications faster.

Q. What is Regex and why do we use it?
Ans:-

Q. What is Callback Function?
Ans:- A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.

Q. Differnce between Substring and SubStr?
Ans:- 
It is same as slice method. It extract the string from given index.
example-	let a = 'Hello my name'
		let b = a.substr(2,7)
		console.log(b); o/p- 'llo my'

substring()- It is same as substr mehtod. But the diffrence is that it does not include the character of last index.
example -	let a = 'Hello my name'
		let b = a.substring(2,7)
		console.log(b) o/p- 'llo m


Q. Difference between Substring and Slice?
Ans:- 
Slice() is used to extract elements from an array and return a new array, and it would not modify the origin array.

substring()- It is same as substr mehtod. But the diffrence is that it does not include the character of last index.
example -	let a = 'Hello my name'
		let b = a.substring(2,7)
		console.log(b) o/p- 'llo m

Q.For in and For off Loop Differnece?
Ans:- For in Iterates over the keys while for of iterates over the values.

Q. Rem, Em, vh and vw Units and why to use it?
Ans:- em – It is used to set the relative size. It is relative to the font-size of the element. 
Note: Here 2em meaning 2times the size of current font. 
rem – Relative to the browser base font-size. 
px – It defines the font-size in terms of pixels. (96px = 1in)
vh – Relative to 1% of the height of the viewport. 
vw – Relative to 1% of the width of the viewport. 


Q. Make an TodoList?
Ans:-

