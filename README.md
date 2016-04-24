# rig-sass
[![Dependency Status](https://david-dm.org/vladfilipro/rig-sass.svg)](https://david-dm.org/vladfilipro/rig-sass)

A rig containing a task used for outputting messages to console

## How to use
1. Install rigs package: `npm install rigs`
2. Install rig-sass: `npm install rig-sass`

## Available tasks in rig-sass
- `rig-sass__sass`: A task for converting sass files into css files
  - properties:
    - `sourcemap`: Boolean, when set to TRUE, it will generate sourcemaps
    - `minify`: Boolean, when set to TRUE, it will minify the resulting css file
    - `rename`: String, represents the extension of the output css file
    - `src`: String, refers to sass entry point
    - `dest`: String, refers to the output path

    ```
    {
       taskname: 'sass',
       sourcemap: true,
       minify: false,
       src: './main.scss',
       dest: '/styles'
    }
    ```

### Generated using [webcase-rig](https://www.npmjs.com/package/webcase-rig) version 1.0.0
