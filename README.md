# cfh-stylesheet
Competitive For Honor Stylesheet

This project depends on node.

The most flexible way to add this to your system is using
[Nvm-windows](https://github.com/coreybutler/nvm-windows/releases)

This allows you to install multiple versions and switch between them.

```
nvm list available
nvm install 12.1.0
nvm use 12.1.0
```

Then you must install this projects dependencies, mainly [sass](https://sass-lang.com/),
our css pre-processor of choice. This allows us to use variables, functions, mixins, etc
which will all make the stylesheet much more maintainable.

```
npm ci install
```

After that, you can edit source files and run 

```
npm run build
```

to turn those in to a stylesheet
in the dist folder that you can upload to reddit.
