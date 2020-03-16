# 15. Manage the useEffect dependency array

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/15-effect-deps?from-embed)

## Notes

- Something that’s really important to know about React’s useEffect hook is that it eagerly attempts to synchronize the “state of the world” with the state of your application. That means that your effect callback will run every time your component is rendered. This normally won’t lead to bugs (in fact, it does a great job at preventing bugs that plagued React apps before useEffect was available), but it can definitely be sub-optimal (and in some cases can result in an infinite loop).

- In this lesson we’ll observe that our effect callback is getting called more than it needs to be, and you’ll learn how to add a dependency array so it is updated only when the state it relies on changes. And in real applications, you’ll want to make sure you have and follow the rules from the ESLint plugin: eslint-plugin-react-hooks (many tools like Create React App have this installed and configured by default).

## Additional resource
