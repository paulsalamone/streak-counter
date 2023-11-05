# @paulsalamone/streak-counter

This is a basic "streak counter" inspired by Duoligno. It was written in Typescript (TS) and meant for the browser, i.e. for state management it uses Local Storage.

## How to Install:

```shell
yarn add @paulsalamone/streak-counter
```
Or
```shell
npm install @paulsalamone/streak-counter
```

## Usage:
```javascript
import {streakCounter} from '@paulsalamone/streak-counter'
const today = new Date()
const streak = streakCounter(localStorage, today)
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2021",
//    startDate: "11/11/2021",
// }
```
