# How to learn with Learnpack

<!-- hide -->
By [@alesanchezr](https://twitter.com/alesanchezr) and [other contributors](https://github.com/4GeeksAcademy/html-tutorial-exercises-course/graphs/contributors)

<p>
<img alt="last commit" src="https://img.shields.io/github/last-commit/4geeksacademy/javascript-arrays-exercises-tutorial" class="text-center" />
<img alt="last commit" src="https://img.shields.io/twitter/follow/learnpack?style=social&logo=twitter" class="text-center" />
</p>
<!-- endhide -->

1. How to stop and start the tutorial engine.
1. Navigate throught the exercise steps.
2. Multiple language translations.
3. Compiling your code.
4. Testing your code.
5. Save your progress to github.

<!-- hide -->

## 🌱 How to start

There are two ways to run the exercises: Immediately in gitpod (recommended) or locally in your computer (requires installation).

### A) Open immediately with Gitpod (one-click)

This exercises are configured to easily open in gitpod.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/4GeeksAcademy/html-tutorial-exercises-course.git)

### B) Manual installation

1. Install learnpack, the package manager for learning tutorials and the html compiler plugin for learnpack, make sure you also have node.js 14+:

```
$ npm i learnpack -g
$ learnpack plugins:install learnpack-html
```

2. Download this particular exercises using learnpack and `cd` into the folder:

```
$ learnpack download html-tutorial-exercises-course
$ cd html-tutorial-exercises-course
```

Note: Once you finish downloading, you will find a "exercises" folder that contains all the exercises within.

3. Start the tutorial/exercises by running the following command at the same level were your bc.json file is:

```sh
$ npm i jest@24.8.0 -g
$ learnpack start
```
