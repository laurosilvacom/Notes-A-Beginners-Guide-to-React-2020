# 24. Lifting and colocating React State

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/24-lifting-and-colocating?from-embed)

## Notes

- A common question from React beginners is how to share state between two sibling components. The answer is to Lift the state which basically amounts to finding the lowest common parent shared between the two components and placing the state management there, and then passing the state and a mechanism for updating that state down into the components that need it.

- As a community we’re pretty good at doing this and it becomes natural over time. One thing that we typically have trouble remembering to do is to push state back down (or colocate state). In this lesson we’ll learn how to lift state up and push state back down.

## Additional resource
