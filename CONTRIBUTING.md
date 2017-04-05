# Contributing

## Tools & Workflow

The workflow to test into a browser the component is setted with gulp.

All the files versionned for live testing are written `./test/src` folder.
The gulp workflow will generate, from those files, a `./test/dest` used by a local server (running via gulp) to renderer into your browser the component.

You have several commands for making the `./test/dest` folder :

```sh
# run gulp tasks to build the `./test/dest` folder
npm run test

# run gulp tasks to build the `./test/dest` folder in watch mode, and setup a localserver with livereload
npm start
```

Thoses commands generates css for the `./test` folder and for the `./dest` folder (in normal and minified version).



## Writing a Trowel Component
[Checkout the documentation](https://github.com/Trowel/Trowel/blob/master/doc/3-create-your-own-trowel-component.md) from the trowel-core project, to learn about how writting a Trowel Component

## Good practices
To be written
