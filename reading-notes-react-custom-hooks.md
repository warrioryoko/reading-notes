So, custom hooks.

Reading up on it, it sounds like it practically every operation in react involving some sort of state information being passed around should be written as something that calls a custom hook or involves them.

You can write your own hooks, since it's just a design pattern, and each hook has its own independent state. Just call them at the topmost component level, don't use them in loops, conditions or nesting, and definitely don't call them in a plain old javascript utility file.

The 10 custom hooks are REALLY helpful, and I'm sure there are others out there I can look up. Logic and design patterns seem to be a pretty established thing, and everybody needs the same basic operations. The chances I'm going to write lower level or basic functionality better than someone else who's already written it is slim.