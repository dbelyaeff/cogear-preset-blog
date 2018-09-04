# Cogear.JS preset `blog`

Ready to use site preset. Just clone repository, install dependencies and run `cogear` in project directory from command line.

![screenshot](https://github.com/codemotion/cogear-theme-blog/raw/master/screenshot.jpg)

# Installation

Make sure that [Cogear.JS](https://cogearjs.org) is installed. [How to install](https://cogearjs.org/docs/)

Clone this repo to the target local directory:
``` shell
> cd ~/Sites/
> git clone --recurse-submodules https://github.com/codemotion/cogear-preset-blog blog
```
Pay attention to `--recurse-submodules` option. It's required, becase [`cogear-theme-blog`](https://github.com/codemotion/cogear-theme-blog) is presented as git [submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

Install dependencies:
``` shell
> cd ~/Sites/blog
> npm install
or
> yarn install
```

You're ready to go! Fire up **Cogear.JS** in `dev` mode, your new blog will be opened in browser automatically!
``` shell
> cogear # development mode by default
```

# Read the docs
https://cogearjs.org/docs