The fact that this.state in React is equivalent to what is currently rendered, and its value cannot be trusted immediately after calling setState() explains a lot of behavior I struggled with in Foundations II.

Also interesting, is that if the 'keys' of the data being updated in setState are the same/duplicated, only the last call applied.

this.setState({ count: this.state.count + 1 })
this.setState({ count: this.state.count + 2 })
this.setState({ count: this.state.count + 3 })

doesn't update count three times, it updates it ONCE.

The ability to pass a function, and doing so as an 'updater' function to get around that is apparently the solution.

But I'm unclear exactly how some of the code in the updater function works.

changeCount = () => {
  this.setState((prevState) => {
    return { count: prevState.count - 1}
  })
}

Where is prevState coming from? I don't understand in this code snippet how you're able to grab the previous state in prevState, unless prevState is a reserved definition?

Keys are important, m'kay? They need to be unique among their siblings (not globally), and you have the *option* to write map methods and the like in JSX rather than store them in variables, then refer to the variable in JSX.

Don't nest JSX, make components! Make your components as atomic as possible; build and name them for what they do from their own perspective, not the context in which they will be used. Also, don't write components that attempt to modify their own props.

React testing library - GOD KCD is VERBOSE. He can't just give a simple example, he just feels the need to give a simple BOOK.