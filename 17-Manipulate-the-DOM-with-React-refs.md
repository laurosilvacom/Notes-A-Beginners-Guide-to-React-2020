# 17. Manipulate the DOM with React refs

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/17-dom-refs?from-embed)

## Notes

- React is really good at creating and updating DOM elements, but sometimes you need to work with them yourself. A common use case for this is when you’re using a third party library that wasn’t built for or with React specifically. To do this, we need to have some value that’s associated with our component (like state) to store a reference to the DOM element, but doesn’t trigger re-renders when it’s updated (unlike state). React has something specifically for this and it’s called a ref.

- You create a ref object with the useRef hook and that object’s current property is the current value of the ref. It can be anything, but if you pass that ref object to a component as a prop called ref, then React will set the current property to the DOM element it creates so you can reference it and manipulate it in your useEffect hook.

## Additional resource
