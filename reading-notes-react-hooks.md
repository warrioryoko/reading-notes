So, Hooks.

So, you can use state logic without having to change state itself?

I don't fully understand the useEffect code example;

useEffect(() => {
    ChatAPI.subscribeToFriendStatus(props.friend.id, handleStatusChange);
    return () => {
      ChatAPI.unsubscribeFromFriendStatus(props.friend.id, handleStatusChange);
    };
  });

I don't understand exactly when the return happens.

Anyway. Use state lets you define state and its updater function at the same time.

useEffect lets you do other things, but I'm very unclear on when exactly it fires, and under what conditions.

Hooks are specifically for use in functions, and do not work in classes. So, this lets us use functional components for everything... maybe.

Hooks RETURN a value, and the function that updates it as the first and second elements. We use array destructuring to store these, consequently. MAKES SENSE, FINALLY!

OKAY. useEffect runs on first render, and every update. Got it. Makes sense.