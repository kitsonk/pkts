# Website for PKTS

Requirements:

* [npm and Node.js](https://nodejs.org/)
* [git](https://git-scm.com/)
* [now](https://zeit.co/)

The following needs to be installed:

```
> npm install hexo -g
```

Clone this repo and get it running:

```
> git clone https://github.com/kitsonk/pkts
> cd pkts
> npm install
```

There are 7 themes installed (but not configured).  To access them, change to the name of the directory in the root `_config.yml` file.  Each one has a set of configuration options in its own `_config.yml`.

Documentation for [hexo](https://hexo.io/docs/commands.html) but basically:

```
> hexo new "Example Post"
> hexo new page "Example Page"
> hexo serve
> hexo generate
```

Once you have a now account setup, `hexo deploy` should work.
