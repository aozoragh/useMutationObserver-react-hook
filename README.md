"# useMutationObserver-react-hook"
Use a useEffect() hook that depends on the values of callback and options.
Check if the given ref is initialized. If it is, create a new MutationObserver and pass it the callback.
Call MutationObserver.observe() with the given options to watch the given ref for changes.
Use MutationObserver.disconnect() to remove the observer from the ref when the component unmounts.
