# streak-counter
a streak counter for the browser, inspired by Duolingo.

# `@Srinu1239/streak-counter` - a basic streak counter

This is a basic streak counter - inspired by Duolingo - written in TypeScript and meant for the browser (uses `localStorage`).

## Install

```shell
yarn add @Srinu1239/streak-counter
```
npm install @Srinu1239/streak-counter

## Usage

import {streakCounter} from '@jsjoeio/streak-counter'

const today = new Date()
const streak = streakCounter(localStorage, today)
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2021",
//    startDate: "11/11/2021",
// }