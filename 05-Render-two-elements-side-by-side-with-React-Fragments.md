# 05. Render two elements side-by-side with React Fragments

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/05-fragements?from-embed)

## Notes

- In React, you can’t render two React elements side-by-side (<span>Hello</span><span>World</span>). They have to be wrapped in another element (like a `<div>`).
- This may seem like an odd limitation, but when you think about the fact that JSX is compiled to `React.createElement` calls, it makes sense.
- How to side-step this limitation with React Fragments.

## Additional resource
