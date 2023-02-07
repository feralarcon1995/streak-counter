
# streak-counter
# `@feralarcon1995/streak-counter` - a basic streak counter 
 
 This is a basic streak counter - inspired by Duolingo - 
 written in TypeScript and meant for the browser (uses `localStorage` ). 
 
 ## Install 
 ```
npm install @feralarcon1995/streak-counter
 
 ```


## Usage/Examples

```javascript
import {streakCounter} from '@feralarcon1995/streak-counter'

const today = new Date()
const streak = streakCounter(localStorage, today)
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "06/02/2023",
//    startDate: "06/02/2023",
// }
```

