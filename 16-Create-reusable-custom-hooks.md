# 16. Create reusable custom hooks

## Links

#### [📹 Video]()

#### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/16-custom-hooks?from-embed)

## Notes

- One of the things we love about programming is the ability to take code, place it in a function, and reuse it in other places in the software. Let’s imagine a scenario where we want to share our localStorage code with other components so other components could synchronize state with localStorage (or we could even do it with different variables in the same component). Take a step back from React specifically and considering how code reuse works in JavaScript in general, we can simply make a function, put our relevant code in that function, and then call it from the original location. That process works exactly the same with React hooks code, so let’s do that!

- In the process, we’ll learn a few of the conventions for doing this and we’ll learn about some additional challenges that come with generalizing our code. As always, follow AHA programming practices!

## Additional resource
