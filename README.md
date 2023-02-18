<h1 align="center">Welcome to Dockerized-MERN-App-Boilerplate 👋</h1>
<p>
<img alt="Version" src="https://img.shields.io/badge/version-0.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

  > Dockerized Boilerplate for MERN application ( `React.js` & `typescript` & `Vite` )
  
  
 ## 🚀 Usage
 ### Backend:

Install the dependencies:

```sh
npm install
```

Run dev server:

```sh
npm run dev
```
 ### Frontend:
```sh
npm install
```
Run dev server:

```sh
npm run dev
```

  ## 🐳 docker-compose
  
  Build docker containers:

```sh
docker-compose build
```
  Run docker containers:

```sh
docker-compose up
```

## Scripts available
### Backend
```sh
// npm run 
  "scripts": {
    "start": "node ./build/src/index.js",
    "dev": "nodemon --exec 'ts-node' ./src/index.ts",
    "lint": "gts lint",
    "clean": "gts clean",
    "compile": "tsc",
    "fix": "gts fix",
    "prepare": "npm.cmd run compile",
    "pretest": "npm.cmd run compile",
    "posttest": "npm.cmd run lint"
  },
```


### Frontend
```sh
// npm run 
  "scripts": {
    "dev": "vite",
    "build": "tsc && vite build",
    "preview": "vite preview"
  },
```



## Technologies Used

- Backend
  - Typescript & gts - (gts is Google's TypeScript style guide)
  
- Frontend
  - Typescript
  - Vite - is a build tool that aims to provide a faster and leaner development experience for modern web projects



  
## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
