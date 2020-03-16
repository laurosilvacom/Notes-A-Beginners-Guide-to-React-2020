# 25. Make HTTP Requests with React

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/25-http?from-embed)

## Notes

- Most useful React applications involve interacting with a server to load and persist data. To do this on the web, we use HTTP requests with the browser’s built-in fetch API (or you may use some other open source library that’s built on top of this API). HTTP requests like this are inherently asynchronous in nature and they’re also side-effects so we’ll need to manage not only starting the request, but also what we should show the user while the request is “in flight.”

- In this lesson we’ll use a public GraphQL server that serves up pokemon data to load information for a given pokemon name. We’ll learn how to fetch that data inside a React.useEffect callback and display the results when the request completes.

## Additional resource
