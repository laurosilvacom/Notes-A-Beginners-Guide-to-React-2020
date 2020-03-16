# 20. Make Dynamic Forms with React

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/20-dynamic-forms?from-embed)

## Notes

- Often, it can be useful to know what the user’s input is as they’re typing it and use that information to change what is rendered. This can be good for dynamic search or filter inputs, or triggering changes when a user checks a checkbox, or a myriad of other use cases. In this example, we’re going to dynamically show an error message if the user types something invalid so they don’t have to wait until they submit the form to know they’re doing something wrong.

- To do this we’ll store the input’s value in state and then use that state to derive an error message which will be displayed if there is an error.

## Additional resource
