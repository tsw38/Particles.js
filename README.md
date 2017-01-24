## How to get Set Up

In the project directory first run to install all necessary node modules
```npm install browserify uglify -g && clear```

After editing any javascript in particles.js run:
```
  browserify particles.js | uglifyjs > particles.min.js
```
