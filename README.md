<h1 align="center">Install and set up SASS in a project with Dart Sass</h1>
<p align="center">A new and improved way of installing and setting up SASS in your project. Recent release 2021: version <b>1.45</b></p>

![Dart_SASS](https://user-images.githubusercontent.com/62628408/147435542-9c8d9472-5f9a-4fad-8612-9836bbb2b67f.png)

## Installation of Dart SASS using NPM

Read the following steps on how to install Dart SASS using NodeJS.

### Install SASS globally.

The first step is to install SASS globally.

```js
npm install -g sass
```

_If you run into any errors, try adding **sudo** as a prefix._

```js
sudo npm install -g sass
```

### Create our directories

Next step is to create our SCSS and CSS folders.

You can do that in the command line or just create the folders natively in your PC.
To do that in the command line, type the following.

This will create our SCSS folder

```js
mkdir scss
```

And this will create our CSS folder

```js
mkdir css
```

### Watch SASS

Now we have created our directories, we need to activate the watch flag to watch the SCSS folder and compile any changes to CSS.

```js
sass --watch scss:css
```

Here we are watching a folder called SCSS which compiles every changes to a folder called CSS. You can customize this directory according to what your project works with.

E.g

```js
sass --watch scss:dist/css
```

Which is targeting the CSS file inside the dist folder.

Finally, we have successfully gotten SASS up and running in our projects.

You can turn off the the `main.css.map` inside the `package.json` settings.

## Installation of Dart SASS locally

You can also install Dart SASS into your machine by downloading one of their <a href="https://github.com/sass/dart-sass/releases/tag/1.45.1">packages</a> and adding it to a path folder in your machine.

You can read more on how to do that <a href="https://katiek2.github.io/path-doc/">here</a>

Available for Windows, Mac and Linux.

## Why Dart SASS?

Dart Sass has replaced Ruby Sass as the canonical implementation of the Sass language. We chose Dart because it presented a number of advantages. <a href="https://github.com/sass/dart-sass#why-dart">Read</a> more

## Important links

- <a href="https://github.com/sass/dart-sass/releases/tag/1.45.1">Dart SASS packages</a>
- <a href="https://sass-lang.com/documentation/cli/dart-sass#usage">Dart SASS CLI</a>
- <a href="https://sass-lang.com/install">SASS Install docs</a>
