# Typescript-Gulp

## Start project

- Initialize the project
```
npm init
```

- Install our dependencies
```
npm install -g gulp-cli
npm install --save-dev typescript gulp gulp-typescript
```

- Test the resulting app
```
gulp
node dist/main.js
```

## Browserify

```
npm install --save-dev browserify tsify vinyl-source-stream
```

## Watchify, Babel, and Uglify

- Watchify
```
npm install --save-dev watchify gulp-util
```
- Uglify
```
npm install --save-dev gulp-uglify vinyl-buffer gulp-sourcemaps
```
- Babel
```
npm install --save-dev babelify babel-core babel-preset-es2015 vinyl-buffer gulp-sourcemaps
```

# React & Webpack
- Initialize the project
```
npm init
```
- Install our dependencies
```
npm install -g webpack
npm install --save react react-dom @types/react @types/react-dom
npm install --save-dev typescript awesome-typescript-loader source-map-loader
npm link typescript
```