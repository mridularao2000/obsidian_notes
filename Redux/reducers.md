Parent:: [[Redux (Classic)]]
Imports:: [[actions]] -> green
Uses:: [[How to make mindmaps?]] -> yellow
Next:: [[next for reducer]] 
Previous:: [[previous for reducer]]
## What it does
Handles state transitions in response to dispatched actions.

## Code

```
js
import { ADD_TODO } FROM './constants'
export default function todos(state, action){
	switch(action.type) {
		case ADD_TODO:
			return [...state, { text: action.text }]
	}
}
```

