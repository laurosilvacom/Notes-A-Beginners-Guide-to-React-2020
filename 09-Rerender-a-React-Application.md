# 09. Rerender a React Application

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/09-re-render?from-embed)

## Notes

- Applications aren’t really applications if they don’t change over time to represent changes in the application over time. Normally in React you’ll use state to manage this, but before we get to that, we’ll just call ReactDOM.render on the same element so you get an understanding of what React is doing for you. So we’ll learn how React deals with the new elements you give it, compare it to the previous elements, and make surgical updates to the DOM to give you the fastest and best user experience possible (because updating the DOM is typically the slowest part in the whole process).

## Additional resource
