# 14. Use a lazy initializer with useState

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/14-lazy-initialization?from-embed)

## Notes

- Something that’s important to recognize is that every time you call the state updater function (like the setName function in our component), that will trigger a re-render of the component that manages that state (the Greeting component in our example). This is exactly what we want to have happen, but it can be a problem in some situations and there are some optimizations we can apply for useState specifically in the event that it is a problem.

- In our case, we’re reading into localStorage to initialize our state value for the first render of our Greeting component. But after that first render, we don’t need to read into localStorage anymore because we’re managing that state in memory now (specifically in that name variable that React gives us each render). So reading into localStorage every render after the first one is unnecessary. So React allows us to specify a function instead of an actual value, and then it will only call that function when it needs to–on the initial render.

- In this lesson, I’ll show you how to do this and demonstrate how it works.

## Additional resource
