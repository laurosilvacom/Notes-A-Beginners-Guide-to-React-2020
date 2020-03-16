# 26. Handle HTTP Errors with React

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/26-http-errors?from-embed)

## Notes

- Unfortunately, sometimes a server request fails and we need to display a helpful error message to the user. In this lesson we’ll handle a promise rejection so we can collect that error information, and we’ll also learn how we can best display manage the state of our request so we have a deterministic render method to ensure we always show the user the proper information based on the current state of our React component.

- A common mistake people make is to create a state variable called isLoading and set that to true or false. Instead, we’ll be using a status variable which can be set to idle, pending, resolved, or rejected. You can learn more about why this is important from Stop using isLoading booleans.

## Additional resource
