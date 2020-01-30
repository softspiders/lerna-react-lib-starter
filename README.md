SOFTSPIDERS

# lerna-react-lib-starter

[React](https://reactjs.org/) application starter with library in [Lerna](https://lerna.js.org/) monorepo

---

## Feature tags

- lerna
- lib
- react
- starter

## Authors

[Alexander Lapygin](https://github.com/AlexanderLapygin) - adaptation [react-lib-starter](https://github.com/antonybudianto/react-lib-starter) to *Soft Spiders*

## Inspired by

[Antony Budianto](https://github.com/antonybudianto)'s [react-lib-starter](https://github.com/antonybudianto/react-lib-starter)

---

## Direct ancestors

[Starter for Lerna monorepo](https://github.com/softspiders/lerna)

---

## Install
1. Clone this repo
2. Install dependencies
   ```sh
   # yarn is fine too
   npm i
   ```
3. Run bootstrap
   ```sh
   npm run bootstrap
   ```

   This will bootstrap and link between app and lib
4. Now, it's ready!

## Dev flow
1. Change dir to `packages/example-lib`
2. Run start
   ```sh
   npm start
   ```
3. Change dir to `packages/example-app`
   ```sh
   npm start
   ```
4. Try changing the lib, it should reflect the changes directly
5. Now, you can start developing your React library!

## Prod flow
1. Make sure you've commited all the changes
2. Change dir to root of this repo
3. Run release (it will run `npm run build` first via `prerelease` hook)
   ```sh
   npm run release
   ```
---

### License

Licensed under the [MIT license](./LICENSE). 

