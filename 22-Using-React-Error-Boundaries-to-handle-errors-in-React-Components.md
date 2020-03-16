# 22. Using React Error Boundaries to handle errors in React Components

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/22-error-boundaries?from-embed)

## Notes

- No matter how hard you try, eventually your app code just isn’t going to behave the way you expect it to and you’ll need to handle those exceptions. If a render is thrown and unhandled, your application will be removed from the page, leaving the user with a blank screen... Kind of awkward...

- Luckily for us, there’s a simple way to handle errors in your application using a special kind of component called an Error Boundary. Unfortunately, there is currently no way to create an Error Boundary component with a function and you have to use a class component instead, but we got another lucky break because there’s a terrific open source library we can use called react-error-boundary.

- In this lesson, we’ll learn how to write our own simple error boundary and then how to use react-error-boundary instead. We’ll also learn the implications of where we place our Error Boundaries in our React component tree.

## Additional resource
