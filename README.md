# ⚛️ SCSS Files for Wes Bos' React for Beginners Course

## ❔What is this?
In Wes Bos' React for Beginners course, in video 22 Wes goes over animating React components using CSS. Yet, Wes uses the Stylus CSS framework which is fine but not my cup of tea. Whamp whomp.

Instead, I wanted to use SCSS/Sass and CodeKit to compile my styles so I converted all of the included .styl (Stylus) files to .scss (Sass). 

While not difficult to do, it took a bit of time to convert the files over so I thought anyone else taking the course who wanted to use SCSS instead of Stylus could benefit from this.

## 🔑 How to use these files
This worked for my setup so you may have to adjust for your particular workflow.

The folder structure for this project is as follows:

```
/catch-of-the-day
|-- /node_modules
|-- package-lock.json
|-- package.json
|-- /public
|   |-- favicon.ico
|   |-- /images
|   |-- index.html
|-- /src
    |-- base.js
    |-- /components
    |-- /css
    |   |-- _animations-finished.styl
    |   |-- _animations.styl
    |   |-- _colours.styl
    |   |-- _fonts.styl
    |   |-- _normalize.styl
    |   |-- _typography.styl
    |   |-- /fonts
    |   |-- /images
    |   |-- style.css
    |   |-- style.styl
    |-- helpers.js
    |-- index.js
    |-- sample-fishes.js
    |-- /scss
        |-- _animations.scss
        |-- _colours.scss
        |-- _fonts.scss
        |-- _normalize.scss
        |-- _typography.scss
        |-- README.md
        |-- style.scss
```

So, clone this into your `/src/` folder so that you have a `/scss/` folder at the same level as the `/css/` folder. Then set up you package scripts (Gulp, Grunt, etc.) to output the `/scss/style.scss` file to `/css/style.css`.  

Alternatively, if you use CodeKit like me, just drop the project into CodeKit, ignore all of the component and other files except `style.scss` and you are good to go. With CodeKit, this works seamlessly with your React project without any other build steps, watchers or scripts. It's like magic.

### ⌚️ When to use these files?
These files are the defaults as of video 22, 7m24s, *before* Wes goes into adjusting them in the course. These are __not__ the finished files so use these as a starting point to finish the course.

### 🍦 Sweetness.