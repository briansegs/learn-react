# ADVANCED JSX

## Curly Braces in JSX

[Curly Braces in JSX](https://github.com/briansegs/learn-react/tree/main/advanced-react/curly-braces-in-jsx)

- Any code in between the tags of a JSX element will be read as JSX, not as regular JavaScript! JSX doesn’t add numbers - it reads them as text, just like HTML.

- I need a way to write code that says, “Even though I am located in between JSX tags, treat me like ordinary JavaScript and not like JSX.”

- I can do this by wrapping my code in curly braces.

## Variables in JSX

[Variables in JSX](https://github.com/briansegs/learn-react/tree/main/advanced-react/variables-in-jsx)

- When I inject JavaScript into JSX, that JavaScript is part of the same environment as the rest of the JavaScript in my file.

- That means that I can access variables while inside of a JSX expression, even if those variables were declared on the outside.

## Variable Attributes in JSX

[Variable Attributes in JSX](https://github.com/briansegs/learn-react/tree/main/advanced-react/variable-attributes-in-jsx)

- When writing JSX, it’s common to use variables to set attributes.

## Event Listeners in JSX

[Event Listeners in JSX](https://github.com/briansegs/learn-react/tree/main/advanced-react/event-listeners-in-jsx)

- JSX elements can have event listeners, just like HTML elements can. Programming in React means constantly working with event listeners.

- I create an event listener by giving a JSX element a special attribute. Here’s an example:

```js
function myFunc() {
  alert('Make myFunc the pFunc... omg that was horrible i am so sorry');
}

<img onClick={myFunc} />
```

- Note that in HTML, event listener names are written in all lowercase, such as `onclick` or `onmouseover`. In JSX, event listener names are written in camelCase, such as `onClick` or `onMouseOver`.

## JSX Conditionals

[JSX Conditionals](https://github.com/briansegs/learn-react/tree/main/advanced-react/jsx-conditionals)

- How can you write a conditional, if you can’t inject an `if` statement into JSX? Well, one option is to write an `if` statement, and not inject it into JSX.

- The words `if` and `else` should not be injected in between JSX tags. The `if` statement should be on the outside, and no JavaScript injection is necessary.

## JSX Conditionals: The Ternary Operator

[JSX Conditionals: The Ternary Operator](https://github.com/briansegs/learn-react/tree/main/advanced-react/jsx-conditionals_the-ternary-operator)

- There’s a more compact way to write conditionals in JSX: the ternary operator.

- The ternary operator works the same way in React as it does in regular JavaScript. However, it shows up in React surprisingly often.

## Project - Animal Fun Facts

[Animal Fun Facts](https://github.com/briansegs/learn-react/tree/main/advanced-react/project_animal-fun-facts)

- In this project, I built a program that allows users to click an animal on the screen in order to have a fun fact pop up.
