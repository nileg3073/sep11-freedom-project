# Tool Learning Log

## Tool: react.dev

### Learning Log 2:

- Went back on [react.dev](https://react.dev?utm_) and explored more React features.
- Spent more time looking at components and how they work together.
- Learned about `useState` and how it keeps track of changes.
- Looked at examples where clicking a button changes something on the page.
- Started understanding how React updates the page without me changing the HTML myself.

Example I looked at:

```js
import { useState } from 'react';

function MyButton() {
  const [count, setCount] = useState(0);

  return (
    <button onClick={() => setCount(count + 1)}>
      Clicked {count} times
    </button>
  );
}
```

- The `useState` part was new to me, but the example made it easier to follow.
- I still need more practice using it without following the example.

### Questions

- How do I use props and `useState` together?
- How do I add React features to a website I already made?

### Next Steps

- Try making a button that changes text when clicked.
- Experiment more with components and `useState`.
