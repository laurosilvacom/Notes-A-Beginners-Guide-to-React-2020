# 10. Style React Components with className and inline Styles

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/10-styling?from-embed)

## Notes

- Application layout is only one part of the user interface equation. Another part is styling.

```html

```

- One of the most basic ways to style React components is with inline CSS. JSX elements can take a style attribute which takes in an object:

- One of the nice things about having style as an object is the possibility to include your styling in the props object.

Notice that we use the className shorthand in the object. When the property key and value are the same, you don't need to write them out.

- Creating Reusable Box component. In this example we have a functional `Box` component that takes in `props`. By default the containing `div` has a `className` and a style property. All the other properties we assign to `Box` when we use the component in the App we can spread out.

- This works. Although when you don't use a className property, our classes would render like class="box undefined". To solve this we can assign a default value of nothing while we're destructuring our props:

- A concern in this case could be that the composer of these elements needs to know the CSS classnames. It would be better if the author could just define a size like small, medium or large. That's why we could replace className with a size property that takes in a string:

## Additional resource

- [Tailwind CSS Docs](https://tailwindcss.com)
- [styled-components](https://github.com/styled-components/styled-components)
- [React Docs - Styling and CSS](https://reactjs.org/docs/faq-styling.html)
