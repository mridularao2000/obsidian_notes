Parent::[[Redux (Classic)]]

What it does:
Defines action creator functions that reference the action-type constants. 

## Code
```js
import { ADD_TODO } from './constants'
export const addTodo = (text) => ({type: ADD_TODO, text});
```