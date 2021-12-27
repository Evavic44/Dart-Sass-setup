<h1 align="center">Dart SASS</h1>
<p>A new and improved way of setting up SASS in your project.</p>

## Installation Instructions

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

Coming soon.

## Important links

- <a href="https://sass-lang.com/documentation/cli/dart-sass#usage">Dart SASS CLI</a>
- <a href="https://sass-lang.com/install">SASS Install docs</a>
