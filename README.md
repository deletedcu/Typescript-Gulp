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
