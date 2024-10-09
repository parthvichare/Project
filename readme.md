//Important Learnings 
1. ()=>({}): Use when you want to return an object directly from the function.
2. () => {}: Use when you need to perform some logic, execute multiple statements, or return a value conditionally.

<!-- When you write ()=>({ key: value }), you're saying, "This arrow function will return an object. -->


()=>{} :- Logic Arrow
()=>({}):- Update data Arrow(Object Literal)

{(item, index) => ()} :- Mapping Arrow to render the items from the Array
Common in React when rendering lists, such as with .map() to create JSX elements.

<!-- To Tell the React we are access the Javascript mode -->

code:- style={{ display: imageLoaded[item.id] ? 'block' : 'none' }}

<!-- //Outer Curly Braces {}:
In JSX, the outer curly braces are used to embed JavaScript expressions within the JSX markup. This is how you tell React that you're entering JavaScript mode.

//Inner Curly Braces {}:
The inner curly braces are used to define an object literal. In this case, it's the style object that you're passing to the style attribute of the div or img element. -->

