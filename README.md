# How to learn with Learnpack

<!-- hide -->

By [@alesanchezr](https://twitter.com/alesanchezr) and [other contributors](https://github.com/learnpack/how-to-use-learnpack-tutorial/graphs/contributors)

<p>
<img alt="last commit" src="https://img.shields.io/github/last-commit/learnpack/how-to-use-learnpack-tutorial" class="text-center" />
<img alt="last commit" src="https://img.shields.io/twitter/follow/learnpack?style=social&logo=twitter" class="text-center" />
</p>

<!-- endhide -->

1. How to stop and start the tutorial engine.
2. Navigate through the exercise steps.
3. Multiple language translations.
4. Compiling your code.
5. Testing your code.
6. Save your progress to github.

<!-- hide -->
## 🌱 How to start

There are two ways to run the exercises: Immediately in gitpod (recommended) or locally in your computer (requires installation).

### A) One click installation (recommended):

You can open these exercises in just a few seconds by clicking: [Open in Codespaces](https://codespaces.new/?repo=4GeeksAcademy/css-layouts-tutorial-exercises) (recommended) or [Open in Gitpod](https://gitpod.io#https://github.com/4GeeksAcademy/css-layouts-tutorial-exercises.git).

> Once you have VSCode open the LearnPack exercises should start automatically. If exercises don't run automatically you can try typing on your terminal: `$ learnpack start`

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
<!-- endhide -->
