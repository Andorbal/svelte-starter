# svelte-starter
Simple starter kit for a [Svelte](https://svelte.technology) app

## Purpose

**TL;DR** This is a simple jumping-off point for Svelte apps.

While going through the [getting started](https://svelte.technology/guide) guide for Svelte, I came across a line that said using modules is the recommended way to build a serious app, but that required more setup. OK, I thought... What setup? But the guide didn't go into it.

So I dug around and got a simple app building that used modules built by [rollup](http://rollupjs.org). I tried to boil it down to the bare essentials and this is what I came up with.

## How to use

Just clone this repo, remove (or replace) git's origin remote, and build through npm.

```bash
$ git clone https://github.com/Andorbal/svelte-starter.git
$ cd svelte-startup
$ git remote rm origin
$ npm install
$ npm start
```

This will start a webserver on port 3000, and uses [livereload](https://github.com/napcs/node-livereload). So you can open your browser, point it at http://localhost:3000, and edit away! You can also run `NODE_ENV=production npm run build` to get a minified version of the bundle. From there, you can deploy the contents of the build directory to the location of your choice.

If you use [yarn](https://yarnpkg.com), I have a lock file included so you can use that instead of npm.

## Next steps

I'd like this eventually be similar to [create-react-app](https://github.com/facebookincubator/create-react-app), but that's the future. My short term goals will be driven by the pain points as I explore this un-framework.

## License

[MIT](https://raw.githubusercontent.com/Andorbal/svelte-startup/master/LICENSE)
