# 23. Use the key prop when Rendering a List with React

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/23-rendering-lists?from-embed)

## Notes

- It doesn’t take long working with React before you want to render a list of items and when you do, you’ll inevitably encounter this console warning: “Warning: Each child in a list should have a unique key prop.” This warning is pretty simple to silence by providing the bespoken key prop, but it is really useful to understand what that warning is about and the bugs that can happen if you do not address the warning properly.

- In this lesson we’ll see a demo of this problem and understand a situation that can happen when we don’t handle it properly. We’re using inputs in this example, but the same thing can happen for your own components that maintain state. You definitely do not want to ignore this warning.

## Additional resource
